# Projet-data-analysis



## Présentation

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MohamedJAIDANE/Projet-data-analysis/main)
ceci est un prototype de projet en analyse de donnée
on a utilisé la bibliothèque pandas

<img src='img/pandas.png' width=80px>

## :file_folder: Dataset 
## Data Dictionary
_Note: For binary variables: `1` = true and `0` = false._

| Column                                                                                                                                                                                                          | Explanation                                                                                                                            |   |   |   |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|---|---|---|
| is_canceled                                                                                                                                                                                                     | Binary variable indicating whether a booking was canceled                                                                              |   |   |   |
| lead_time                                                                                                                                                                                                       | Number of days between booking date and arrival date                                                                                   |   |   |   |
| arrival_date_week_number, arrival_date_day_of_month, arrival_date_month                                                                                                                                         | Week number, day date, and month number of arrival date                                                                                |   |   |   |
| stays_in_weekend_nights, stays_in_week_nights                                                                                                                                                                   | Number of weekend nights (Saturday and Sunday) and weeknights (Monday to Friday) the customer booked                                   |   |   |   |
| adults, children, babies                                                                                                                                                                                        | Number of adults, children, babies booked for the stay                                                                                 |   |   |   |
| is_repeated_guest                                                                                                                                                                                               | Binary variable indicating whether the customer was a repeat guest                                                                     |   |   |   |
| previous_cancellations                                                                                                                                                                                          | Number of prior bookings that were canceled by the customer                                                                            |   |   |   |
| previous_bookings_not_canceled                                                                                                                                                                                  | Number of prior bookings that were not canceled by the customer                                                                        |   |   |   |
| required_car_parking_spaces                                                                                                                                                                                     | Number of parking spaces requested by the customer                                                                                     |   |   |   |
| total_of_special_requests                                                                                                                                                                                       | Number of special requests made by the customer                                                                                        |   |   |   |
| avg_daily_rate                                                                                                                                                                                                  | Average daily rate, as defined by dividing the sum of all lodging transactions by the total number of staying nights                   |   |   |   |
| booked_by_company                                                                                                                                                                                               | Binary variable indicating whether a company booked the booking                                                                        |   |   |   |
| booked_by_agent                                                                                                                                                                                                 | Binary variable indicating whether an agent booked the booking                                                                         |   |   |   |
| hotel_City                                                                                                                                                                                                      | Binary variable indicating whether the booked hotel is a "City Hotel"                                                                  |   |   |   |
| hotel_Resort                                                                                                                                                                                                    | Binary variable indicating whether the booked hotel is a "Resort Hotel"                                                                |   |   |   |
| meal_BB                                                                                                                                                                                                         | Binary variable indicating whether a bed & breakfast meal was booked                                                                   |   |   |   |
| meal_HB                                                                                                                                                                                                         | Binary variable indicating whether a half board meal was booked                                                                        |   |   |   |
| meal_FB                                                                                                                                                                                                         | Binary variable indicating whether a full board meal was booked                                                                        |   |   |   |
| meal_No_meal                                                                                                                                                                                                    | Binary variable indicating whether there was no meal package booked                                                                    |   |   |   |
| market_segment_Aviation, market_segment_Complementary, market_segment_Corporate, market_segment_Direct, market_segment_Groups, market_segment_Offline_TA_TO, market_segment_Online_TA, market_segment_Undefined | Indicates market segment designation with a value of 1. "TA"= travel agent, "TO"= tour operators                                       |   |   |   |
| distribution_channel_Corporate, distribution_channel_Direct, distribution_channel_GDS, distribution_channel_TA_TO, distribution_channel_Undefined                                                               | Indicates booking distribution channel with a value of 1. "TA"= travel agent, "TO"= tour operators, "GDS" = Global Distribution System |   |   |   |
| reserved_room_type_A, reserved_room_type_B, reserved_room_type_C, reserved_room_type_D, reserved_room_type_E, reserved_room_type_F, reserved_room_type_G, reserved_room_type_H, reserved_room_type_L            | Indicates code of room type reserved with a value of 1. Code is presented instead of designation for anonymity reasons                 |   |   |   |
| deposit_type_No_Deposit                                                                                                                                                                                         | Binary variable indicating whether a deposit was made                                                                                  |   |   |   |
| deposit_type_Non_Refund                                                                                                                                                                                         | Binary variable indicating whether a deposit was made in the value of the total stay cost                                              |   |   |   |
| deposit_type_Refundable                                                                                                                                                                                         | Binary variable indicating whether a deposit was made with a value under the total stay cost                                           |   |   |   |
| customer_type_Contract                                                                                                                                                                                          | Binary variable indicating whether the booking has an allotment or other type of contract associated to it                             |   |   |   |
| customer_type_Group                                                                                                                                                                                             | Binary variable indicating whether the booking is associated to a group                                                                |   |   |   |
| customer_type_Transient                                                                                                                                                                                         | Binary variable indicating whether the booking is not part of a group or contract, and is not associated to other transient booking    |   |   |   |
| customer_type_Transient-Party                                                                                                                                                                                   | Binary variable indicating whether the booking is transient, but is associated to at least another transient booking                   |   |   |   |

