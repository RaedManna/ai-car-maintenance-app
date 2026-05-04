### AI Predictive Maintenance App for Cars

An AI-powered predictive maintenance mobile application for vehicles, developed as a Computer Engineering graduation project by a team of four students.

The application focuses on predicting vehicle part failures, fuel-related status, and maintenance/service needs, while also helping users find nearby mechanics, dealerships, charging stations, and service centers.

---

## Overview

This project was designed to combine mobile development, backend/database systems, OCR, external APIs, testing, and AI-assisted prediction logic into one practical vehicle maintenance application.

The app allows users to manage vehicle-related information, analyze possible maintenance needs, extract data from vehicle-related documents, and receive location-based service recommendations.

The project was received very positively by the Computer Engineering faculty.

---

## Team and My Contribution

This project was developed by a team of four Computer Engineering students.

My main responsibilities focused on:

- Backend development
- Database design and database workflows
- Supabase integration
- Testing and validation
- Backend-to-frontend data flow support
- API integration support
- Ensuring reliability across core application workflows

I contributed mainly to the technical foundation behind the application, making sure that data storage, backend logic, database operations, and testing flows worked correctly with the rest of the system.

---

## Tech Stack

**Mobile Frontend:** Flutter, Dart, Android Studio  
**Backend & Database:** Supabase, PostgreSQL  
**AI / Data:** Python, Machine Learning, Deep Learning, Predictive Analytics  
**OCR:** OCR-based document parsing  
**APIs:** Google Places API, Google Maps API  
**Testing:** Unit Testing, Integration Testing, API Testing, Database Testing, Functional Testing  

---

## Main Features

- Vehicle part failure prediction
- Fuel-related status and maintenance/service prediction
- Vehicle information management
- OCR-based document parsing and information extraction
- Supabase backend and database integration
- Nearby mechanics, dealerships, charging stations, and service center recommendations
- Google Places API integration for location-based service suggestions
- Testing for backend, database, OCR, API, and recommendation workflows

---

## System Modules

### Backend and Database Module

The backend/database layer was built using Supabase and PostgreSQL.

This module handled:

- User and vehicle data storage
- Maintenance-related records
- Database insert, update, fetch, and validation flows
- Backend support for prediction and recommendation workflows
- Data consistency between the mobile app and Supabase
- Handling missing, invalid, or incomplete data

My work was mainly focused on making sure the backend and database flows were reliable, structured, and properly connected to the application.

---

### AI Prediction Module

The AI prediction module was designed to estimate vehicle maintenance needs, including possible part failures and fuel-related status.

This module supported:

- Vehicle part failure prediction
- Fuel-related status prediction
- Maintenance/service need estimation
- Processing vehicle-related inputs for prediction workflows

---

### Mobile Application Module

The mobile application was built using Flutter and Android Studio.

This module allowed users to:

- Enter and manage vehicle information
- View maintenance predictions
- Upload or scan vehicle-related documents
- Receive nearby service recommendations
- Navigate between the main app features

---

### OCR Module

The OCR module was used to extract relevant information from vehicle-related documents.

It supported:

- Document text extraction
- Vehicle information extraction
- Reducing manual user input
- Passing extracted information into backend and prediction workflows

---

### Recommendation Module

The recommendation module integrated Google Places API to suggest nearby services based on user needs and location.

It supported recommendations for:

- Mechanics
- Dealerships
- Charging stations
- Service centers

---

## Testing

Testing was a major part of the project, especially for validating backend, database, OCR, API, recommendation, and full application workflows.

### Unit Testing

Unit tests were used to validate individual functions and modules, including:

- Vehicle part failure prediction logic
- Fuel-status prediction logic
- Input validation functions
- Data preprocessing functions
- OCR parsing helper functions
- Supabase helper/query functions
- Recommendation filtering logic

---

### Integration Testing

Integration tests were used to verify that different parts of the system worked correctly together.

Tested integration areas included:

- Flutter frontend integration with Supabase
- Frontend integration with AI prediction outputs
- OCR integration with extracted vehicle data
- Supabase database flows with user and vehicle records
- Google Places API integration for service recommendations
- Backend/database support for full maintenance recommendation workflows

---

### API Testing

API testing was used to validate external service behavior and response handling.

Tested areas included:

- Google Places API request and response handling
- Location-based search result validation
- Handling failed or incomplete API responses
- Validating service categories such as mechanics, dealerships, charging stations, and service centers
- Ensuring recommendation results were relevant to the user’s location and selected service need

---

### Database Testing

Database testing focused on verifying that application data was stored, retrieved, updated, and handled correctly through Supabase.

Tested areas included:

- User data storage
- Vehicle data storage
- Maintenance-related records
- Insert, update, fetch, and validation operations
- Data consistency between Flutter forms and Supabase tables
- Handling missing, invalid, or incomplete records
- Ensuring backend flows returned the expected data to the application

---

### OCR Testing

OCR testing was used to validate document parsing and information extraction.

Tested areas included:

- Extraction accuracy from vehicle-related documents
- Handling unclear or incomplete document inputs
- Parsing key vehicle information fields
- Validating extracted text before storing or using it in prediction workflows
- Checking whether extracted data could be correctly passed into backend/database flows

---

### UI and Functional Testing

The mobile application was manually and functionally tested to ensure that important user flows worked as expected.

Tested flows included:

- Adding vehicle information
- Editing vehicle information
- Viewing predicted maintenance results
- Uploading or scanning documents for OCR
- Viewing nearby recommended services
- Navigating between main app screens
- Handling invalid input and empty fields
- Checking whether displayed results matched stored backend data

---

### End-to-End Testing

End-to-end testing was used to validate complete user workflows across the system.

Example tested workflows included:

- Entering vehicle information
- Saving vehicle data to Supabase
- Running prediction logic
- Extracting document data using OCR
- Updating backend/database records
- Retrieving recommendations through Google Places API
- Displaying final maintenance and service results in the mobile app

---

### Error Handling and Edge Case Testing

The system was tested against common failure scenarios, including:

- Missing vehicle data
- Invalid user inputs
- Empty OCR results
- Failed API responses
- No nearby service results found
- Database connection or query errors
- Unexpected prediction outputs
- Incomplete records
- Incorrect or unsupported document formats

---

## Project Outcome

- Completed as a Computer Engineering graduation project
- Developed by a team of four students
- Recognized by Computer Engineering faculty as one of the strongest projects of the year
- Demonstrated practical use of backend development, database systems, mobile development, AI-assisted logic, OCR, API integration, and software testing

---

## Author

**Raed H. Manna**  
Computer Engineering Graduate | Junior Full-Stack Developer  

Main contribution areas: Backend, Database, Supabase Integration, Testing, Workflow Validation

- GitHub: [RaedManna](https://github.com/RaedManna)
- LinkedIn: [raedhmanna](https://www.linkedin.com/in/raedhmanna)
- Email: raedmanna1@yahoo.com
