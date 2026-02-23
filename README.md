# 🔍 Defect Identification

This document identifies defects in the Online Course Registration System requirements.

---

# 1️⃣ Inconsistencies (5)

### 1. Registration Deadline Conflict (R2 & R3)
- R2: Registration is not allowed after the deadline.
- R3: Late registration is allowed for 3 days after the deadline.
- Issue: These two requirements contradict each other.

---

### 2. Seat Availability Conflict (R4 & R5)
- R4: The system shall show available seats.
- R5: The system shall allow registration even if seats are full.
- Issue: Registration should not be allowed if seats are full.

---

### 3. Schedule Conflict Rule (R9 & R10)
- R9: The system shall prevent schedule conflicts.
- R10: Students may register for two courses at the same time if one is online.
- Issue: One requirement blocks conflicts while the other allows it.

---

### 4. Credit Hour Limit Conflict (R11 & R12)
- R11: Students are limited to 18 credit hours.
- R12: Students may register up to 24 credit hours with advisor approval.
- Issue: Maximum credit hour limit is unclear.

---

### 5. Drop Deadline Conflict (R13 & R15)
- R13: Students may drop courses until Week 6.
- R15: Course drops are not allowed after the deadline.
- Issue: The drop deadline is not clearly defined.

---

# 2️⃣ Incompleteness (5)

### 6. Confirmation Method Not Specified (R6)
- The system shall send confirmation.
- Issue: Method (email/SMS) and timing are not specified.

---

### 7. Instructor Approval Process Undefined (R8)
- Issue: Approval process is not described (manual or system-based).

---

### 8. Advisor Approval Process Missing (R12)
- Issue: It is not defined how advisor approval is recorded.

---

### 9. Drop Fee Amount Missing (R14)
- Issue: The exact fee amount is not specified.

---

### 10. Waitlist Details Missing (R16)
- Issue: Maximum waitlist size and visibility are not defined.

---

# 3️⃣ Ambiguities (3)

### 11. “Register Quickly” (R20)
- Issue: The term "quickly" is unclear and not measurable.

---

### 12. “Send Confirmation” (R6)
- Issue: It is unclear what type of confirmation is being sent.

---

### 13. “Priority Enrollment” (R19)
- Issue: The method of giving priority is not clearly explained.

---

# 4️⃣ Unverifiable Requirements (2)

### 14. Performance Requirement (R20)
- “Students shall be able to register quickly.”
- Issue: No measurable performance criteria provided.

---

### 15. Confirmation Requirement (R6)
- “The system shall send confirmation.”
- Issue: No timing or method defined for verification.

---

# 5️⃣ Missing Business Rules (Additional Findings)

### 16. Maximum Number of Courses Not Defined
- Only credit hours are defined, not number of courses.

---

### 17. Late Registration Eligibility Not Defined
- It is not specified who is allowed late registration.

---

### 18. Refund Policy Not Defined
- No rule exists regarding refund after course drop.

---

# ✅ Summary

- 5 Inconsistencies  
- 5 Incompleteness  
- 3 Ambiguities  
- 2 Unverifiable Requirements  
- 3 Missing Business Rules  

Total Defects Identified: 18
