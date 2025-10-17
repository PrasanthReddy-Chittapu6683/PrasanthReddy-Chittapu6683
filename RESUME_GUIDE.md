# Resume Usage Guide

This folder contains multiple versions of your professional resume optimized for different purposes.

## 📄 Resume Files

### **1. Prasanth_Resume.md** (Primary - Markdown)
- **Purpose:** Rich formatted resume with links and visual elements
- **Best For:** GitHub, Portfolio website, Online sharing
- **Features:** Clickable links, formatted tables, emoji indicators

### **2. Prasanth_Resume_ATS.txt** (ATS-Optimized)
- **Purpose:** Plain text for Applicant Tracking Systems
- **Best For:** Job applications, recruiter databases, ATS parsing
- **Features:** Clean text, keyword-rich, easily parsable

### **3. Prasanth_CV.docx** (Original)
- **Purpose:** Microsoft Word format
- **Best For:** Traditional applications requiring Word documents

---

## 🔄 Converting Your Resume

### **Markdown to PDF (Recommended for Applications)**

#### **Method 1: Using Pandoc (Best Quality)**
```bash
# Install Pandoc
brew install pandoc

# Convert to PDF with nice formatting
pandoc Prasanth_Resume.md -o Prasanth_Resume.pdf \
  --pdf-engine=xelatex \
  -V geometry:margin=0.75in \
  -V fontsize=11pt \
  -V colorlinks=true

# Or simple conversion
pandoc Prasanth_Resume.md -o Prasanth_Resume.pdf
```

#### **Method 2: Using Online Tools**
1. Go to https://www.markdowntopdf.com/
2. Upload `Prasanth_Resume.md`
3. Download the generated PDF

#### **Method 3: Using VS Code**
1. Install "Markdown PDF" extension in VS Code
2. Open `Prasanth_Resume.md`
3. Right-click → "Markdown PDF: Export (pdf)"

### **Markdown to DOCX**
```bash
# Using Pandoc
pandoc Prasanth_Resume.md -o Prasanth_Resume.docx

# With reference document for styling
pandoc Prasanth_Resume.md -o Prasanth_Resume.docx \
  --reference-doc=template.docx
```

### **Markdown to HTML**
```bash
# Using Pandoc
pandoc Prasanth_Resume.md -o Prasanth_Resume.html \
  --standalone \
  --css=resume-style.css
```

---

## 💼 When to Use Each Version

### **For Job Applications:**
1. **ATS Systems:** Use `Prasanth_Resume_ATS.txt` (paste into online forms)
2. **Email/Upload:** Use PDF converted from `Prasanth_Resume.md`
3. **Word Required:** Use `Prasanth_CV.docx` or convert Markdown to DOCX

### **For Networking:**
1. **LinkedIn:** Share link to GitHub README
2. **Portfolio:** Embed Markdown or HTML version
3. **Email:** Send PDF version

### **For Recruiters:**
1. **Initial Contact:** PDF version (professional, formatted)
2. **ATS Submission:** Plain text version
3. **Follow-up:** Link to GitHub profile README

---

## ✏️ Updating Your Resume

### **Quick Updates:**
Edit `Prasanth_Resume.md` and regenerate other formats:

```bash
# After editing the Markdown file:
pandoc Prasanth_Resume.md -o Prasanth_Resume.pdf
pandoc Prasanth_Resume.md -o Prasanth_Resume.docx

# Commit changes
git add Prasanth_Resume.*
git commit -m "📝 Updated resume with latest projects"
git push
```

### **Keep in Sync:**
When you update your GitHub README, make sure to also update your resume files to maintain consistency.

---

## 📋 Resume Sections Checklist

- ✅ Professional Summary (15+ years highlighted)
- ✅ Technical Skills (Comprehensive, categorized)
- ✅ Professional Experience (Achievement-focused)
- ✅ Featured Projects (With links and tech stacks)
- ✅ Specialized Expertise (ONE-UI, Agentic AI, etc.)
- ✅ Education & Certifications
- ✅ Open Source Contributions
- ✅ Contact Information

---

## 🎯 Tailoring for Specific Jobs

### **For AI/ML Roles:**
Emphasize:
- LangChain, LangGraph, Agentic AI sections
- MCP Server development
- Python, TensorFlow, PyTorch
- Vector databases and RAG systems
- ElevenLabs and voice AI

### **For Frontend Roles:**
Emphasize:
- React, NextJS, TypeScript expertise
- Component library development
- ONE-UI architecture
- GSAP animations
- Performance optimization (95+ Lighthouse)

### **For Full-Stack Roles:**
Emphasize:
- React + Node.js experience
- PostgreSQL, Supabase, GraphQL
- End-to-end application development
- Design systems + Backend APIs
- Mobile with React Native

### **For Design System Roles:**
Emphasize:
- ONE-UI architecture experience
- Standalone component library development
- MUI, ShadCN, Daisy UI expertise
- Figma-to-code workflows
- Multi-brand theming frameworks

---

## 🚀 Pro Tips

1. **Customize for each application:** Reorder sections based on job requirements
2. **Use keywords:** Include technology names from job descriptions
3. **Quantify achievements:** Use numbers (95+ Lighthouse score, 60% load time reduction)
4. **Keep it current:** Update with latest projects and technologies
5. **Proofread:** Check for typos and formatting consistency
6. **File naming:** Use descriptive names (e.g., `Prasanth_CV_Frontend_2025.pdf`)

---

## 📊 Resume Stats

- **Total Pages:** ~6-7 pages (comprehensive technical resume)
- **Sections:** 10 major sections
- **Projects Featured:** 20+ with links and descriptions
- **Technologies Listed:** 80+ tools and frameworks
- **Years of Experience:** 15+ (November 2010 - Present)

---

## 🔗 Quick Links

- **Live Portfolio:** https://cvpkr-portfolio.web.app/
- **GitHub Profile:** https://github.com/PrasanthReddy-Chittapu6683
- **LinkedIn:** https://linkedin.com/in/prasanth-kumar-reddy-cv-385768b5
- **GitHub README:** https://github.com/PrasanthReddy-Chittapu6683/PrasanthReddy-Chittapu6683

---

**Last Updated:** October 17, 2025

