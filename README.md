# Budget Buddy Application 

## Table of Contents
1. [Overview](#overview)
2. [Team Members](#team-members)
3. [Installation](#installation)
4. [Device Requirements](#device-requirements)
5. [How to Use Our App](#how-to-use-our-app)
   - [Dashboard Page](#dashboard-page)
   - [Pop-Up Menu](#pop-up-menu)
   - [Transactions Page](#transactions-page)
   - [Statistics Page](#statistics-page)
   - [Profile Page](#profile-page)
6. [Features](#features)
   - [Required Feature - Single Sign-On (SSO)](#required-feature---single-sign-on-sso)
   - [Required Feature - Settings](#required-feature---settings)
   - [Required Feature - REST API](#required-feature---rest-api)
   - [Required Feature - Biometrics](#required-feature---biometrics)
   - [Required Feature - Multi-Language](#required-feature---multi-language)
   - [Required Feature - Offline Mode](#required-feature---offline-mode)
   - [Required Feature - Real-time Notifications](#required-feature---real-time-notifications)
   - [Feature 1 - Set a Budget](#feature-1---set-a-budget)
   - [Feature 2 - Log a Transaction](#feature-2---log-a-transaction)
   - [Feature 3 - Export Data to CSV](#feature-3---export-data-to-csv)
   - [Feature 4 - Profile Picture](#feature-4---profile-picture)
   - [Feature 5 - Save Graph & Chart](#feature-5---save-graph--chart)
   - [Feature 6 - Budget History](#feature-6---Budget-history)
7. [GitHub Actions](#github-actions)
8. [Comprehensive Report](#comprehensive-report)
9. [Demonstration video link](#demonstration-video-link)

# Overview
Effective money management is crucial for personal as well as professional achievement 
in the chaotic economy of today. "Budget Buddy" is a unique budgeting application that we 
developed after realizing the growing demand for useful solutions to assist people in 
managing their personal finances. The goal of "Budget Buddy" is to offer a simple, practical, 
and efficient way for individuals to manage their personal finances. 

## Team Members
- Avish Judnarain, ST10030291
- Kaushil Dajee, ST10079389
- Jereshan Sinan, ST10033851
- Eben Nkulu Mwema, ST10091324
  
Original GitHub Link:
https://github.com/ST10030291/OPSC7312-FinanceBuddy.git

## Installation
Clone this repository to your local machine using `git clone <repository_url>`.
Open the project in Android Studio.
Build and run the app on your Android device or emulator.

## Device Requirements
Users will need an Android device running an Android version between Android 7 (API Level 24), codename "Nougat" and Android 12L (API Level 32), codename "Snow Cone".

## How to Use Our App
When you open the app, you will be required to either Sign Up for a new account or Log In. 
You are also able to log in with Google SSO via your Google account.

### Dashboard Page
On the Dashboard page you will be greeted by a message with your desired username. A floating island will display your budget/available budget and transaction count for the current month. Under this, you will find a breakdown of your budget for the month with different categories and their allocated amounts, followed by a monthly budget insight, a visual display of how well you are keeping to your budget.

<img src="https://i.imgur.com/2S1OanX.png" alt="Dashboard Screenshot" width="200"/>
<img src="https://i.imgur.com/z2sAJwF.jpg" alt="Dashboard Screenshot" width="200"/>

### Pop-Up Menu
Via this pop-up, you can set a budget for the month or log a transaction. To set a budget, you enter the total budget, add categories with amounts, and click create. To log a transaction, enter the transaction name, amount, and category.

### Transactions Page
This page shows a detailed list of all recorded transactions, including their name, amount, date, and category.

<img src="https://i.imgur.com/N5vBFhZ.jpg" alt="Dashboard Screenshot" width="200"/>
<img src="https://i.imgur.com/JXzQmaZ.jpg" alt="Dashboard Screenshot" width="200"/>

### Statistics Page
Displays total spending on a specific category as percentages in a Pie Chart and horizontal bar graph. Users can save charts to device storage and filter by monthly dates.

### Profile Page
Here, you can view account information and change settings related to your account, such as changing your profile picture and language setting. You can also view a history of your budgets.

<img src="https://i.imgur.com/NQM0I7j.jpg" alt="Dashboard Screenshot" width="200"/>

# Features:
## Required Feature - Single Sign-On (SSO)
The user can register and log in to the app using single sign-on (SSO), implemented with Google.

## Required Feature - Settings
The user can change app settings, including language from English to Afrikaans.

## Required Feature - REST API
Connects to a custom REST API linked to the app's database.

## Required Feature - Biometrics
The user can log in via biometric options (fingerprint or face recognition) or through Google SSO.

## Required Feature - Multi-Language 
Supports multi-language options to cater to a broader audience.

## Required Feature - Offline Mode
The app supports offline functionality, allowing users to view dashboard details, add transactions, and view past transactions without an internet connection.

## Required Feature - Real-time Notifications
Users will receive notifications when they are approaching their budget limit (between 90-99% of the budget spent), when they've reached their budget limit (100% of the budget spent) and when they've exceeded their budget limit (101% or more of the budget spent).

## Feature 1 - Set a Budget
Users can set a budget for the current month via the pop-up button by entering a total budget and allocating funds to categories.

## Feature 2 - Log a Transaction
Users can log real-life transactions to track expenses. Future versions may integrate with banking apps.

## Feature 3 - Export Data to CSV
In account settings, users can export all data to a CSV file for planning or accounting purposes.

## Feature 4 - Profile Picture
To personalize the app, users can add their profile picture.

## Feature 5 - Save Graph & Chart 
Users can save graphs and charts displayed on the statistics page to their device storage.

## Feature 6 - Budget History
The budget history feature lets users view a record of their past budgets, helping them track financial patterns over time.

## GitHub Actions
We implemented GitHub Actions using a YAML configuration in `.github/workflows` This config is activated each time we push to the `main` branch.
These are the main steps in our workflow:

Environment Setup: The workflow begins by checking out the repository and setting environment variables for the current date and repository name.
JDK Setup: Configures Java 17 using the Zulu distribution, which is cached to speed up any future runs.
Gradle Build and Tests: Runs unit tests, assembles both debug and release APKs, and generates an AAB for the release, ensuring each build is reliable and ready for distribution.
Artifact Uploads: Each generated APK and AAB is uploaded as an artifact, labeled by date and repository, allowing easy access for further testing or deployment.

## Comprehensive Report
As a team, we used GitHub for collaborative development, creating a shared repository to host the source code. Through branching, members could work on different features or bug fixes simultaneously without interference. GitHub Actions were used to automate tests and deployments, improving the development cycle's efficiency. This approach helped maintain version control, enhanced team coordination, and delivered a well-organized, high-quality application.

## Demonstration Video Link
https://www.youtube.com/watch?v=b7en3eQLTrw


## Playstore 
The App is in review and in internal testing as of the 4th of October 2024

Thank you for using our application! 😊
