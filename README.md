# ScholarSearch - AI-Powered Academic Search

ScholarSearch is a Next.js application that leverages Google's Gemini AI to provide intelligent academic search results. The application allows users to search for scholarly articles, research papers, and other academic resources.

## Features

- AI-powered search using Google's Gemini API
- Academic content discovery
- Filter results by content type
- Modern UI with dark/light mode support

## Getting Started

### Prerequisites

- Node.js 16.x or higher
- npm or yarn
- Google Gemini API key

### Installation

1. Clone the repository
2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Set up environment variables:
   - Copy `.env.local.example` to `.env.local`
   - Add your Gemini API key to `.env.local`

```
NEXT_PUBLIC_GEMINI_API_KEY=your_api_key_here
```

4. Run the development server:

```bash
npm run dev
# or
yarn dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser


## Technologies Used

- Next.js
- React
- TypeScript
- Tailwind CSS
- Google Gemini AI
- shadcn/ui components

## License

This project is licensed under the MIT License.
