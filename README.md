
# Green-Bus-Booking-Project
BusBooking Project By using Java in NetBeans Where Admin Can Add the Seats into respective District Buses and User can Book the Seats of selected Bus No
# Green-Bus-Booking-Project

# Project-documentation

<p align="center">
  <a href="" rel="noopener">
 <img width=500px height=200px src="swag.png" alt="Project logo"></a>
</p>


<h3 align="center">Green-Bus-Booking</h3>

---

<p align="center"> Few lines describing your project.
    <br> 
</p>

## 📝 Table of Contents
- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>
Fully Functional Bus Booking Project for Green Bus System. The technologies used in this project are Core Java, Java Frame, MYSQL DataBase. There are a few important packages in the project are, Grean Bus System Package is first page from which the User can Book the Bus or Admin can Add the Seats, Seats its another Panel When we Select Add seat Option from the Green Bus System by entering the date and Bus no we can add the Seats of Bus for the entered Date by selecting the Bus Booking Package from where we can See the available Seats and Booked seats from JTable1 and we can Bokk the Seat by selecting the unbooked seat from the Table and by entering the Name and Mobile no on the Jpanel, By Loading JDBC Driver and Establishing Connectivity with MySQL DataBase we Can Store the Data of Users and Availability of the Bus of respective Date and Bus No. SkillLync helped me by providing the wire-frames for all relevant feature pages

## 🏁 Getting Started <a name = "getting_started"></a>
When run the the Code on your System, First One Panel will Open There will be 2 options one is for Booking the Bus and another one is for adding the seats into Bus Booking System. By clicking on Book Bus Button you can Book the bus by clicking on available Seats on Otherside By clicking on Add Seat Button you can Add Seats into Bus Booking System by ENtering the Bus no and By selecting the Date.

### Prerequisites
First You need to install Apache Netbeans 17 you can download it by using the below link 
https://netbeans.apache.org/download/index.html
Next you need to install MySQL Server, MySQL Shell, MySQL WorkBench 
and you need download some of the Jar files
i.e, JCalendar and mysql connector Jar file
https://dev.mysql.com/downloads/installer/

### Installing

Fist Click ond NetBeans URL and Install it and Then
After Completing the download start the SetUP 
After SetUp has been Started you need to select on Custom and click on Next
You can see the Available Products
In the Click on MySQL Server and go inside of it and Drag it to the Product to be installed Box
Do the Same for MySQL Application and MySQL Shell and Click on Next 
After that You can see the Installation Set Up and click on Execute and Product will install one by one 
After completing the SetUp click on next and on Product Configuration Click on Next 
Now Type and networking will be visible and there you Check for port no 3306 and keep the default and Click on next 
Net set Root password keep Clicking on Next and Execute Your MySQL installation will be completed .
Then Download the MYSQL Connectors Jar file and JCalendar Jar file from Same MySQL Website   and then Extract it and keep it in one folder


## 🔧 Running the tests <a name = "tests"></a>
First you need Open Apache Netbeans application and then you can import this Project from Git Hub and you can also add all the liberaries which you downloaded
that is MySQL Connector liberary and another one is Jcalendar liberary and then another one is you need to Create one Database of name GreenBus and inside of that you need to create 2 tables, one is bookings table containing of 6 columns of name Id, BusNo, Seat, Customer, Mobile, Date here another one Seats table which will contain 5 tables of name Id, BusNo, Seat, Date, Status. In both the table Seat column reperesents the Seat No. By using Left Join Query we can get required output in the Booking Panel.   

## 🎈 Usage <a name="usage"></a>
The main Use of this BusBooking System is that Bus Contractor can add the Seats into Bus on the respective days and User Can book the seats of their required Bus by entering the Bus No and by selecting the Date after that they can see the Status of Bus Seats Wheather seat is Booked or Unbooked. By Selecting UnBooked Seat and by Entering their Details they can Book the Seat.

## 🚀 Deployment <a name = "deployment"></a>
First Extract the file from GitHub and import it into Apache NetBeans and you can run the program


## ✍️ Authors <a name = "authors"></a>
- [@SkillLymc](https://github.com/kylelobo) - FSD

## 🎉 Acknowledgements <a name = "acknowledgement"></a>
- Skill-Lync
- Tutor Channel
