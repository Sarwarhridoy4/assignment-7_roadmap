---
## 📅 Day-by-Day Plan (Sept 27 → Oct 2)
---

### **Day 1 – Sept 27 (Today)**

**🎯 Goal: Backend setup & authentication**

- [ ] Setup **Express + TypeScript** project (separate repo).
- [ ] Configure **Prisma + PostgreSQL** (db schema with User, Blog, Project, Resume).
- [ ] Implement **JWT auth**:

  - Register, Login, Logout.
  - Password hashing with bcrypt.
  - Middleware for `auth` & `role-based` routes.

- [ ] Test auth routes with Postman.
- [ ] Commit progress to GitHub (`init backend`, `setup prisma schema`, `auth module`).

---

### **Day 2 – Sept 28**

**🎯 Goal: Backend core APIs**

- [ ] Blog CRUD APIs (`/blogs`).
- [ ] Project CRUD APIs (`/projects`).
- [ ] Resume schema + basic CRUD (for resume builder).
- [ ] Protect private routes with JWT + role-based access.
- [ ] Add **global error handler** & proper validation.
- [ ] Test APIs with Postman.
- [ ] Update README with API docs.
- [ ] Commit (`blogs module`, `projects module`, `resume module`, `error handling`).

---

### **Day 3 – Sept 29**

**🎯 Goal: Frontend setup (Next.js)**

- [ ] Setup **Next.js + TypeScript + TailwindCSS** (separate repo).
- [ ] Layout: Navbar, Footer, SEO config (`next/head`).
- [ ] Pages:

  - `/` Home
  - `/about`
  - `/blogs` + `/blogs/[id]`
  - `/projects` + `/projects/[id]`
  - `/resume-builder`
  - `/dashboard`

- [ ] Setup **Axios or fetch wrapper** for API calls.
- [ ] Setup **JWT auth context** (store token in HttpOnly cookie or localStorage).
- [ ] Commit (`init frontend`, `basic layout`, `routing`, `auth context`).

---

### **Day 4 – Sept 30**

**🎯 Goal: Core features frontend**

- [ ] Auth forms (Register, Login).
- [ ] Blog listing (ISR) + single blog page (getStaticPaths + revalidate).
- [ ] Blog CRUD UI (if admin).
- [ ] Project showcase (SSR/ISR).
- [ ] Resume builder UI (form with sections: Contact, Work, Education, Skills).
- [ ] Connect API → Frontend for blogs, projects, resume.
- [ ] Commit (`auth UI`, `blogs UI`, `projects UI`, `resume form`).

---

### **Day 5 – Oct 1**

**🎯 Goal: Dashboard + polish**

- [ ] Dashboard (admin-only):

  - Manage blogs/projects.
  - Show stats (dummy charts with Recharts or Chart.js).

- [ ] Implement Rich Text Editor (e.g., React Quill or TipTap) for blog/project editing.
- [ ] Add toast notifications (`react-hot-toast`).
- [ ] Add form validation + error handling everywhere.
- [ ] Commit (`dashboard`, `RTE`, `toasts`, `validations`).

---

### **Day 6 – Oct 2**

**🎯 Goal: Final polish, SEO & Deployment**

- [ ] Implement **dynamic SEO meta tags** (blogs, projects, about, resume).
- [ ] Add Open Graph + Twitter Card support.
- [ ] Add animations + loading states (skeletons).
- [ ] Accessibility check (semantic HTML, ARIA labels).
- [ ] Deploy:

  - **Backend → Render/Vercel/Railway/Heroku**
  - **Frontend → Vercel**

- [ ] Prepare **README.md** (features, setup, tech stack, live links).
- [ ] Record **demo video (5–10 min)** walkthrough.
- [ ] Commit (`seo`, `deploy`, `final polish`).

---

✅ By **Oct 2 night**, you’ll be done with full project + deployment + demo video.
Oct 3 is buffer day in case of unexpected bugs.

---

## 📌 GitHub Commit Roadmap

### **Backend Repo (Express + Prisma + JWT)**

1. `chore: initialize express backend with typescript setup`
2. `chore: configure prisma schema for users, blogs, projects, resume`
3. `feat(auth): add user registration with bcrypt password hashing`
4. `feat(auth): implement login and JWT token generation`
5. `feat(middleware): add JWT auth and role-based access control`
6. `feat(blog): implement CRUD routes for blog management`
7. `feat(project): implement CRUD routes for project management`
8. `feat(resume): add resume schema and CRUD APIs`
9. `fix: add centralized error handling and validation middleware`
10. `docs: update backend README with API documentation and setup guide`

(You can add extra commits for bug fixes or deployment like `chore: add docker support` or `deploy: setup railway deployment` if needed.)

---

### **Frontend Repo (Next.js + Tailwind + API Integration)**

1. `chore: initialize nextjs frontend with typescript and tailwind setup`
2. `feat(layout): add navbar, footer, and global SEO config`
3. `feat(auth): implement login and register forms with JWT integration`
4. `feat(blog): add blogs listing page with ISR`
5. `feat(blog): add single blog page with dynamic meta tags`
6. `feat(projects): add projects showcase with SSR/ISR`
7. `feat(resume): implement resume builder form with PDF export`
8. `feat(dashboard): add admin dashboard with blog/project management`
9. `feat(editor): integrate rich text editor for blog/project content`
10. `chore: add react-hot-toast, form validation, and error handling`
11. `seo: add dynamic meta tags for blogs, projects, and about page`
12. `docs: update frontend README with deployment link and usage guide`

---

💡 Tip: Don’t commit giant chunks. Push progress incrementally (after finishing a feature or fixing a bug). This will **prove real development history**.

---
