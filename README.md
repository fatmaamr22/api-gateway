## 📋 The Project Applies the concepts of microservices And Spring Cloud
## 👥 Team Members
- **Fatma Amro**
- **Sayed Hassan**
- **Mohab Abdelsalam**
- **Mohamed Khaled**

## 🛠️ Prerequisites
Make sure you have the following installed:
- **Java JDK 8** or higher
- **MySQL Server**
- **Maven 3**

## Other Repos
- **https://github.com/fatmaamr22/api-gateway**
- **https://github.com/mohab-wahdan/eureca-server**
- **https://github.com/sayedhassan-a/students-service**
- **https://github.com/mohab-wahdan/instructors-servic**
- **https://github.com/fatmaamr22/courses-servic**
- **https://github.com/Mohamad-Khalid/rooms-service**

## 🚀 How to Run the Project

### Step 1: Clone All Repositories

1. **Create a new database in MySQL:**
    ```sql
   create database microStudent;
   create database microCourse;
    ```
### Step 2: in eureka app 
```bash
mvn spring-boot:run
```
### Step 3: in api-gateway app 
```bash
mvn spring-boot:run
```
### Step 4: in student app 
```bash
mvn spring-boot:run
```
### Step 5: in course app 
```bash
mvn spring-boot:run
```
### Step 6: finally try some requests to test the app using postman

## some links to test with:
- **http://localhost:8087/courses/1/students**
- **http://localhost:8087/sayed/1/students**

