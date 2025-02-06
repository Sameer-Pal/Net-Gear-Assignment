Net Gear Assigment 
Fetching Testimonials from Google Sheets
Setup and Configuration

Google Sheets API Setup

Create a Google Cloud Project
Enable Google Sheets API
Responsive design with Tailwind CSS
Smooth animations using AOS (Animate On Scroll)
Dynamic components for About Us, Services, Why Choose Us, and Contact Us
Organized file structure with component-based architect# Net Gear Assigment 

## Fetching Testimonials from Google Sheets
### Setup and Configuration

**Google Sheets API Setup**


```bin
Create a Google Cloud Project
Enable Google Sheets API
Responsive design with Tailwind CSS
Smooth animations using AOS (Animate On Scroll)
Dynamic components for About Us, Services, Why Choose Us, and Contact Us
Organized file structure with component-based architecture
```

## Tech Stack

**Frontend**: React.js, Tailwind CSS

**Icons**: React Icons

**Routing**: React Router DOM



## Setup Steps

**Clone the repository**:

```bin
git  clone https://github.com/yourusername/lancer-unit.git
cd lancer-unit
```
**Install dependencies**:
```bin 
npm install
```
**Start the development server**:
```bin 
npm start
```
Open your browser and visit:
```bin
http://localhost:3000 
```

### Project Structure

```bin
│── src/
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── Footer.jsx
│   │   ├── AboutUs.jsx
│   │   ├── Services.jsx
│   │   ├── WhyChooseUs.jsx
│   │   ├── ContactUs.jsx
│   ├── Home.jsx
│   ├── App.jsx
│   ├── index.js
│── public/
│── package.json
│── tailwind.config.js
│── README.md
```
### Usage

The Navbar provides easy navigation across different sections
The Home component includes all sections: About Us, Services, Why Choose Us, How It Works, and Contact Us
The Footer contains essential links and social media handles

# Dependencies

**React.js**: UI framework

**Tailwind CSS**: Styling framework

**React Icons**: Icons used across the website

**React Router DOM**: For routing (if needed in the future)

**Motion Div**: Endless Scrolling 

# Troubleshooting
**React Icons Issue**

If you encounter an issue with react-icons, install it manually:
```bin
npm install react-icons
```
ure

Tech Stack

Frontend: React.js, Tailwind CSS
Icons: React Icons
Routing: React Router DOM
Animations: AOS (Animate On Scroll)

Installation
Prerequisites

Node.js
npm

Setup Steps

Clone the repository:
bashCopygit clone https://github.com/yourusername/lancer-unit.git
cd lancer-unit

Install dependencies:
bashCopynpm install

Start the development server:
bashCopynpm start

Open your browser and visit:
Copyhttp://localhost:3000


Project Structure
CopyLancer-Unit/
│── src/
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── Footer.jsx
│   │   ├── AboutUs.jsx
│   │   ├── Services.jsx
│   │   ├── WhyChooseUs.jsx
│   │   ├── ContactUs.jsx
│   ├── Home.jsx
│   ├── App.jsx
│   ├── index.js
│── public/
│── package.json
│── tailwind.config.js
│── README.md
Usage

The Navbar provides easy navigation across different sections
The Home component includes all sections: About Us, Services, Why Choose Us, How It Works, and Contact Us
The Footer contains essential links and social media handles

Dependencies

React.js: UI framework
Tailwind CSS: Styling framework
React Icons: Icons used across the website
AOS: Scroll animations
React Router DOM: For routing (if needed in the future)

Troubleshooting
React Icons Issue
If you encounter an issue with react-icons, install it manually:
bashCopynpm install react-icons
AOS Animations
If animations do not work properly, try importing AOS globally in index.js:
javascriptCopyimport AOS from 'aos';
import 'aos/dist/aos.css';
AOS.init();
License
This project is licensed under the MIT License.
