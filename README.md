<div style="text-align: center;">
<h1>Simple taxi service</h1>
</div> 
<hr/>
<h3>How my program looks, you can see few screenshots  below:</h3>
Login (or registration)
<br/>
<img src="login.png" alt="entering into system">
Main menu
<br/>
<img src="main menu.png" alt="entering into system">
General information
<br/>
<img src="general information.png" alt="entering into system">
<hr/>
<h3>Description</h3>
This is a simple web application which can do:<br/>
    - create driver <br/>
    - create manufacturer <br/>
    - create car <br/>
    - remove car or driver <br/>
    - add car to a driver <br/>
    - display all information <br/>
<hr/>
<h3>Architecture</h3>
<table>
    <tr><th>3-tier architecture</th></tr>
    <tr><th>Controllers (Presentation layer)</th></tr>
    <tr><th>↓↑</th></tr>
    <tr><th>Services (Application layer)</th></tr>
    <tr><th>↓↑</th></tr>
    <tr><th>DAO (Data access layer)</th></tr>
</table>
<hr/>
<h3>Technologies</h3>
<table>
    <tr><th>Technology</th><th>version</th></tr>
    <tr><th>JDK</th><th>11</th></tr>
    <tr><th>Maven</th><th>4.0.0</th></tr>
    <tr><th>Tomcat</th><th>9.0.50</th></tr>
    <tr><th>MySQL</th><th>8.0.30</th></tr>
</table>
<hr/>
<h3>How to run application</h3>
1. Clone the project from GitHub<br/>
2. Use /resources/init_db.sql to create a schema and tables<br/>
3. Configure /util/ConnectionUtil.java with your own URL, username, password and JDBC driver<br/>
4. Configure Tomcat server (it is recommended to use version 9.0.50)<br/>
5. Run the program 
