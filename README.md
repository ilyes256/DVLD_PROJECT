# Driving License Management System (DVLD Project)

## Overview
The **Driving License Management System (DVLD)** is a **C# Windows Forms (.NET)** application designed to automate the process of issuing, renewing, and managing driving licenses. It includes features such as application processing, license verification, examination scheduling, and user management.

### Three-Tier Architecture
This project follows a **Three-Tier Architecture**, ensuring modularity, scalability, and maintainability:
1. **Presentation Layer (UI)** – Developed using **C# Windows Forms (.NET)** for a user-friendly graphical interface.
2. **Business Logic Layer (BLL)** – Manages core logic and processing for license applications, renewals, and verifications.
3. **Data Access Layer (DAL)** – Handles database interactions with **Microsoft SQL Server** and **ADO.NET** for secure data storage.

## Core Services Provided
- Issuing a new driving license ($5)
- Re-examination ($5)
- License renewal ($5)
- Replacement for lost license ($5)
- Replacement for damaged license ($5)
- Releasing a suspended license ($5)
- Issuing an international license ($5)

## License Categories and Fees
- **Small Motorcycle License** (18 years, $15, 5 years)
- **Heavy Motorcycle License** (21 years, $30, 5 years)
- **Standard Car License** (18 years, $20, 10 years)
- **Commercial License (Taxi/Limo)** (21 years, $200, 10 years)
- **Agricultural Vehicle License** (21 years, $50, 10 years)
- **Small/Medium Bus License** (21 years, $250, 10 years)
- **Truck/Heavy Vehicle License** (21 years, $300, 10 years)

## Application Requirements
- **Minimum Age Requirement** – The applicant must meet the required age for the selected license category.
- **No Duplicate Licenses** – An applicant cannot hold two licenses of the same category.
- **Multiple License Allowance** – An applicant can hold licenses for different categories.
- **Valid Identification** – Applicants must submit a valid passport or national ID card.
- **Training Certification** – A training certificate is required before applying for license exams.

## Testing Process
1. **Vision Test** ($10 fee) – Required before proceeding.
2. **Theoretical Test** ($20 fee) – Covers traffic laws and road safety.
3. **Practical Driving Test** (Fee varies by license) – Hands-on driving evaluation.

## License Issuance
Once all tests are passed, a driving license is issued containing:
- License Number, Holder’s Photo, National ID, Full Name, Date of Birth, License Category, Issue Date, Expiration Date, License Conditions, License Status.

## Additional Services
- **License Inquiry** – Search by National ID or License Number.
- **Re-Examination** – Retake failed tests ($5 + test fee).
- **License Renewal** – $10 fee, vision test required.
- **Lost License Replacement** – $20 fee, system verifies eligibility.
- **Damaged License Replacement** – $20 fee, must surrender damaged license.
- **Suspended License Release** – Pay fines to retrieve license.
- **International Driving License** – $20 fee, valid Standard Car License required.

## Tech Stack
- **Frontend:** C# Windows Forms (.NET)
- **Backend:** C# (.NET Framework)
- **Database:** Microsoft SQL Server (.bak backup available)
- **Architecture:** Three-Tier Architecture

## Installation Guide
### Prerequisites
- **Visual Studio**
- **.NET Framework / .NET Core SDK**
- **Microsoft SQL Server & SSMS**

### Setup Steps
1. Clone the repository
  
2. Restore the database in SQL Server Management Studio (SSMS) using the provided **DVLD.bak** file

3. Update app.config with the database connection string.

4. Open the project in Visual Studio using the solution file **DVLD.sln**
