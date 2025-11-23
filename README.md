<<<<<<< HEAD
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
=======
# AI Text Summarizer – SummarIQ

A full-stack web application that summarizes any text using AI. Built with **React**, **FastAPI**, and deployed online using **Vercel** and **Render**.

---

## Features

- Summarizes text efficiently using the **Groq Llama-3.1-8b-instant** AI model.
- Dark/Light mode toggle for better user experience.
- Loading indicators while summarization is in progress.
- Clear input and output with a single click.
- Fully deployed: backend on **Render**, frontend on **Vercel**.

---

## Tech Stack

- **Frontend:** React, Vite, CSS  
- **Backend:** FastAPI, Groq API  
- **Deployment:** Vercel (frontend), Render (backend)

---

## Getting Started

### Prerequisites

- Node.js
- Python 3.10+
- Git

### Backend Setup

```bash
cd backend
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
export GROQ_API_KEY=your_api_key   # or use .env file
uvicorn main:app --reload

>>>>>>> e9c9cda4bffeb9b2b6f8f57be70058156cb1b1f7
