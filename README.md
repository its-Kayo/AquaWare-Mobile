# AquaWare Mobile - Community Water Outage Monitoring Platform

## Overview

AquaWare Mobile is an Android application designed to help residents of Antigua and Barbuda monitor, report, and stay informed about water outages within their communities.

The application enables users to submit reports about water availability, view outage information by village, receive notifications about disruptions, and access water conservation resources. AquaAware aims to improve communication and awareness during water service interruptions through a community-driven reporting system.

---

## Problem Statement

Residents often experience uncertainty during water outages due to limited access to timely information regarding affected areas and service restoration.

AquaWare addresses this issue by providing a centralized platform where users can:

* Report water outages in their community
* View current water status by village
* Receive outage alerts and announcements
* Access water conservation information
* Track community-reported service disruptions

---

## Features

### User Authentication

* Secure account registration and login
* User profile management
* Firebase Authentication integration

### Community Water Reporting

Users can submit reports indicating:

* Water Available
* Low Water Pressure
* No Water Service

Reports include:

* Village selection
* Timestamp
* Optional comments

### Village Status Dashboard

* View current water conditions across communities
* Community-driven reporting system
* Real-time updates from cloud database

### Notifications

* Receive alerts for outages and announcements
* Stay informed about reported disruptions in selected areas

### Conservation Tips

* Water-saving recommendations
* Educational content promoting responsible water usage

### Admin Moderation

Administrative users can:

* Review community reports
* Manage announcements
* Remove invalid or duplicate reports

---

## Technology Stack

### Frontend

* Kotlin
* Jetpack Compose
* Material Design 3

### Backend & Cloud Services

* Firebase Authentication
* Firebase Firestore
* Firebase Cloud Messaging

### Development Tools

* Android Studio
* Git
* GitHub

### Future Integrations

* Google Maps SDK
* Offline Data Synchronization
* Analytics Dashboard

---

## System Architecture

AquaWare follows a modern Android architecture using:

* MVVM (Model-View-ViewModel)
* Repository Pattern
* Firebase Cloud Services
* State Management with Compose

---

## Installation

### Prerequisites

* Android Studio Hedgehog or newer
* Android SDK 24+
* Firebase Project Configuration

### Setup

1. Clone the repository

```bash
git clone https://github.com/yourusername/AquaWare-Mobile.git
```

2. Open the project in Android Studio

3. Connect Firebase

* Create a Firebase project
* Enable Authentication
* Enable Firestore Database
* Enable Cloud Messaging
* Add the `google-services.json` file to the app directory

4. Sync Gradle

5. Build and run the application

---

## Project Structure

```text
app/
├── data/
│   ├── model/
│   ├── repository/
│   └── remote/
│
├── ui/
│   ├── authentication/
│   ├── dashboard/
│   ├── reports/
│   ├── notifications/
│   └── profile/
│
├── viewmodel/
│
└── util/
```

---

## Future Enhancements

### Version 2

* Interactive outage map
* Offline reporting support
* Photo attachments for reports
* Report verification system

### Version 3

* Historical outage analytics
* Predictive outage insights
* Utility provider integration
* Advanced notification filtering

---

## Learning Outcomes

This project demonstrates practical experience in:

* Android Development with Kotlin
* Jetpack Compose UI Development
* Firebase Authentication
* Cloud Database Management
* Push Notification Systems
* Mobile Application Architecture
* User Experience Design
* Real-Time Data Synchronization

---

## Author

Kayode Dorsett

Computer Science Student
University of the West Indies Five Islands Campus

GitHub: https://github.com/its-Kayo

---

## License

This project is developed for educational and portfolio purposes.
