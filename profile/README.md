# 📖 Skincare Service Booking System

## 🌟 Introduction
The **Skincare Service Booking System** is designed to streamline the process of booking skincare services, managing events, and facilitating customer interactions with skincare professionals. This system enhances customer convenience while providing robust tools for staff, managers, and administrators.

---

## DOCUMENT
- [DOCUMENT](https://docs.google.com/document/d/175XiFym-YpAiUe4I1nQgz5gRQ5I5JFviCiXpIX6ph_A/edit?tab=t.0#heading=h.w1od5y64bg0k)

## 🛠️ Key Features
- **Service Booking**: Customers can book, reschedule, or cancel skincare services.
- **Event Management**: Managers can create, update, and monitor promotional events.
- **Customer Interaction**: Real-time communication between customers, staff, and therapists.
- **Skin Type Test**: Guests can take a skin type test and save results upon account creation.
- **Reports & Feedback**: Managers receive monthly reports; customers can give feedback after services.
- **Secure Payment**: Online payments for services and event tickets with refund policies.

---

## 👥 Actors
- **Guest**: View services, events, therapists; take skin type test.
- **Customer**: Book/cancel services, register for events, give feedback.
- **Staff**: Check-in/out customers, update schedules.
- **Skin Therapist**: View schedules, perform services, track customer progress.
- **Manager**: Manage services, events, reports, and request account creation.
- **Admin**: Manage user accounts and access rights.

---

## 🔍 System Context Diagram
The context diagram below illustrates the interaction between the external actors and the system. <br>

![image](![Context diagram-Final](https://github.com/user-attachments/assets/814eb86a-3a7b-4df8-8934-5e9dbc1fe8f3)
)

## System Architecture 

![System architecture](https://github.com/user-attachments/assets/13bb6753-5783-4220-87b8-64ae5de87e88)

## Package Diagram

- Backend package:
![Another Diagram-Package Diagram Back-end](https://github.com/user-attachments/assets/56096160-c2d7-4343-96e1-442a30abc82c)

- Frontend package:
![Another Diagram-Package diagram front-end (1)](https://github.com/user-attachments/assets/bd2e333d-cc37-4c67-ac7c-087d82d1cda2)




**Explanation:**
- **Guest → System**: View services and events, take tests.
- **Customer ↔ System**: Book services, register for events, update bookings, provide feedback.
- **Staff ↔ System**: Check-in/out, view schedule.
- **Skin Therapist ↔ System**: Track customer services, view schedule.
- **Manager ↔ System**: Manage services, events, and view reports.
- **Admin ↔ System**: Handle user accounts.

---

## 🔄 Main Flows

### 1️⃣ Service Booking Flow
- Manager creates services (with optional multi-step details).
- Customer books, schedules, or cancels services.
- Staff manages check-in/out.
- Therapists provide services and record outcomes.

### 2️⃣ Event Management Flow
- Manager creates events.
- Customers purchase event tickets.
- Staff checks attendees into events.

---

## 📊 Reporting & Insights
- **Service Usage**: Monthly reports with top/bottom 5 services.
- **Event Participation**: Event attendance statistics.

---

## 🔐 Security & Access Control
- **Authentication**: .
- **Role-Based Access**: .

---

## 🚀 Technology Stack (Tentative)
- **Frontend**: ReactJS
- **Backend**: .NET
- **Database**: MySQL
- **Authentication**: 
- **Payment Integration**: ZaloPay/ VNPay

---

## 📝 Additional Notes
- **Refund Policy**: Full refunds only 48 hours before the start date.
- **Skin Type Test**: Available to guests and saved for logged-in users.
- **Event Tickets**: Unique QR codes and OTP for event check-in.

---

*This README provides a high-level overview of the system. For more detailed use case descriptions and diagrams, refer to the system's documentation.*

