# Skillovilla_Project_SQL

The airline db contains the flights data related to flights,aircrafts,tickets,ticket_flights,airports,seats,bookings and boarding_passes.

Analysed below requirements:

- Represent the “book_date” column in “yyyy-mmm-dd” format using Bookings table Expected output: book_ref, book_date (in “yyyy-mmm-dd” format) , total amount
- Get the following columns in the exact same sequence. Expected columns in the output: ticket_no, boarding_no,seat_number, passenger_id, passenger_name.
- Write a query to find the seat number which is least allocated among all the seats?
- In the database, identify the month wise highest paying passenger name and passenger id. Expected output: Month_name(“mmm-yy” format),passenger id passenger name and total amount
- In the database, identify the month wise least paying passenger name and passenger id? Expected output: Month_name(“mmm-yy” format),passenger_id, passenger_name and total amount
- Identify the travel details of non stop journeys or return journeys (having more than 1 flight). Expected Output: Passenger_id, passenger_name, ticket_number and flight count
- How many tickets are there without boarding passes? Expected Output: just one number is required.
- Identify details of the longest flight (using flights table)? Expected Output: Flight number, departure airport, arrival airport, aircraft code and durations.
- Identify details of all the morning flights (morning means between 6AM to 11 AM, using flights table)? Expected output: flight_id, flight_number, scheduled_departure,scheduled_arrival and timings.
- dentify the earliest morning flight available from every airport. Expected output: flight_id, flight_number, scheduled_departure, scheduled_arrival, departure airport and timings.
- Questions: Find list of airport codes in Europe/Moscow timezone Expected Output: Airport_code.
- Write a query to get the count of seats in various fare condition for every aircraft code? Expected Outputs: Aircraft_code, fare_conditions ,seat count
- How many aircrafts codes have at least one Business class seats? Expected Output : Count of aircraft codes
- Find out the name of the airport having maximum number of departure flight Expected Output : Airport_name
- Find out the name of the airport having least number of scheduled departure flights Expected Output : Airport_name
- How many flights from ‘DME’ airport don’t have actual departure? Expected Output : Flight Count
- Identify flight ids having range between 3000 to 6000 Expected Output : Flight_Number , aircraft_code, ranges
- Write a query to get the count of flights flying between URS and KUF? Expected Output : Flight_count
- Write a query to get the count of flights flying from either from NOZ or KRR? Expected Output : Flight count
- Write a query to get the count of flights flying from KZN,DME,NBC,NJC,GDX,SGC,VKO,ROV Expected Output : Departure airport ,count of flights flying from these airports.
- Write a query to extract flight details having range between 3000 and 6000 and flying from DME Expected Output:Flight_no,aircraft_code,range,departure_airport
- Find the list of flight ids which are using aircrafts from “Airbus” company and got cancelled or delayed Expected Output : Flight_id,aircraft_model
- Find the list of flight ids which are using aircrafts from “Boeing” company and got cancelled or delayed Expected Output : Flight_id,aircraft_model
- Which airport(name) has most cancelled flights (arriving)? Expected Output : Airport_name
- Identify flight ids which are using “Airbus aircrafts” Expected Output : Flight_id,aircraft_model
- Identify date-wise last flight id flying from every airport? Expected Output: Flight_id, flight_number, schedule_departure, departure_airport
- Identify list of customers who will get the refund due to cancellation of the flights and how much amount they will get? Expected Output : Passenger_name, total_refund
- Identify date wise first cancelled flight id flying for every airport? Expected Output : Flight_id, flight_number, schedule_departure, departure_airport
- Identify list of Airbus flight ids which got cancelled. Expected Output : Flight_id
- Identify list of flight ids having highest range. Expected Output : Flight_no, range
