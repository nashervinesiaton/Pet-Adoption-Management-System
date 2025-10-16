
<html>
<head>
<link rel ="stylesheet" type = "text/css" href = "style.css">
</head>
<body>
<h2>
<div class = "flow">
<img src="img/Header.png" alt="Flow diagram">
</class>
</h2>

# FurEverHome: Pet Adoption Record System

## Description
**FurEver Home** is a simple CRUD-web based application designed to help managed pet records for an animal shelter.ccvvcc
The system allows an **admin** to add, view, update, and delete pet details such as name, breed, age, and adoption status.

---

# Features 
- **Add Pets:** Create new pet profiles with details like name, breed, age and status.
- **View Pets:** Display all pet records in a simple organized list.
- **Update Pets:** Edit and Update existing pet information.
- **Delete Pet Record:** Remove records of pets that are no longer available for adoption.

---

## User Role
- **Admin** - Manages all pet record in the system.

---

## Tech Stack
- **Frontend:** - HTML, CSS
- **Backend** - PHP
- **Database** - MySQL

--- 

##  System Flow of FurEverHome: Pet Adoption Record System

### 1. System Start
- The admin opens the system through a web browser.  
- The homepage or dashboard appears with navigation options:  
  - Add Pet  
  - View Pets  
  - Update Pet  
  - Delete Pet  

### 2. Add Pet
- Admin selects *Add Pet* from the navigation bar.  
- A form appears where the admin enters:
  - Pet ID (auto-generated or manually input)  
  - Pet Name  
  - Breed  
  - Age  
  - Gender  
  - Status (e.g., Available, Adopted, Pending Adoption)  
- When the admin clicks *Save*, the system:
  - Validates the input data.  
  - Inserts the new record into the *database (pets table)*.  
  - Displays a message: “Pet successfully added.”

### 3. View Pets
- Admin clicks *View Pets*.  
- The system retrieves all records from the database using a *SELECT* query.  
- Results are displayed in a table format, showing:  
  Pet ID | Name | Breed | Age | Gender | Status | Actions (Edit / Delete)  
- The admin can:
  - Review current records.  
  - Click *Edit* or *Delete* beside a pet entry.

### 4. Update Pet
- When the admin clicks *Edit*, the system loads the selected pet’s details into an editable form.  
- Admin modifies any details (e.g., updates the status from “Available” to “Adopted”).  
- On clicking *Update*, the system:
  - Validates the updated data.  
  - Executes an *UPDATE* query to modify the record in the database.  
  - Displays: “Pet record successfully updated.”

### 5. Delete Pet
- Admin clicks *Delete* beside a pet record.  
- A confirmation prompt appears (“Are you sure you want to delete this pet?”).  
- If confirmed:
  - The system executes a *DELETE* query to remove the record from the database.  
  - Displays: “Pet record successfully deleted.”  
- If canceled:
  - No changes occur, and the admin is returned to the pet list.

### 6. Logout / Exit
- The admin can log out (if authentication is implemented) or simply close the system.  
- Session ends, and the system returns to the start state.
 <h2>Developers</h2>
 <img src="img/Team.png">
  </body>
</html>
