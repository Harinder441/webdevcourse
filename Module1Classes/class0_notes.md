# Class 0: Git & Development Environment Setup
## Version Control and Development Tools

### 1. Introduction to Version Control

#### What is Version Control?
- System for tracking code changes
- History of modifications
- Collaboration tool
- Backup mechanism

#### Why Use Version Control?
- Track code changes
- Collaborate with others
- Maintain code history
- Manage different versions
- Backup code safely

### 2. Git Fundamentals

#### Basic Concepts
- Repository (repo)
- Commit
- Branch
- Merge
- Remote

#### Git Workflow
1. Working Directory
2. Staging Area
3. Local Repository
4. Remote Repository

### 3. Essential Git Commands

#### Setup and Configuration
```bash
# Configure user information
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

#### Basic Commands
```bash
# Initialize repository
git init

# Check status
git status

# Add files to staging
git add filename
git add .  # add all files

# Commit changes
git commit -m "Commit message"

# View history
git log
```

#### Remote Repository Commands
```bash
# Add remote
git remote add origin <repository-url>

# Push changes
git push origin main

# Pull changes
git pull origin main

# Clone repository
git clone <repository-url>
```

### 4. GitHub Basics

#### Account Setup
- Creating GitHub account
- Setting up SSH keys
- Profile configuration
- Repository creation

#### GitHub Features
- Issues tracking
- Pull requests
- Project boards
- GitHub Pages
- Actions (CI/CD)

#### Best Practices
- Clear repository names
- Meaningful commit messages
- Regular commits
- Branch management
- Documentation (README.md)

### 5. Development Environment Setup

#### Code Editor: VS Code
1. Installation
   - Download from official website
   - System-specific setup
   - Basic configuration

2. Essential Extensions
   - Git Integration
   - Live Server
   - HTML/CSS Support
   - ESLint
   - Prettier

#### Browser Setup
1. Chrome Installation
   - Download and install
   - Set as default browser
   - Install dev tools

2. Developer Tools
   - Elements panel
   - Console
   - Network tab
   - Sources panel

### 6. Git-VS Code Integration

#### VS Code Git Features
- Source Control panel
- Git status indicators
- Commit interface
- Branch creation
- Merge conflicts resolution

#### Common Operations
1. Through UI:
   - Stage changes
   - Commit changes
   - Push/pull
   - View history

2. Through Terminal:
   - Integrated terminal
   - Git commands
   - Command palette

### 7. Project Setup Exercise

#### Initialize TODO List Project
1. Create Project Structure:
```bash
todo-list/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── README.md
```

2. Git Setup:
```bash
# Initialize repository
git init

# Create .gitignore
echo "node_modules/" > .gitignore

# Initial commit
git add .
git commit -m "Initial project setup"
```

3. GitHub Setup:
   - Create repository
   - Connect local to remote
   - Push initial commit

### 8. Best Practices

#### Git Workflow
- Regular commits
- Clear commit messages
- Feature branches
- Pull before push
- Review changes

#### Project Organization
- Clear folder structure
- Consistent naming
- Proper documentation
- Clean code principles

### Homework Assignment

1. Environment Setup:
   - Install all required tools
   - Configure Git and GitHub
   - Set up VS Code
   - Test configurations

2. Practice Exercise:
   - Create test repository
   - Make multiple commits
   - Create and merge branches
   - Push to GitHub

### Additional Resources

1. Documentation:
   - Git Documentation
   - GitHub Guides
   - VS Code Docs
   - Chrome DevTools Docs

2. Tools:
   - Git GUI clients
   - Git cheat sheets
   - Markdown editors
   - GitHub Desktop

### Next Class Preview
- Web development basics
- Internet fundamentals
- Client-server architecture
- Project wireframing 