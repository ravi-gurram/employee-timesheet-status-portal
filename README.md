# Employee Timesheet and Weekly Status Report Portal

A full-stack web application built with **Spring Boot**, **Thymeleaf**, **Spring Data JPA**, and **H2 Database**. This portal allows employees to submit timesheets and weekly status reports, view submissions, and enables administrators to review and manage all records.

---

## 📋 Features

- **Submit Timesheet** — Log daily hours by project/client with auto-calculated totals
- **Submit Weekly Status Report** — Document accomplishments, achievements, blockers, and plans
- **View Submissions** — Browse and search all submitted timesheets and status reports
- **Admin Review Dashboard** — Update submission statuses (Submitted → Reviewed → Approved / Rejected)
- **Print / Export** — Browser-based print-friendly views for PDF export
- **H2 In-Memory Database** — Built-in console for data inspection

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Language | Java 17 |
| Framework | Spring Boot 3.2.3 |
| Web | Spring Web (MVC) |
| Persistence | Spring Data JPA + Hibernate |
| Database | H2 (in-memory) |
| Build Tool | Maven |
| Templating | Thymeleaf |
| Frontend | HTML5, CSS3, Vanilla JavaScript |

---

## 📁 Folder Structure

```
employee-timesheet-status-portal/
├── src/
│   └── main/
│       ├── java/com/timesheet/portal/
...
```

---

## 🚀 How to Run Locally

```bash
git clone <repo-url>
cd employee-timesheet-status-portal
mvn clean install
mvn spring-boot:run
```

App: http://localhost:8080
H2 Console: http://localhost:8080/h2-console
