🍽️ Restaurant Management System 🍽️
GUI-based Python application using Tkinter for restaurant billing, menu display, order calculation, and integrated calculator. Handles food items like drinks, burgers, pizzas with dynamic pricing, taxes, and service charges.
​

✨ Features
📱 Intuitive Tkinter interface with colorful frames for menu, inputs, and totals

🧮 Built-in calculator for precise computations (add, subtract, multiply, divide)

💰 Automatic cost breakdown: per-item pricing, 20% service charge, 3% tax, subtotals

📝 Real-time order number generation and reset functionality

⏰ Live clock display and text input area for notes

🎨 Styled labels with bold fonts and vibrant colors (ED420B orange, 33A9CE blue)
​

🚀 Quick Start
Ensure Python 3.x with Tkinter installed (standard in most distributions)

Save code as Restaurant-Management.py

Run: python Restaurant-Management.py

Enter quantities in fields, click "Total" for bill, use calculator as needed
​

📁 Code Structure
text
Restaurant-Management.py  # Single-file app (~15k chars)
├── Price list window (separate Tk window)
├── Main window: 
│   ├── Food input frame (8 items: Drink ₹10, Burger King ₹30, etc.)
│   ├── Payment display (cost, service, tax, total)
│   ├── Buttons: Price, Total, Reset, Quit
│   ├── Calculator grid (0-9, ±×÷, C, =)
│   └── Clock & text area
└── No external files needed
Items include Drink(10), Burger King(30), Cherry(15), Nacho Fries(20), Pizza(30), Biscuits(10), Roll(10), Tea(15).
​

🎮 How It Works
Enter quantities (e.g., 2 for Burger King), hit "Total": computes p1=qty*price, sums costs, adds service(20%), tax(3%). Displays order number (random 1-10000). Reset clears all. Calculator handles math independently.
​

text
Sample Bill:
Cost: ₹100
Service: ₹20
Tax: ₹3
Subtotal: ₹123
Total: ₹123
Order #4567
👨‍💻 Developed By
text
   _____ _          _    ____  _                 
  / ____| |__   ___| | _|  _ \(_) ___  ___ _ __  
 | |    | '_ \ / __| |/ / | | | |/ _ \/ _ \ '_ \ 
 | |____| | | | (__|   <| |_| | |  __/  __/ | | |
  \_____|_| |_|\___|_|\_\____/|_|\___|\___|_| |_|
                                                
     🚀 Crafted with Passion by Ritik Sharma 🚀
     Jammu, India | CSE Undergraduate | 2026
     GitHub: @ERRROR22 | Email: ritiksharma4451@gmail.com
Epic ASCII flair for the coding chef! 🌟 [file:21]

⚙️ Customization Tips
Edit price1 to price8 variables for new rates

Update item labels/names in Label creations

Add messagebox for confirmations or save totals to file [file:21]

Launch and Bill Away! 🚀🍔 [file:21]
📄 License
MIT License - Free to use, modify, and distribute. []

🤝 Contributing
Fork the repo, add features like GUI (Tkinter/PyQt), database (SQLite), or inventory tracking. Pull requests welcome! []

Happy Managing! 🍕🔥
