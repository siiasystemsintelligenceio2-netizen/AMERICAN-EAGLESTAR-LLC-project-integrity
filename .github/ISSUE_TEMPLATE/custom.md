git checkout -b docs/project-idea-template

mkdir -p .github/ISSUE_TEMPLATE

cat > .github/ISSUE_TEMPLATE/project_idea_template.md <<'EOF'
---
name: Project Idea Template
about: Submit a new project idea, enhancement, or active-development concept.
title: "[PROJECT IDEAS] "
labels: documentation, enhancement, help wanted, question
assignees: siiasystemsintelligenceio2-netizen
---

## Project Idea Template

### About

Describe this issue template's purpose here.

---

## 1. Idea Description

Provide a clear and concise description of your project idea.

## 2. Steps to Create Your Idea

1. Go to `copilot`.
2. Describe your new idea `in chat`.
3. Download any `New Material or CODE`.
4. Upload to `Optional Idea Submission`.
5. Continue with `Active Development`.

## 3. Expected Outcome

Clearly and concisely describe what you expected to happen.

## 4. Screenshots Optional

If applicable, add screenshots to help explain your Project Idea.

## 5. Environment

Please complete the following information.

### Desktop

- OS: `[e.g., iOS]`
- Browser: `[e.g., Chrome, Safari]`
- Version: `[e.g., 22]`

### Smartphone

- Device: `[e.g., iPhone 6]`
- OS: `[e.g., iOS 8.1]`
- Browser: `[e.g., Stock Browser, Safari]`
- Version: `[e.g., 22]`

## 6. Additional Context Optional

Add any other relevant context about your project idea.

---

## Optional Additional Items

**Issue default title:**

**Assignees:**

**Labels:**
EOF

git add .github/ISSUE_TEMPLATE/project_idea_template.md
git commit -m "docs: add project idea issue template"
git push -u origin docs/project-idea-template
