# Daily-Journal-Node.js-App

A simple command-line journal app built using **Node.js**. It helps you create, read, and delete journal entries saved in a local JSON file. This project is ideal for learning **file system (fs)** operations, working with **JSON data**, and **basic CLI interactivity**.

---

## 📦 Features

- 📝 Add journal entries with title and content
- 📖 View all existing journal entries
- ❌ Delete a journal entry by its unique ID
- 💾 Data is stored persistently in a JSON file
- 🧠 Simple and clean project structure to learn Node.js fundamentals

---

## 🛠️ Technologies Used

- **Node.js**
- **File System (`fs`)**
- **JavaScript (ES6+)**
- No external libraries required

---

## 📂 Folder Structure

```
📁 daily-journal-node
├── 📁 controllers
│   └── 📄 journalController.js
├── 📁 data
│   └── 📄 journal.json
├── 📁 node_modules
├── 📁 utils
│   └── 📄 fileHelper.js
├── 📄 app.js
├── 📄 package.json
├── 📄 package-lock.json
└── 📄 README.md

```


---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/abdul-rahman-0x/daily-journal-node.git
cd daily-journal-node
```


### 2. Run the App

```
node app.js
```



## 🧪 How to Use

When you run `node app.js`, the app will guide you through the following steps:

---

### ➕ Add a New Entry

```bash
> Enter Title: "Workout Log"
> Enter Content: "Ran 5km and did pushups"
✅ Entry saved successfully!
```



### 📜 View All Entries
```bash
📖 Journal Entries:
-----------------------
🆔: 1
📌 Title: Workout Log
📝 Content: Ran 5km and did pushups
🕒 Created At: 2025-07-26T15:30:00.000Z
-----------------------
```


### 🗑️ Delete an Entry

```
> Enter ID to delete: 1
🗑️ Entry deleted successfully.
```


### 📄 Sample JSON Data (data/journal.json)


```
[
  {
    "id": 1,
    "title": "Workout Log",
    "content": "Ran 5km and did pushups",
    "createdAt": "2025-07-26T15:30:00.000Z"
  }
]
```


##  Author - Roman Shaikh



### 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.


```

---

### 📦 2. `package.json`

```json
{
  "name": "daily-journal-node",
  "version": "1.0.0",
  "description": "A simple daily journal app using Node.js and JSON file system",
  "main": "index.js",
  "scripts": {
    "start": "node index.js"
  },
  "author": "Roman Shaikh",
  "license": "MIT"
}
```





