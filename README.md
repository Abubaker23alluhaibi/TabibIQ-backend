# Tabib IQ Frontend

Frontend application for Tabib IQ medical consultation platform built with React.

## 🚀 Features

- **Multi-language Support**: Arabic, English, and Kurdish
- **Responsive Design**: Works on all devices
- **User Authentication**: Login, registration, and profile management
- **Doctor Management**: Browse doctors, book appointments
- **Admin Dashboard**: Complete admin panel for managing users and doctors
- **Modern UI**: Beautiful and intuitive user interface

## 📋 Prerequisites

- Node.js (v14 or higher)
- npm or yarn

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd tabib-iq-frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Setup**
   Create a `.env` file in the root directory:
   ```env
   REACT_APP_API_URL=https://tabib-iq-backend-production.up.railway.app/api
   ```

## 🚀 Running the Application

### Development
```bash
npm start
```

### Production Build
```bash
npm run build
```

The application will start on `http://localhost:3000`

## 📁 Project Structure

```
tabib-iq-frontend/
├── public/                 # Static files
│   ├── index.html         # Main HTML file
│   ├── favicon.ico        # App icon
│   └── manifest.json      # PWA manifest
├── src/                   # Source code
│   ├── App.js            # Main App component
│   ├── AuthContext.js    # Authentication context
│   ├── Login.js          # Login component
│   ├── UserHome.js       # User home page
│   ├── DoctorDashboard.js # Doctor dashboard
│   ├── AdminDashboard.js # Admin dashboard
│   ├── locales/          # Translation files
│   │   ├── ar/           # Arabic translations
│   │   ├── en/           # English translations
│   │   └── ku/           # Kurdish translations
│   └── index.js          # App entry point
├── package.json          # Dependencies and scripts
├── .env                  # Environment variables
├── vercel.json           # Vercel deployment config
├── netlify.toml          # Netlify deployment config
└── railway.json          # Railway deployment config
```

## 🌐 Deployment

### Vercel (Recommended)
1. Connect your GitHub repository to Vercel
2. Set environment variables in Vercel dashboard:
   ```env
   REACT_APP_API_URL=https://tabib-iq-backend-production.up.railway.app/api
   ```
3. Deploy automatically

### Netlify
1. Connect your GitHub repository to Netlify
2. Set environment variables in Netlify dashboard
3. Deploy automatically

### Railway
1. Connect your GitHub repository to Railway
2. Set environment variables in Railway dashboard
3. Deploy automatically

## 🔧 Configuration

### Environment Variables
- `REACT_APP_API_URL`: Backend API URL

### Build Configuration
- Build command: `npm run build`
- Output directory: `build`
- Node version: 18.x

## 📱 Features

### User Features
- Browse doctors by specialty and location
- Book appointments with doctors
- Manage personal profile
- View appointment history
- Medicine reminders

### Doctor Features
- Doctor dashboard
- Appointment management
- Patient records
- Analytics and reports

### Admin Features
- User management
- Doctor approval system
- Health center management
- System analytics

## 🎨 Design

- **Color Scheme**: Blue and teal theme
- **Typography**: Modern and readable fonts
- **Layout**: Responsive grid system
- **Icons**: Material Design icons
- **Animations**: Smooth transitions and hover effects

## 🌍 Internationalization

The app supports three languages:
- **Arabic (ar)**: Right-to-left layout
- **English (en)**: Left-to-right layout  
- **Kurdish (ku)**: Right-to-left layout

Translation files are located in `src/locales/`

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the ISC License.

## 🆘 Support

For support, please contact the development team or create an issue in the repository. 