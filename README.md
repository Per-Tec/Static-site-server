## ⚙️ Prerequisites

- AWS EC2 or any remote Linux server
- SSH access with a `.pem` or `.ssh` key
- Node.js, npm, rsync installed locally
- Nginx installed and running on the server

---

## 🛠️ Setup Instructions

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/npm-static-site-server.git
cd npm-static-site-server

# 🔧 Static Site Server with Nginx + Vite

This project demonstrates how to host a static website using:
- A Linux server (EC2 on AWS)
- Nginx as the web server
- A Vite-built frontend site
- A Bash deployment script using `rsync` + `ssh`

## 📁 Project Structure
vite-project/
├── dist/ # Built static files (auto-generated)
├── public/ # Static assets (favicon, images)
├── src/ # Source code (HTML, CSS, JS)
│ └── main.ts
├── index.html # Main HTML page
├── deploy.sh # Deployment script using rsync
├── vite.config.ts # Vite config
├── tsconfig.json # TypeScript config
├── package.json # Project dependencies
└── README.md # You're here

Project url - https://roadmap.sh/projects/static-site-server
