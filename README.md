# EX01 Developing a Simple Webserver

# Date:19.09.2025
# AIM:
To develop a simple webserver to serve html pages and display the configuration details of laptop.

# DESIGN STEPS:
## Step 1:
HTML content creation.

## Step 2:
Design of webserver workflow.

## Step 3:
Implementation using Python code.

## Step 4:
Serving the HTML pages.

## Step 5:
Testing the webserver.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TCP/IP Model</title>
<style>
body {
  background-color: #fff8dc;  /* light cream */
  font-family: Arial, sans-serif;
  margin: 30px;
}

h1 {
  text-align: center;
  color: #b22222;
  text-decoration: underline;
}

table {
  border-collapse: collapse;
  width: 90%;
  margin: 20px auto;
  background-color: #ffffff;
}

th, td {
  border: 1px solid #000;
  padding: 10px;
  text-align: left;
}

th {
  background-color: #f2d7d5;
  color: #000;
  text-align: center;
}

tr:nth-child(even) {
  background-color: #f9f9f9;
}

.footer {
  text-align: center;
  margin-top: 20px;
  font-style: italic;
}
</style>
</head>
<body>

<h1>TCP/IP Model</h1>

<p style="text-align:center;">The TCP/IP model (Internet Protocol Suite) is a set of communication protocols that define how data travels across a network.</p>

<table>
  <tr>
    <th>Layer</th>
    <th>Protocols / Examples</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><b>Application Layer</b></td>
    <td>HTTP, FTP, SMTP, DNS, Telnet</td>
    <td>Used for applications and user-level communication such as web browsing, email, and file transfer.</td>
  </tr>
  <tr>
    <td><b>Transport Layer</b></td>
    <td>TCP, UDP</td>
    <td>Responsible for reliable data transfer, segmentation, and reassembly of data packets.</td>
  </tr>
  <tr>
    <td><b>Internet Layer</b></td>
    <td>IP, ICMP, ARP</td>
    <td>Handles logical addressing, routing, and error reporting of data packets.</td>
  </tr>
  <tr>
    <td><b>Network Access Layer (Link Layer)</b></td>
    <td>Ethernet, Wi-Fi, PPP</td>
    <td>Deals with physical connection, hardware addressing, and data transmission over the network medium.</td>
  </tr>
</table>

<p class="footer">– Prepared by Aathishwaran K –</p>

</body>
</html>
```
# OUTPUT:
<img width="1918" height="959" alt="Screenshot 2025-10-11 091147" src="https://github.com/user-attachments/assets/278b5c4d-cc4d-472c-a245-2e15d0ffa2da" />

 
<img width="647" height="340" alt="Screenshot 2025-10-11 091344" src="https://github.com/user-attachments/assets/142b44e3-40fe-4c12-bd94-80c018e8fc16" />
<img width="1298" height="254" alt="Screenshot 2025-10-11 091249" src="https://github.com/user-attachments/assets/cffc3b41-54cd-4a7e-829c-da2a0d986abf" />


# RESULT:
The program for implementing simple webserver is executed successfully.
