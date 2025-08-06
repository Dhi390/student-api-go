<<<<<<< HEAD
## Sample Response

```json
{
  "id": 1,
  "name": "Amit Kumar",
  "course": "B.Tech",
  "year": "3rd"
}
# student-api-go
=======
 Student API – GoLang + Postman Test

A minimal backend API built with GoLang that returns student data via a single endpoint. Includes a Postman collection for manual and automated testing using Newman CLI.

---

 Features

- Single GET endpoint: `/student`
- Returns student data in JSON format
- Postman collection included
- Newman CLI support for automation

---

 Tech Stack

- Language: GoLang  
- Testing Tools: Postman, Newman CLI  
- Server: net/http (standard Go library)

---

Project Structure

main.go                  → GoLang server with /student endpoint  
postman_collection.json  → Postman test collection  
README.md                → Project documentation

---

⚙How to Run

1. Start the server  
   go run main.go

2. Import `postman_collection.json` into Postman

3. Test the `/student` endpoint manually

4. Run automated test with Newman  
   newman run postman_collection.json

---

 Contact

Developer: Dhiru Yadav  
Email: yadavdhiru389@gmail.com  
LinkedIn: linkedin.com/in/dhiru-yadav  
GitHub: github.com/Dhi390
>>>>>>> 00ee78feba85d6f34a9af51a02809bd4437d246c
