# Hotel-Booking-Analysis

hotelHotel (H1 = Resort Hotel or H2 = City Hotel)
is_canceled=Value indicating if the booking was canceled (1) or not (0)
lead_time= Number of days that elapsed between the entering date of the booking into the PMS and the arrival date
arrival_date_year =Year of arrival date
arrival_date_month =Month of arrival date
arrival_date_week_number Week number of year for arrival date
arrival_date_day_of_month=Day of arrival date
stays_in_weekend_nights=Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
stays_in_week_nights=Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
adults=Number of adults
children=Number of children
babies=Number of babies


Type of booking, assuming one of four categories:
Contract - when the booking has an allotment or other type of contract associated to it; Group – when the booking is associated to a group; Transient – when the booking is not part of a group or contract, and is not associated to other transient booking; Transient-party – when the booking is transient, but is associated to at least other transient booking
adr=Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights
required_car_parking_spaces=Number of car parking spaces required by the customer
total_of_special_requests=Number of special requests made by the customer (e.g. twin bed or high floor)
reservation_status=Reservation last status, assuming one of three categories: Canceled – booking was canceled by the customer; Check-Out – customer has checked in but already departed; No-Show – customer did not check-in and did inform the hotel of the reason why
reservation_status_date=Date at which the last status was set. This variable can be used in conjunction with the Reservation Status to understand when was the booking canceled or when did the customer checked-out of the hotel
