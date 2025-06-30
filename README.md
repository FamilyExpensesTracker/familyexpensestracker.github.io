# 🏠 Family Expense Tracker - Live Application

[![Live Demo](https://img.shields.io/badge/Live%20Demo-familyexpensestracker.github.io-blue?style=for-the-badge)](https://familyexpensestracker.github.io/)
[![MIT License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Development Repo](https://img.shields.io/badge/Development-GitHub-black?style=for-the-badge)](https://github.com/FamilyExpensesTracker/FamilyExpensesTracker)

> **🌐 Live deployment of the Family Expense Tracker web application**

This repository contains the deployed static content for the [Family Expense Tracker](https://github.com/FamilyExpensesTracker/FamilyExpensesTracker) - a modern, multilingual family expense tracking web application that runs entirely in your browser with **100% local data storage**.

## 🚀 Quick Start

**[🔗 Start Tracking Your Expenses Now](https://familyexpensestracker.github.io/)**

No installation, registration, or setup required - just click and start tracking!

## 🔒 Privacy First - Your Data is Safe

- **🏠 100% Local Storage**: All data stays in your browser only
- **🚫 No Server Communication**: Zero data transmission to external servers  
- **🔐 No Account Required**: No registration, login, or personal information needed
- **💾 You Control Your Data**: Export/import functionality for backup and portability

⚠️ **Important**: Since data is stored locally, regular exports are recommended to prevent loss!

## ✨ Key Features

### 🌍 **Multilingual Support**
- **English** 🇺🇸, **French** 🇫🇷, **Japanese** 🇯🇵
- Auto-detection based on browser language

### 💱 **Multi-Currency Support**  
- **USD** ($), **EUR** (€), **JPY** (¥)
- Smart formatting based on selected currency

### 📊 **Advanced Dashboard**
- **Custom Date Range Analysis**: Flexible period selection for detailed insights
- **Interactive Charts**: Category breakdown, spending trends, family member analysis
- **Real-time Statistics**: Monthly, yearly, and average spending metrics
- **Independent Controls**: Each chart has its own date range filters

### 🔐 **Secure Data Management**
- **Encrypted Exports**: Optional password-based AES-256 encryption
- **Cross-app Compatibility**: Import data from other expense tracking apps
- **Smart Validation**: Prevents data corruption and duplicate imports

### 🎨 **Modern User Experience**
- **Responsive Design**: Works perfectly on all devices
- **Glassmorphism UI**: Modern frosted glass aesthetic  
- **Smooth Animations**: Professional hover effects and transitions
- **Accessibility**: Proper contrast and keyboard navigation

## 📱 How to Use

### 1. **Add Expenses**
- Fill in amount, description, category, date, and family member
- Choose from 11 predefined categories (🍕 Food, 🚗 Transport, etc.)
- Data saves automatically

### 2. **View Dashboard**  
- See spending statistics and interactive charts
- Use period selectors (7D, 30D, 3M, 6M, 1Y, All, Custom)
- Each chart can be filtered independently

### 3. **Manage History**
- View all expenses with powerful filtering options
- Sort by date or amount (ascending/descending)
- Delete expenses with confirmation dialogs

### 4. **Export/Import Data**
- **Export**: Choose plain text or encrypted (password-protected)
- **Import**: Supports both encrypted and plain JSON files
- **Backup**: Regular exports recommended for data safety

## 🛠️ Technical Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic markup and structure |
| **CSS3** | Modern styling with glassmorphism effects |
| **Vanilla JavaScript ES6+** | Core functionality without frameworks |
| **Chart.js** | Interactive data visualizations |
| **Local Storage API** | Client-side data persistence |
| **Web Crypto API** | Secure encryption for data exports |

## 🌐 Browser Support

| Browser | Minimum Version | Status |
|---------|----------------|--------|
| **Chrome** | 60+ | ✅ Fully Supported |
| **Firefox** | 55+ | ✅ Fully Supported |
| **Safari** | 12+ | ✅ Fully Supported |
| **Edge** | 79+ | ✅ Fully Supported |
| **Mobile** | Modern browsers | ✅ Fully Responsive |

## 📊 Data Format

The application uses structured JSON for data storage and export:

```json
{
  "expenses": [
    {
      "id": "1640995200000",
      "amount": 25.50,
      "description": "Grocery shopping",
      "category": "Food",
      "date": "2023-12-31",
      "paidBy": "John",
      "timestamp": "2023-12-31T18:00:00.000Z"
    }
  ],
  "language": "en",
  "currency": "USD",
  "exportDate": "2023-12-31T18:00:00.000Z",
  "version": "1.0"
}
```

## 🗂️ Available Categories

- 🍕 **Food** - Restaurants, groceries, takeout
- 🚗 **Transportation** - Gas, public transport, rideshare  
- 🛍️ **Shopping** - Clothing, electronics, purchases
- 🎬 **Entertainment** - Movies, games, subscriptions
- 💡 **Utilities** - Bills, electricity, water, internet
- 🏥 **Healthcare** - Medical expenses, pharmacy
- 📚 **Education** - Books, courses, tuition
- ✈️ **Travel** - Flights, hotels, vacation
- 💅 **Personal Care** - Haircuts, cosmetics, spa
- 🏡 **Housing** - Rent, maintenance, furniture
- 📦 **Other** - Miscellaneous expenses

## 🔗 Repository Links

- **🌐 Live Application**: [familyexpensestracker.github.io](https://familyexpensestracker.github.io/)
- **💻 Development Repository**: [FamilyExpensesTracker/FamilyExpensesTracker](https://github.com/FamilyExpensesTracker/FamilyExpensesTracker)
- **🐛 Issues & Feature Requests**: [GitHub Issues](https://github.com/FamilyExpensesTracker/FamilyExpensesTracker/issues)

## 🤝 Contributing

This repository contains the **deployed static files**. For development contributions:

1. **Fork** the [main development repository](https://github.com/FamilyExpensesTracker/FamilyExpensesTracker)
2. **Create** a feature branch
3. **Submit** a pull request to the main repo
4. **Deployments** to this repository happen automatically

## 💡 Troubleshooting

### Common Issues

| Issue | Solution |
|-------|----------|
| **Charts not loading** | Refresh page, check JavaScript is enabled |
| **Data not saving** | Ensure not in private/incognito mode |
| **Import/export issues** | Verify JSON format, check file permissions |

### Getting Help

- 📖 **Documentation**: [Main Repository README](https://github.com/FamilyExpensesTracker/FamilyExpensesTracker#readme)
- 🐛 **Bug Reports**: [GitHub Issues](https://github.com/FamilyExpensesTracker/FamilyExpensesTracker/issues)
- 💬 **Feature Requests**: [GitHub Discussions](https://github.com/FamilyExpensesTracker/FamilyExpensesTracker/discussions)

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 🌟 Support the Project

If you find this application useful:

- ⭐ **Star** the [main repository](https://github.com/FamilyExpensesTracker/FamilyExpensesTracker)
- 🐛 **Report issues** to help improve the app
- 💡 **Suggest features** for future updates
- 🤝 **Share** with friends and family

## 👨‍💻 Credits

**Author**: [Mounir IDRASSI](https://github.com/idrassi)  
**Created**: June 2025  
**License**: MIT

### Acknowledgments
- **Chart.js** for beautiful data visualizations
- **Flag Icons CSS** for country flag icons  
- **Open-source community** for inspiration and feedback

---

**🏠 Start tracking your family expenses today!**  
**[familyexpensestracker.github.io](https://familyexpensestracker.github.io/)**

*Made with ❤️ for families everywhere!*
