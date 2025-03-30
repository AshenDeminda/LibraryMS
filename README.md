<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Library Management System - README</title>
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6;">

    <h1>📚 Library Management System 🚀</h1>

    <h2>🔹 Group No: 07</h2>
    <ul>
        <li>🏅 <b>EG/2022/5003</b> – Dilhara K.K.V.R</li>
        <li>🏅 <b>EG/2022/5113</b> – Jayawickrama J.A.N.D</li>
        <li>🏅 <b>EG/2022/5290</b> – Rathnayake R.M.A.D</li>
    </ul>

    <h2>🎯 Project Objective</h2>
    <p>The <b>Library Management System</b> is designed to help librarians efficiently manage books and members. 
    It provides features for <b>adding, removing, searching, and sorting books and members</b> while ensuring smooth book 
    <b>issuance and return tracking</b>. 📖</p>

    <h2>✨ Key Features</h2>
    <ul>
        <li>✅ <b>User-Friendly Console Interface</b> 🖥️</li>
        <li>✅ <b>Advanced Sorting & Searching</b> 🔍</li>
        <li>✅ <b>Auto-Save & Load Data (Persistent Storage)</b> 💾</li>
        <li>✅ <b>Fast Performance with Optimized Algorithms</b> ⚡</li>
    </ul>

    <h2>🛠️ Data Structures & Algorithms Used</h2>

    <h3>📌 Data Structures</h3>
    <ul>
        <li>📖 <b>Dynamic Arrays</b> – For storing book data.</li>
        <li>👥 <b>Linked Lists</b> – For storing member data.</li>
    </ul>

    <h3>📌 Sorting Algorithms</h3>
    <ul>
        <li>⚡ <b>Quick Sort</b> – Sorts books by <b>Title</b> and <b>Author</b>.</li>
        <li>⚡ <b>Merge Sort</b> – Sorts books by <b>Year</b>.</li>
    </ul>

    <h3>📌 Searching Algorithms</h3>
    <ul>
        <li>🔍 <b>Linear Search</b> – For finding books by <b>Title</b> or <b>Author</b> (Efficient for unsorted text data).</li>
        <li>🔍 <b>Binary Search</b> – For finding books by <b>ISBN</b> (Requires sorted data but is much faster for large datasets).</li>
    </ul>

    <h2>🚀 Performance Comparison</h2>
    
    <h3>📊 Sorting Algorithm Efficiency</h3>
    <ul>
        <li>✅ <b>Quick Sort & Merge Sort</b> → 🚀 <b>O(n log n)</b> (Faster for large datasets)</li>
        <li>❌ <b>Bubble Sort (Tested)</b> → 🐌 <b>O(n²)</b> (Significantly slower)</li>
    </ul>

    <h3>📊 Searching Algorithm Efficiency</h3>
    <ul>
        <li>✅ <b>Linear Search</b> → Best for unsorted data.</li>
        <li>✅ <b>Binary Search</b> → Best for sorted datasets, much faster than linear search.</li>
    </ul>

    <h2>🎯 Why These Algorithms?</h2>
    <ul>
        <li>✔️ <b>Quick Sort & Merge Sort</b> outperform <b>Bubble Sort</b> significantly for large data sets.</li>
        <li>✔️ <b>Binary Search</b> is used for ISBN lookup because it's faster in <b>sorted datasets</b>.</li>
        <li>✔️ <b>Linear Search</b> is used for Title/Author since sorting text strings is complex.</li>
    </ul>

    <h2>📌 How to Run</h2>
    <ol>
        <li><b>Clone the Repository</b></li>
        <pre>
            <code>
git clone https://github.com/your-repo-url
cd Library-Management-System
            </code>
        </pre>
        
        <li><b>Run the Program</b></li>
        <pre>
            <code>
dotnet run
            </code>
        </pre>

        <li>🎉 <b>Enjoy Managing Your Library!</b> 🚀</li>
    </ol>

</body>
</html>
