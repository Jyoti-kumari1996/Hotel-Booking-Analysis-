# Hotel-Booking-Analysis-
I am thrilled to share a new project on Hotel-Booking-Analysis using excel.
First Step: Understanding the behaviour of data and cleaning the raw data using ETL process Extract,Load and Transform.
Second Step: Create pivots and extract the insights of the data information.
Third Step: Data visualization according to the required problem statement. 
Required Formula:
1. For “room_status”
=IF([@[reserved_room_type]]=[@[assigned_room_type]],"Correct","in-Correct")
For “guest_type”
=IF(AND([@adults]=2,[@children]=0,[@babies]=0),"TwoAdults",IF(AND([@adults]=1,[@children]=0,[@babies]=0),"Single","Family"))
Sample Insights:
1.People prefer City Hotel as compared to Resort Hotel.															
2.Young Couples consist of one male and female  are more keen to book hotels as compared to family.															
3. It seems that people are interested to book hotel from the month of April to October.															
Final conclusion to improve Hotel Booking :
Hotels will provide some coupons online or offline or cashback or offers to people specially for single or family with children 1 or 2 from Nov to March every year.[Hotel Booking Analysis(AutoRecovered).xlsx](https://github.com/user-attachments/files/16244904/Hotel.Booking.Analysis.AutoRecovered.xlsx)


