# QuickStatements 3.0 Home Page 

## Table of Contents

1. [Overview](#overview)
2. [Home Page Features](#home-page-features)
   - [Navigation](#navigation)
   - [User Authentication](#authentication)
   - [Welcome Message](#welcome-message)
   - [New Batch Button](#new-batch-button)
     - [Key Components of the New Batch Form](#key-components-of-the-new-batch-form)
   - [Batch ID Input Form](#batch-id-input-form)
   - [Username Input Form](#username-input-form)
3. [Conclusion](#conclusion)

---

## Overview
Welcome to the QuickStatements 3.0 application! 

QuickStatements is a powerful tool used by Wikidata contributors to batch-upload and modify data on Wikidata. It simplifies the process of adding or modifying multiple statements efficiently through automated workflows, making it essential for users who frequently work with large datasets. This documentation aims to guide users through the features of QuickStatements v3 Home Page, making it easier to get started.

This document outlines the features available on the home page and provides a brief overview of how to use them.

---

## Home Page Features

### Navigation
The home page includes a navigation bar with links to various sections:
- **QuickStatements 3.0**: A link to the homepage.
- **New Batch**: A link to create a new batch.
- **Last Batches**: A link to view recent batches (functionality not defined yet).
- **Git Repository**: A link to the [QuickStatements GitHub Repository](https://github.com/WikiMovimentoBrasil/quickstatements3).

### Authentication
The navigation bar will also display user authentication status:
- **Anonymous Users**: A "Login" link is displayed.
- **Logged-in Users**: The username is shown along with a link to "Your Last Batches".

### Welcome Message
At the top of the page, you will see a welcoming message that greets users:
> **"Welcome to QuickStatements 3.0"**

### New Batch Button

**Description**: 
This button allows users to create a new batch.

**Functionality**: 
Clicking this button will navigate you to the new batch creation page. 
- This template allows users to specify the command format, batch name, and commands to execute.

**New Batch Interface**:
Once you access the new batch interface, you will see a form that consists of several key elements:

#### Key Components of the New Batch Form

1. **Error Display**: If there are any issues with your input, error messages will be shown prominently at the top of the form in red color.

2. **Command Format Selection**: 
   - You can select the format for your commands from a dropdown menu. The options are:
     - **V1**: A specific command format.
     - **CSV**: A format for comma-separated values.

3. **Custom Batch Name**: 
   - Enter a name for your batch in the text box provided. This helps in identifying your batch later.

4. **Commands Text Area**: 
   - Use the large text area to input your commands. This area allows for multiple lines, making it easy to enter several commands at once.

**Submitting Your Batch**

After filling out the form, click the **Execute** button to submit your batch. 
The system will then process your commands based on the selected format.

### Batch ID Input Form
- **Description**: This form allows users to enter a Batch ID to view details of a specific batch.
- **Input Field**:
  - Fill in the BachID which is a Number. This is a required Field so can't be blank when submitting.
  - **Functionality**: Upon submission, it will redirect you to the details of the entered batch. Click on the Submit Button --> "See batch details"

### Username Input Form
- **Description**: This form allows users to enter a username to see all batches associated with that user.
- **Input Field**:
  - Fill in the Username which is a Text. This is a required Field so can't be blank when submitting.
  - **Functionality**: Upon submission, it will show all batches related to the entered username. Click on the Submit Button --> "See batches by user"

---

## Conclusion
The home page of QuickStatements 3.0 is designed to be user-friendly and efficient, allowing users to quickly create new batches or access existing batch details. With its simple layout and intuitive forms, users can easily navigate through the functionalities available in the application.

---