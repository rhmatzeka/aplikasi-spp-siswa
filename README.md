# School Fee Payment App (SPP)

A Java desktop app for recording school tuition (SPP) payments. School staff can manage students, classes and staff, record payments, and print reports.

This was a programming course assignment.

## Features

- **Login** with a splash screen and a main dashboard
- **Manage data**: students, classes, staff, and tuition rates
- **Payment transactions**: record who paid, for which month, and how much
- **Printable reports** for students, staff and transactions (JasperReports)

## Tech stack

Java (Swing, built with NetBeans), MySQL, JasperReports / iReport 5, JCalendar

## Getting started

You need JDK 8, NetBeans and MySQL (XAMPP works).

1. Create a database named `db_raditarzhabid` and import `uji coba dah/db_raditarzhabid.sql`.
2. Open the folder `uji coba dah/raditarzhabid` as a project in NetBeans.
3. Add the `.jar` files from `uji coba dah/raditarzhabid/yang diperlukan` to the project libraries (MySQL connector, JasperReports, JCalendar and their dependencies).
4. Check the database connection in `src/config/KoneksiDB.java` (default: `localhost:3306`, user `root`).
5. Run the project.

## Project structure

All code lives in `uji coba dah/raditarzhabid/`:

| Path | What it is |
| --- | --- |
| `src/view/` | App screens: login, dashboard, CRUD forms, payment form |
| `src/laporan/` | Report templates |
| `src/config/` | Database connection and user session |
| `yang diperlukan/` | Required libraries (`.jar`) |

`uji coba dah/Aplikasi SPP.aip` is the installer project file.
