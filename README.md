# HotelReservationCancellationPrediction
Likelihood of hotel reservation cancellation prediction based on booking details using XGBoost.

The model makes decision based on all available booking information which consist of the following:
- No of adults: Number of adults
- No of children: Number of Children
- noofweekend_nights: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
- noofweek_nights: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
- typeofmeal_plan: Type of meal plan booked by the customer:
- requiredcarparking_space: Does the customer require a car parking space? (0 - No, 1- Yes)
- roomtypereserved: Type of room reserved by the customer. The values are ciphered (encoded) by INN Hotels.
- lead_time: Number of days between the date of booking and the arrival date
- arrival_year: Year of arrival date
- arrival_month: Month of arrival date
- arrival_date: Date of the month
- Market segment type: Market segment designation.
- repeated_guest: Is the customer a repeated guest? (0 - No, 1- Yes)
- noofprevious_cancellations: Number of previous bookings that were canceled by the customer prior to the current booking
- noofpreviousbookingsnot_canceled: Number of previous bookings not canceled by the customer prior to the current booking
- avgpriceper_room: Average price per day of the reservation; prices of the rooms are dynamic. (in euros)
- noofspecial_requests: Total number of special requests made by the customer (e.g. high floor, view from the room, etc)

Kaggle Competition: https://www.kaggle.com/competitions/playground-series-s3e7  
Kaggle Notebook: https://www.kaggle.com/code/mnokno/reservation-cancellation-prediction-using-xgboost  