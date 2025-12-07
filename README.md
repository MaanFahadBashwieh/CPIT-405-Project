SmartQ is a modern queue management system built using React, Vite, Firebase Authentication, and Firebase Firestore.
It allows administrators to create and manage queues, while users can easily join a queue by scanning a QR Code.

Authentication (Admin Only)

Firebase Authentication (Login + Register)

Secure session handling

Admin-only protected routes

Queue Management (Admin Panel)

Create a new queue with a chosen wait time per user

Pause / Resume queue

Next (serve next user)

Delete queue

View:

Users in the queue

Currently served user

Total active queues

Total users

User Queue Flow

Users scan a QR code generated for each queue

QR opens the join page


User joins queue by entering:

Name

Email

User gets:

Position in the queue

Estimated wait time
