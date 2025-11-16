<!-- @format -->

# Admin Food Management CRM

A comprehensive admin dashboard for managing restaurant food delivery operations, built with Next.js 15 and modern web technologies.

## 📋 Overview

Admin Food Management CRM is a powerful customer relationship management system designed specifically for food delivery businesses. It provides administrators with complete control over restaurants, customers, riders, orders, payments, and food categories through an intuitive and responsive interface.

## ✨ Features

### Dashboard & Analytics

- **Real-time Analytics**: Monitor key performance metrics including total orders, revenue, active restaurants, and customer base
- **Income & Orders Charts**: Visualize business trends with interactive charts powered by Recharts
- **Top Performers**: Track top-selling items and highest-performing restaurants

### Core Management Modules

- **Restaurant Management**: Comprehensive restaurant profile management with detailed information tracking
- **Customer Management**: View and manage customer accounts, profiles, and activity history
- **Rider Management**: Oversee delivery personnel with assignment tracking and performance metrics
- **Order Management**: Real-time order tracking, status updates, and delivery assignment
- **Food Categories**: Organize and manage food categories with custom images and metadata
- **Payment Processing**: Handle transactions, view payment history, and manage financial records
- **Withdrawal Requests**: Process and approve restaurant withdrawal requests

### Settings & Configuration

- **Personal Information**: Admin profile management
- **Restaurant Information**: Configure restaurant-specific settings
- **FAQs Management**: Create and manage frequently asked questions
- **Help & Support**: Customer support ticket management
- **Privacy Policy & Terms**: Update legal documentation
- **Password Management**: Secure password change functionality

### Authentication

- **Secure Sign-In**: Protected authentication system
- **Password Recovery**: Forget password flow with email verification
- **OTP Verification**: Two-factor authentication support
- **Password Reset**: Secure password reset functionality

## 🛠 Tech Stack

- **Framework**: [Next.js 15.5.3](https://nextjs.org/) with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS 4.0
- **UI Components**:
  - Radix UI primitives
  - Custom component library with shadcn/ui
  - Lucide React icons
- **Charts**: Recharts for data visualization
- **Animations**: Motion (Framer Motion)
- **State Management**: React 19.1.0
- **Notifications**: React Hot Toast

## 📦 Installation

### Prerequisites

- Node.js 20.x or higher
- npm, yarn, pnpm, or bun package manager

### Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/rahul3507/Admin-Food-Management-CRM.git
   cd Admin-Food-Management-CRM
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   # or
   bun install
   ```

3. **Run the development server**

   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```

4. **Open your browser**

   Navigate to [http://localhost:3000](http://localhost:3000) to see the application.

## 🚀 Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the application for production
- `npm run start` - Start the production server
- `npm run lint` - Run ESLint for code quality checks

## 📁 Project Structure

```
admin_food_management_crm/
├── src/
│   ├── app/                      # Next.js App Router
│   │   ├── (auth)/              # Authentication routes
│   │   ├── customer/            # Customer management
│   │   ├── food-categories/     # Food category management
│   │   ├── orders/              # Order management
│   │   ├── payment/             # Payment processing
│   │   ├── restaurant/          # Restaurant management
│   │   ├── rider/               # Rider management
│   │   ├── settings/            # Settings & configuration
│   │   └── widthdraw-request/   # Withdrawal management
│   ├── components/              # React components
│   │   ├── authentication/      # Auth-related components
│   │   ├── common/              # Shared components
│   │   ├── dashboard/           # Dashboard widgets
│   │   ├── ui/                  # Base UI components
│   │   └── [module]/            # Module-specific components
│   ├── data/                    # Mock data & constants
│   ├── hooks/                   # Custom React hooks
│   ├── lib/                     # Utility functions
│   └── types/                   # TypeScript type definitions
├── public/                       # Static assets
│   ├── dashboardLogo/
│   ├── foodCategoriesImages/
│   └── promotion/
└── [config files]               # Configuration files
```

## 🎨 UI Components

The project utilizes a comprehensive set of reusable UI components built with Radix UI and Tailwind CSS:

- **Forms**: Input, Label, Checkbox, Select, Switch
- **Overlays**: Dialog, Tooltip, Modal
- **Layout**: Card, Separator, Scroll Area, Collapsible
- **Navigation**: Tabs, Pagination
- **Feedback**: Loader, Progress, Toast notifications
- **Data Display**: Custom Tables, Cards, Charts

## 🔐 Authentication Flow

1. **Sign In** - Secure login with credentials
2. **Forget Password** - Email-based password recovery
3. **OTP Verification** - Verify identity with one-time password
4. **Reset Password** - Set new password securely

## 📊 Key Features Breakdown

### Dashboard Analytics

- Total orders tracking
- Revenue monitoring
- Active restaurant count
- Customer base metrics
- Performance trend visualization

### Order Management

- View all orders with filtering
- Update order status
- Assign riders to deliveries
- Track delivery progress
- View detailed order information

### Payment Management

- Transaction history
- Payment status tracking
- Revenue reports
- Withdrawal request processing

## 🌐 Deployment

### Deploy on Vercel

The easiest way to deploy this Next.js application is using the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme):

1. Push your code to a Git repository (GitHub, GitLab, or Bitbucket)
2. Import your repository to Vercel
3. Vercel will automatically detect Next.js and configure the build settings
4. Deploy with a single click

For detailed deployment instructions, refer to the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying).

### Other Deployment Options

- **Docker**: Containerize the application for deployment on any cloud platform
- **Node.js Server**: Deploy to any Node.js hosting provider
- **Static Export**: Export to static HTML for edge networks (if applicable)

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is private and proprietary.

## 📧 Contact

For questions or support, please contact the development team.

## 🙏 Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- UI components from [Radix UI](https://www.radix-ui.com/)
- Icons from [Lucide React](https://lucide.dev/)
- Charts powered by [Recharts](https://recharts.org/)

---

**Note**: This is an admin dashboard application. Ensure proper authentication and authorization are implemented before deploying to production.
