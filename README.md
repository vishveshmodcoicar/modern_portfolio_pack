React JS Resume Starter Pack and Digital Portfolio 
- A tutorial inspired by @sonnysangha

Welcome to the Resume Portfolio Starter Pack!  
This project lets you showcase your skills, experience, and projects in a modern, customizable portfolio website.

Features

- **Easy customization** via a single JSON file
- Responsive, modern design
- Downloadable resume
- Social media and project links
- Ready for deployment

Here's a preview :

https://vishveshmodcoicar.netlify.app/

---

 Getting Started

 1. Clone the Repository

```bash
git clone https://github.com/yourusername/your-portfolio-repo.git
cd your-portfolio-repo
```

2. Install Dependencies

```bash
npm install
```

3. Start the Development Server

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) to view your portfolio.

---
Customizing Your Portfolio

All your personal information, projects, and links are managed in one file:  
**`public/resumeData.json`**

Main Sections to Edit

 1. Personal Info

```json
"main": {
  "name": "Your Name",
  "occupation": "Your Profession",
  "description": "A short tagline about you.",
  "image": "yourphoto.jpg", // Place your image in public/images/
  "bio": "A longer bio about you.",
  ...
}
```

2. Contact Details

```json
"email": "your@email.com",
"phone": "+1234567890",
"address": {
  "street": "Your Street",
  "city": "Your City",
  "state": "Your State",
  "zip": "Your Zip"
}
```

 3. Resume Download

- Place your PDF resume in `public/resume/`
- Update the path:
  ```json
  "resumedownload": "/resume/your_resume.pdf"
  ```

4. Social Links

```json
"social": [
  {
    "name": "linkedin",
    "url": "https://linkedin.com/in/yourprofile",
    "className": "fa fa-linkedin"
  },
  ...
]
```

5. Work Experience & Education

Edit the `"work"` and `"education"` arrays to reflect your background.
 6. Skills

```json
"skills": [
  { "name": "ReactJs", "level": "90%" },
  ...
]
```

 7. Portfolio Projects

```json
"portfolio": {
  "projects": [
    {
      "title": "Project Title",
      "category": "Project Category",
      "image": "project.jpg", // Place image in public/images/portfolio/
      "url": "https://link-to-project.com"
    },
    ...
  ]
}
```

 8. Testimonials

```json
"testimonials": {
  "testimonials": [
    { "text": "Great work!", "user": "Client Name" },
    ...
  ]
}
```

---
Adding Images

- **Profile Image:** Place in `public/images/` and update `"image"` in `resumeData.json`
- **Project Images:** Place in `public/images/portfolio/` and reference in the `"image"` field for each project

---
Deployment

You can deploy your portfolio to platforms like **Vercel**, **Netlify**, or **GitHub Pages**.

1. Build your project:
   ```bash
   npm run build
   ```
2. Follow your chosen platform's instructions for deploying a React app.

---
Tips

- **Favicon:** Replace `public/favicon.ico` with your own icon for a personal touch.
- **Styling:** Customize styles in `public/css/` for colors, fonts, and layout.
- **Live Preview:** Use `npm start` to see changes instantly as you edit your JSON or images.

---
Need Help?

If you have questions or need help customizing, feel free to open an issue or reach out!

---

**Enjoy building your personal brand!**  
— Vishvesh Modcoicar
