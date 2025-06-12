# Startup Idea Validator

A web application that helps entrepreneurs assess the viability of their startup ideas using AI-powered analysis.

## Features

- Submit startup ideas through an intuitive form
- Get AI-powered analysis including:
  - Idea Summary
  - Viability Score
  - SWOT Analysis
  - Competitor Discovery
  - Market Insights
  - Recommendations
- Export analysis results as PDF
- Modern, responsive UI built with React and Tailwind CSS

## Tech Stack

- Frontend: React + Vite, TypeScript
- UI Components: shadcn/ui
- Styling: Tailwind CSS
- AI Integration: OpenAI API (GPT-4) or Gemini API
- PDF Export: react-to-pdf

## Getting Started

1. Clone the repository:
```bash
git clone <repository-url>
cd startup-validator
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your API keys:
```env
VITE_OPENAI_API_KEY=your_openai_api_key
VITE_GEMINI_API_KEY=your_gemini_api_key
```

4. Start the development server:
```bash
npm run dev
```

5. Open [http://localhost:5173](http://localhost:5173) in your browser.

## Usage

1. Fill out the startup idea form with:
   - Your startup idea
   - Target market
   - Unique value proposition
   - Business model

2. Submit the form to get an AI-powered analysis

3. Review the analysis results including:
   - Idea summary
   - Viability score
   - SWOT analysis
   - Competitor information
   - Market insights
   - Recommendations

4. Export the analysis as PDF for future reference

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
