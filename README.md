# subjects

### Task Description

You will receive a file containing a list of students, their grade averages, and their subject preferences in the following format:

```
Name        Grade Average    1st Pick    2nd Pick    3rd Pick    4th Pick    5th Pick    6th Pick
Fabian      2.6              IOT         SOS         OPS         BAP         GAD         ENT
John        2.8              SOS         OPS         BAP         IOT         GAD         ENT
Tyrone      3.0              ENT         OPS         GAD         IOT         SOS         BAP
```

Each student is able to choose from the following subjects:
- IOT (Internet of Things)
- ENT (Entrepreneurship)
- OPS (Operations)
- BAP (Business Applications)
- GAD (Game Design)
- SOS (Social Sciences)

### Student Subject Selection Process

1. **First Pick Preference**: Each student will select their preferred subjects in order of preference. The first subject listed by a student is their top choice.
2. **Priority Assignment**: Students with lower grade averages (better grades) get priority in subject assignment.
3. **Subject Capacity**: The number of students in each subject is determined by dividing the total number of students by the number of subjects. For example, if there are 25 students and 6 subjects, each subject should ideally have \( \frac{25}{6} \approx 4 \) students, with adjustments as necessary to accommodate all students.

### Assignment Algorithm

1. Assign each student to their top choice if possible.
2. If a student’s top choice is full, attempt to assign them to their second choice, and so on.
3. Continue this process until all students are assigned to a subject.

### Implementation Requirements

- Implement this subject assignment process in Java using Maven.
- Ensure your implementation is thoroughly tested.

### Deliverables

1. **Java Program**: A Maven project that implements the described functionality.
2. **Tests**: Include tests to verify that the subject assignment works correctly according to the rules stated.

---
