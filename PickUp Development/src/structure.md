# PickUp System

**There are 2 parties who interact the system;**

1. Consumer
2. Driver

**Functions of the system**

- Allow consumer to order a pick up service
    - Does not schedule the appointment/car service (perhaps later versions, it will) 
- Alert driver of pickup and dropoff times and locations 
- Remind consumer of scheduled service

**Data needed to be collected**

- Service Date
- Appointment start time *(When the car must be at the service)*
- Appointment end time *(When the car must be picked up from the service)
- Pick up time *(When the car is picked up from the house)* [Calculated from route]
- Return time *(When the car is returned to the house)* [Calculated from route]
- Charge Estimation
- Consumer address
- Service address
- Consumer name
- Consumer phone
- Consumer email
- Key pickup details *(Where we can find the keys to your car)*

**Where the data is gathered and sent**

- Collected in a webpage
- Passed to a gscript
- Emailed/Texted to consumer/driver

### Wrapping the Data - Structure, Convention, and Access

- The formData object contains all the relevant data