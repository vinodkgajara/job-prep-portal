# PrepHire — Job Portal & Placement Preparation Platform

Full-stack React + TypeScript + Tailwind CSS + Express + SQLite (`node:sqlite`) web application covering:

1. **Job Portal**: Search & filter roles by work mode, experience level, sector, and CTC; save jobs; apply with resume/cover note and track application status; post new job openings.
2. **Preparation Hub (Aptitude, DSA, Technical, HR)**: Structured study notes with formulas, worked examples, code snippets, and common pitfalls, paired with interactive MCQ & STAR behavioral practice problems with hints and explanations.
3. **Companies Hiring Process**: Detailed dossiers for Google, Amazon, Microsoft, Atlassian, Flipkart, Goldman Sachs, Zoho, TCS (NQT/Digital/Prime), Accenture, and Deloitte — including eligibility criteria, round-by-round timeline, exam pattern tables, topic-wise syllabus weightage, and interview prep tips.
4. **Dedicated DSA Sheet**: 10 topic-wise modules with curated coding problems, progressive hints, complexity analysis, C++/Java/Python/JavaScript solutions, status tracking (`Unsolved`, `Solved`, `Needs Revision`), starred problems, and persistent personal notes.

## Running Locally

```bash
npm install
npm run build
npm start
```

The server starts on `http://localhost:3001` (configurable via `PORT` environment variable) and stores data in `data/prephire.db`.

For development with hot reload:
- Terminal 1: `npm run dev` (Express API on port 3001)
- Terminal 2: `npm run dev:client` (Vite dev server on port 5173 with `/api` proxy)
