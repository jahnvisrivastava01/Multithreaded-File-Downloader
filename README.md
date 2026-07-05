# 🧵 Multithreaded File Downloader

<p align="center">
  <strong>Download multiple files simultaneously using Python Multithreading 🚀</strong>
</p>

---

## 📖 Overview

This project demonstrates how **Python Multithreading** can significantly improve the speed of downloading multiple files from the internet.

Instead of downloading files one after another, the program creates a separate thread for each download, allowing multiple files to be downloaded concurrently.

---

## ✨ Features

* 🧵 Multi-threaded file downloading
* ⚡ Concurrent downloads for improved performance
* 📁 Automatically creates a download folder
* 📄 Supports downloading different file types
* ⏱️ Measures execution time
* 🛡️ Basic exception handling
* 💻 Beginner-friendly and easy to understand

---

## 🛠️ Tech Stack

| Technology | Purpose                     |
| ---------- | --------------------------- |
| Python     | Programming Language        |
| threading  | Concurrent execution        |
| requests   | Download files from URLs    |
| os         | File and directory handling |
| time       | Performance measurement     |

---

## 📂 Project Structure

```text
Multithreaded-File-Downloader/
│
├── downloader.ipynb
├── requirements.txt
├── README.md
└── downloads/
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/Multithreaded-File-Downloader.git
```

### 2️⃣ Move into the project directory

```bash
cd Multithreaded-File-Downloader
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the notebook

Open `downloader.ipynb` in:

* Google Colab
* Jupyter Notebook

Run all the cells to start downloading files.

---

## ⚙️ How It Works

1. Stores multiple file URLs.
2. Creates a download directory automatically.
3. Creates one thread for each file.
4. Downloads all files simultaneously.
5. Waits for every thread to finish.
6. Displays the total execution time.

---

## 📊 Sample Output

```text
Thread-1 is downloading dummy.pdf...
Thread-2 is downloading sample.zip...
Thread-3 is downloading sample.txt...

✅ dummy.pdf downloaded successfully!
✅ sample.zip downloaded successfully!
✅ sample.txt downloaded successfully!

🎉 All downloads completed!

Total Time : 2.34 seconds
```

---

## 💡 Future Improvements

* 📊 Progress Bar using `tqdm`
* 🔄 Retry failed downloads
* 📝 Logging support
* 📈 Single-thread vs Multi-thread performance comparison
* 🎨 GUI using Tkinter
* 🌐 React + Flask web interface
* 📥 Download URLs from a text file
* 📊 Download statistics dashboard

---

## 🎯 Learning Outcomes

Through this project, you'll gain hands-on experience with:

* Python Multithreading
* Thread Creation
* Thread Synchronization (`join()`)
* File Handling
* HTTP Requests
* Exception Handling
* Performance Measurement

---

## ⭐ Author
Jahnvi Srivastava

