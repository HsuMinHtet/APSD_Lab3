# Lab3 - Problem Statement

## Office Manager System

This system manages functions related to office operations for a dental clinic, including dentist and patient registration, appointment scheduling, and notifications.

---

### Office Manager’s Functions

- **Register the Dentist**
  - Dentist details: `Id`, `firstName`, `lastName`, `phone`, `email`, `specialization`

- **Register the Patient**
  - Patient details: `firstName`, `lastName`, `phone`, `email`, `address`, `DOB`

- **Confirm/Record an Appointment**
  - Schedule appointments based on the Patient’s appointment form.
  - Ensure no duplicates for:
    - Specific `date/time`
    - `Dentist`
    - `Surgery location`

- **Send Appointment Notification**
  - Notify the Patient by email about the confirmed appointment.

---

### Patient’s Functions

- **Sign In**
  - Secure access to personal appointment management.

- **Register an Appointment Form**
  - Appointment rules:
    - No more than **5 appointments** in a week.
    - Only if no **outstanding unpaid bills**.

- **View Appointments**
  - See appointment details and assigned Dentist information.

- **Edit Appointment**
  - Modify existing appointment details as needed.

- **Cancel Appointment**
  - Cancel an upcoming appointment.

---

### Dentist’s Functions

- **Sign In**
  - Secure access to view appointment information.

- **View List of Appointments**
  - See details of scheduled appointments, including:
    - Appointment time
    - Patient information
    - Surgery location
   
  ![image](https://github.com/user-attachments/assets/5e20334d-0d05-4b13-9739-09febb147c44)

