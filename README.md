# VTS
**Vacation tracking system**

# 1. Vision
A Vacation Tracking System (VTS) will provide individual employees with the capability to manage their own vacation time, sick leave, and personal time off, without having to be an expert in company policy or the local facility’s leave policies.The most important goal of this system is to give individual employees the capability and responsibility to manage this particular aspect of their employment 
agreements with the company. 

#2. Actors 
The system contains the following actors.

- Employee: The main user of this system. An employee uses this system to manage his or her vacation time. 
- Manager: An employee who has all the abilities and goals of a regular employee, but with the added responsibility of approving vacation requests for immediate subordinates. 
- Clerk: A member of the HR department who has sufficient rights to view employees’ personal data and is responsible for ensuring that employees’ information in all HR systems is up to date and correct.
- System Admin: A role responsible for the smooth running of the system’s technical resources 

#3. Functional Requirements 

A. Employee requirements:
- FR-1 : Employee can login to the system using the portal
- FR-2 : System must validate the employee credentials 
- FR-3 : Validate the applied leave days if employee is eligible and have enough balance
- FR-4 : view all leave requests " pending - approved - cancelled - rejected "
- FR-5 : system must allow HR to edit any of all requests manually 
- FR-6 : Route requests that needs manager approval to the employee direct manager
- FR-7 : Track leave requests and notify employee of any update using email   

B. Manager requirements:
- FR-8 : System will allow manager to view employee leave balance and new request
- FR-9 : Notify manager using email when new leave request needs approval is submitted 
- FR-10 : Manager can reject - accept any application applied by employee
- F4-11 : System allows manager to award employees with extra time   

C. HR requirements:
- FR-12 : HR is allowed to edit employee records
- FR-13 : HR can manage leave types 
- FR-14 : HR can override leave rules

D. System Admin requirements:
- FR-15 : System admin can backup data from the system logs

#4. Non-Functional Requirements 
- NFR-1 : System should have friendly and easy to use interface 
- NFR-2 : System should have strong security system to ensure employee can access only the valid records 
- NFR-3 : System must handle many requests in peak time efficiency
- NFR-4 : system shall have a calendar to help employees track leaves 

#5. Constrains 
- System must integrate with HR legacy system
- The system shall use the company's existing SSO infrastructure
- Employee can apply leave up to the next 18 months

#6. Diagrams
--
A. Use-case Diagram 

<img width="735" height="688" alt="image" src="https://github.com/user-attachments/assets/bdf7ed1e-07a3-4afd-ae03-06e62525164c" />










