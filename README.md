**Credit Risk & Loan Monitoring Platform**
A MySQL-based relational database system that simulates a simplified core banking loan monitoring platform. It manages borrowers, loans, EMI schedules, payments, delinquency tracking, and portfolio risk reporting using triggers and stored procedures.

**Features**

1️⃣ Borrower & Loan Management
Maintain complete borrower profiles and manage multiple loans with proper status tracking (Active, Closed, Defaulted, Written-off).

2️⃣ Automated EMI & Repayment Schedule Generation
Generate installment schedules based on loan terms and track due dates, installment amounts, and payment status.

3️⃣ Payment Processing & Allocation System
Record payments and allocate them to specific EMIs, supporting partial payments and automatic balance updates.

4️⃣ Delinquency & Risk Bucket Classification
Automatically detect overdue installments and classify loans into risk categories (Current, 30/60/90+ days overdue).

5️⃣ Portfolio Analytics & Performance Reporting
Generate reports such as Portfolio at Risk (PAR), collection rate, branch performance, and outstanding loan summaries.

6️⃣ Audit Logging & Data Integrity Enforcement
Implement primary/foreign key constraints, triggers, and audit logs to ensure data consistency and traceability.

**Folder Structure**
docs/ – design docs & diagrams
sql/ – SQL scripts
