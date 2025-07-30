# mcp-learning-path
An AI-powered learning path generator using LangChain, Streamlit,Python,youtube api,Google Drive Api and Google APIs.
Learning Path Generator with Model Context Protocol (MCP)
This project is a Streamlit-based web application that generates personalized learning paths using the Model Context Protocol (MCP). It integrates with various services including YouTube, Google Drive, and Notion to create comprehensive learning experiences.

Features
🎯 Generate personalized learning paths based on your goals
🎥 Integration with YouTube for video content
📁 Google Drive integration for document storage
📝 Notion integration for note-taking and organization
🚀 Real-time progress tracking
🎨 User-friendly Streamlit interface
Prerequisites
Python 3.10+
Google ai Studio API Key
Pipedream URLs for integrations (YouTube and either Drive or Notion)
Installation
Clone the repository:

Create and activate a virtual environment:

Install the required packages:

pip install -r requirements.txt
Configuration
Before running the application, you'll need to set up:

Google API Key
Pipedream URLs for:
YouTube (required)
Google Drive or Notion (based on your preference)
Running the Application
To start the application, run:

streamlit run app.py
The application will be available at http://localhost:8501 by default.

Usage
Enter your Google ai studio API key and Pipedream URLs in the sidebar
Select your preferred secondary tool (Drive or Notion)
Enter your learning goal (e.g., "I want to learn python basics in 3 days")
Click "Generate Learning Path" to create your personalized learning plan
Project Structure
app.py - Main Streamlit application
utils.py - Utility functions and helper methods
prompt.py - Prompt template
requirements.txt - Project dependencies

###   STEPS TO COMPLETE THE PROJECT ##
Project-5: Learning Path Generator
Prerequisites:

Gemini api Key
Pipedream authorised YouTube, Google Drive, Notion URLs
To get the Gemini AI Studio API key:

Go to Google AI Studio: Access the Google AI Studio page at Google AI Studio
Log in to your Google account.
Get API key: Click on the "Get API key" button, usually found in the left-side navigation panel.
Click on the "Create API Key" button, located at the top right.
Click on the "Create API Key in the New Project" button (if you have an existing project, you can use the key from that project). It will generate an API key. Click the "Copy" button to copy the key. Click on the "Create API Key in the New Project" button (if you have an existing project, you can use the key from that project). It will generate an API key. Click the "Copy" button to copy the key.

To get the Gemini AI Studio API key:
For Pipedream MCP servers:

Pipedream navigate and sign in with a Google account
YouTube Data MCP Server: YouTube Data MCP Server

In the Configuration:
Connect with your Google account and give all required permissions to access
Copy the MCP server URL
Do the same for the drive and notion MCP servers:

Google Drive MCP Server
Notion MCP Server
Project Setup Guide:
Prerequisites:

A terminal or command prompt.
Cursor IDE
Python 3.10+ is installed on your system.
Python installation in Windows
Python installation in Mac
To update the python latest version: How to Update Python Version on Windows-Quick Guide
Setup Steps

Follow these steps in your terminal or command prompt:

Step 1: Navigate to Your Home Directory (Optional, but Recommended Starting Point)
Step 2: Clone the Git Hub repo link

Repo Link: Git Hub repo link
Click on the “Code” button
  <img width="472" height="329" alt="image" src="https://github.com/user-attachments/assets/7eefef5e-01fd-439a-ab0e-533a81fa784a" />
<img width="472" height="329" alt="image" src="https://github.com/user-attachments/assets/89d58ddb-7303-4cd9-b747-ea8eb933d3e4" />


Click on the “Download ZIP”, it will download a zip file to your downloads
Go to the downloads and “unzip/uncompress” it. It will create a new folder with the same name.
Step 3: Open the Project Folder with the Cursor IDE:

Open the cursor, click on the “file” (left side, top corner)
Click on the “Open Folder”, select our unzipped folder
Now, your project file is open in your Cursor IDE
Step 4: Create a Virtual Environment

Run the following command while inside the project directory:
python -m venv venv


Explanation: This command uses the venv module from Python's standard library to create a virtual environment named venv inside your current directory (project directory).
Step 5: Activate the Virtual Environment

On Ubuntu (or other Linux/macOS):
source venv/bin/activate


On Windows: Using Command Prompt (cmd.exe):
venv\Scripts\activate


Verification: After activation, your terminal prompt should change, typically showing (venv) at the beginning, like this:
(venv) yourusername@yourcomputer:~/mcplearningpath_generator$
    

Step 6: Install Requirements

Install the listed packages using pip. Run this command inside the activated virtual environment:
pip install -r requirements.txt


Step 7: Install Requirements

Run the app.py file from your terminal by using streamlit
streamlit run app.py


The application will be available at Local Host Streamlit by default.


