# Calendar Booking Automation

**Description**  
A very basic workflow to create and send email confirmations whenever a person books an appointment, and add them as a contact to the hubspot CRM.

**Functioning**  
Each time a person books an appointment, the workflow gets triggered, a confirmation email is prepared for them by the AI agent, and then the confirmation email gets sent to the attendee's email.

**Impact:**  
The confirmaiton is sent within 10 seconds of the attendee booking an appointment. Then sends them another confirmation before 24 hours of booking the appointment, then another confirmation 3 hours before, and then another one an hour before the call.

This drastically increases the show-up rate of the attendees by upto 30-40%.

**Tools Used:**  
n8n, Gmail, Cal.com, OpenAI agent, Hubspot CRM.


