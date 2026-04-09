# CATIA Macros

This repository contains some simple CATIA V5 macros that I created to automate small repetitive tasks during design work.

---

## Macro 1: Part Auto Renamer

### Description
This macro renames all parts in an assembly in a simple sequence format.

### What it does
- Renames components like VINAY_001, VINAY_002, etc.
- Helps keep assembly names organized
- Saves manual effort

### Example
Part1 → VINAY_001  
Part2 → VINAY_002  

---

## Macro 2: BOM Generator

### Description
This macro reads all components in an assembly and shows a basic BOM list.

### What it does
- Extracts part names from assembly
- Displays them in order
- Gives a quick view of components

### Example
1. Part_A  
2. Bolt_M8  
3. Plate_01  

---

## Tools Used
- CATIA V5  
- VBScript  

---

## How to use
1. Open CATIA assembly (.CATProduct)  
2. Go to Tools → Macro → Run  
3. Select the macro file  
4. Run  

---

## Note
These macros are created based on CATIA scripting structure. They are simple implementations meant for learning and basic automation.

---

## Macro 3: BOM Export (CSV)

### Description
This macro extracts part names from a CATIA assembly and exports them to a CSV file.

### What it does
- Reads all components in assembly
- Creates a BOM list
- Saves output as CSV (can be opened in Excel)

### Output
File: BOM_Output.csv

### Note
File path can be modified inside the script based on user system.

## Author
Vinay Raghavendra Gangumalla
