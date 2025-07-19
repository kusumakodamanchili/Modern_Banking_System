# 🏦 Modern Banking System

A comprehensive banking application built entirely with HTML, CSS, and JavaScript that provides all basic banking operations including account creation, transactions, and account management.

## Features

### 🆕 Account Management

- **Create New Account**: Register with personal details and initial deposit
- **Secure Login**: Email and password authentication
- **Profile Management**: Update contact information

### 💰 Banking Operations

- **Check Balance**: View current account balance
- **Deposit Money**: Add funds to your account
- **Withdraw Money**: Remove funds from your account
- **Transfer Money**: Send money to other accounts
- **Transaction History**: View detailed transaction records

### 🔒 Data Persistence

- **Local Storage**: All data is saved in your browser's local storage
- **No Server Required**: Works completely offline
- **Data Persistence**: Your accounts and transactions are saved between sessions

## 🚀 Quick Start

### Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No server or installation required!

### How to Run

1. **Open the file**

   - Simply double-click on `bank.html`
   - Or open it in your web browser
   - The banking system will be ready to use!

2. **Alternative method**
   - Right-click on `bank.html`
   - Select "Open with" → Choose your preferred browser

## 📋 Sample Accounts

The system comes with two pre-configured sample accounts for testing:

| Account Number | Name       | Email            | Password    | Balance |
| -------------- | ---------- | ---------------- | ----------- | ------- |
| 1001           | John Doe   | john@example.com | password123 | ₹50,000 |
| 1002           | Jane Smith | jane@example.com | password123 | ₹75,000 |

## 🛠️ How to Use

### Creating a New Account

1. Click "Create New Account" on the welcome screen
2. Fill in all required fields:
   - Full Name
   - Email Address
   - Phone Number
   - Password (and confirmation)
   - Initial Deposit (minimum ₹1,000)
3. Click "Create Account"
4. **Save your assigned account number** - it will be displayed after successful creation
5. Use your email and password to login

### Logging In

1. Click "Login to Existing Account"
2. Enter your email address and password
3. Click "Login"

### Performing Banking Operations

1. **Check Balance**: Select "Check Balance" from the menu
2. **Deposit**: Select "Deposit Money" and enter the amount
3. **Withdraw**: Select "Withdraw Money" and enter the amount
4. **Transfer**: Select "Transfer Money", enter recipient account number and amount
5. **View Transactions**: Select "Transaction History" to see your recent transactions
6. **Update Profile**: Select "Update Profile" to change contact information

## 💾 Data Storage

The application uses your browser's **localStorage** to save all data:

- **Accounts**: All account information is stored locally
- **Transactions**: Complete transaction history is preserved
- **Security**: Data is stored only on your device
- **Privacy**: No data is sent to any external servers

### Important Notes:

- Data is stored only in your current browser
- Clearing browser data will delete all accounts and transactions
- Data is not shared between different browsers or devices
- This is a demonstration system - do not use for real financial transactions

## 🎨 User Interface

### Modern Design

- **Responsive Layout**: Works perfectly on desktop and mobile
- **Beautiful Gradients**: Modern color schemes and animations
- **Intuitive Navigation**: Easy-to-use interface
- **Real-time Updates**: Balance and transaction updates instantly

### Features

- **Welcome Screen**: Choose between login and account creation
- **Dashboard**: Overview of account balance and operations
- **Transaction History**: Detailed view of all transactions
- **Profile Management**: Update personal information
- **Error Handling**: Clear error messages and validation

## 🔧 Technical Details

### Frontend Technologies

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with gradients, animations, and responsive design
- **JavaScript**: Client-side logic and data management
- **LocalStorage API**: Browser-based data persistence

### Key Features

- **No Dependencies**: Pure HTML, CSS, and JavaScript
- **Cross-browser Compatible**: Works on all modern browsers
- **Offline Capable**: No internet connection required
- **Mobile Responsive**: Optimized for all screen sizes

## 🛡️ Security Considerations

- **Client-side Only**: All data is stored locally in your browser
- **No External Servers**: No data is transmitted to external services
- **Password Protection**: Basic password authentication for accounts
- **Input Validation**: Form validation and error handling

**Note**: This is a demonstration system for educational purposes. For real banking, always use official banking services with proper security measures.

## 📱 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🐛 Troubleshooting

### Common Issues

1. **Data not saving**

   - Ensure cookies and localStorage are enabled in your browser
   - Check if you're in private/incognito mode (data won't persist)

2. **Page not loading**

   - Try opening the file directly in your browser
   - Check if JavaScript is enabled

3. **Styling issues**
   - Try refreshing the page
   - Clear browser cache if needed

### Data Management

- **Clear All Data**: Clear your browser's localStorage to reset the system
- **Export Data**: Currently not available (future feature)
- **Backup**: Data is stored locally, so regular browser backups will include it

## 🔄 Future Enhancements

Potential features for future versions:

- Data export/import functionality
- Multiple currency support
- Account statements and reports
- ATM card management
- Loan applications
- Interest calculations
- Admin panel for bank management
- Data backup and restore

## 📄 License

This project is for educational purposes. Feel free to modify and extend it for your learning needs.

## 🤝 Contributing

Feel free to submit issues, feature requests, or suggestions to improve this banking system.

---

**Important**: This is a demonstration banking system and should not be used for real financial transactions. Always use official banking services for actual financial operations.
