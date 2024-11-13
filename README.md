# Automated Attendance System Using Face Detection and OCR

This project presents an **Automated Attendance System** designed for schools and colleges, where attendance tracking is often labor-intensive and prone to errors. Leveraging **YOLO** for face detection, **EasyOCR** for roll number extraction, and **Excel** for attendance tracking, the system automates the process and improves accuracy. The user-friendly interface, built with **customtkitner**, makes it accessible and easy to operate for educators.

## Project Overview
Manual attendance processes are inefficient, time-consuming, and susceptible to errors. This project aims to overcome these challenges by implementing an automated attendance solution. Using face detection and OCR technologies, the system detects student faces and extracts roll numbers from stickers affixed to the left side of their faces, marking attendance accurately and efficiently.

##Project Paper and Report
   ```bash
      Paper : https://doi.org/10.33564/IJEAST.2024.v09i04.011
      Report : https://drive.google.com/file/d/14EC9RtsSFbBoCKLE9MXoKaMuaxvY7Mqt/view?usp=drive_link
   ```
## Features
- **Automatic Face Detection**: Detects student faces in real-time or from provided images using a custom-trained YOLO model.
- **OCR for Roll Number Extraction**: Extracts roll numbers from stickers on the left side of students' faces using EasyOCR.
- **Excel Integration**: Automatically logs attendance into an Excel file, creating new sheets for each day and generating weekly attendance summaries.
- **User-Friendly GUI**: Built with customtkitner for ease of use, allowing educators to manage attendance with minimal effort.
- **Automated Reporting**: Attendance percentages are automatically calculated, and weekly reports are generated at the end of each week.

## Project Structure
The project is organized as follows:
- `Attendance_Process.py` - Main script for the attendance system
- `APP.py` - Graphical user interface script built using customtkinter
- `model/` - YOLO model configuration and weights
- `readme.md` - Project documentation

## Workflow

1. **Initialization**: System loads YOLO model and EasyOCR for face and roll number detection.
2. **Mode Selection**: Choose between live webcam capture or image input mode.
3. **Face Detection**: Detects and marks student faces in the image or live feed.
4. **Roll Number Extraction**: Extracts roll number from sticker positioned on the left side of detected faces.
5. **Excel Logging**: Attendance is recorded in an Excel sheet, creating a daily attendance log.
6. **Report Generation**: At the end of each week, attendance percentage is calculated, and a summary report is created.

## Software and Libraries Used
- **Python** - Core programming language
- **YOLO (You Only Look Once)** - Custom-trained face detection model
- **EasyOCR** - Optical character recognition for roll number extraction
- **customtkitner** - Custom GUI framework in Python
- **Microsoft Excel** - Used to log and manage attendance data

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/https://github.com/TejasVarute/Attendace-System-using-YOLO
