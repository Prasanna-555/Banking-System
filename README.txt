# 🏦 SecureBank - Complete Banking System

A modern, full-featured banking application built with React, TypeScript, and Tailwind CSS. This project demonstrates a complete banking system with user authentication, transaction management, admin controls, and more.

## 🌟 Features

### 🔐 Authentication & Security
- **User Registration & Login** with email/password
- **Session Management** with localStorage persistence
- **Role-based Access Control** (Admin/User)
- **Account Security** with freeze/unfreeze functionality
- **Password Management** with visibility toggles

### 💰 Banking Operations
- **Account Dashboard** with balance overview and quick stats
- **Deposit Funds** with transaction descriptions
- **Withdraw Money** with balance validation
- **Transfer Funds** to other users via email
- **Transaction History** with filtering and search
- **CSV Export** for transaction records

### 💳 Cards Management
- **Visual Card Display** for debit and credit cards
- **Card Details** with show/hide functionality
- **Card Controls** (block/unblock, settings, delete)
- **Copy Card Numbers** to clipboard
- **Request New Cards** with delivery tracking

### ⚙️ User Settings
- **Profile Management** (name, email, phone, address)
- **Security Settings** (2FA, login alerts, session timeout)
- **Notification Preferences** (email, SMS, push notifications)
- **Privacy Controls** (data export, account deletion)
- **Password Change** with current password verification

### 👨‍💼 Admin Features
- **Admin Dashboard** with system analytics and charts
- **User Management** (view, edit, freeze/unfreeze, delete users)
- **Transaction Monitoring** with detailed insights
- **System Reports** (transactions, users, financial, performance)
- **Export Capabilities** (CSV, PDF, Excel formats)

## 🚀 Live Demo

**Live Application**: [https://leafy-taiyaki-31ca70.netlify.app](https://leafy-taiyaki-31ca70.netlify.app)

### Demo Credentials

#### Admin Account
- **Email**: `admin@bank.com`
- **Password**: `password123`
- **Features**: Full admin access, user management, reports

#### Regular User Account
- **Email**: `john@example.com`
- **Password**: `password123`
- **Features**: Standard banking operations

## 🛠️ Tech Stack

- **Frontend**: React 18 + TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Build Tool**: Vite
- **Deployment**: Netlify
- **State Management**: React Context API
- **Data Persistence**: localStorage (demo purposes)

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd banking-system
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

## 🏗️ Project Structure

```
src/
├── components/
│   ├── Auth/
│   │   ├── LoginForm.tsx
│   │   └── RegisterForm.tsx
│   ├── Dashboard/
│   │   └── DashboardOverview.tsx
│   ├── Transactions/
│   │   ├── DepositForm.tsx
│   │   ├── WithdrawForm.tsx
│   │   ├── TransferForm.tsx
│   │   └── TransactionHistory.tsx
│   ├── Cards/
│   │   └── CardsManagement.tsx
│   ├── Settings/
│   │   └── UserSettings.tsx
│   ├── Admin/
│   │   ├── AdminDashboard.tsx
│   │   ├── UserManagement.tsx
│   │   └── Reports.tsx
│   └── Layout/
│       ├── Header.tsx
│       └── Sidebar.tsx
├── contexts/
│   └── AuthContext.tsx
├── types/
│   └── index.ts
└── App.tsx
```

## 💡 Key Features Explained

### Currency & Localization
- **Indian Rupees (₹)** as primary currency
- **Indian number formatting** (lakhs/crores)
- **Realistic Indian banking limits** and amounts

### Transaction Limits
- **Daily Withdrawal**: ₹4,00,000
- **ATM Withdrawal**: ₹40,000 per transaction
- **Daily Transfer**: ₹8,00,000
- **No fees** for first 5 withdrawals per month

### Security Features
- **Account Freeze** functionality for security
- **Login Alerts** for new device access
- **Session Timeout** for automatic logout
- **Two-Factor Authentication** ready (UI implemented)

### Admin Capabilities
- **User Management** with freeze/unfreeze controls
- **Transaction Monitoring** across all users
- **System Analytics** with charts and metrics
- **Report Generation** in multiple formats

## 🎨 Design Features

- **Modern UI/UX** with clean, professional design
- **Responsive Design** for all device sizes
- **Smooth Animations** and micro-interactions
- **Consistent Color Scheme** with blue/purple gradients
- **Apple-level Design Aesthetics** with attention to detail
- **Accessibility** considerations throughout

## 📊 Sample Data

The application includes realistic sample data:
- **Multiple user accounts** with varying balances
- **Transaction history** with different types
- **Credit/Debit cards** with realistic details
- **Admin analytics** with meaningful metrics

## 🔧 Configuration

### Environment Variables
Currently using mock data and localStorage. For production:
- Set up backend API endpoints
- Configure database connections
- Add environment variables for API keys

### Customization
- **Colors**: Modify Tailwind config for brand colors
- **Currency**: Update formatCurrency functions for different currencies
- **Limits**: Adjust transaction limits in respective components

## 🚀 Deployment

### Netlify (Current)
The app is deployed on Netlify with automatic builds from the main branch.

### Other Platforms
Can be deployed to:
- **Vercel**: Zero-config deployment
- **GitHub Pages**: Static hosting
- **AWS S3**: With CloudFront distribution
- **Firebase Hosting**: Google's hosting solution

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **React Team** for the amazing framework
- **Tailwind CSS** for the utility-first CSS framework
- **Lucide** for the beautiful icon set
- **Vite** for the fast build tool

## 📞 Support

For support, email support@securebank.com or create an issue in the repository.

---

**Built with ❤️ using React, TypeScript, and Tailwind CSS**