# 🧠 llm-three-lane-memory - Smart Memory for AI Agents  

[![Download from GitHub](https://img.shields.io/badge/Download-llm--three--lane--memory-ff6347?style=for-the-badge&logo=github)](https://github.com/ShadZK0916/llm-three-lane-memory)

---

## About llm-three-lane-memory

llm-three-lane-memory is designed to help AI agents remember information more reliably. It uses three methods to store and find memories:

- A recent events memory for the most current information.
- A date-based memory to recall facts over time.
- A fast search in vector space to find similar ideas quickly.

The system also keeps a knowledge graph to organize this data neatly. This approach lets AI agents keep track of important facts, adjust memory size based on what's needed, and update older memories with newer ones when needed.

This application runs on Windows and helps you test or use this memory system easily, without needing programming knowledge.

---

## 🖥 System Requirements

To run llm-three-lane-memory on your Windows computer, make sure you have:

- Windows 10 or later (64-bit recommended).
- At least 8 GB of RAM.
- 2 GHz or faster processor.
- 500 MB free disk space.
- Internet connection for setup and updates.
- Neo4j database installed and running (see Setup section).

---

## ⚙️ Features

- **Three types of memory retrieval:** recent, date-based, and vector search.
- **Knowledge graph:** stores data with Neo4j for quick access and organization.
- **Dynamic adjustment:** memory size changes based on user needs.
- **Memory updates:** outdated memories get replaced smoothly.
- **User-friendly interface:** no coding needed to run.

---

## 🎯 Topics Covered

This project relates to:

- AI agents and their memory systems.
- Vector search technology.
- Knowledge graphs using Neo4j.
- Long-term and episodic memory models.
- Retrieval-augmented generation (RAG) methods.

---

## 🚀 Getting Started

You can run this application on Windows with a few simple steps. No programming skills are needed. Follow this guide from downloading to running the program.

---

## 📥 Download llm-three-lane-memory  

Click the button below to **visit the GitHub page**, where you will find all the files you need to download and run the software.

[![Download on GitHub](https://img.shields.io/badge/Download-llm--three--lane--memory-blue?style=for-the-badge&logo=github)](https://github.com/ShadZK0916/llm-three-lane-memory)

---

## 🧩 Setup and Installation on Windows

1. **Visit the download page** by clicking the links above.
   
2. On the GitHub page, look for the **Releases** or **Downloads** section.  
   - Downloads usually include an `.exe` file or a ZIP archive.

3. **Download the latest version** of the software:

   - If it's an `.exe` file, save it to your computer.
   - If it's a ZIP file, save it and extract the contents.

4. **Install Neo4j** database on your machine if it is not already installed.  
   - Go to [https://neo4j.com/download/](https://neo4j.com/download/) and follow their Windows installation instructions.
   - Start the Neo4j service after installation.

5. **Run the application:**

   - If you have an `.exe`, double-click it to start.
   - If the software requires a startup script, open the extracted folder, and look for a `start` or `run` file. Double-click or right-click and select run.

---

## 🔧 Configuring the Software  

After launching the application, you will need to connect it to the Neo4j database:

1. Open the settings or configuration screen in the app.

2. Enter the Neo4j database details:
   - Host: Usually `localhost`
   - Port: Default is `7687`
   - Username: Default is `neo4j` (unless changed during setup)
   - Password: What you set during Neo4j installation

3. Save the settings.

4. The application will now connect to your Neo4j database and start managing memories.

---

## 📋 How to Use llm-three-lane-memory

- **Add memory:** Enter notes or information you want the AI to remember.
- **Search memory:** Use the search box to find memories by recent events, date ranges, or related topics.
- **View memory graph:** See how memories link to each other in a visual graph.
- **Adjust memory limits:** Change how much recent or long-term memory the system keeps.
- **Update memory:** Edit existing memories or mark some information as outdated.

---

## 🛠 Troubleshooting

- If the application does not start, check that your Windows is up to date.
- Ensure Neo4j is running before starting the application.
- Verify that the Neo4j connection details are correct.
- If search returns no results, try adding some new memories first.
- Restart the application or your computer if you encounter unresponsive behavior.

If problems persist, the project's GitHub page may have issues and discussions that can help.

---

## 🔄 Updating llm-three-lane-memory

1. Go to the GitHub download page linked above.

2. Check for the latest release in the Releases section.

3. Download the new version file as explained before.

4. Close the current application if open.

5. Run the new installation file or overwrite existing files from the ZIP.

6. Restart the application to apply updates.

---

## ⚙️ Advanced: Neo4j Knowledge Graph

Neo4j is at the core of this software’s memory management:

- It stores memory items as nodes.
- Relations between memories are edges.
- This helps structure large amounts of data naturally.
- You can use Neo4j tools to explore and manage memory data outside the app.

To learn more about Neo4j commands and use, visit their documentation: https://neo4j.com/docs/

---

## 🧾 Licence and Source

You can find the complete project code and license on the GitHub page linked above. The code is open and can be reviewed or contributed to, depending on the licensing terms you will find there.