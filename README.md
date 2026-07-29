
# ✈️ Airline Ticket Reservation System

# 📘 Use Case 2: Flight Search and Discovery

## 📌 Overview

The **Flight Search and Discovery** module enables passengers to search, filter, compare, and explore available flights based on their travel requirements. It provides advanced search capabilities, detailed flight information, and optimized results using Java Stream API for grouping and aggregation.

---

## 🎯 Objectives

- Search flights using various travel criteria.
- Filter and sort flights based on passenger preferences.
- Display detailed flight information.
- Provide real-time flight availability and status.
- Utilize Java Stream API for grouping, filtering, and aggregation operations.

---

# 🧩 Use Case Scenarios

## 🔹 2.1 Flight Search Operations

The system allows passengers to:

- Search flights by source airport code or city.
- Search flights by destination airport code or city.
- Filter flights by departure date.
- Filter flights by return date for round-trip journeys.
- Specify the number of passengers (Adults, Children, Infants).
- Select travel class:
  - Economy
  - Premium Economy
  - Business
  - First Class
- Search one-way, round-trip, or multi-city flights.
- Apply filters based on:
  - Price Range
  - Departure Time
  - Arrival Time
  - Flight Duration
- Filter flights by preferred airline.
- Filter flights by number of stops:
  - Non-stop
  - One Stop
  - Two or More Stops
- Sort search results by:
  - Price (Low to High / High to Low)
  - Duration (Shortest First)
  - Departure Time
  - Arrival Time

---

## 🔹 2.2 Flight Information Display

The system displays comprehensive flight information including:

- List of available flights matching search criteria.
- Airline name.
- Flight number.
- Aircraft type.
- Departure and arrival times with timezone information.
- Total flight duration.
- Layover duration (for connecting flights).
- Available seats by travel class.
- Fare breakdown:
  - Base Fare
  - Taxes
  - Additional Fees
  - Total Fare
- Baggage allowance:
  - Cabin Baggage
  - Check-in Baggage
- Cancellation policy.
- Flight modification policy.
- Flight amenities:
  - WiFi
  - Meals
  - Entertainment
- Real-time flight status and delay information.

---

## 🔹 2.3 Advanced Search Features (Streams with groupingBy)

The system leverages the Java Stream API to perform advanced data processing.

### Stream Operations

- Group flights by airline using `Collectors.groupingBy()`.
- Group flights by price range categories.
- Group flights by departure time slots:
  - Morning
  - Afternoon
  - Evening
  - Night
- Calculate average fare by airline.
- Find the cheapest flight for each route using the `min()` collector.
- Filter and group connecting flights based on layover duration.
- Aggregate available seats across all travel classes.
- Group round-trip options based on total journey time.

---

# 🔐 Key Features

- Flexible flight search.
- Multiple filtering options.
- Advanced sorting capabilities.
- Detailed flight information.
- Real-time flight status.
- Fare comparison.
- Java Stream API integration.
- Efficient grouping and aggregation operations.

---

# 🏗️ Design Approach

The module follows Object-Oriented Programming principles and a layered architecture.

### OOP Principles

- Abstraction
- Encapsulation
- Inheritance
- Polymorphism

### Architecture

- Controller Layer
- Service Layer
- Repository Layer
- Model Layer
- Utility Layer

The design separates responsibilities across different layers, improving maintainability, scalability, and code reusability.

---

## 📊 Expected Outcome

- Fast and efficient flight search.
- Accurate flight filtering and sorting.
- Enhanced user experience with detailed flight information.
- Efficient data processing using Java Stream API.
- Improved application scalability and maintainability.

---

## 📚 Learning Outcomes

- Implementing flight search functionality.
- Applying filtering and sorting techniques.
- Using Java Stream API effectively.
- Working with `Collectors.groupingBy()`.
- Performing aggregation operations using Streams.
- Designing scalable search modules.
- Applying Object-Oriented Programming principles.
- Building layered architecture in Java applications.
- Optimizing data processing using functional programming concepts.
```

