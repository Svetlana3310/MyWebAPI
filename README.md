# MyWebAPI

1. Get All Students
GET /api/students
curl -X GET http://localhost:8081/api/students


2. Get a Specific Student by ID
GET /api/students/{id}
curl -X GET http://localhost:8081/api/students/1


3. Create a New Student
POST /api/students
curl -X POST http://localhost:8081/api/students \
-H "Content-Type: application/json" \
-d '{"name":"Charlie"}'


4. Update an Existing Student
PUT /api/students/{id}
curl -X PUT http://localhost:8081/api/students/1 \
-H "Content-Type: application/json" \
-d '{"id":1,"name":"UpdatedStudent"}'


5. Delete a Student
DELETE /api/students/{id}
curl -X DELETE http://localhost:8081/api/students/1

GET /api/students: Retrieves a list of all students.
GET /api/students/{id}: Retrieves a specific student by their ID.
POST /api/students: Creates a new student.
PUT /api/students/{id}: Updates an existing student.
DELETE /api/students/{id}: Deletes a student by their ID.

1. Get All Subjects
GET /api/subjects
curl -X GET http://localhost:5000/api/subjects


2. Get a Specific Subject by ID
GET /api/subjects/{id}
curl -X GET http://localhost:5000/api/subjects/1


3. Create a New Subject
POST /api/subjects
curl -X POST http://localhost:5000/api/subjects \
-H "Content-Type: application/json" \
-d '{"name":"History"}'

4. Update an Existing Subject
PUT /api/subjects/{id}
curl -X PUT http://localhost:5000/api/subjects/1 \
-H "Content-Type: application/json" \
-d '{"id":1,"name":"UpdatedSubject"}'

5. Delete a Subject
DELETE /api/subjects/{id}
curl -X DELETE http://localhost:5000/api/subjects/1

GET /api/subjects: Retrieves a list of all subjects.
GET /api/subjects/{id}: Retrieves a specific subject by its ID.
POST /api/subjects: Creates a new subject.
PUT /api/subjects/{id}: Updates an existing subject.
DELETE /api/subjects/{id}: Deletes a subject by its ID.
