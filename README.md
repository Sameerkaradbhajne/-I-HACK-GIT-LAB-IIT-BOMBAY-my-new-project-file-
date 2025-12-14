# CodeForge Commander

**All-in-One GitLab DevSecOps AI Agent for VS Code**

A VS Code extension built for the **i-Hack 2025 GitLab CodeForge Track** that integrates AI-powered DevSecOps workflows directly into your IDE.

---

## 🚀 Features

### 1. **Issue to Code** (Dev)
- Generate code from issue descriptions using AI
- Fetch and implement real GitLab Issues with one click
- Supports multiple programming languages

### 2. **Pipeline Healer** (Ops)
- Automatically diagnose failed CI/CD pipelines
- Fetch job logs from GitLab and analyze with AI
- Get instant fix suggestions

### 3. **Security Sentinel** (Sec)
- Scan open files for security vulnerabilities
- Fix hardcoded secrets, SQL injection risks, etc.
- AI-powered secure code generation

### 4. **Implement GitLab Issue**
- Browse open issues from your GitLab project
- Select an issue and generate implementation code
- Deep GitLab API integration

### 5. **Pipeline Status Dashboard**
- View all pipelines with real-time status (✅ Success, ❌ Failed, 🔄 Running)
- Click to view detailed pipeline information
- Quick access to Pipeline Healer for failed jobs

### 6. **SAST Vulnerabilities Viewer**
- Fetch security vulnerabilities from GitLab Security Dashboard
- AI-powered vulnerability fixes
- Fallback demo mode for projects without SAST enabled

---

## 🛠️ Installation

1. Clone this repository
2. Run `npm install`
3. Run `npm run compile`
4. Press `F5` to launch the Extension Development Host

---

## ⚙️ Configuration

Update the following in `src/extension.ts`:

```typescript
const GITLAB_TOKEN = 'your-gitlab-personal-access-token';
const PROJECT_ID = 'your-gitlab-project-id';
```

---

## 📋 Commands

- `CodeForge: Generate Code from Issue` - Generate code from a description
- `CodeForge: Heal Pipeline` - Diagnose and fix failed pipelines
- `CodeForge: Fix Security` - Scan and fix security vulnerabilities
- `CodeForge: Implement GitLab Issue` - Browse and implement GitLab issues
- `CodeForge: View Pipeline Status` - View all pipeline statuses
- `CodeForge: View SAST Vulnerabilities` - View and fix SAST findings

---

## 🏆 i-Hack 2025 Hackathon

This project demonstrates:
- **Deep GitLab Integration**: Uses Issues, Pipelines, Jobs, and Security APIs
- **AI-Powered DevSecOps**: Combines AI with GitLab's platform
- **Developer Productivity**: Reduces context switching and speeds up workflows
- **Shift-Left Security**: Catches vulnerabilities before code is pushed

---

## 🔧 Tech Stack

- **VS Code Extension API**
- **GitLab REST API**
- **AI Integration**: Pollinations.ai (with fallback to mock mode)
- **TypeScript**
- **Webpack**

---

## 📝 License

MIT

---

## 👥 Author

Built for i-Hack 2025 GitLab CodeForge Track
