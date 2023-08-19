# SupportHero

## R1: Description of your website

### Purpose:

The primary purpose of this web application is to streamline and standardise the note-taking process for support workers during their one-on-one sessions with clients. This addresses the problem of inconsistent and often inadequate note-taking practices which result in incomplete client profiles. Such gaps in documentation can affect the quality of client care and add undue workload to team leaders. By ensuring that each interaction with a client is consistently documented in a structured manner, the application aims to enhance the quality of client care, reduce oversight errors, and alleviate the burden on team leaders.

### Functionality / features:
Client Profiles: These profiles contain information about each client, including their care plan, personal details, who their care leader is. Each profile will have an option to view a full history of previous progress notes for that Client.
Structured Note Entry: This feature leads support workers through a structured form when they document a shift after it has completed. This ensures progress note standards for increased readability and better outcomes for Clients. 
Dashboard: When a user is logged in, they have a dashboard where they can select to see upcoming shifts, see if they are missing any notes and a history of their previous notes. Workers can also see a list of the Clients they work with.
User Authentication: Login function to ensure users can only see details they are allowed to. This would also allow for admins to be authenticated so they are able to create Client and Worker profiles. Would include other admin tools like removing users as well. 
Database Tables: Will have separate tables for Clients, Workers, Progress Notes and Rosters to manage the data efficiently. 
Data Encryption: In an effort to maintain confidentiality and ensure privacy of client interactions, all notes and client profiles will be encrypted.

### Target audience:
Organisations or Businesses would use this software as their way to support their employees in tracking their shifts, clients and note taking.
Support Leaders and Administrators would use this software to add new clients and workers, manage their pairings and track progress notes.
Support Workers: This would be the largest section of users who would interact with the system regularly. Used to look up Client information, shift information and submitting their progress notes. 

### Tech stack:
Frontend: React will be used to create an interactive and responsive frontend.
Backend: Node.js and Express.js. Node will allow the application to execute Javascript on the server side and express will be used to create the applications API.
Database: MongoDB - NoSQL database that will store data in a JSON format. 
Authentication: JWT will be used for user authentication. 
Encryption: The application will use bcrypt for hashing passwords and encrypting the data that needs to be hashed for privacy reasons. 

## R2: Dataflow Diagram

## R3: Application Architecture Diagram

## R4: User Stories

## R5: Wireframes

## R6: Trello Board 