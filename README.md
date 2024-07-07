# Phone Fix Booking System

## Executive Summary

The project showcases proficiency in JavaScript and web development techniques, providing a practical solution for managing phone repair bookings. The system includes form validation, cost calculations, and advanced JavaScript features to enhance user experience.

## Project Overview

The Phone Fix Booking System design meets all assignment requirements, featuring:

- Form validation using JavaScript or HTML5 validation.
- Cost calculations for services and courtesy phone rentals.
- User-friendly form submission and reset functionalities.
- A dynamically generated Repair Booking Job Sheet.
- Advanced JavaScript techniques for enhanced functionality.

## Introduction

### Home Page (index.html)

The home page provides an itinerary form for booking phone repairs, including:

**Components:**

- **Title**: A select box with options (Mr, Mrs, Ms, Miss, Dr).
- **First Name & Last Name**: Allows alphabetical characters, spaces, and the - symbol.
- **Post Code**: A length of 4 numbers.
- **Phone Number**: Allows numbers, spaces, and ( ), -, + symbols.
- **Dates**: Valid dates with conditions (purchase date must be earlier than repair date, no future dates).
- **Warranty**: Disabled if the purchase date is greater than 24 months.
- **IMEI Number**: Only numbers with a length of 15.
- **Make**: A select box with options (Apple, LG, Motorola, Nokia, Samsung, Sony, Other).
- **Fault Category**: A select box with options (Battery, Charging, Screen, SD-storage, Software, Other).

### Courtesy Phone Section

Allows users to select a courtesy phone and/or a charger, displaying the items in a table and calculating the bond.

**Components:**

- **Item Type**: A select box with options (iPhones: $275, Other phones: $100, Chargers: $30).
- **Cost Calculation**: Calculates the bond based on item type and customer type (no bond for business customers).

### Cost Section

Displays the calculated costs:

- **Bond**: Cost for courtesy phone and charger for consumers.
- **Service Fee**: $85 if the phone is out of warranty.
- **Total**: The total cost excluding GST.
- **GST**: 15% of the total.
- **Total (+GST)**: The total cost including GST.

### Form Buttons

**Components:**

- **Reset**: Resets the form and recalculates default values.
- **Submit**: Validates form data, displays errors, and generates a Repair Booking Job Sheet if validated.
- **FAQs**: Opens a new window with FAQs imported from a JSON/XML file, including a search box for filtering.

### Repair Booking Job Sheet

A printable document styled for black and white printing, including:

- Unique job number (using cookies, local storage, IndexedDB).
- Invoice date and time.
- Repair details with date/time in 12-hour format and warranty status.

### Advanced JS (advanced.html)

- **Address Search & Auto Completion API**: Auto-completes address fields to improve UX.
- **User Preferences Storage**: Remembers user preferences (background color, image, etc.) using Cookies and Local Storage API.
- **Drag-and-Drop API**: Allows drag-and-drop functionality for selecting courtesy phones.
- **Modal Form**: Displays the Repair Booking Sheet in a modal before submission for review.
- **File Upload Feature**: Allows users to upload images of the repair phones and display them on the page.
- **Interactive NZ Map**: Uses SVGMap or Imagemap to display all shops in different regions.
- **Geolocation & Google Map API**: Shows the current customer service and the distance to the nearest shop.


## Technologies Used

- **Frontend**:
  - HTML5
  - CSS3 (Grid and Flexbox)
  - JavaScript

- **Tools and Platforms**:
  - Git (for version control)
  - JSON/XML (for FAQs data)

## Documentation & Functionality

- **Code Quality**: Consistent variable naming, comments, clean code.
- **Responsive Design**: Mobile-first approach using CSS grid and flexbox.
- **Validation**: All validation uses JavaScript.
- **Deployment**: Published on GitHub or any other hosting platform.
- **Review Document**: A `review.doc` file explaining issues faced, improvements needed, and reflections on the project and course.

---
