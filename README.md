# Pterodactyl Custom Panel

A modern, customizable Pterodactyl-inspired panel software with custom theme support and server management capabilities.

## Features

- 🎨 **Custom Theme System** - Upload and apply custom background images
- 🖥️ **Server Management** - Full server control with console access
- 📊 **Dashboard Analytics** - Real-time server statistics and monitoring
- 🔐 **Authentication System** - Secure login with role-based access
- ⚙️ **Settings Management** - Comprehensive admin configuration
- 📱 **Responsive Design** - Works on desktop, tablet, and mobile

## Quick Install

Run this command on your VPS to install automatically:

\`\`\`bash
curl -sSL https://raw.githubusercontent.com/Saturo56/pterodactyl-panel/main/scripts/install-pterodactyl-panel.sh | bash
\`\`\`

## Manual Installation

1. Clone the repository:
\`\`\`bash
git clone https://github.com/Saturo56/pterodactyl-panel.git
cd pterodactyl-panel
\`\`\`

2. Install dependencies:
\`\`\`bash
npm install
\`\`\`

3. Build the application:
\`\`\`bash
npm run build
\`\`\`

4. Start the server:
\`\`\`bash
npm start
\`\`\`

The panel will be available at `http://your-server-ip:3000`

## Default Login

- **Email:** admin@panel.com
- **Password:** admin123

## Configuration

The panel can be configured through the Settings page after logging in. Key configuration options include:

- General panel settings
- User management and roles
- Security policies
- System monitoring
- API configuration
- Notification settings

## Theme System

The custom theme system allows you to:

- Upload custom background images
- Choose from preset themes
- Preview themes before applying
- Manage and delete custom themes

Supported image formats: JPG, PNG, GIF (max 10MB)

## Server Management

Features include:

- Server creation and configuration
- Real-time console access
- File management system
- Server statistics monitoring
- Start/stop/restart controls
- Resource usage tracking

## Requirements

- Node.js 18+ 
- 2GB+ RAM
- 10GB+ storage
- Ubuntu 20.04+ or similar Linux distribution

## Support

For issues and support, please open an issue on GitHub.

## License

MIT License - see LICENSE file for details.
