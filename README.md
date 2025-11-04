# Cryptocurrency Price Quoter

A modern React application built with TypeScript and Vite that allows users to quote cryptocurrency prices in real-time against various fiat currencies.

## Features

- **Real-time Price Quotes**: Get current cryptocurrency prices with live data from CryptoCompare API
- **Multiple Currency Support**: Quote cryptocurrencies against USD and other major fiat currencies
- **Comprehensive Price Information**: View current price, daily high/low, 24-hour change percentage, and last update time
- **Responsive Design**: Clean, modern UI with a beautiful background and semi-transparent content areas
- **Type-Safe**: Built with TypeScript for enhanced developer experience and runtime safety
- **Form Validation**: Client-side validation with error messages for required fields

## Technologies Used

- **React 18** - Modern React with hooks and functional components
- **TypeScript** - Type-safe JavaScript for better development experience
- **Vite** - Fast build tool and development server
- **Zustand** - Lightweight state management
- **Zod** - Schema validation for API responses
- **Axios** - HTTP client for API requests
- **CSS3** - Custom styling with modern CSS features

## Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd cripto-react-typescript
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## Project Structure

```
src/
├── components/
│   ├── CriptoSearchForm.tsx    # Currency and cryptocurrency selection form
│   ├── CryptoPriceDisplay.tsx  # Price display component
│   ├── ErrorMessage.tsx        # Error message component
│   └── Spinner.tsx             # Loading spinner component
├── data/
│   └── index.ts                # Currency data
├── schema/
│   └── cripto-schema.ts        # Zod validation schemas
├── services/
│   └── CryptoService.ts        # API service functions
├── types/
│   └── index.ts                # TypeScript type definitions
├── store.ts                    # Zustand state management
├── App.tsx                     # Main application component
├── index.css                   # Global styles
└── main.tsx                    # Application entry point
```

## API Usage

The application uses the CryptoCompare API to fetch:
- List of top cryptocurrencies by market cap
- Real-time price data for selected currency pairs

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run tests and linting
5. Submit a pull request

## License

This project is licensed under the MIT License.
