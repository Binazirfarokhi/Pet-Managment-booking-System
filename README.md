# Pet-Managment-booking-System

## Pet Booking System (Power Apps + Dataverse + Power Automate)

I developed a **Pet Booking System** in **Microsoft Power Apps** to replace traditional phone-based bookings.

### What it does
- **Users** can submit a booking request for their dog directly in the app.
- The request is saved in **Dataverse** and displayed in an **admin view**.
- **Admins** can review each request and either **approve** or **reject** it.
- When the admin takes action, a **Power Automate** flow sends an **automatic email notification** to the user indicating whether the booking was accepted or declined.

### Tech used
- Power Apps (Canvas App)
- Dataverse (to store booking requests)
- Power Automate (email notifications / approval logic)

### Business value
This solution streamlines the booking process, reduces phone calls to customer service, and provides faster feedback to customers.

## Demo
### User  Submit a Request : 

![Pet Booking Demo](petgif.gif)

### Admin change the status :

![Pet Booking Demo](AdminGif.gif)
