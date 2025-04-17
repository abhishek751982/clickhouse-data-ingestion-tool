# 📊 Bidirectional ClickHouse & Flat File Ingestion Tool

A full-stack web application that enables seamless **bidirectional data transfer** between **ClickHouse** databases and **Flat File (CSV)** formats.

Supports column selection, JWT authentication, data preview, and record count reporting — all from an intuitive frontend UI.

---

## 🔧 Features

- 🔁 **Bidirectional Ingestion**
  - ClickHouse → Flat File (CSV)
  - Flat File (CSV) → ClickHouse

- ✅ **JWT Authentication** for secure ClickHouse access

- 🧠 **Schema Discovery & Column Selection**
  - Auto-fetch table schema
  - Select desired columns via checkboxes

- 📊 **Ingestion Summary**
  - Record count display
  - Status tracking (connecting, ingesting, completed)

---

## 🖼️ UI Screenshots

### 🔘 Source Selection
![Source Selection](https://github.com/user-attachments/assets/b8e68447-da42-4ffd-a58d-23c366822da6)  
![Source Selection](https://github.com/user-attachments/assets/ae3e4bbb-8b7d-4f2f-a356-97f6bdb3ab04)

### 📋 Column Selection & Data Preview
![Column Selection](https://github.com/user-attachments/assets/f6788f2f-a338-430e-82db-cf6cbd99575e)

### ⏳ Ingestion Progress & Summary
![Ingestion Progress](https://github.com/user-attachments/assets/61d91e24-2e74-421d-b693-72247cdcf463)

---

## 🚀 Tech Stack

| Layer      | Technology                    |
|------------|-------------------------------|
| Frontend   | React.js + Tailwind CSS       |
| Backend    | Go                            |
| Database   | ClickHouse (with JWT)         |

---

## ⚙️ Installation & Setup

### 🔽 Clone the Repository

```bash
git clone https://github.com/abhishek751982/clickhouse-data-ingestion-tool.git
cd clickhouse-data-ingestion-tool
```
---

## 🖥️ Backend Setup

1. **Navigate to the Backend directory**

```bash
cd backend
```
2. **Install Go dependencies**

```bash
go mod download
```
3. **Start the server**
```bash
go run main.go
```
---

## 🌐 Frontend Setup

1. **Navigate to the frontend directory**

```bash
cd frontend
```
2. **Install dependencies**

```bash
npm install
```
3. **Start the development server**

```bash
npm run dev
```
The frontend will be available at http://localhost:5173
