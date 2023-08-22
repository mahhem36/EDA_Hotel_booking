# EDA_Hotel_booking
**Problem Statement:**

The objective of this project is to perform an exploratory data analysis (EDA) on a hotel booking dataset and gain insights into various aspects of hotel bookings. The dataset contains information about bookings made at hotels, including features such as booking dates, guest demographics, room types, and booking status.

# Datasets Hotel_booking
- hotel: Name of hotel ( City or Resort)
- is_canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)
- lead_time: time (in days) between booking transaction and actual arrival.
- arrival_date_year: Year of arrival
- arrival_date_month: month of arrival
- arrival_date_week_number: week number of arrival date.
- arrival_date_day_of_month: Day of month of arrival date
- stays_in_weekend_nights: No. of weekend nights spent in a hotel
- stays_in_week_nights: No. of weeknights spent in a hotel
- adults: No. of adults in single booking record.
- children: No. of children in single booking record.
- babies: No. of babies in single booking record. 
- meal: Type of meal chosen 
- country: Country of origin of customers (as mentioned by them)
- market_segment: What segment via booking was made and for what purpose.
- distribution_channel: Via which medium booking was made.
- is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for 
                     Yes)
- previous_cancellations: No. of previous canceled bookings.
- previous_bookings_not_canceled: No. of previous non-canceled bookings.
- reserved_room_type: Room type reserved by a customer.
- assigned_room_type: Room type assigned to the customer.
- booking_changes: No. of booking changes done by customers
- deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
- agent: Id of agent for booking
- company: Id of the company making a booking
- days_in_waiting_list: No. of days on waiting list.
- customer_type: Type of customer(Transient, Group, etc.)
- adr: Average Daily rate.
- required_car_parking_spaces: No. of car parking asked in booking
- total_of_special_requests: total no. of special request.
- reservation_status: Whether a customer has checked out or canceled,or not showed 
- reservation_status_date: Date of making reservation status.
# Data Cleaning
**(1) Removing Duplicate rows:**
All duplicate rows were dropped.

**(2) Handling null values:**
Null values in columns company,children and agent were replaced by 0.
Null values in column country were replaced by 'unknown'.

# Univariate Analysis
Performed univariate analysis and made following conclusions:

1]City Hotel is most preffered hotel by guests. Thus city hotels has maximum bookings.

2]Repeated guests are very few which only 3.2 %.

3]Guests use different channels for making bookings out of which most preferred way is TA/TO.

4] Most common stay length is less than 4 days and generally people prefer City hotel for short stay, but for long stays, Resort Hotel is preferred.

5]July- August are the most busier and profitable months for both of hotels.

# Bivariate and Multivariate Analysis

1]City hotel has the highest ADR. That means city hotels are generating more revenues than the resort hotels. More the ADR more is the revenue

2] Both hotels have very small percentage that customer will repeat, but Resort hotel has slightly higher repeat % than City Hotel.

3] Moslty bookings are done by couples.

4]Resort hotels has slightly high avg lead time. That means customers plan their trips very early.

5]'Direct' and 'TA/TO' has almost equally contributed in adr in both type of hotels i.e. 'City Hotel' and 'Resort Hotel'.

6]GDS has highly contributed in adr in 'City Hotel' type

7]GDS needs to increase Resort Hotel bookings.

# conclusion:

1]City hotels are the most preferred hotel type by the guests. We can say City hotel is the busiest hotel.

2]Most of the customers do not require car parking spaces

3]BB( Bed & Breakfast) is the most preferred type of meal by the guests.

4]Maximum number of guests were from Portugal,

5]Most of the bookings for City hotels and Resort hotel were happened in 2016.

6]Average ADR for city hotel is high as compared to resort hotels. These City hotels are generating more revenue than the resort hotels.

7]Booking cancellation rate is high for City hotels which almost 30 %.

8]Average lead time for resort hotel is high.

9]Waiting time period for City hotel is high as compared to resort hotels. That means city hotels are much busier than Resort hotels.

10]Resort hotels have the most repeated guests.

11]Optimal stay in both the type hotel is less than 7 days. Usually people stay for a week.

# Challenges

(1) There was a lot of duplicate data.

(2) Data was present in wrong datatype format.

(3) Choosing appropriate visualization techniques to use was difficult.

(4) A lot of null values were there in the dataset.




