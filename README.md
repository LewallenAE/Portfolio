# 🧠 Anthony Lewallen – Developer Portfolio

## Check out 🚀 **[Eugenius – Full-Stack AI Chat UI](https://react-llm-chat.vercel.app/)**  
*(React + Express + OpenAI API | Markdown rendering, dark/light mode, animated loaders, chat history)*

---

## 💼 About This Portfolio

This repository contains the source code and structure for my portfolio site, showcasing full-stack and AI-focused projects I've built using JavaScript, Java, Python, and LLMs. It's deployed via GitHub Pages and acts as a hub for my work.

---

## 🛠️ Tech Stack

- **Languages** Java, Python, JavaScript
- **Frontend**: React, Vite, TypeScript, Tailwind CSS  
- **Backend**: Node.js, Express  
- **AI/LLM**: OpenAI API  
- **Java Projects**: OOP, JavaFX, interfaces, abstract classes  
- **Deployment**: GitHub Pages, Vercel, Render (Back-End)

---

## 📂 Featured Projects

💬 **[Eugenius](https://github.com/LewallenAE/react-llm-chat)** – A full-stack LLM chatbot using React, Node.js, and the OpenAI API with markdown rendering, animated loaders, and persistent chat history

🐙 **[GitFolio](https://github.com/LewallenAE/gitfolio)** – GitHub-powered portfolio generator with live repo cards and commit stats  
*Try entering `LewallenAE` or `torvalds` in the search bar!*

🐯 **[Java Zoo Project](https://github.com/LewallenAE/Portfolio/tree/main/Desktop/Portfolio/src/Zoo)** – Object-oriented animal simulation using inheritance, interfaces, and polymorphism

🦁 **[Zoo Upgrade Project](https://github.com/LewallenAE/Portfolio/tree/main/Desktop/Portfolio/src/Zoo_Upgrade)** – Refactored zoo simulation with file I/O, serialization, and persistent animal states

📚 **[Library Search Engine (CLI)](https://github.com/LewallenAE/Portfolio/tree/main/Desktop/Portfolio/src/Library)** – Command-line Java library manager with search and sort capabilities

🔎 **[Library Search Engine GUI w/ SQL](https://github.com/LewallenAE/Portfolio/tree/main/Desktop/Portfolio/src/LibraryGUI)** – A full-stack JavaFX GUI app for managing library data backed by a SQL database


## 📁 Project Folder Structure Structure

### How to Run This Repo Out of the Box

Make sure your local folder structure matches the layout below when importing into IntelliJ, Eclipse, VS Code, or any Java-friendly IDE.

- 
```
| /Wherever/Portfolio/
├── .idea/                        # IntelliJ project files (auto-generated)
├── .gitignore
├── Portfolio.iml                # IntelliJ module file
├── pom.xml                      # Maven config
├── target/
│   └── classes/                 # Compiled Java class files
├── src/
│
│   ├── Library/                 # CLI-based Library Management System (Java)
│   │   ├── Book.java
│   │   ├── Library.java
│   │   ├── LibraryMenu.java
│   │   ├── LibrarySerializer.java
│   │   ├── Main.java            # Entry point for CLI
│   │   ├── SortUtil.java
│   │   └── UserInteractionLogger.java
│
│   ├── resources/               # Data and testing files used by Library CLI
│   │   ├── data/
│   │   │   ├── books.txt
│   │   │   ├── library.ser      # Serialized library object
│   │   │   └── user_interactions.log
│   │   └── test/
│   │       └── test_books.txt  #for unit testing if needed
│
│   ├── LibraryGUI/              # JavaFX-based GUI for the Library system
│   │   └── main/
│   │       ├── java/
│   │       │   ├── module-info.java
│   │       │   └── com/
│   │       │        └── librarygui/
│   │       │                ├── Book.java
│   │       │                └── LibraryUI.java
│   │       └── resources/
│   │           ├── primary.fxml
│   │           └── secondary.fxml
│
│   ├── Zoo/                     # Intro OOP project (no I/O)
│   │   ├── Animal.java
│   │   ├── Dolphin.java         # Implements Swim
│   │   ├── Eat.java             # Interface
│   │   ├── Main.java            # Entry point for zoo simulation
│   │   ├── Penguin.java         # Implements Walk and Swim
│   │   ├── Swim.java            # Interface
│   │   ├── Tiger.java           # Implements Walk and Eat
│   │   └── Walk.java            # Interface
│
│   └── Zoo_Upgrade/             # Advanced Zoo w/ File I/O + Serialization
│       ├── Animal.java
│       ├── Dolphin.java
│       ├── Eat.java
│       ├── Main.java
│       ├── Penguin.java
│       ├── Swim.java
│       ├── Tiger.java
│       └── Walk.java
```

---

## 👋 Contact

- 🔗 [LinkedIn](https://linkedin.com/in/anthony-lewallen)  
- 💻 [GitHub](https://github.com/LewallenAE)

---

> “I don't just build projects—I engineer experiences.” 🚀
