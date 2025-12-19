
<html>
<head>
</head>
<body>
<img src="img/Header.png" alt="Flow diagram"> 

# FurEverHome: Pet Adoption Record System

## Description
**FurEver Home** is a data-driven command center for animal shelters. You manage the entire shelter lifecycle from a single, flat-design interface. This system replaces simple lists with analytics, clinical logs, and automated pipelines.

---

# Features 
- **Command Center Dashboard:** To track occupancy, adoption rates, and medical alerts through real-time metric cards.
- **Pet Profile 360:** To access medical history, behavioral analysis, and personality bios in one tabbed view.
- **Adoption Pipeline:** To move applications through five stages from new inquiry to finalized using a drag and drop Kanban board.
- **Medical Bay & Behavioral Logs:** To log vaccinations, surgeries, and social assessments with progress bars and score sliders.
- **Unified Inbox & Foster Network:** To chat with adopters and track the capacity of foster home through a dedicated management grid.
- **Notification Center:** To receive color-coded alerts for new applications or criticial medical tasks. 
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

### 1. Daily Overview
- The admin log in to the Command Center.
- Check the occupancy progress bar and medical alert cards.
- The activity feed tells the admin exactly what happened while they were away.


### 2. Communication and Inbox
- Open the Notification Center to see new messages. 

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
