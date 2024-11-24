# *HSTU Bus Schedule Management System*

*A Project submitted to the Department of Computer Science and Engineering*  
Hajee Mohammad Danesh Science and Technology University  

*Course Title*: Software Engineering  
*Course Code*: CSE 305  

### *Submitted To*  
*Pankaj Bhowmik*  
Lecturer  
Department of Computer Science and Engineering  

### *Submitted By*  
*Nahida Farzana*  
Student ID: 2102057  
Level 3, Semester I  

---

### HSTU Bus Schedule Management System

### Objectives

The said "HSTU Bus Schedule Management System" aims to facilitate the traveling of students easy. It has both the weekly and daily bus schedules that show the buses available for that day currently. The schedules will be updated automatically to reflect the buses from the present time. Extra buses will be added by the administrators when it is needed according to the number of waiting students. Students will board buses using their ID cards. The realtime location of the buses plus the time estimation needed for reaching a stop will also be made available in this system.

---

### **Iterative Model in Use**

![An image of iterative model](https://www.tutorialspoint.com/sdlc/images/sdlc_iterative_model.jpg)

The development of this system will be done by using the Iterative Model. This model is useful because:

- **Feedback**: Each step lets the users upgrade the system through feedback.  
- **Complexity Handling**: It makes the system easy to work on and understand for completion as it is built in parts.  
- **Improvisations**: The main and initial features are built in and the value-added features can be there later.

---

The complete system comprises of:

**Students:** Can view the timings of buses, can use their id cards to travel and track the buses.
**Admins:** They can add extra buses and schedule them.
**Bus Drivers:** Update the current location of the bus with the schedule.

In the future, they may provide additional features like notification, routing benefits, and fuel tracking.

---
### **Design Using the Iterative Model**
#### Phase 1: Requirements

• Need Identification: Discussion with the students, administration staff, and drivers about problems and their needs.  
• Feature List:  
 • Display Bus Schedules: The schedule for the whole week and for a day.  
• Real-time up-to-minute current schedule updates.  
• Addition of more routes as the demand arises.  
• ID card issuance for boarding of buses.
- Arrive at the venue of the bus and arrival time of the bus tracking.

#### **Phase 2: System Design**

- **Operation:**  
  - **Database:** Schedules, student IDs, and GPS locators.  
  - **Modules:**  
    - Schedule Management  
    - Admin Controls  
    - Real-Time Tracking
ID Card System  

- **Plan:** Divide the system into small pieces, which is called increments, and it will be carried out step by step.
Phase 3: System Configuration-Iterative Steps 

We will build the system in chunks. 

Step 1: Schedules 
- Addition of weekly schedules. 
- Displaying of daily schedule starting from the current time of the device. 

Step 2: Admin Controls 
- Adding of buses by admin based on the number of students. 
- Recovery of records of buses should be maintained. 

Step 3: ID Card Scanning
- ID cards of students are scanned to board buses.  
- Maintaining and checking student profile in secured format.

Step 4: Bus Tracking 
- Live location of the bus appeared on the map.
- Time taken by buses at every stop is estimated.

---
### Testing

- **Unit Testing**: Every unit from the ID scanner to schedule update functions needs to be tested if they are performing as expected or not.
- **Integrated Testing**: If the system integrates all the various components well and works as one. 
- **User Testing**: Test users would be students and admins who would use the system in real operation and provide feedback.
- **Load Testing Performance**: The ability of the application to perform quite well during peak time.

---

Deployment and Maintenance

- **Phased Release:** We will have a phased release so that the users can enjoy the feature right from the time it comes out.
- **Feedback:** There will be a facility to obtain users' inputs at periodic intervals for the purpose of system improvement.
- **Updates**: Bug fixes and further developments for new features.

---
Main Functions and Benefits

- **Dynamic Schedules:** Ready schedules for easy availability.
- **Admin Controls:** Easy for admins to manage the functioning of buses.
- **ID Scanning:** Board in a safe and secure way.
- **Live Tracking**: Time it will arrive and where the bus is.
