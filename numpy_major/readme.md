🧮 NumPy Calculator

🎯 Project Overview

NumPy Calculator is an interactive Python Jupyter Notebook project that demonstrates how to perform mathematical computations efficiently using NumPy.
It acts as both a simple calculator and a NumPy learning tool, allowing users to perform arithmetic and basic statistical operations with clean, modular code and user-friendly interaction.

✨ Features
🧩 1. Input Handling & Validation

Accepts multiple space-separated numbers from the user.

Uses NumPy arrays for processing numeric data.

Handles invalid input gracefully using try-except.

Prevents crashes when encountering non-numeric values.

➕ 2. Arithmetic Operations

Performs four fundamental mathematical operations:

Addition: Computes the total sum of numbers.

Subtraction: Performs sequential subtraction.

Multiplication: Calculates the product of elements.

Division: Handles element-wise division safely, including divide-by-zero checks.

📊 3. Statistical & Array Operations

Demonstrates use of NumPy’s mathematical and statistical methods:

mean(), sum(), max(), min(), std()

Calculates totals, averages, and simple data summaries.

⚙️ 4. Interactive Menu System

Provides a terminal-based, menu-driven interface.

Users can select the operation they want to perform.

Displays clear, formatted results for each selection.

🧠 Learning Objectives

By exploring this notebook, you’ll understand:

NumPy Basics: Creating arrays, performing arithmetic operations, and leveraging vectorization.

Python Programming Concepts: Modular function design, input handling, and conditional execution.

Practical Application: Combining NumPy and Python logic to create real-world mini utilities.

🚀 Getting Started
🔧 Prerequisites

Make sure you have the following installed:

Python 3.6 or higher

Jupyter Notebook or JupyterLab

NumPy library

⚙️ Installation

Clone the repository and install dependencies:

git clone https://github.com/KushmithaTA8/numpy-calculator.git  
cd numpy-calculator  
pip install numpy jupyter  

▶️ Running the Notebook
Option 1: Jupyter Notebook
jupyter notebook Calculator_project.ipynb

Option 2: JupyterLab
jupyter lab Calculator_project.ipynb

Option 3: Google Colab

Upload Calculator_project.ipynb to Google Drive.

Open with Google Colab.

Run all cells (Runtime → Run all).

Option 4: VS Code

Install Python & Jupyter extensions.

Open the .ipynb file.

Select a Python kernel and run cells.

💻 Example Usage
Enter numbers separated by space: 10 20 30  
Choose operation:  
1. Add  
2. Subtract  
3. Multiply  
4. Divide  


Result:
Sum: 60

or

Enter numbers separated by space: 6 3  
Choose operation: 4  
Result: 2.0

🔧 Key NumPy Functions Demonstrated
Category	Functions
Array Creation	array(), astype()
Arithmetic	add(), subtract(), multiply(), divide()
Statistics	mean(), sum(), max(), min(), std()
Validation	try-except for input and divide-by-zero handling
📁 Project Structure
numpy-calculator/
│
├── Calculator_project.ipynb     # Main notebook  
├── README.md                    # Project documentation  
├── requirements.txt              # Dependencies (NumPy, Jupyter)  
└── LICENSE                       # License file  

💡 Use Cases

This project can be adapted for:

Educational demonstrations of NumPy basics

Teaching Python input/output handling

Mini calculators for basic statistical analysis

Beginner-friendly NumPy tutorials

🤝 Contributing

Contributions are welcome! You can:

Add more mathematical or statistical functions.

Create a GUI using tkinter or streamlit.

Add unit testing and improve code performance.

How to Contribute
# 1. Fork the repository  
# 2. Create your feature branch  
git checkout -b feature/AmazingFeature  
# 3. Commit your changes  
git commit -m "Add some AmazingFeature"  
# 4. Push to your branch  
git push origin feature/AmazingFeature  
# 5. Open a Pull Request  

📝 License

This project is licensed under the MIT License — see the LICENSE file for details.

👩‍💻 Author

Kushmitha T A
💻 Python Developer | Data Enthusiast | Machine Learning Learner

📧 Email: kushmitha8904@gmail.com

🌐 GitHub: KushmithaTA8

💼 LinkedIn: Kushmitha T A

🙏 Acknowledgments

NumPy Documentation

Jupyter Project

Python open-source community for excellent resources

🐛 Troubleshooting

❓ Kernel not responding

Restart the kernel → Kernel → Restart & Clear Output

⚠️ Import Errors

Reinstall NumPy:

pip install --upgrade numpy


🧮 Notebook not running

Ensure the correct Python kernel is selected.

Verify that dependencies are installed properly.

⭐ If you found this project helpful, please give it a star on GitHub!
📬 For questions or suggestions, open an issue or reach out directly.

🎉 Happy Learning with NumPy!