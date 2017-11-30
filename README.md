# Load-Appointment-Service

## Purpose
An XML payload is sent to the service using a POST method. Using the contents of the payload, the service will enrich the payload and update the SQL Server tables with Appointment details. The enriched XML payload is then returned as response.
 
The Load-Appointment-Service will be perform below things.
*   Enrich the data fetched from SQL Server
*   Update Appointment details in SQL Server
*   Perform appointment sequence business logic and retrun the sequence status whether to process Appoinment or not. 
*   Perform load configuration calculation logic