# Hotel_Booking_EDA_Capstone_Project

## Project Description

This project is an exploratory data analysis (EDA) of hotel booking data. The goal of this analysis is to uncover insights and patterns in the booking data, which can help in understanding customer behavior, booking trends, and potential areas for improvement in hotel management.

## Data Description

The dataset used in this project contains hotel booking information. The key features include:

- `hotel`: Type of hotel (e.g., Resort Hotel, City Hotel)
- `is_canceled`: Whether the booking was canceled
- `lead_time`: Number of days between the booking date and the arrival date
- `arrival_date_year`: Year of arrival
- `arrival_date_month`: Month of arrival
- `arrival_date_week_number`: Week number of arrival
- `arrival_date_day_of_month`: Day of arrival
- `stays_in_weekend_nights`: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
- `stays_in_week_nights`: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
- `adults`: Number of adults
- `children`: Number of children
- `babies`: Number of babies
- `meal`: Type of meal booked
- `country`: Country of origin of the guests
- `market_segment`: Market segment designation
- `distribution_channel`: Booking distribution channel
- `is_repeated_guest`: Whether the booking was from a repeated guest
- `previous_cancellations`: Number of previous cancellations
- `previous_bookings_not_canceled`: Number of previous non-canceled bookings
- `reserved_room_type`: Code of room type reserved
- `assigned_room_type`: Code for the type of room assigned to the booking
- `booking_changes`: Number of changes made to the booking
- `deposit_type`: Type of deposit made for the booking
- `agent`: ID of the travel agency that made the booking
- `company`: ID of the company that made the booking
- `days_in_waiting_list`: Number of days the booking was on the waiting list
- `customer_type`: Type of booking, e.g., Contract, Group, Transient, Transient-party
- `adr`: Average Daily Rate, calculated by dividing the sum of all lodging transactions by the total number of staying nights
- `required_car_parking_spaces`: Number of car parking spaces required by the customer
- `total_of_special_requests`: Number of special requests made by the customer
- `reservation_status`: Reservation status (e.g., Canceled, Check-Out, No-Show)
- `reservation_status_date`: Date at which the last status was set

The analysis in the notebook provides insights into various aspects of hotel bookings. Below is a detailed explanation of the insights derived from each of the 14 charts included in the analysis:

Booking Trends Over Time:

## Chart 1: Bookings by Year: Shows the total number of bookings per year. Highlights trends in booking volumes over different years.
## Chart 2: Bookings by Month: Displays the distribution of bookings across different months. Useful for identifying peak and off-peak months for bookings.
Cancellation Rates and Factors Affecting Cancellations:

## Chart 3: Cancellation Rate by Hotel Type: Compares cancellation rates between resort hotels and city hotels. Provides insights into which type of hotel experiences more cancellations.
## Chart 4: Lead Time and Cancellations: Examines the relationship between the lead time (number of days between booking and arrival) and the likelihood of cancellations.

## Distribution of Bookings Across Different Market Segments:

## Chart 5: Bookings by Market Segment: Shows the number of bookings originating from different market segments (e.g., direct, corporate, online travel agents).
## Chart 6: Cancellation Rate by Market Segment: Displays the cancellation rates for each market segment, highlighting which segments have higher cancellation rates.

## Customer Demographics and Booking Patterns:

## Chart 7: Bookings by Country: Visualizes the distribution of bookings by the country of origin of the guests. Helps identify the major sources of bookings.
## Chart 8: Number of Guests per Booking: Analyzes the average number of adults, children, and babies per booking.

## Impact of Lead Time on Booking Cancellations:

## Chart 9: Lead Time Distribution: Shows the distribution of lead times for bookings, providing insights into how far in advance guests tend to book.
## Chart 10: Cancellation Rate by Lead Time: Explores how the cancellation rate varies with different lead times.


## Comparison Between Reserved and Assigned Room Types:

## Chart 11: Reserved vs. Assigned Room Type: Compares the types of rooms guests reserve versus the rooms they are assigned. Highlights discrepancies and overbooking practices.

## Special Requests and Their Frequency:

## Chart 12: Number of Special Requests: Shows the distribution of the number of special requests made by guests. Helps understand how often guests make special requests.
## Chart 13: Special Requests and Cancellations: Analyzes the relationship between the number of special requests and the likelihood of cancellations.
## Overall Booking and Cancellation Insights:

## Chart 14: Heatmap of Correlation Between Variables: Displays the correlation matrix for various numerical features in the dataset. Useful for identifying relationships between different booking attributes and cancellations.
These charts collectively provide a comprehensive understanding of the booking patterns, customer behavior, and factors influencing cancellations in hotel bookings.


