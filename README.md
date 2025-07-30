# 🚀 Learning Path Generator with Model Context Protocol (MCP)

This project is a **Streamlit-based web application** that generates personalized learning paths using the **Model Context Protocol (MCP)**. It integrates seamlessly with platforms like **YouTube**, **Google Drive**, and **Notion** to deliver a well-rounded and dynamic learning experience.

---

## ✨ Features

- 🎯 Generate **personalized learning paths** based on your goals
- 🎥 Integration with **YouTube** for curated video content
- 📁 **Google Drive** integration for storing documents
- 📝 **Notion** integration for note-taking and planning
- 📊 **Real-time progress tracking**
- 🖥️ Intuitive and interactive **Streamlit UI**

---

## ⚙️ Prerequisites

- Python **3.10+**
- A **Google AI Studio API Key**
- Active **Pipedream webhook URLs** for integrations:
  - YouTube (required)
  - Google Drive **or** Notion

---

## 🛠️ Installation

1. **Clone the repository**:

```bash
git clone https://github.com/PITTIHARSHAVARDHAN/mcp-learning-path.git
cd mcp-learning-path
Create and activate a virtual environment:

bash
Copy
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install the dependencies:

bash
Copy
pip install -r requirements.txt
🔧 Configuration
Before running the app, make sure to configure the following:

Your Google AI Studio API key

Pipedream webhook URLs for:

✅ YouTube (Required)

✅ Google Drive or Notion (Choose one)

You’ll enter these details through the Streamlit sidebar when the app is running.

🚀 Running the Application
To start the application, run:

bash
Copy
streamlit run app.py
The app will open in your browser at: http://localhost:8501

🧠 Usage
Open the app in your browser.

Enter your Google AI Studio API key and Pipedream URLs in the sidebar.

Select your preferred integration (Google Drive or Notion).

Type your learning goal, e.g.:

"I want to learn Python basics in 3 days"

Click "Generate Learning Path" to build your customized roadmap!

📁 Project Structure
bash
Copy
.
├── app.py              # Main Streamlit app
├── utils.py            # Helper functions
├── prompt.py           # Prompt templates for the LLM
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
📌 License
MIT License (or your choice)

🙌 Contributions
Contributions, issues, and feature requests are welcome!
Feel free to open an issue or submit a pull request.

🌐 Live Demo
Coming soon via Streamlit Community Cloud!

yaml
Copy
Edit

---

### ✅ What to do:

1. Copy the content above.
2. Open your terminal and run:
   ```bash
   nano README.md
Paste the content and save (CTRL+O → Enter → CTRL+X)

Then run:

bash
Copy
Edit
git add README.md
git commit -m "docs: add full project README"
git push origin main
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


