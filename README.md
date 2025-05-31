# 🚌 ST Bus Ticket Booking System

A simple C-based console application for booking bus tickets to different destinations with pricing based on passenger categories.

# 📋 Features

Destination selection from predefined cities.

Ticket pricing based on:

Children (1–12 years)

Adults (13–75 years)

Females (13–75 years)

Aged (above 75 years – free ticket)

Separate fare rates for each destination.

Choice of payment mode: Cash or Online.

Displays a complete ticket summary.


# 🧮 Fare Chart

Destination	Child Fare	Adult Fare	Female Fare	Aged Fare

Wani	₹18	₹35	₹18	₹0
Arni	₹25	₹50	₹25	₹0
Kalamb	₹35	₹70	₹35	₹0
Darwha	₹45	₹95	₹45	₹0
Nagpur	₹60	₹120	₹60	₹0


# 🛠 How to Run

1. Save the code in a file, e.g., st_bus_booking.c.


2. Compile it using a C compiler:

gcc st_bus_booking.c -o st_bus_booking


3. Run the executable:

./st_bus_booking


# 📌 Notes

The program uses simple if-else and switch-case logic.

Input validation for destination code is handled.

Aged passengers ride for free.

