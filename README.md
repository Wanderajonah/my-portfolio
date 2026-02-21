# Portfolio Website - Wandera Jonah

A modern, professional, and fully responsive portfolio website for a MERN Stack and WordPress Developer.

## 🚀 Features

- **Modern Design**: Clean, premium dark mode UI with smooth animations
- **Fully Responsive**: Mobile-first design that works on all devices
- **Smooth Animations**: Powered by Framer Motion for engaging user experience
- **SEO Optimized**: Proper metadata and semantic HTML
- **Contact Form**: Integrated contact form with backend API support
- **Project Showcase**: Beautiful project cards with hover effects
- **Skills Display**: Animated progress bars and skill categories
- **CV Download**: Downloadable resume/CV functionality

## 🛠 Tech Stack

### Frontend
- **React 18** - UI library
- **Vite** - Fast build tool and dev server
- **TypeScript** - Type-safe development
- **Tailwind CSS 3** - Modern utility-first CSS framework
- **Framer Motion** - Smooth animations and transitions
- **Lucide React** - Beautiful icon library
- **React Intersection Observer** - Scroll animations

### Backend (Optional)
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database for contact form submissions
- **Mongoose** - MongoDB object modeling

## 📁 Project Structure

```
portfolio/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Navbar.tsx
│   │   │   ├── Hero.tsx
│   │   │   ├── About.tsx
│   │   │   ├── Skills.tsx
│   │   │   ├── Projects.tsx
│   │   │   ├── Services.tsx
│   │   │   ├── Resume.tsx
│   │   │   ├── Contact.tsx
│   │   │   └── Footer.tsx
│   │   ├── App.tsx
│   │   ├── main.tsx
│   │   └── index.css
│   ├── public/
│   │   └── Wandera_Jonah_CV.pdf
│   ├── index.html
│   ├── vite.config.ts
│   └── package.json
└── backend/
    ├── server.js
    ├── package.json
    └── .env.example
```

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ and npm/yarn
- MongoDB (for backend, optional)

### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

### Backend Setup (Optional)

1. Navigate to the backend directory:
```bash
cd backend
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file (copy from `.env.example`):
```bash
cp .env.example .env
```

4. Update `.env` with your MongoDB connection string:
```
MONGODB_URI=mongodb://localhost:27017/portfolio
PORT=5000
```

5. Start the backend server:
```bash
npm run dev
```

The backend API will run on `http://localhost:5000`

## 📝 Configuration

### Contact Form

The contact form can work in two ways:

1. **Backend API** (Recommended): Update the `VITE_API_URL` in `.env` or modify the API URL in `Contact.tsx` to point to your backend
2. **EmailJS** (Optional): Uncomment and configure EmailJS in `Contact.tsx`

### CV/Resume

Place your actual CV/Resume PDF file in `frontend/public/` as `Wandera_Jonah_CV.pdf`

### Social Media Links

Update social media links in:
- `Hero.tsx` - Hero section social icons
- `Footer.tsx` - Footer social icons

### Projects

Edit the projects array in `Projects.tsx` to showcase your actual projects.

### Personal Information

Update personal information in:
- `Hero.tsx` - Name, title, tagline
- `About.tsx` - Bio and description
- `layout.tsx` - SEO metadata

## 🎨 Customization

### Colors

The color scheme uses Tailwind CSS classes. Main colors:
- Primary: Blue (`blue-400`, `blue-500`, `blue-600`)
- Secondary: Purple (`purple-500`, `purple-600`)
- Background: Black/Gray (`black`, `gray-900`, `gray-800`)

### Animations

Animations are powered by Framer Motion. Adjust animation timings and effects in individual components.

### Typography

Fonts are configured in `layout.tsx` using Geist Sans and Geist Mono from Next.js.

## 📦 Building for Production

### Frontend

```bash
cd frontend
npm run build
npm run preview
```

### Backend

```bash
cd backend
npm start
```

## 🌐 Deployment

### Frontend (Vercel/Netlify)

1. **Vercel**:
   - Connect your GitHub repository
   - Build command: `cd frontend && npm run build`
   - Output directory: `frontend/dist`
   - Install command: `cd frontend && npm install`

2. **Netlify**:
   - Connect your repository
   - Build command: `cd frontend && npm run build`
   - Publish directory: `frontend/dist`

### Backend (Railway/Render/Heroku)

1. Set environment variables (MongoDB URI, PORT)
2. Deploy using your platform's instructions
3. Update frontend API URL to point to deployed backend

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

**Wandera Jonah**
- MERN Stack & WordPress Developer
- Location: Uganda

## 🙏 Acknowledgments

- Next.js team for the amazing framework
- Framer Motion for smooth animations
- Tailwind CSS for the utility-first approach
- Lucide for beautiful icons

---

Built with ❤️ using React, Vite, TypeScript, and Tailwind CSS

