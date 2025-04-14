# Optica "Cul d'Ampolla" - Level 1 Exercise

## Description

This exercise focuses on designing a database for an optical store named **"Cul d'Ampolla"**. The objective is to support the management of clients and sales of eyeglasses.

### Business Requirements

The store wants to store and manage the following information:

#### Providers
For each eyeglass provider, the system must store:
- Name  
- Address (street, number, floor, door, city, postal code, country)  
- Phone number  
- Fax  
- NIF (tax identification number)  

#### Glasses
For each pair of eyeglasses:
- Brand  
- Lens graduation (left and right)  
- Frame type (floating, plastic, or metal)  
- Frame color  
- Color of each lens  
- Price  

#### Clients
For each client:
- Name  
- Postal address  
- Phone number  
- Email  
- Registration date  
- Referring client (optional — the client who recommended the store)  

#### Employees and Sales
- The system must record the **employee** who sold each pair of glasses.  
- The system must store the **date and time** of the sale.

---

## Exercise 2

Imagine we have a **graphical user interface** from the client’s point of view.  
**How would you design the database to support and facilitate the required information?**

> Your task is to propose a relational database schema that fulfills all the information and relationships described above.
