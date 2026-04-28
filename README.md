# Bank Loan Application System (Multi-Role)

A comprehensive Angular 21 application for managing bank loan applications with support for multiple user roles: Customer, Loan Officer, and Admin.

## Features

- **Customer Role**: Submit loan applications, track application status, and view loan details
- **Loan Officer Role**: Review applications, approve/reject applications, and manage customer requests
- **Admin Role**: Manage users, view all applications, generate reports, and system configuration

## Quick Start

### Prerequisites
- Node.js 18+ and npm 9+
- Angular CLI 21+

### Installation

```bash
# Clone the repository
git clone https://github.com/madhurakhade312/bank-loan-application-system.git
cd bank-loan-application-system

# Install dependencies
npm install

# Start development server
npm start
```

Navigate to `http://localhost:4200/` in your browser.

### Build for Production

```bash
npm run build
```

## Project Structure

```
src/
├── app/
│   ├── models/
│   │   ├── user.model.ts
│   │   └── loan.model.ts
│   ├── services/
│   │   ├── auth.service.ts
│   │   ├── loan.service.ts
│   │   └── user.service.ts
│   ├── guards/
│   │   └── role.guard.ts
│   ├── components/
│   │   └── navbar/
│   ├── modules/
│   │   ├── customer/
│   │   ├── loan-officer/
│   │   └── admin/
│   ├── app.config.ts
│   ├── app.routes.ts
│   └── app.component.ts
├── styles.scss
└── index.html
```

## User Roles

### Customer
- Apply for new loan
- View application status
- Track loan progress
- View loan details

### Loan Officer
- View pending applications
- Approve/Reject applications
- Add comments and recommendations
- Manage customer requests

### Admin
- Manage user accounts
- View all applications
- Generate reports
- System configuration

## Technology Stack

- **Framework**: Angular 21
- **Language**: TypeScript 5.6+
- **Styling**: SCSS
- **State Management**: RxJS
- **Build Tool**: Angular CLI
- **Testing**: Jasmine & Karma

## Default Test Credentials

### Customer
- Username: `customer1`
- Password: `password123`

### Loan Officer
- Username: `officer1`
- Password: `password123`

### Admin
- Username: `admin1`
- Password: `password123`

## API Integration

Update the API base URLs in the service files:

- `src/app/services/auth.service.ts` - Authentication endpoints
- `src/app/services/loan.service.ts` - Loan management endpoints
- `src/app/services/user.service.ts` - User management endpoints

## Development Server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Running Tests

Run `ng test` to execute the unit tests via Karma.

## Running Linter

Run `ng lint` to lint your app.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support, email support@bankloan.com or open an issue on GitHub.
