Create a professional, high-resolution UML Class Diagram for a **Clinic Management System** based on the following classes:

1. **User:** id, name, email, password, status
2. **Role:** id, name
3. **UserRole:** user_id, role_id
4. **Patient:** id, patient_code, full_name, gender, dob, phone, address
5. **Doctor:** id, user_id, specialization, phone, status
6. **DoctorSchedule:** id, doctor_id, day_of_week, start_time, end_time
7. **Appointment:** id, patient_id, doctor_id, appointment_date, start_time, end_time, status

**Relationships:**
- User (1) → Doctor (0..1)
- User (1) → UserRole (0..*)
- Role (1) → UserRole (0..*)
- Patient (1) → Appointment (0..*)
- Doctor (1) → Appointment (0..*)
- Doctor (1) → DoctorSchedule (0..*)

**Design Requirements:**
- Follow standard UML class diagram notation.
- Display all attributes with their correct data types.
- Show accurate relationships and multiplicities.
- Use modern, professional styling with subtle colors.
- Arrange classes logically with minimal crossing lines.
- Use a clean white background and readable typography.
- Generate a sharp, high-resolution diagram suitable for university teaching and software documentation.
- Do not omit classes, attributes, or relationships.