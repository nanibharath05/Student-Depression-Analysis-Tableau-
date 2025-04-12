
# Student Depression Analysis 



## 📊 Project Description
This interactive Tableau dashboard was created to visualize and analyze data related to student mental health and depression. The primary objectives were to:

📚 Understand levels of academic pressure and how they affect students

💰 Explore the impact of financial stress on mental well-being

😌 Measure study satisfaction and its correlation with age and stress

💤 Analyze sleep duration and its relation to student health

⏰ Examine study hours and their influence on psychological stress

The dashboard brings together student survey data into a cohesive view, enabling stakeholders to identify patterns and make data-driven decisions for student support and interventions.


##  📈 Key Visualizations

📚 Academic Pressure vs. Student Count

💸 Financial Stress vs. Student Count

📖 Study Satisfaction Trends

🛌 Sleep Duration Breakdown

⌛ Study Hours Distribution & Trends



Each visualization includes interactive filters, average age color coding, and labeled data points to highlight meaningful trends.
## 📈 Tableau Dashboard Features

🧩 Drag-and-drop interactivity

🎨 Visual cues via color gradients and labels

🧠 Behavioral insights from custom filters

📅 Dynamic views filtered by study hours and more
## 🛠️ Installation 
### Tableau Installation

* Go to the official Tableau website:

```bash
👉 https://www.tableau.com/products/desktop
```
* Click on "Try Now"

* Create an account 

* Download and install Tableau Desktop for your operating system (Windows/macOS)

### SQL Server 2022 Developer Edition & SSMS

* Visit the official download page:
```bash
👉 https://www.microsoft.com/en-in/sql-server/sql-server-downloads
```
* Scroll down to the section titled "Developer".

* Click on the “Download now” button under the Developer edition.

* This edition is free and includes all features of the Enterprise  edition, licensed for development and testing purposes only.

* Run the downloaded installer and follow the on-screen instructions to install SQL Server 2022 Developer Edition.

* While installing at right side bottom you can observe SSMS click on it and download and install it

    
## 📥 Setting Up the Database

📂 Step-by-Step Instructions:
* Open SSMS and connect to your SQL Server instance.

* In the query editor, run the following command to create the database:
```bash
    CREATE DATABASE [Tableau Project 1];
```
* Then execute this command to switch to the new database:
```bash
    USE [Tableau Project 1];
```
* On the left panel (Object Explorer), locate the newly created database Tableau Project 1.

* Right-click on Tableau Project 1 > go to Tasks > click Import Flat File…

* In the Import Wizard:

    1.Click Browse, and select the Depression Student Dataset (.csv) file from your system.

    2.Confirm column mappings and data types

    3.Finish the import

* Once completed, your dataset will be added as a new table under the database Tableau Project 1.
## 🔗 Connecting Tableau to SQL Server

🧭 Step-by-Step Instructions:
* Open Tableau Desktop

* On the start screen, under "Connect", click on: Microsoft SQL Server

* In the connection window, fill out the following:

    Server: Your_Server_Name

    Authentication: Choose Windows Authentication

* Click Sign In

* Once connected, under "Database", select: Tableau Project 1

You will now see all tables (e.g., the imported Depression Student Dataset) and can start building visualizations.
## 📊 Creating Sheets in Tableau

1️⃣ Academic Pressure & Student Count

Goal: Visualize how many students face different levels of academic pressure.

Steps:

* Open a new worksheet.

* Drag Academic Pressure to Columns.

* Drag Index Column to Rows and set it to Count.

* Drag Age to Color to display average age by color.

* Add Academic Pressure and Count of Index Column as Labels.

* Drag Study Hours as a Filter.

![image alt](https://github.com/nanibharath05/Student-Depression-Analysis-Tableau-/blob/8387cb764c14e7b04f72391309d5d6cf1919cc8f/Screenshot%202025-04-11%20192541.png)

2️⃣ Financial Stress & Student Count

Goal: Understand how financial stress levels vary among students.

Steps:

* Create a new sheet.

* Drag Financial Stress to Columns.

* Drag Index Column to Rows and set it to Count.

* Drag Age to Color to show average age.

* Add Labels for Financial Stress and count.

* Drag Study Hours to Filter.

3️⃣ Study Satisfaction & Student Count

Goal: Analyze how satisfied students are with their studies.

Steps :

* Open a new worksheet.

* Drag Study Satisfaction to Columns.

* Drag Index Column to Rows as Count.

* Use Color for Age, and Label for satisfaction level & count.

* Drag Study Hours to Filter.

4️⃣ Sleep Duration & Student Count

Goal: View how sleep duration affects the number of students and age range.

Steps :

* Create another worksheet.

* Drag Sleep Duration to Columns.

* Drag Index Column to Rows and set to Count.

* Use Color to show average Age.

* Add Labels for clarity.

* Drag Study Hours to Filter.

5️⃣ Study Hours & Student Count

Goal: Visualize how long students study and how it relates to stress levels and age.

Steps :

* Create the final worksheet.

* Drag Study Hours to Columns.

* Drag Index Column to Rows as Count.

* Add Age to Color and Study Hours to Label.

* Drag Study Hours to Filter.

## 🧩 Dashboard

🛠️ Step-by-Step Instructions:

* Open Tableau Desktop

* In the bottom tab area, click on the "New Dashboard" icon
👉 This looks like a small window with a "+" sign.

* In the left pane, under Sheets, you’ll see the sheets you’ve created:

      1. Academic Pressure & Student Count

      2. Financial Stress & Student Count

      3. Study Satisfaction & Student Count

      4. Sleep Duration & Student Count

      5. Study Hours & Student Count

* Drag each sheet onto the dashboard canvas one by one.
  Arrange them as per your layout preference: Side by side, stacked, or in a grid layout

* Use containers (horizontal or vertical) to organize the layout cleanly: Click the small gray bar that appears at the top/side to move or resize

* Once your dashboard is organized:

* Preview it using Presentation Mode (F7 or top-right icon)

* Save your work as a .twbx file

* Go to File > Save As, and choose Tableau Packaged Workbook (.twbx)
