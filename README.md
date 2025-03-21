# PatInformed Automation

This is a Selenium WebDriver-based test automation project for searching patents on the [WIPO Pat-Informed](https://patinformed.wipo.int/) website.

## **Project Overview**
This project automates the process of:
1. Opening the Pat-Informed website.
2. Accepting terms and conditions.
3. Searching for a patent dynamically based on user input.
4. Clicking on the first result.
5. Extracting and displaying the **Filing Date** and **Publication Date**.

## **Technologies Used**
- **Java** (Programming Language)
- **Selenium WebDriver** (Automation Framework)
- **TestNG** (Testing Framework)
- **Maven** (Dependency Management)

## **Installation Steps**
### **1. Prerequisites**
Ensure you have the following installed:
- **Java 8 or later**
- **Eclipse IDE** (or any Java-supported IDE)
- **Maven**
- **Google Chrome** (latest version)
- **ChromeDriver** (Ensure it matches your Chrome version)

# TestAssignment

## 🚀 How to Run the Maven Project

### **Prerequisites**
Ensure you have the following installed:
- **Java (JDK 11 or later)** → Check with `java -version`
- **Apache Maven** → Check with `mvn -v`
- **Git (optional)** → Check with `git --version`

---

### **1️⃣ Clone the Repository (If Not Already Cloned)**
```sh
 git clone https://github.com/Mahadeva1437/TestAssignment.git
 cd TestAssignment
```

---

### **2️⃣ Build & Run the Project**
#### **Step 1: Navigate to Project Directory**
```sh
cd C:\Users\Dell\eclipse-workspace2\TestAssignment
```

#### **Step 2: Clean the Project**
```sh
mvn clean
```

#### **Step 3: Compile the Source Code**
```sh
mvn compile
```

#### **Step 4: Run Unit Tests** (if applicable)
```sh
mvn test
```

#### **Step 5: Package the Project**
```sh
mvn package
```
This will generate a JAR/WAR file inside the `target/` folder.

#### **Step 6: Run the Application**

**(A) If it's a Java Application (`.jar` file)**
```sh
java -jar target/TestAssignment-0.0.1-SNAPSHOT.jar
```

**(B) If it's a Web Application (`.war` file)**
Deploy the `.war` file to Tomcat or run:
```sh
mvn tomcat7:run
```

**(C) If the Project Has a `main` Method**
```sh
mvn exec:java -Dexec.mainClass="com.example.MainClass"
```
Replace `com.example.MainClass` with the actual fully qualified class name.

---

### **3️⃣ Push Latest Code to GitHub**
#### **Step 1: Check Status**
```sh
git status
```
#### **Step 2: Add Changes**
```sh
git add .
```
#### **Step 3: Commit Changes**
```sh
git commit -m "Latest code update with fixes"
```
#### **Step 4: Pull the Latest Code to Avoid Conflicts**
```sh
git pull origin main --rebase
```
#### **Step 5: Push Changes**
```sh
git push origin main
```

---

### **🔍 Troubleshooting**
- **Check Maven Version**: `mvn -v`
- **Check Java Version**: `java -version`
- **Enable Debugging**: `mvn clean install -X`

🚀 **Now your Maven project is set up and ready to run!**



### **2. Clone the Repository**
Run the following command in your terminal:
```sh
git clone [<repository-url>](https://github.com/Mahadeva1437/TestAssignment.git)

