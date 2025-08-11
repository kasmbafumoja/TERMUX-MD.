# termux md - Social Media Video Downloader
*powered by kas*

A comprehensive web-based automation platform for downloading social media videos.

## Features
- Social media video downloading with URL input
- Multiple platform support (YouTube, TikTok, Instagram, etc.)
- Quality selection and format options
- Automation workflows and scheduling
- File management and download history
- Mobile-first responsive design

## Deployment on Render

### Quick Deploy
1. Fork this repository to your GitHub account
2. Go to [Render.com](https://render.com) and sign up/login
3. Click "New +" → "Web Service"
4. Connect your GitHub repository
5. Use these settings:
   - **Build Command**: `npm ci && npm run build`
   - **Start Command**: `npm start`
   - **Environment**: Node.js
   - **Plan**: Free (or paid for better performance)

### Environment Variables
Set these in Render dashboard:
- `NODE_ENV=production`
- `PORT` (automatically set by Render)

### Manual Steps
1. Create account on [Render.com](https://render.com)
2. Connect your GitHub account
3. Import this repository
4. Configure build settings as above
5. Deploy

Your app will be available at: `https://your-app-name.onrender.com`

## Local Development
```bash
npm install
npm run dev
```

## Built With
- React 18 with TypeScript
- Express.js backend
- Tailwind CSS + shadcn/ui
- Vite build system
