# 💸 Expense Tracker

> A premium, modern personal finance application designed to help you track expenses, manage budgets, monitor savings and understand your financial habits.

<p align="center">
  <strong>Take control of your money.</strong><br/>
  Track. Analyze. Save. Grow.
</p>

---

## ✨ About

Expense Tracker is a modern, full-stack personal finance application built with a premium dark-themed interface, smooth animations and a Firebase-powered backend.

It helps users manage their finances in one place through transaction tracking, budgeting, savings goals, financial analytics and smart spending insights.

Designed with a minimal fintech aesthetic, the application focuses on simplicity, performance, security and a smooth user experience across desktop and mobile devices.

---

## 🚀 Features

### 📊 Financial Dashboard
- Total balance overview
- Monthly income and expenses
- Savings overview
- Spending trends
- Recent transactions
- Budget overview
- Financial summaries

### 💳 Transaction Management
- Add income and expenses
- Edit and delete transactions
- Transaction categories
- Search and filtering
- Date-based transaction history
- Transaction notes
- Merchant information
- Tags

### 📈 Analytics
- Income vs expenses
- Spending breakdown by category
- Monthly spending trends
- Daily expense analysis
- Savings analysis
- Previous month comparisons

### 🎯 Budget Management
- Monthly budgets
- Category-based budgets
- Spending progress
- Budget warnings
- Remaining budget tracking

### 💰 Savings Goals
- Create savings goals
- Set target amounts
- Track contributions
- Progress tracking
- Goal milestones

### 🏦 Account Management
- Multiple accounts
- Cash accounts
- Bank accounts
- Savings accounts
- Credit cards
- Account balance tracking

### 🔄 Recurring Transactions
- Recurring expenses
- Recurring income
- Monthly subscriptions
- Bills and payments

### 🧠 Smart Financial Insights
- Spending pattern analysis
- Monthly comparisons
- Spending suggestions
- Unusual expense detection
- Financial summaries

### 📅 Financial Calendar
- Income dates
- Expense dates
- Upcoming bills
- Recurring payments
- Budget deadlines

### 📸 Receipt Management
- Receipt uploads
- Receipt attachment to transactions
- Receipt history
- OCR-based extraction where configured

### 🔐 Privacy & Security
- Firebase Authentication
- Secure user-specific data
- Firestore security rules
- Privacy mode
- Data export

---

## 🎨 Design

The application follows a premium minimal fintech design language.

- Dark-themed UI
- Minimal typography
- Subtle blue gradients
- Clean financial cards
- Smooth animations
- Responsive layouts
- Premium microinteractions
- Modern mobile-first design

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React | Frontend |
| TypeScript | Type safety |
| Tailwind CSS | Styling |
| Framer Motion | Animations |
| Firebase Authentication | Authentication |
| Cloud Firestore | Database |
| Firebase Storage | File storage |
| Recharts | Charts and analytics |
| Lucide | Icons |
| Vite | Development and build tooling |

---

## 🏗️ Architecture

```text
Expense Tracker
│
├── Frontend
│   ├── React
│   ├── TypeScript
│   ├── Tailwind CSS
│   └── Framer Motion
│
├── Firebase
│   ├── Authentication
│   ├── Cloud Firestore
│   ├── Security Rules
│   └── Storage
│
└── Analytics
    └── Recharts
```

---

## 📂 Project Structure

```text
expense-tracker/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── services/
│   ├── context/
│   ├── types/
│   ├── lib/
│   ├── styles/
│   ├── App.tsx
│   └── main.tsx
├── firestore.rules
├── firestore.indexes.json
├── firebase.json
├── .env.example
├── .gitignore
├── package.json
└── README.md
```

---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/expense-tracker.git
```

### 2. Navigate to the project

```bash
cd expense-tracker
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure Firebase

Create a Firebase project through the Firebase Console.

Enable:

- Firebase Authentication
- Cloud Firestore
- Firebase Storage (optional)

Configure the appropriate authentication providers.

### 5. Configure environment variables

Create a `.env` file in the project root.

```env
VITE_FIREBASE_API_KEY=
VITE_FIREBASE_AUTH_DOMAIN=
VITE_FIREBASE_PROJECT_ID=
VITE_FIREBASE_STORAGE_BUCKET=
VITE_FIREBASE_MESSAGING_SENDER_ID=
VITE_FIREBASE_APP_ID=
```

Fill in the values from your Firebase project settings.

Never commit private service account keys or server-side secrets.

### 6. Start the development server

```bash
npm run dev
```

### 7. Build for production

```bash
npm run build
```

---

## 🔒 Security

The application uses Firebase for authentication and database services.

Security practices:

- Firebase Authentication
- Firestore Security Rules
- User-specific data access
- Secure Storage rules
- Input validation
- Protected application routes

Users should only be able to access their own private financial data.

---

## 📱 Responsive Design

Designed to work across:

- Desktop
- Laptop
- Tablet
- Mobile

The mobile experience includes a responsive navigation system and mobile-friendly transaction management.

---

## 🗺️ Roadmap

- [ ] Smart financial insights
- [ ] Subscription tracking
- [ ] Receipt scanning
- [ ] Safe-to-spend calculator
- [ ] Financial calendar
- [ ] Savings challenges
- [ ] AI-powered transaction categorization
- [ ] Financial forecasting
- [ ] Shared expense tracking
- [ ] Monthly financial reports
- [ ] Advanced privacy mode

---

## 🤝 Contributing

Contributions, ideas and feedback are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Commit your changes.
5. Open a Pull Request.

---

## ⚠️ Disclaimer

This application is designed for personal financial tracking and educational purposes.

Financial insights and projections are estimates based on recorded data and should not be considered professional financial advice.

---

## 📄 License

No license has been added yet.

---

<p align="center">
  <strong>Made to make money management simpler. 💚</strong>
</p>
