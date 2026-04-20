# SmartBudget

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Overview
SmartBudget is a modern, user-friendly personal finance manager designed to help you track your expenses, create budgets, and visualize your spending habits through beautiful charts. Whether you’re saving for a vacation or managing monthly bills, SmartBudget offers seamless control and insights.

## Features
- Add, edit, and categorize expenses and income
- Create custom budgets and set spending limits
- Visualize data with interactive charts and graphs
- Monthly and yearly financial summaries
- Export data as CSV
- Responsive design for desktop and mobile

## Tech Stack
- Frontend: React.js
- State Management: Redux
- Backend: Node.js with Express
- Database: MongoDB
- Authentication: JWT
- Charting: Chart.js

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/arlethhand/SmartBudget.git
   ```
2. Navigate to the project directory:
   ```
   cd SmartBudget
   ```
3. Install dependencies for frontend and backend:
   ```
   cd client && npm install
   cd ../server && npm install
   ```
4. Configure environment variables for the backend (.env):
   ```
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```
5. Run the development servers:
   ```
   # Backend
   cd server
   npm run dev

   # Frontend
   cd ../client
   npm start
   ```

## Usage
1. Register a new account or login using existing credentials.
2. Start adding your income and expenses by category.
3. Set monthly budgets and monitor spending limits.
4. View charts from the dashboard to understand your financial patterns.
5. Export your data anytime for offline use.

## Screenshots
![Dashboard Placeholder](https://via.placeholder.com/800x400?text=Dashboard+Screenshot)

![Budget Setup Placeholder](https://via.placeholder.com/800x400?text=Budget+Setup+Screenshot)

## Contributing
Contributions are warmly welcome! To contribute:
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

Please ensure your code follows the existing style and includes appropriate tests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ by [arlethhand](https://github.com/arlethhand)
