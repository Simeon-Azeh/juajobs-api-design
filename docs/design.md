# JuaJobs API Design Document

## Resource Overview
- **Users**: Workers and employers with authentication
- **Job Postings**: Listings created by employers
- **Applications**: Worker submissions for jobs  
- **Reviews**: Feedback after job completion

## Key Features
- JWT authentication
- Paginated job listings
- Mobile-friendly design (phone numbers, SMS notifications)
- Multi-currency support (KES, NGN, ZAR)

## Entity-Relationship Diagram
![ER Diagram](/diagrams/er_diagram.png)

## Authentication Flow
1. Register → 2. Login → 3. Use JWT in Authorization header