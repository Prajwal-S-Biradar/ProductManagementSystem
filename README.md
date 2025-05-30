
# ProductManagementSystem

🚀 **Features**

### 🔄 Complete CRUD Operations

Add, update, delete, and view product records with ease.

### 🔍 Advanced Search

Quickly search product entries by Product ID or Category.

### 📊 Comprehensive Reports

Generate insightful reports, including:

* 📈 Products with low or high stock levels
* 📚 Products filtered by category or price range
* 🏆 Top N best-selling or highest revenue-generating products

---

## ✅ Input Validation

* **Client-side**: HTML5, JavaScript
* **Server-side**: JSP/Java

---

## 🎨 Professional UI

* Responsive and intuitive interface built with Bootstrap 5
* Smooth navigation and clean, colorful layouts
* Modular design using JSP (View), Servlets (Controller), and JDBC/MySQL (Model)

---

## 🗃️ Database Integration

* MySQL backend with efficient JDBC connection pooling

---

### 🗃️ Database Schema

```sql
CREATE TABLE Products (
ProductID INT PRIMARY KEY,
ProductName VARCHAR(100),
Category VARCHAR(50),
Price DECIMAL(10,2),
Quantity INT
);
```
 
---

## 📋 Prerequisites

Ensure the following software is installed before running the project:

* Java Development Kit (JDK 8 or higher)
* Apache Tomcat (9.0 or higher)
* MySQL Server or XAMPP
* MySQL JDBC Driver (`mysql-connector-java`)
* Modern Web Browser: Chrome, Firefox, or Edge

---

| Module Name          | Description                                           |
| -------------------- | ----------------------------------------------------- |
| `ProductAdd.jsp`     | Add new products                                      |
| `ProductUpdate.jsp`  | Update details of existing products                   |
| `ProductDelete.jsp`  | Delete a product record                               |
| `ProductDisplay.jsp` | View all products or search by Product ID or Category |
| `ProductReports.jsp` | Generate dynamic inventory and sales reports          |

---

## 🎨 UI Highlights

* Clean layout using Bootstrap cards & tables
* Color-coded buttons for key actions (Add, Update, Delete)
* Real-time form feedback and hover effects
* Consistent font and spacing (Google Fonts – Poppins)

---

## 🔧 Technologies Used

* **Frontend**: HTML, CSS, JSP, Bootstrap
* **Backend**: Java (Servlets/JSP), JDBC
* **Database**: MySQL
* **Server**: Apache Tomcat

---

## 🗂️ Project Structure
ProductWebApp/                                        
├── WebContent/                                                                             
│ ├── index.jsp                                                
│ ├── productadd.jsp                                                 
│ ├── productupdate.jsp                                                           
│ ├── productdelete.jsp                                            
│ ├── productdisplay.jsp                                                
│ ├── reports.jsp                                                                           
│ ├── report_form.jsp                                                                                   
│ └── report_result.jsp                                                                                  
├── src/                                                                                                    
│ ├── com/                                                                                 
│ ├── dao/                                                                 
│ │ └── ProductDAO.java                                                                    
│ ├── model/                                                                        
│ │ └── Product.java                                                                             
│ └── servlet/                                                      
│ ├── AddProductServlet.java                                                                            
│ ├── UpdateProductServlet.java                                       
│ ├── DeleteProductServlet.java                                                            
│ ├── DisplayProductsServlet.java                                                                  
│ ├── ReportServlet.java                                                         
│ └── ReportCriteriaServlet.java                                                    
└── WEB-INF/web.xml                                                                          


---

## 🖼️ Screenshots

![index](https://github.com/Prajwal-S-Biradar/ProductManagementSystem/blob/main/output/index.png)
![add product](https://github.com/Prajwal-S-Biradar/ProductManagementSystem/blob/main/output/add%20product.png)
![update product ](https://github.com/Prajwal-S-Biradar/ProductManagementSystem/blob/main/output/update%20product.png)
![delete product ](https://github.com/Prajwal-S-Biradar/ProductManagementSystem/blob/main/output/delete%20product.png)
![Product list](https://github.com/Prajwal-S-Biradar/ProductManagementSystem/blob/main/output/product%20list.png)
![report result 1](https://github.com/Prajwal-S-Biradar/ProductManagementSystem/blob/main/output/report%20result%201.png)
![report result 2](https://github.com/Prajwal-S-Biradar/ProductManagementSystem/blob/main/output/report%20result%202.png)

---

