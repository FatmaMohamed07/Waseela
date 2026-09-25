# وسيلة | Waseela

**Waseela** is a web platform designed to document and share charitable contributions, equipment, and supplies delivered to people and organizations in need.

The platform helps organize donation-related achievements, display supporting images and videos, and track the financial progress of each contribution.

## Features

* Arabic RTL user interface.
* Display documented medical equipment and supplies.
* Show the receiving hospital or organization.
* Display the current status of each achievement.
* Track the total required amount and the amount collected.
* Display donation progress as a percentage and progress bar.
* View detailed images and videos through an interactive gallery.
* Admin login system.
* Admin-only panel for adding new documentation.
* Upload a main image and multiple detail images/videos.
* Edit the status and financial information of existing records.
* Delete existing documentation.
* Copy the electronic wallet number for donations.
* Direct contact through WhatsApp and Telegram.
* Responsive design for different screen sizes.

## Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript**
* **Supabase**
* **Font Awesome**
* **Google Fonts**

The project uses Supabase for authentication, database operations, and file storage.

## How It Works

### For Visitors

Visitors can:

1. Browse documented equipment and supplies.
2. View the hospital or organization receiving the equipment.
3. See the current donation status.
4. View the required and collected amounts.
5. Check the donation progress.
6. Open a detailed gallery containing images and videos.
7. Contact the team through WhatsApp or Telegram.
8. Copy the electronic wallet number to make a donation.

### For Admins

After logging in, admins can:

1. Add a new documented achievement.
2. Enter the equipment or supplies name.
3. Enter the receiving hospital or organization.
4. Select the current status.
5. Enter the required and collected amounts.
6. Upload the main image.
7. Upload multiple detail images or videos.
8. Add additional notes or descriptions.
9. Edit existing records.
10. Delete records.

## Admin System

The website includes an admin authentication system using **Supabase Authentication**.

When an admin is logged in, the admin panel becomes available and additional controls appear on the documented items, including **Edit** and **Delete** actions.

When no admin is logged in, these controls remain hidden.

## Donation Progress

Each documented contribution can contain:

* Total required amount.
* Current collected amount.
* Completion percentage.
* Visual progress bar.

The percentage is calculated automatically based on the collected amount compared with the target amount.

## Images & Videos

Each documentation record supports:

* One main image.
* Multiple detail images.
* Multiple detail videos.

Visitors can open a record to view its media in an interactive gallery and navigate between the available images and videos.

## Contact & Donations

The website provides direct communication options through:

* WhatsApp group
* Telegram channel

It also displays an electronic wallet number with a button that allows users to copy the number easily.

## Design

The interface is designed for Arabic users and uses:

* RTL layout.
* Arabic typography.
* Green and gold color palette.
* Responsive cards.
* Interactive modals.
* Responsive layouts for smaller screens.

## Project Structure

The current implementation is contained in an HTML file with:

* HTML for the page structure.
* CSS for styling and responsive design.
* JavaScript for application logic and Supabase integration.

## Backend

The project uses **Supabase** for:

* User authentication.
* Equipment/documentation database.
* Image and video storage.
* Adding, updating, retrieving, and deleting records.

## Project Goal

The goal of **Waseela** is to make charitable work more organized and transparent by documenting donated equipment and supplies and showing their progress and supporting media in one accessible platform.

## 🌐 Live Website

If you would like to explore the project and see how it works:

**[Visit Waseela Website](https://waseela-nu.vercel.app/)**

---

## About the Project

**وسيلة | Waseela**

خيرٌ مستمر بأيادٍ شابة.. نبتغي بها الوسيلة إلى الله عز وجل ونعمل على توثيق وإيصال الصدقات والأجهزة للمستحقين.

The project was created by a group of students working to support charitable donations and help ensure that contributions reach those who need them.
