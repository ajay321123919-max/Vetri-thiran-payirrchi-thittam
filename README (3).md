# 3. Project Design Phase

## System Components
| Component | Purpose |
|---|---|
| ServiceNow Instance | Configuration environment |
| EEE User | Test identity |
| bb1 | READ permission |
| bb2 | CREATE permission |
| bb3 | WRITE permission |
| bb4 | DELETE permission |
| u_institution_details | Protected custom table |

## Table Design
- Student Roll Number – Auto Number
- Student Name – Reference to User
- Faculty Name – Reference to User
- Branch – Choice: ECE / EEE / CSE
- Email – String
- Phone Number – String
- Description – Multi String
