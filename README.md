# CPSC481 Group1 Portfolio II

## Group Members 
Thomas Mattern - 30147476
Shubham Aggarwal - 30113383
Joshua Geng - 30152297
Julia Lat - 30151032
Tochi Isaac - 30145286

## What cases/function were implemented?
We have implemented a high-fidelity prototype of an Academic Planning Navigator for the University of calgary with the following key features:

### 1. Dashboard Overview
* Student Profile: Displays current GPA, total credits, and a progress bar for overall degree completion.
* Course Schedule: Shows "In Progress" courses for the current semester and "Planned" courses for the upcoming semester.
* Course Details: Clicking "View Details" opens a screen with course descriptions, credits, professors, and recent offerings.

### 2. Degree Requirements & Interactive Course Tree
* Progress Tracking: The overall degree completion progress bar broken was broken down into 4 different ones organized by Major, Minor, Technical Electives, and COST options.
* Interactive Course Tree Color-Coded Status: Courses are color-coded based on their status (Green = Completed, Red = Prerequisites Missing, Yellow = In Progress).
    * Drag-and-Drop Planning: Users can customize their degree plan by searching for courses in the sidebar and dragging them into slots in the year-by-year grid.

### 3. Advising System
* Appointment Booking: A fully functional form to book academic advising appointments.
* Available Time Slots: Users can select a department, view available time slots, and enter a reason for the visit.
* Booking Management: Users can view their active appointments and cancel them if necessary.

## What Data should be entered?
The prototype is pre-populated with most necessary data (student history, course lists, and prerequisites). 

Advising Section:
* You will need to select a "Department", an "Available Time Slot" and enter a "Reason for Advising" when booking an appointment.
* Important: Please keep the date set to the default (August 17, 2025) to ensure the demo scenarios time slots function as intended.

## Instructions
1. Target Display: Desktop or Laptop Web Browser Resolution at 1920x1080 
2. Open `index.html` in your web browser to start the prototype.
3. Navigate to the "Requirements" tab and click "Open Major Requirements".
4.  Use the Search Feature: On the right-hand sidebar of the Major Requirements page, use the search bar to find specific courses (e.g., "ENGG").
5.  Drag and Drop: Drag courses from the search results onto the course grid boxes to replace them or fill empty "SLOT" boxes. Observe how the prerequisite status colors update.
6.  Book an Appointment: Navigate to the "Advising" tab, select a department and time slot (keeping the date as 2025-08-17), and confirm your booking.