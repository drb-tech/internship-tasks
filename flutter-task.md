
# DRB Internship – Flutter Task

## Objective

Build a **simple mobile app using Flutter** for a logistics manager to:

* View vehicles, drivers, and trips.
* Assign delivery tasks (trips) to a driver and vehicle.
* Track and update trip status.
* View detailed information when selecting a vehicle, driver, or trip.

**Note:** You may choose to implement only **one main screen** (Drivers, Trips, or Vehicles) along with the related details/assignment flow, instead of building all.

---

## Requirements

### 1. Vehicles Screen

* Show a list of vehicles (mock data).
* Each vehicle should display:

  * Vehicle ID/Name
  * Vehicle Type (Truck, Van, Bike, etc.)
  * Current Status (Available / Assigned)
* On tap → Navigate to **Vehicle Details Screen**:

  * Vehicle Name, Type, Status
  * Assigned Driver (if any)
  * Current Trip (if any)

### 2. Drivers Screen

* Show a list of drivers (mock data).
* Each driver should display:

  * Driver Name
  * License Number
  * Current Status (Available / On Trip)
* On tap → Navigate to **Driver Details Screen**:

  * Driver Name, License Number
  * Current Status
  * Assigned Vehicle (if any)
  * Ongoing/Last Trip (if any)

### 3. Trips Screen

* Show a list of trips.
* Each trip should display:

  * Trip ID
  * Assigned Driver
  * Assigned Vehicle
  * Pickup → Drop-off
  * Status (Pending / In Progress / Completed)
* On tap → Navigate to **Trip Details Screen**:

  * Trip ID
  * Driver & Vehicle Details
  * Pickup & Drop-off
  * Status (with option to update status)

### 4. Assign Trip Screen

* Form to create a new trip:

  * Select Driver (dropdown → only Available drivers).
  * Select Vehicle (dropdown → only Available vehicles).
  * Pickup location (text).
  * Drop-off location (text).
* On submission:

  * Create a new trip with **Pending** status.
  * Update Driver status → On Trip.
  * Update Vehicle status → Assigned.

### 5. Responsive UI Requirement

* Support different screen sizes (small mobile → tablet).
* Use flexible layouts (`Expanded`, `Flexible`, `MediaQuery`, `LayoutBuilder`).
* Avoid hardcoded sizes.

---

## Evaluation Criteria

* **UI/UX** → Clean, simple, responsive, and user-friendly.
* **Code Quality** → Readable, modular, well-structured, and commented.
* **State Management** → Any approach (`setState`, Provider, Riverpod, Bloc, etc.).
* **Navigation** → Proper Flutter navigation to detail screens.
* **Data Handling** → Efficient use of mock/local data.
* **Bonus** → Search/filter, animations, map view, or trip history summary.

---

## Submission Guidelines

1. Submit your source code via:

   * **GitHub Repository**, or
   * **Zip file upload**.
2. Include a **README** inside your project with:

   * Setup instructions.
   * Assumptions made.
   * Features implemented.
3. Provide a **short note** about your chosen screen (Drivers, Trips, or Vehicles).

---

## Deadline

Submit your task by **25/09/2025**.
