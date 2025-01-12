# CODTECH-SQL-Task3

**Name**: Sahil Ningonda Sankeshwari

**Company**: CODTECH IT SOLUTIONS

**ID** :CT08LPU

**Domain**: SQL

**Tasks Duration**: January 10th,2025 to February 10th, 2025.

**Mentor**:Santhosh

**Task 3: Database Migration**

**Objective**:
Migrate data between two databases (e.g., MySQL to PostgreSQL) while ensuring data integrity.

**Purpose**:
Data migration ensures seamless transitions between systems, maintaining accessibility and accuracy of data during platform changes.

**Deliverable**:
1.Scripts for data migration
2.A summary report explaining the migration process

**Output for Task3:**
We’ll create two additional tables (source_table and destination_table) to demonstrate data migration (Task 3) and backup/recovery (Task 4).

source_table


![SourceTable](https://github.com/user-attachments/assets/ff27bbfe-7cb2-4a66-9223-c35b707ed421)

destination_table


![destinationTable](https://github.com/user-attachments/assets/bff6c82f-c42d-4192-8595-c484bf3439ba)

**Migration Query :**
-- Migrate data from source_table to destination_table
INSERT INTO destination_table (name, age, city)
SELECT name, age, city
FROM source_table;

Migrate data from source_table to destination_table.



![Q31](https://github.com/user-attachments/assets/0d68c7b9-cb04-423e-8854-4713a75b62cb)

**Explanation:**

The data from source_table was successfully migrated to destination_table.

Both tables now contain identical rows, ensuring data integrity.



