# CloudStore ☁️

A modern cloud storage web application inspired by platforms like Google Drive and Dropbox, where users can securely upload, organize, and manage files through a clean and responsive interface.

Developed collaboratively as part of an IBM internship project.

---

## 🚀 Live Demo

🔗 https://cloudstoragesystem-cjqn.onrender.com

---

## Features ✨

- Secure user authentication
- Upload and manage files
- Nested folder organization
- Starred files and trash system
- Storage usage dashboard
- Admin dashboard
- Real-time upload progress
- Drag-and-drop uploads
- Responsive modern UI
- AWS S3 cloud storage integration

## Technologies Used 🛠️

### Frontend
- React
- Vite
- Tailwind CSS
- Material UI
- React Router
- Framer Motion
- Three.js

### Backend
- FastAPI
- Python
- JWT Authentication

### Database & Cloud
- PostgreSQL
- AWS S3

## My Contributions 💡

- Developed major parts of the frontend UI
- Converted the application design into a responsive React interface
- Worked on layouts, reusable components, responsiveness, and animations
- Collaborated with teammates for backend integration and API connectivity

## Setup ⚙️

### Clone the Repository

```bash
git clone <your-repo-url>
cd CloudStore
```

### Backend Setup

```bash
cd backend

python -m venv venv

# Windows
venv\Scripts\activate

# Linux/Mac
source venv/bin/activate

pip install -r requirements.txt

uvicorn main:app --reload
```

### Frontend Setup

```bash
npm install
npm run dev
```

## Environment Variables 🔑

Create a `.env` file inside the backend folder:

```env
DATABASE_URL=
JWT_SECRET_KEY=

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_REGION=
S3_BUCKET_NAME=

CORS_ALLOWED_ORIGINS=
FRONTEND_URL=
```

## 📸 Application Preview

<table>
<tr>
<td align="center"><strong> Dashboard </strong></td>
<td align="center"><strong> File Upload Interface </strong></td>
</tr>

<tr>
<td>
<img width="1907" height="977" alt="fig-4 3" src="https://github.com/user-attachments/assets/47bcba1c-d75a-4ef9-b266-d6c4e65493f5" />
</td>

<td>
<img width="1250" height="716" alt="fig-4 7" src="https://github.com/user-attachments/assets/0a4654a0-32d5-469d-b5b0-896a68514991" />
</td>
</tr>

<tr>
<td align="center"><strong> Storage Overview </strong></td>
<td align="center"><strong> Admin Dashboard </strong></td>
</tr>

<tr>
<td>
<img width="794" height="607" alt="fig-4 4" src="https://github.com/user-attachments/assets/c5e858b2-13df-42eb-9cdf-9bbb46aa3970" />
</td>

<td>
<img width="1919" height="979" alt="fig-4 11" src="https://github.com/user-attachments/assets/95787fc7-9c73-447a-93cb-cd50bbb0b59d" />
</td>
</tr>

</table>
