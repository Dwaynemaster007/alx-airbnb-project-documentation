# System Process Flowchart

## Objective
This task involved creating a flowchart to visualize the step-by-step process of a core backend functionality. The flowchart serves as a clear, visual guide for the logic and decision points within a specific workflow.

## Chosen Process: Property Booking
The flowchart details the end-to-end process for a user booking a property. This process was selected for its complexity, as it involves multiple decision points and interactions with various data stores. The key steps include:
1.  **User Initiation**: A guest selects a property and specifies their desired dates.
2.  **Availability Check**: The system checks the booking dates against the property's availability data.
3.  **User Authentication**: The system verifies the user's login status.
4.  **Payment Processing**: The user is directed to the payment gateway to complete the transaction.
5.  **Status Update**: The booking and payment records are updated in the database.
6.  **Notifications**: The user and host are notified of the booking status.

## Diagram
The flowchart, created using Draw.io, is included below. It clearly maps the sequence of actions, data inputs, and outputs, providing a comprehensive overview of the booking workflow.

![Airbnb Booking Process Flowchart](flowcharts/booking-process-flowchart.png)
