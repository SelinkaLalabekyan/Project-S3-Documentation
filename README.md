# Project-S3-Documentation and Checklist
Supporting documentation, project management board, and final report assets for the Clarity Map application.

Screenshots, Diagrams, and Other Supporting Documentation

This section confirms the integration of key visual and structural elements into the report and provides a clear list of project artifacts created during the development process.

Application Screenshots (Visual Evidence): All screenshots demonstrating the functional user flows of the platform are included in Section 5.3 User Guide or Demonstration of Software Functionality.

Figure 1. Sign In Window

Figure 2. User Dashboard Showing Profile Metrics and Impact Over Time

Figure 3. Community Leaderboard and Weekly Goals

Figure 4. Dashboard with Interactive Pollution Heatmap

Figure 5. Mission Information Window

Figure 6. Upload Before Photo and Geo-Validation Check

Figure 7. Admin Panel for Mission Verification (Before/After & Approval)

Software Architecture Diagram: A diagram illustrating the clear separation of the multi-component system (Frontend, Flask Backend API, PostgreSQL Database, and the dedicated ML Microservice) to confirm a scalable microservice design.

Code Snippets: Python code snippets demonstrating the core backend logic for Geo-Validation, ML Inference, and Reward Calculation are included in Section 3.1 Detailed Tasks and Implementation.

ML Model Summary: A summary table showing the Convolutional Neural Network (CNN) model architecture (layers, parameters) and initial training accuracy, verifying the technical feasibility of the ML component.


ADA Compliance Checklist and Evidence of Adherence

The Clarity Map platform adhered to core principles of the Web Content Accessibility Guidelines (WCAG 2.1) to ensure usability for individuals with disabilities.

WCAG 2.1 Principle,Checklist Item,Evidence/Implementation
Perceivable,Color Contrast (1.4.3),"Implementation of a high-contrast color palette, particularly for text on buttons and the severity levels on the Pollution Heatmap (Red/Yellow/Green), ensuring readability."
,Text Alternatives (1.1.1),"Use of descriptive alt text for all non-text content, especially on uploaded images (the ""Before"" and ""After"" photos) to ensure screen reader compatibility."
Operable,Keyboard Accessibility (2.1.1),"Confirmation that all interactive elements (Sign-in form, Mission buttons, Admin Approve/Reject buttons) are fully operable using only the keyboard."
,Focus Indicator (2.4.7),Implementation of clear visual focus indicators (high-contrast outlines) to show the user which element is currently selected during keyboard navigation.
Understandable,Predictable Navigation (3.2.3),"Consistent placement of navigation components (Dashboard, Missions, Logout) and uniform application of the main green-theme buttons across all pages."
,Input Assistance (3.3),"Clear, simple labeling and error messages for the Sign-in and Mission Submission forms, guiding the user without ambiguity."
