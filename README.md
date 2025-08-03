
# Therapist Review Site

A React + Next.js app for therapists to review skilled nursing facilities, with license verification via the CA DCA license search tool.

## 🚀 Features
- Therapist registration and login
- License number input and verification (simulated)
- Facility review form with ratings for:
  - Flexibility
  - Management
  - Cleanliness
  - Staff
- Review list display

## 🛠 How to Run Locally
1. Unzip this project folder
2. Open a terminal in the folder and run:

```bash
npm install
npm run dev
```

3. Visit http://localhost:3000 in your browser

## 🌐 How to Deploy
1. Push this folder to a GitHub repo
2. Go to https://vercel.com and connect your repo
3. Click **Deploy**

---

## 📌 Note
- License verification currently uses a placeholder API handler with Puppeteer
- To enable real verification, deploy the `/api/verify.js` backend on [Railway](https://railway.app) or [Render](https://render.com)
