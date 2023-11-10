# React Developer Portfolio template
#### Live Demo https://rutvikdeveloperportfolio.netlify.app/
### Preview ( Dark Mode )

<img src="/preview.gif" alt="preview" width="600px" />

## Follow Below instructions to add your deatils in the portfolio.

### Change and customize every section according to your need, All you need to do is edit `/src/Details.js`

#### Open `/src/Details.js` & modify it as per your need.

```javascript
/ Enter your Personal Details here
export const personalDetails = {
  name: "Rutvik Jasani",
  tagline: "passionate Front-End Developer",
  img: profile,
  about: `I'm Frontend Web Developer,equiped with an experience of two years and a potent skill set, proficient in Next.js, React.js, JavaScript, TypeScript, Tailwind CSS, Bootstrap, Material-UI (MUI), Redux Toolkit (RTK),  HTML, and CSS.  I specialize in creating stunning and responsive web applications. With a keen eye for design and cutting-edge technology, I can transform concepts into polished, high-performance digital experiences. Let me bring your web projects to life with my expertise and flair..`,
};

// Enter your Social Media URLs here
export const socialMediaUrl = {
  linkdein: "https://www.linkedin.com/",
  github: "https://www.github.com/",
  twitter: "https://twitter.com/",
  instagram: "https://www.instagram.com/",
};

// Enter your Work Experience here
export const workDetails = [
  {
    Position: "Frontend Web Developer",
    Company: `PropVIVO`,
    Location: "Surat",
    Type: "Full Time",
    Duration: "Jul 2023 - Present",
  },
  {
    Position: "Frontend Web Developer",
    Company: `Flex Team`,
    Location: "Surat",
    Type: "Full Time",
    Duration: "Aug 2022 - Jun 2023",
  },
  {
    Position: "Internship",
    Company: `Flex Team`,
    Location: "Surat",
    Type: "Internship",
    Duration: "May 2022 - Jul 2022",
  },
];

// Enter your Education Details here
export const eduDetails = [
  {
    Position: "Master of Computer Application`",
    Company: "Jain (Deemed-to-be University)",
    Location: "Distant",
    Type: "Full Time",
    Duration: "Jan 2022 - Present",
  },
  {
    Position: "Bachelor of Computer Applications",
    Company: `C. B. PATEL COMPUTER COLLEGE`,
    Location: "Surat",
    Type: "Full Time",
    Duration: "Aug 2019 - 2022",
  },
];

// Tech Stack and Tools
export const techStackDetails = {
  html: html,
  css: css,
  js: js,
  react: react,
  redux: redux,
  typescript: typescript,
  nextJs: nextJs,
  MUI:MUI,
  tailwind: tailwind,
  bootstrap: bootstrap,
  vscode: vscode,
  postman: postman,
  npm: npm,
  git: git,
  github: github,
  figma: figma,
};

// Enter your Project Details here
export const projectDetails = [ ... ];

// Enter your Contact Details here
export const contactDetails = {
  email: "ritikjasani119@gmail.com",
  phone: "+91 87358 00946",
};
```
