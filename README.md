# Assignment: Build a micro KYC Module

## Assignment Overview:
You are tasked with creating a solution that involves consuming multiple Setu APIs, and building a new KYC Module that will be accessed via a Browser (phone or desktop), and packaging the application using Docker for easy deployment. The assignment will require proficiency in React for frontend development, Python for backend.

## Objective:
Develop a browser-based KYC (Know Your Customer) module that validates the PAN and Bank Account of a customer.

## Requirements:
1. The module should first accept the PAN as input and perform its verification by calling the PAN API.
2. After successful PAN verification, the module should accept the Bank Account number and perform its verification using the DG RPD API.

## Tasks:
1. Integrate the PAN API to perform PAN verification.
2. Integrate the RPD (Reverse Penny Drop) API to perform Bank Account verification.
3. Display a success screen with relevant details upon successful verification.
4. Display a failure screen with relevant details and actionable items if the verification fails.
5. Provide a button to retry the verification flow at any point.
6. Capture the data for each user and store in a database.
7. Expose Admin flows to the admin to view the data of all users and view the analytics 
8. Analytics can be list/view of (you are free to choose how you present the information)
    - total KYC attempted, 
    - total KYC successful, 
    - total KYC failed, 
    - total KYC failed due to PAN, 
    - total KYC failed due to Bank Account, 
    - total KYC failed due to PAN and Bank Account.

## Deliverables:
1. Source code of the KYC module.
2. Documentation explaining the code and how to set up and run the module.
3. A video demonstrating the working of the module for success and failure scenarios.
4. A video demonstrating the working of the admin flows and analytics.

## Tech Stack:
1. React
2. Python
3. Docker

## Additional Details:
1. PAN API: https://docs.setu.co/data/pan/quickstart
2. RPD API: https://docs.setu.co/data/bav/reverse-penny-drop/quickstart
3. For API Keys, please refer to this video on signing up for Setu Bridge Portal: https://www.loom.com/share/3f1d6e15f2364742a45d775632ed0c4c?sid=49596d62-21cb-42e8-a9bc-632db60e6008 and configure your products and get the API keys.

## Submission:
Publish the completed work on GitHub, working demo video link and share the repository link once done.