# Hotel-Booking-Analysis--EDA-Project

The project focused on performing Exploratory Data Analysis (EDA) to uncover patterns and trends in a hotel booking dataset.The dataset contained information, such as Booking details, Guest information and history, Reservation timing details, Room and service information, Financial -Pricing and Reservation Status.
First,we cleaned and preprocessed the data, which involved removing missing values,handling duplicates data.Next, we visualized the data using techniques Like a pie chart,countplot, scatterplot more chart etc.. to explore trends,compared data,categrical data, correlations, and distributions effectively.

The hotel booking dataset spans years, from (2015 ,2016 and 2017) and includes data for two types of hotels: City Hotel and Resort hotel. The dataset provides year, month, and day-wise booking information, focusing on guest stays, including weekend nights (Saturday-Sunday) and weeknights (Monday-Friday), along with the total number of family members (adults, children, babies) in the bookings.

The dataset also analyzes various market segments to determine the sources of bookings, such as direct bookings from customers, online travel agents, offline travel agents, and tour operators. It identifies the most frequent and new guests, examines which types of customers make the most bookings, and assesses the availability of parking spaces. Additionally, it tracks the total number of special requests made by guests, highlighting the most common types of requests.

* Booking details （7 attributes）

hotel: The type of hotel, either "City Hotel" or "Resort Hotel."
booking_changes: Number of changes/amendments made to the booking.
market_segment: Market segment designation.
distribution_channel: Booking distribution channel.
days_in_waiting_list: Number of days in the waiting list before booking.
agent: ID of the travel agency.
company: ID of the company.

* Guest information and history （8 attributes）

customer_type: Type of booking (transient, contract, group, etc.).
adults, children, babies: Number of adults, children and babies.
country: Customer's conuntry of origin.
is_repeated_guest: Binary value indicating whether the guest is a repeated guest or not.
previous_cancellations: Number of previous booking cancellations.
previous_bookings_not_canceled: Number of previous bookings not cancelled.

* Reservation timing （7 attributes）

arrival_date_year, arrival_date_month, arrival_date_day_of_month: The year, month and day of arrival date.
arrival_date_week_number: Week number of arrival date.
lead_time: Number of days between booking and arrival.
stays_in_weekend_nights, stays_in_week_nights: Number of weekend nights and weekday nights respectively the guest stays.

* Room and service information （5 attributes）

meal: Type of meal booked.
reserved_room_type, assigned_room_type: Code of room type reserved and assigned at check-in, respectively.
required_car_parking_spaces: Number of car parking spaces required.
total_of_special_requests: Number of special requests made.

* Financial and Pricing （2 attributes）
deposit_type: Type of deposit made.
adr: Average daily rate.

* Reservation Status (3 attributes)
is_canceled: Binary value indicating whether the booking was cancelled or not.
reservation_status: Reservation last status.
reservation_status_date: Date of the last status.
