# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Đinh Quang Minh  
**MSSV:** 1871020392  
**Lớp/Nhóm:** CNTT 18-01  

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Student Grade Database
  - Description: Contains all student grades and academic records
  - Importance: High

- Asset 2: User Accounts
  - Description: Accounts for lecturers and students to access the system
  - Importance: High

- Asset 3: System Logs
  - Description: Records all system activities and grade changes
  - Importance: Medium

---

## 2. Mapping CIA

- Incident A:
  - Confidentiality: Low
  - Integrity: Low
  - Availability: High

- Incident B:
  - Confidentiality: Low
  - Integrity: High
  - Availability: Medium

- Incident C:
  - Confidentiality: High
  - Integrity: Low
  - Availability: Low

---

## 3. Phân tích sự cố B

- Threat: Unauthorized user or insider modifies grades without permission  
- Vulnerability: Weak access control, lack of monitoring logs, no multi-factor authentication  
- Mitigation: Enable MFA, enforce role-based access control, log all grade changes, require approval for modifications  

---

## 4. Reflection

If I were an administrator, I would prioritize Incident B because unauthorized grade modification directly affects students' outcomes and system trust. Incident A is temporary and can be resolved quickly. Incident C should be investigated in parallel. Ensuring strict control over grade modification and maintaining logs is critical.

---

## 5. Bonus Flag

`FIT4012{A-A-B-I-C-C}`