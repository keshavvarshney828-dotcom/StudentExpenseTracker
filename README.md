# 🎓 Student Expense Tracker

A simple and user-friendly iOS application built using **Swift and SwiftUI** to help students manage their daily expenses, monitor monthly spending, and stay within their budget.

## 📱 About the Project

The Student Expense Tracker is a B.Tech iOS App Development project designed to make expense management easier for students. Users can record expenses, categorize transactions, set a monthly budget, and view their expense history.

## ✨ Features

- **Dashboard:** View monthly spending, total budget, and remaining balance.
- **Add Expenses:** Record expense name, amount, category, and date.
- **Expense Categories:** Organize expenses into Food, Travel, Books, Shopping, Fees, and Other.
- **Expense History:** View all recorded transactions.
- **Delete Expenses:** Remove transactions that are no longer needed.
- **Monthly Budget:** Set and update your monthly spending limit.
- **Local Storage:** Save expenses and budget on the device using `UserDefaults`.
- **Indian Currency:** Display expense amounts in Indian Rupees (₹).
- **Offline Support:** Access and manage expenses without an internet connection.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Swift | Programming language |
| SwiftUI | User interface development |
| Xcode | Development environment |
| UserDefaults | Local data persistence |
| Codable | Encoding and decoding expense data |
| Foundation | Date handling and data management |

## 📋 Requirements

- macOS with Xcode installed
- iOS 17.0 or later deployment target
- Basic knowledge of Swift and SwiftUI
- iPhone simulator or a compatible iPhone for testing

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/keshavvarshney828/StudentExpenseTracker.git
```

### 2. Open the Project

Open the `.xcodeproj` file in Xcode. If your project uses an `.xcworkspace`, open that instead.

### 3. Configure the Project

- Select the `StudentExpenseTracker` scheme.
- Choose an iPhone simulator.
- Ensure the deployment target is iOS 17.0 or later.
- Check that the app entry point is defined only once.

### 4. Run the App

Click the **Run ▶** button in Xcode to build and launch the application.

## 📂 Project Structure

```text
StudentExpenseTracker/
├── StudentExpenseTrackerApp.swift
├── ContentView.swift
├── Assets.xcassets/
└── README.md
```

*Note: The structure above represents the basic single-file implementation. You can split the code into separate model, view, and data-manager files as the project grows.*

## 📖 How to Use

1. Launch the application.
2. View your monthly spending on the dashboard.
3. Select **Set Monthly Budget** to configure your budget.
4. Tap **Add New Expense**.
5. Enter the expense name and amount.
6. Select a category and date.
7. Tap **Save Expense**.
8. Open the History tab to view or delete transactions.

## 💾 Data Storage

The app uses `UserDefaults` to store the monthly budget and JSON-encoded expense records locally on the device.

**Note:** Data is stored locally and is not synchronized between devices. Uninstalling the app may remove its locally stored data.

## 🔮 Future Improvements

- [ ] Expense charts and visual analytics
- [ ] Weekly and yearly spending reports
- [ ] Search and filter transactions
- [ ] Edit existing expenses
- [ ] Export reports to CSV or PDF
- [ ] Expense reminders and notifications
- [ ] Recurring expenses
- [ ] Face ID or passcode protection
- [ ] Cloud synchronization

## 🎯 Learning Outcomes

This project demonstrates practical use of:

- Swift and SwiftUI fundamentals
- State management in SwiftUI
- Data models and structures
- Forms, lists, and navigation
- Local data persistence
- Date-based filtering and calculations
- Basic application architecture

## 👨‍🎓 Academic Project

**Project Name:** Student Expense Tracker  
**Domain:** iOS App Development  
**Platform:** Apple iOS  
**Language:** Swift  
**Framework:** SwiftUI  
**Project Type:** B.Tech Lab Project




If you find this project useful, consider giving the repository a ⭐ on GitHub!
