# 📚 Library Management System 🚀  
## 🎯 Project Objective  
The **Library Management System** is designed to help librarians efficiently manage books and members.  
It provides features for **adding, removing, searching, and sorting books and members** while ensuring smooth book **issuance and return tracking**. 📖  

## ✨ Key Features  
✅ **User-Friendly Console Interface** 🖥️  
✅ **Advanced Sorting & Searching** 🔍  
✅ **Auto-Save & Load Data (Persistent Storage)** 💾  
✅ **Fast Performance with Optimized Algorithms** ⚡  

## 🛠️ Data Structures & Algorithms Used  
### 📌 **Data Structures**  
- **📖 Dynamic Arrays** – For storing book data.  
- **👥 Linked Lists** – For storing member data.  

### 📌 **Sorting Algorithms**  
- **⚡ Quick Sort** – Sorts books by **Title** and **Author**.  
- **⚡ Merge Sort** – Sorts books by **Year**.  

### 📌 Searching Algorithms  
- **🔍 Partial Matching (Substring Search)** → Allows searching by a **part of the book name** or **author name**.  
- **🔍 Linear Search** – Used for **Title** and **Author** searches (Efficient for unsorted text data).  
- **🔍 Binary Search** – Used for **ISBN lookup** (Requires sorted data and is much faster for large datasets).   

## 🚀 Performance Comparison  
📊 **Sorting Algorithm Efficiency**  
- **Quick Sort & Merge Sort** → 🚀 **O(n log n)** (Faster for large datasets)  
- **Bubble Sort (Tested)** → 🐌 **O(n²)** (Significantly slower)  

📊 **Searching Algorithm Efficiency**  
- **Linear Search** → ✅ Best for unsorted data.  
- **Binary Search** → ✅ Best for sorted datasets, much faster than linear search.  

## 🎯 Why These Algorithms?  
✔️ **Quick Sort & Merge Sort** outperform **Bubble Sort** significantly for large data sets.  
✔️ **Binary Search** is used for ISBN lookup because it's faster in **sorted datasets**.  
✔️ **Linear Search** is used for Title/Author since sorting text strings is complex.  
