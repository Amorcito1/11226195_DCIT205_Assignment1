# 11226195_DCIT205_Assignment1
# README

## Student Information

- **Name:** Theresa Apelegre Nyaama
- **Student ID:** 11226195

## Introduction

Welcome to my project repository! This README document provides essential information about me and the content of this repository.

## Project Overview

Welcome to the Missing Grade System—an innovative solution simplifying the tracking and resolution of missing grades in educational institutions. Boasting an intuitive dashboard, automated notifications, and a secure interface, our system ensures efficient communication and accountability. Instructors input grades, triggering automated alerts for students and instructors. The simplified user interface promotes transparency, allowing students to engage proactively. Administrators benefit from customizable reports for strategic decision-making. Elevate communication, accountability, and decision-making with the Missing Grade System—an essential tool for a more efficient, transparent, and collaborative educational experience.

## Directory StructureAssignment(missing grade system)/
├── components/
│   ├── LandingPage.js
│   ├── LoginPage.js
│   ├── DashboardPage.js
│   ├── GradeReportPage.js
│   ├── MissingGradeFormPage.js
│   ├── InstructorContactPage.js
│   ├── HelpAndSupportPage.js
│   ├── Navbar.js
│   ├── Footer.js
├── App.js
├── index.js
├── styles.css

components/:

This directory holds individual React components, each representing a different page or UI element of your application.
LandingPage.js: Component for the landing page, providing an overview of the system.
LoginPage.js: Component for the login page with a secure login form.
DashboardPage.js: Component displaying an overview of the student's current grades and any missing grade alerts.
GradeReportPage.js: Component showing a detailed view of all courses and grades, with the option to filter by semester/academic year.
MissingGradeFormPage.js: Component containing a form to report missing grades, including fields for course name, instructor name, expected grade, and an explanation field.
InstructorContactPage.js: Component listing instructors with contact details and providing an option to send a simulated email to the instructor.
HelpAndSupportPage.js: Component with an FAQ section regarding grade reporting and a contact form for technical support.
App.js:

The main entry point for your React application. It defines the overall structure of your application, including routing.
index.js:

The entry point for rendering your React app into the HTML document. It typically renders the App component.
styles.css:

This file contains global styles for your application. You can define common styles here and import them into your components.
Other Considerations:

You might consider creating additional directories for assets (images, icons, etc.) or utility functions if needed.
It's common to have a separate folder for Redux or other state management if your application requires it. As of now, your specification doesn't mention any state management, so it's not included in the structure.

