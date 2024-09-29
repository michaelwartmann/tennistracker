# Tennis Session Tracker

## Overview

The **Tennis Session Tracker** is a simple, responsive web application designed to help you track your tennis training sessions. This tool was developed alongside a custom GPT named **Tennis Session Tracker**, which guides you through logging your training data, including groundstroke practice with a ball machine and serve practice.

## Purpose

This project is designed to support a specific tennis training regimen that includes:
- **Groundstroke Practice**: Using a ball machine to improve consistency and accuracy.
- **Serve Practice**: Tracking double faults across multiple service games.

The web application allows you to upload a CSV file generated from your training sessions and view your performance data in a clear and accessible format.

## Features

- **CSV Upload**: Easily upload a CSV file containing your tennis session data.
- **Responsive Design**: The web page is fully responsive, ensuring it displays correctly on both desktop and mobile devices.
- **Dynamic Table Generation**: The uploaded CSV data is displayed in a table format that adapts to different screen sizes.
- **Ease of Use**: Simply drag and drop or select your CSV file, and the data will be displayed in an easy-to-read format.

## Training Routine

### Groundstroke Practice
- **Setup**: You practice with a ball machine that feeds you a set number of shots.
- **Objective**: Track the number of missed shots to calculate your hit percentage.
- **Logging**: After each round, the number of missed shots and total shots are logged, and the hit percentage is calculated.

### Serve Practice
- **Setup**: You focus on serving, logging the sequence of double faults for each service game.
- **Objective**: Track double faults to improve consistency under pressure.
- **Logging**: You enter a sequence representing each service game (e.g., `0 0 0 1 0`), where each digit represents whether a double fault occurred in that game.

## Technologies Used

- **HTML5**: For structuring the web page.
- **CSS3**: For styling the page, including responsive design features.
- **JavaScript**: For reading and displaying the CSV file content dynamically.

## Setup Instructions

1. **Download or Clone the Repository**:
   - Download the code as a ZIP file or clone it using Git:
     ```bash
     git clone https://github.com/your-username/tennis-session-tracker.git
     ```

2. **Navigate to the Project Directory**:
   - Open the directory containing the project files.

3. **Open the `index.html` File**:
   - Simply double-click the `index.html` file to open it in your default web browser.

## Usage Instructions

### 1. Uploading Your CSV File
- Click on the "Choose File" button.
- Select your CSV file from your computer. The file should follow this format:
  ```csv
  Date,Round,Hit Percentage,Double Faults,Service Games Played,Estimated Total Serves,Double Fault Percentage,Total Duration,Calories Burned
  2024-09-28,1,79.17%,1,5,20,5.00%,1 hour,600
  2024-09-28,2,74.75%,0,4,16,0.00%,1 hour,600
  ...

