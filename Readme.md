# Debt Collection Conversation Analysis

## Project Overview
This project analyzes conversations between debt collection agents and borrowers, focusing on three main tasks:

1. **Profanity Detection**: Identifies call IDs where agents or borrowers have used profane language.
2. **Privacy and Compliance Analysis**: Identifies instances where agents share sensitive information without proper identity verification.
3. **Call Quality Metrics Analysis**: Calculates overtalk (simultaneous speaking) and silence percentages per call, along with visualizations.

The analysis leverages both pattern matching and machine learning approaches, with comparative analysis to determine the best method for each scenario.

## Repository Contents
- **Code for Question 1 & 2 (Profanity Detection and Privacy Compliance)**: Includes both regex-based detection systems and machine learning models.
- **Visualization Code for Question 3 (Call Quality Metrics)**: Code for calculating and visualizing overtalk and silence percentages.
- **Technical Report**: Document detailing implementation recommendations and analysis.

## Setup Instructions

# Installation Guide

## Step 1: Prerequisites
Before beginning the installation, ensure you have Python 3 installed on your system.

## Step 2: Set up a Virtual Environment
Create a Python virtual environment using `venv`:
``` bash
python3 -m venv venv
```
Activate the virtual environment:

On Windows:
``` bash
venv\Scripts\activate
```
On macOS/Linux:
``` bash 
source venv/bin/activate
```
## Step 3: Install Dependencies
Install the required Python packages from `requirements.txt`:
``` bash
pip install -r requirements.txt
```
## Step 4: Add the All_Conversations Folder after Unzip
After unzipping the All_Conversations.zip file, place the All_Conversations folder into the project directory Ensure the directory structure looks something like this:
``` bash
/YourProjectFolder
    /All_Conversations
    /venv
    requirements.txt
    temp.ipynb
    ...
```
