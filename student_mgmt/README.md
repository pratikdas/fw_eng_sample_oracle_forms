# Example Oracle Forms

An Oracle Forms 11g compatible set of example Oracle Forms.

## Get Started

_File: [student-db-script.sql](script/student-db-script.sql?raw=true)_

The database script for the student schema is available in the scripts-folder. Just run the script in a tool like SQL Plus, SQL Developer or Toad. The schema contains a simple structure to link students to courses.

## Simple Oracle Form

_File: [QAFE_FORM1.fmb](QAFE_FORM1.fmb?raw=true)_

### Features

- One window with Form Layout, having:
  - Text fields
  - Date fields
  - Number fields
- Enter query mode
- Create, Read, Update, and Delete (CRUD) functionality


## Medium Oracle Form

_File: [QAFE_FORM2.fmb](QAFE_FORM2.fmb?raw=true)_

### Features

- Three windows, having:
  - A data grid with overflow (CRUD)
    - Including LOV for zipcode
  - A data grid
  - A Master-Detail relation
- Enter query mode (only on the master of the main window and data grid)
- Create, Read, Update, and Delete (CRUD) functionality

## Complex Oracle Form

_File: [QAFE_FORM3.fmb](QAFE_FORM3.fmb?raw=true)_

### Features

- One window with Form Layout, having:
  - Text fields
  - Date fields
  - Number fields
- Validation in PL/SQL
  - Simple validation (input bigger than certain value)
  - Complex validation (check in database, if value exists)
- Post-Query using a database View Object
- Event handling with using Triggers and Program Units
- Usage of `SHOW_WINDOW` and `HIDE_WINDOW`
- Usage of `GET_ITEM_PROPERTY` and `SET_ITEM_PROPERTY`
