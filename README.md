# Sleep Tracker

A modern web application built with Next.js that helps users track and analyze their sleep patterns.

![Sleep Tracker](public/sleep-tracker.png)

## Features

- 📊 Visual sleep data representation with charts
- 🔍 Track daily sleep duration and quality
- 📈 View average sleep statistics
- 🎯 Identify best and worst sleep patterns
- 👤 User authentication with Clerk
- 📱 Responsive design for all devices
- 🎨 Modern UI with Tailwind CSS
- 🔒 Secure data storage with PostgreSQL

## Tech Stack

- **Frontend**: Next.js 15, React 19, TailwindCSS 4
- **Backend**: Next.js API Routes, Prisma ORM
- **Database**: PostgreSQL
- **Authentication**: Clerk
- **Charts**: Chart.js with react-chartjs-2
- **TypeScript**: For type safety
- **Styling**: Tailwind CSS with gradient effects
- **Fonts**: Geist Sans and Geist Mono

## Getting Started

### Prerequisites

- Node.js (LTS version)
- PostgreSQL database
- Clerk account for authentication

### Environment Setup

Create a `.env` file in the root directory with:

```env
DATABASE_URL="your_postgresql_connection_string"
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your_clerk_publishable_key"
CLERK_SECRET_KEY="your_clerk_secret_key"
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/sleep-tracker.git
cd sleep-tracker
```

2. Install dependencies:
```bash
npm install
```

3. Set up the database:
```bash
npx prisma generate
npx prisma db push
```

4. Run the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:3000`

## Project Structure

```
├── app/                  # Next.js app directory
│   ├── actions/         # Server actions
│   ├── about/          # About page
│   ├── contact/        # Contact page
│   └── sign-in/        # Authentication pages
├── components/          # React components
├── lib/                 # Utility functions
├── prisma/             # Database schema and migrations
├── public/             # Static assets
└── types/              # TypeScript type definitions
```

## Features in Detail

### Sleep Tracking
- Record daily sleep duration
- Add sleep quality notes
- View historical sleep data

### Analytics
- Visual charts for sleep patterns
- Average sleep calculation
- Best/worst sleep identification

### User Management
- Secure authentication with Clerk
- Personal sleep history
- User profile management

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

- [Next.js](https://nextjs.org/)
- [Clerk](https://clerk.dev/)
- [Prisma](https://www.prisma.io/)
- [TailwindCSS](https://tailwindcss.com/)
- [Chart.js](https://www.chartjs.org/)

## Contact

Your Name - ](https://github.com/AbdullahGujjarr/)

Project Link: [https://github.com/AbdullahGujjarr/sleep-tracker]
