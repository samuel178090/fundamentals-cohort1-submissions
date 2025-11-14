# DeployHub Frontend

A React-Vite dashboard for monitoring backend services with real-time observability.

## 🚀 Features

- **Real-time Dashboard** with auto-refresh every 30 seconds
- **Health Monitoring** with visual status indicators
- **System Metrics** display
- **Responsive Design** for all devices
- **Error Handling** with user-friendly messages
- **API Integration** with axios
- **Modern React 18** with hooks

## 📊 Dashboard Components

### Health Card
- System status indicator
- Uptime tracking
- Memory usage display
- Version information

### Status Card
- Service status monitoring
- Environment information
- Last check timestamp

### Metrics Card
- Application version
- Node.js version
- Build information
- System environment

## 🛠️ Quick Start

### Development
```bash
npm install
npm run dev
```

### Build
```bash
npm run build
npm run preview
```

### Linting
```bash
npm run lint
npm run lint:fix
```

## 🔧 Configuration

### Environment Variables
Create `.env` file:
```bash
VITE_API_URL=http://localhost:3000
```

### API Integration
The frontend connects to backend endpoints:
- `/health` - Basic health status
- `/health/detailed` - Detailed system info
- `/api/status` - Service status
- `/api/version` - Version information

## 🎨 UI Features

- **Auto-refresh** every 30 seconds
- **Loading states** with spinners
- **Error handling** with error banners
- **Status indicators** with color coding
- **Responsive grid** layout
- **Smooth animations** and transitions

## 🚦 CI/CD Pipeline

GitHub Actions workflow:
1. **Lint** - ESLint code quality
2. **Build** - Vite production build
3. **Deploy** - Automated deployment

## 📱 Responsive Design

- Desktop-first approach
- Mobile-friendly breakpoints
- Flexible grid system
- Touch-friendly interactions

## 🔄 Real-time Updates

The dashboard automatically:
- Refreshes data every 30 seconds
- Shows loading states during updates
- Handles connection errors gracefully
- Displays last update timestamp

## 🎯 Monitoring Capabilities

- **Health Status** - Real-time service health
- **System Metrics** - Memory and performance
- **Version Tracking** - Application versions
- **Environment Info** - Deployment environment

This frontend provides comprehensive visibility into your backend services with a beautiful, responsive interface.