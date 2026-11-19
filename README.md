# oop-employee-management-java

# Employee Salary Management System (OOP in Java) 💼☕

## 📌 Overview | نظرة عامة
**English:**  
A Java Object-Oriented Programming (OOP) task demonstrating **Abstraction**, **Inheritance**, **Polymorphism**, and **Packages**. The program models different types of employees (`Contractor` and `Fulltime`) inheriting from an abstract `Employee` base class and calculates their salaries dynamically.

**العربية:**  
تطبيق عملي على مفاهيم البرمجة كائنية التوجه (OOP) بلغة Java، يوضح استخدام **التجريد (Abstraction)**، **الوراثة (Inheritance)**، **تعدد الأشكال (Polymorphism)**، وتنظيم الكود داخل **الحزم (Packages)** لحساب رواتب الموظفين بمختلف أنواعهم.

---

## 🏗️ Project Structure | هيكل المشروع
The project is organized into two main packages:
1. **`emp` Package:**
   - `Employee` *(Abstract Class)*: Holds `protected` attributes (`emp_name`, `payhour`), a parameterized constructor, and an abstract method `calcsal()`.
   - `Contractor` *(Subclass)*: Extends `Employee`, adds a `private` `workhour` attribute, and calculates salary as `workhour * payhour`.
   - `Fulltime` *(Subclass)*: Extends `Employee` and calculates daily salary based on a fixed 8-hour shift (`payhour * 8`).
2. **`Work` Package:**
   - `Main`: Contains the `main` method, initializes a polymorphic array of `Employee` objects, and uses the `instanceof` operator to identify each employee type and display their salary.

---

## 💻 Expected Output | مخرجات البرنامج
```text
Part time
salary: 5000
Part time
salary: 3200
Full time
salary: 4000
Full time
salary: 1600
