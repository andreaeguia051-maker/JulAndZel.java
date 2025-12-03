<h1 align = "center">𐔌 .⋮ Snip & Style: Beauty Salon Appointment System  .ᐟ  ֹ   ₊ ꒱</h1>
<h3 align = "center">A Java console-based appointment scheduling system for salon management.</h3>

<p align = "center">
<b>IT 2110</b> <br/>
Eguia, Andrea B. <br/>
Menorca, Clariezel G. <br/>
Andal, Julius C. <br/>
</p>

---

## ‧₊˚ ┊ Overview

Snip & Style Beauty Salon Appointment System is a console application based on Java, intended to make the process of creating, changing, and cancelling customer appointments at a salon easy. The system will emulate natural appointment management by storing client information, schedules, and services using OOP principles.Abstraction is present as it encapsulates complex processes internally; encapsulation because data will be handled securely; inheritance, in the types of services; and polymorphism, in different method behaviors at runtime. The goal of the project is to develop a useful yet instructive system that implements Java principles and OOP concepts

---

### ✨ Users can:
💇 Schedule an appointment <br/>
📅 View all appointments <br/>
🛠 Modify an existing appointment <br/>
❌ Cancel an appointment <br/>
🚪 Exit the program safely

## ‧₊˚ ┊ Program Structure
```
📂 src/
└── ☕ SalonSystem.java
```

### File Description
 **SalonSystem.java contains the whole software, including:
- The abstract Service class (the foundation for all salon services).
  
- Service subclasses (HaircutService, NailService, SpaService)
  
- The Appointment class is for storing appointment details.
  
- The primary system that manages the menu, user input, scheduling, viewing, updating, and canceling appointments
 

---

## ‧₊˚ ┊ Features

1. **Schedule Appointment**  
   Add a new booking with customer details and selected service.

2. **View All Appointments**  
   Displays every saved appointment with numbering.

3. **Modify Appointment**  
   Edit any existing appointment by selecting its entry number.

4. **Cancel Appointment**  
   Removes an appointment permanently.

5. **Exit**  
   Safely closes the system.

---

## ‧₊˚ ┊ Example Output

---- Snip & Style Salon Appointment System ----

1.Schedule Appointment

2.View All Appointments

3.Modify Appointment

4.Cancel Appointment

5.Exit
## ‧₊˚ ┊ Object-oriented Principles
### 🧩 Abstraction
The system defines all salon services with an abstract class called Service.
This class has mainly the key properties, such as the service name, price, and duration, as well as the abstract method **getDescription()** that every service must define.
This keeps the system neat and makes it easier for the program to treat all services equally.


---

### 🧬 Inheritance
`The classes for **HaircutService**, **NailService**, and **SpaService** are derive from the abstract Service class.They reuse basic variables and behaviors from **Service**, avoiding the need to rewrite common code. Each subclass only includes what is specific to that service, such as its own description.
This simplifies system maintenance and expansion when new services are added.


---

### 🎭 Polymorphism
The **getDescription()** method of the abstract class is overridden by each service type.
This means that depending on the service used, a single method name can produce a variety of results.The **chooseService()** method returns a Service object, which might be a haircut, nail care, or spa service. This allows distinct services to perform independently while remaining controlled by a common interface.

---

### 🔒 Encapsulation
The **Appointment** class protects its information by keeping customer names, dates, times, and services in private variables.
These can only be seen or changed using getter and setter methods, which helps manage and protect the data.
This ensures that appointment information remains constant and prevents unintended changes.
The encapsulation technique prevents undesirable alterations and preserves the system's structure.


## ‧₊˚ ┊ Example Output
```
---- Snip & Style Salon Appointment System ----

Schedule Appointment
View All Appointments
Modify Appointment
Cancel Appointment
Exit

Enter your choice: 1
Enter Customer Name: Andrea
Date (MM/DD/YY): 12/10/25
Time (HH:MM): 03:00 PM
Choose Service:
Haircut
Nail Care
Spa
Appointment successfully scheduled!

```

##  ‧₊˚ ┊ Contributors
| Name | Role |
|------|------|
| **Andrea B. Eguia** | One for All, All for One |
| **Clariezel G. Menorca** | One for All, All for One |
| **Julius Cezar Andal** | One for All, All for One |

---

## ‧₊˚ ┊ Acknowledgment
We would like to express our sincere gratitude to our instructor for the invaluable guidance, support, and expertise provided throughout the completion of this project. We also extend our heartfelt appreciation to our classmates and peers for their cooperation, encouragement, and contributions during the development process.

---

