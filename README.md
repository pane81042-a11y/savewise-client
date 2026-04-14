# SaveWise Client

SaveWise Client is the frontend application for the SaveWise savings tracker platform.

It provides a responsive and accessible user experience for managing savings goals, tracking deposits, viewing progress, exploring dashboard insights, and filtering goals by different criteria.

## Features

- Create, edit, and delete savings goals
- Add deposits and review deposit history
- View progress bars and summary cards
- Dashboard metrics and monthly savings charts
- Filter and sort goals
- Goal detail pages with completed states
- Protected routes for authenticated users
- Keyboard-friendly navigation and accessible UI patterns

## Tech Stack

- React
- React Router
- Context API or Redux Toolkit
- Axios or Fetch API
- Charting library for progress visualization
- CSS, SCSS, Tailwind CSS, or component library of choice

## Getting Started

### 1. Clone the repository
```bash
git clone <your-savewise-client-repo-url>
cd savewise-client
```
### 2. Install dependencies
```bash
npm install
```
### 3. Create environment variables
- Create a .env file and configure the required frontend environment variables.
- Example:
```env
VITE_API_URL=http://localhost:5000
VITE_AUTH_URL=http://localhost:5001
```
### 4. Start the development server
```bash
npm run dev
```
### Scripts
```bash
npm run dev
npm run build
npm run preview
npm run lint
```

## Accessibility Goals
SaveWise Client is designed with accessibility in mind, including keyboard navigation, focus states, semantic structure, and responsive layouts.

## Related Repositories
- SaveWise API
- SaveWise Auth Service
- SaveWise Shared
- SaveWise UI
- SaveWise Infra
