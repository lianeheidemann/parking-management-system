# Parking Management System

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

A parking management system built with **HTML, CSS, and vanilla JavaScript**. It supports vehicle registration, listing, search, and automatic fee calculation based on parking duration.

---

## Features

- Register vehicles by license plate, model, and color
- List parked vehicles
- Search for a vehicle by license plate
- Calculate the amount due from the parking duration
- Configure per-minute, hourly, and additional fees
- Update information dynamically in the interface

---

## Technologies

- HTML5
- CSS3
- JavaScript (Vanilla JS)

---

## How It Works

Vehicle records are stored in a JavaScript array together with their entry date and time.

When a vehicle is retrieved, the system:

1. Calculates the elapsed time since entry.
2. Converts the duration into hours and minutes.
3. Applies the configured fees.
4. Displays the final amount due.

---

## Project Interface

<img width="1438" height="1182" alt="Parking management interface" src="interface.png" />
