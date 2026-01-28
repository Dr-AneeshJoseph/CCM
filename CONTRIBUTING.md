# Contributing to Counter-Current Multiplier Simulator

Thank you for your interest in contributing to this educational project! This document provides guidelines for contributing.

## 🎯 Project Goals

This project aims to:
- Provide clear, accurate visualization of renal physiology
- Be accessible to medical students worldwide
- Remain simple to use and deploy (single HTML file)
- Work offline and on mobile devices

## 🚀 How to Contribute

### Reporting Bugs

1. Check if the bug has already been reported in [Issues](../../issues)
2. If not, create a new issue with:
   - Clear, descriptive title
   - Steps to reproduce
   - Expected vs actual behavior
   - Browser/device information
   - Screenshots if applicable

### Suggesting Enhancements

1. Open an issue with the `enhancement` label
2. Describe the feature and its educational value
3. Include mockups or examples if possible

### Code Contributions

1. **Fork** the repository
2. **Clone** your fork locally
3. **Create a branch** for your feature: `git checkout -b feature/your-feature-name`
4. **Make changes** following the code style guidelines
5. **Test** on multiple browsers and devices
6. **Commit** with clear messages: `git commit -m "Add: description of change"`
7. **Push** to your fork: `git push origin feature/your-feature-name`
8. **Open a Pull Request** with a clear description

## 📝 Code Style Guidelines

### HTML
- Use semantic HTML5 elements
- Keep accessibility in mind (ARIA labels where needed)
- Maintain the single-file structure when possible

### CSS
- Use CSS variables (defined in `:root`)
- Follow mobile-first responsive design
- Keep animations smooth (prefer `transform` and `opacity`)

### JavaScript
- Use clear, descriptive variable names
- Comment complex logic, especially physics/physiology calculations
- Avoid external dependencies
- Keep the simulation scientifically accurate

## 🔬 Scientific Accuracy

This is an educational tool. Any changes to the physiology simulation should:
- Be based on established medical literature
- Include references in the PR description
- Not sacrifice accuracy for visual appeal

## 📋 Pull Request Checklist

Before submitting, ensure:
- [ ] Code works in Chrome, Firefox, Safari, and Edge
- [ ] Mobile responsiveness is maintained
- [ ] No console errors
- [ ] Simulation remains scientifically accurate
- [ ] README updated if adding features
- [ ] Commit messages are clear

## 🏷️ Commit Message Format

```
Type: Short description

Longer description if needed.

References: #issue-number (if applicable)
```

Types:
- `Add:` New feature
- `Fix:` Bug fix
- `Update:` Improvement to existing feature
- `Docs:` Documentation only
- `Style:` Formatting, no code change
- `Refactor:` Code restructuring

## 📜 License

By contributing, you agree that your contributions will be licensed under the MIT License.

## 🙋 Questions?

Feel free to open an issue for any questions about contributing.

---

Thank you for helping make medical education more accessible! 🧬
