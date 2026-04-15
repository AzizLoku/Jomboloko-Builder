# Jomboloko-Builder
Jomboloko Builder is an AI-native meta-website framework that generates complete, scalable sites and apps from simple inputs. It unifies layout creation, components, branding, and automation to power fast deployment for media, business, and ministry platforms.
# Jomboloko Builder — AI‑Native Meta‑Website Builder

Jomboloko Builder is a next‑generation AI‑native platform that allows users to create fully functional, production‑ready websites, components, layouts, and design systems using natural language.  
It combines a canvas editor, schema engine, code generator, and AI orchestration layer into one unified builder experience.

This project is built with:
- Next.js 14 (App Router)
- React 18
- TypeScript
- Tailwind CSS
- Prisma ORM
- PostgreSQL (Supabase/Neon)
- OpenAI / Anthropic AI
- Zustand (state management)
- ShadCN UI (component system)

---

## 🚀 Features

### **AI‑Powered Website Generation**
- Generate full pages, components, and layouts using natural language.
- AI converts prompts → structure → layout → components → code.

### **Canvas Editor**
- Drag‑and‑drop interface
- Select, resize, move, and edit components visually
- Real‑time preview

### **Schema Engine**
- JSON‑based schema that defines every component and layout
- Ensures consistency between canvas, code, and AI output

### **Code Generator**
- Converts schema → production‑ready React/Next.js code
- Supports design tokens, variants, and responsive layouts

### **Design System Intelligence**
- AI understands spacing, typography, colours, and component patterns
- Generates consistent UI aligned with your design system

### **Marketplace**
- Templates
- Components
- AI agents
- Starter kits

### **Deployment System**
- One‑click deploy to Vercel
- Export full codebase

---

## 📦 Project Structure

/app
/api
/dashboard
/(site)

/components
/canvas
/inspector
/project-tree
/ai-panel
/code-panel
/ui

/lib
/ai
/schema
/codegen
/design-system
/utils
db.ts

/prisma
schema.prisma

/public
/styles
/hooks
/types

Code

---

## 🛠️ Getting Started

### **1. Install dependencies**
npm install

Code

### **2. Set up environment variables**
Create a `.env` file:

DATABASE_URL="your_database_url"
OPENAI_API_KEY="your_api_key"

Code

### **3. Run database migrations**
npx prisma migrate dev

Code

### **4. Start the development server**
npm run dev

Code

Your app will be live at:

http://localhost:3000

Code

---

## 🧱 Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Next.js, React, Tailwind, ShadCN |
| Backend | Next.js API Routes, Node.js |
| Database | PostgreSQL (Supabase/Neon) |
| ORM | Prisma |
| AI | OpenAI / Anthropic |
| State | Zustand |
| Deployment | Vercel |

---

## 📘 Roadmap

- [ ] Canvas editor MVP  
- [ ] Schema engine v1  
- [ ] AI orchestration engine  
- [ ] Code generator v1  
- [ ] Design system intelligence  
- [ ] Marketplace v1  
- [ ] Deployment system  
- [ ] Enterprise features  

---

## 🧑‍💻 Author

**Aziz Loku**  
Founder of Jomboloko Builder  
Calgary, Alberta, Canada

---

## 📄 License

MIT License
