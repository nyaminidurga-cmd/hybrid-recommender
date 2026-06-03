# 🤝 Contributing to hybrid-recommender

<div align="center">

![Contributing Banner](https://readme-typing-svg.demolab.com?font=Fira+Code&size=30&weight=700&pause=1000&color=1ABC9C&center=true&width=600&lines=Welcome+Contributors!;Let's+Build+Amazing+Projects;Together!)

</div>

Thank you for your interest in contributing to **hybrid-recommender**! We're excited to have you join our community. This guide will help you get started and make your first contribution.

## 📋 Table of Contents

1. [🌟 Ways to Contribute](#-ways-to-contribute)
2. [🚀 Getting Started](#-getting-started)
3. [📁 Project Structure](#-project-structure)
4. [🐛 Bug Reports & Issues](#-bug-reports--issues)
5. [📝 Pull Request Process](#-pull-request-process)
6. [🎨 Code Style Guidelines](#-code-style-guidelines)
7. [✅ Testing](#-testing)
8. [📞 Getting Help](#-getting-help)

---

## 🌟 Ways to Contribute

### 🔧 Improving the Recommender System
- Fix bugs in existing recommendation logic
- Enhance model performance
- Improve code quality and structure

### 📚 Documentation
- Improve README files
- Add setup guides
- Fix typos and formatting

### 🎨 UI/UX Improvements
- Enhance visual design of the frontend
- Improve user experience
- Make the interface mobile-friendly

### 🧪 Testing
- Add test cases for existing features
- Improve test coverage
- Report bugs with clear reproduction steps

---

## 🚀 Getting Started

### 1. Fork & Clone

```bash
# Fork the repository on GitHub, then clone your fork
git clone https://github.com/YOUR-USERNAME/hybrid-recommender.git
cd hybrid-recommender
```

### 2. Set Up Remote

```bash
# Add the original repository as upstream
git remote add upstream https://github.com/leonagoel/hybrid-recommender.git
```

### 3. Create a Branch

```bash
# Create a new branch for your contribution
git checkout -b feature/your-feature-name
# or
git checkout -b fix/bug-description
# or
git checkout -b docs/update-description
```

### 4. Set Up Environment

```bash
# Install dependencies
npm install

# Create environment variables
cp .env.example .env.local
# Edit .env.local with your credentials
```

### 5. Run Locally

```bash
npm run dev
# → http://localhost:3000
```

---

## 📁 Project Structure

```
hybrid-recommender/
├── frontend/          # Frontend application
├── backend/           # Backend API and recommendation logic
├── src/               # Core source files
├── datasets/          # Dataset files
├── scripts/           # Utility scripts
├── tests/             # Test files
├── supabase/          # Supabase configuration
├── .github/workflows/ # CI/CD pipelines
├── .env.example       # Environment variable template
└── README.md          # Project overview
```

---

## 🐛 Bug Reports & Issues

### Before Submitting
- Search existing issues to avoid duplicates
- Test on different browsers if applicable
- Check if it's already fixed in the latest version

### Contribution Limits
- **Per-person limit:** Max 3 open Issues & 3 open PRs at a time
- Please close or complete existing work before opening new ones
- Focus on one issue/PR at a time for quality contributions

### Issue Template

```markdown
**Bug Description**
Clear description of the bug

**Steps to Reproduce**
1. Go to...
2. Click on...
3. See error

**Expected Behavior**
What you expected to happen

**Screenshots**
Add screenshots if applicable

**Environment**
- Browser: [e.g. Chrome, Firefox]
- OS: [e.g. Windows, macOS, Linux]
- Node version: [e.g. 18.x]
```

---

## 📝 Pull Request Process

### 1. Keep Your Fork Updated

```bash
git fetch upstream
git checkout main
git merge upstream/main
```

### 2. Commit Changes

```bash
git add .
git commit -m "feat: add new recommendation algorithm"
# or
git commit -m "fix: resolve cold start issue"
# or
git commit -m "docs: update setup instructions"
```

Use present tense (`Add feature` not `Added feature`) and keep the first line under 50 characters.

### 3. Push and Create PR

```bash
git push origin your-branch-name
```

Then create a Pull Request on GitHub with:
- Clear title and description
- Reference any related issues (`Closes #123`)
- Screenshots if applicable
- List of changes made

### PR Template

```markdown
## Description
Brief description of changes

## Related Issue
Closes #

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Performance improvement

## Changes Made
- Detailed list of changes

## Testing
How to test the changes

## Screenshots (if applicable)
For UI changes, include before/after screenshots

## Checklist
- [ ] Code follows style guidelines
- [ ] Self-review completed
- [ ] Documentation updated
- [ ] No merge conflicts
- [ ] No sensitive data committed
```

### Review Process
- At least 1 maintainer review required
- All conversations must be resolved
- Feedback addressed before merge

---

## 🎨 Code Style Guidelines

### JavaScript / TypeScript
- Use `const`/`let` instead of `var`
- Use arrow functions where appropriate
- Add comments for complex logic
- Handle errors gracefully
- Follow ESLint rules enforced in the project

```javascript
// Good
const fetchRecommendations = async (userId) => {
  try {
    const results = await getRecommendations(userId);
    return results;
  } catch (error) {
    console.error('Failed to fetch recommendations:', error);
  }
};

// Avoid
function getRec(id) {
  var x = getRecommendations(id);
  return x;
}
```

### General
- Use meaningful variable and function names
- Keep functions small and focused
- Group related logic together
- Remove unused imports and dead code

---

## ✅ Testing

### Manual Testing Checklist
- [ ] Feature works as expected end-to-end
- [ ] No console errors or warnings
- [ ] Tested on Chrome and Firefox
- [ ] Responsive design checked on mobile
- [ ] Different user roles tested if applicable

### Before Submitting a PR
- [ ] Run `npm run dev` and verify no build errors
- [ ] Run `npm run build` to confirm production build passes
- [ ] Verify no sensitive data (API keys, tokens) is committed

---

## 🔒 Security

**Do not** include sensitive information in pull requests:
- API keys, tokens, or credentials
- Database URIs with passwords
- Private encryption keys
- Personal information

If you find a security vulnerability, please open a private issue rather than a public one.

---

## 📞 Getting Help

- 💬 **GitHub Discussions**: Ask questions and get help from the community → [Discussion Board](https://github.com/leonagoel/hybrid-recommender/discussions)
- 🐛 **Issues**: Report bugs or request features → [Issues](https://github.com/leonagoel/hybrid-recommender/issues)
- 📖 **README**: Review the [README.md](README.md) for project overview

---

## 🏆 Recognition

Contributors will be:
- Added to our contributors wall
- Mentioned in release notes
- Given credit in project documentation

---

## 📜 Code of Conduct

Please be respectful and inclusive in all interactions. We strive to create a welcoming environment for developers of all backgrounds and experience levels.

---

<div align="center">

**🌟 Thank you for contributing to hybrid-recommender! 🌟**

**Your contributions help make better recommendations for everyone!**

</div>
