💰 My Finance Hub (CLI-Based Personal Finance Tracker)  
My Finance Hub is a Python-based command-line application that helps users track their income and expenses, view financial summaries over time, and visualize trends. This tool is designed for individuals who want a simple, offline, and lightweight solution to manage personal finances without complex GUIs or databases.

🧾 Key Functionalities  
1. Add Transactions 💸  
• Log income or expense entries via a user-friendly command-line interface  
• Input validation for date, amount, and category (I/E)  
• Option to enter a description for better tracking  

2. View Financial Summary 📊  
• Filter transactions within a custom date range  
• Display total income, total expenses, and calculate net savings  
• View all transaction records in a readable tabular format  

3. Visualize Trends 📈  
• Plot income vs. expense over time using Matplotlib  
• Automatically resample and display daily totals  
• Helps users identify saving patterns and spending habits  

🗂️ File Structure  
• `main.py` - Core application logic and menu loop  
• `data_entry.py` - Input functions for date, amount, category, description  
• `finance_data.csv` - Persistent transaction storage  
• `README.md` - Project documentation  

✅ Technologies Used  
Python, Pandas, Matplotlib, CSV, Object-Oriented Programming (OOPs)  

🚀 How to Use  
1. Clone the repository:  
   `git clone https://github.com/RamyaUlaganathan/my-finance-hub.git`  
2. Install dependencies:  
   `pip install pandas matplotlib`  
3. Run the app:  
   `python main.py`  
4. Follow on-screen prompts to add/view transactions or visualize data  

✨ Highlights  
• CLI-based interface for simplicity and speed  
• Modular code using Python classes and functions  
• Persistent storage using lightweight CSV files  
• Clear visualization for better financial awareness  
• No external database or GUI required  
