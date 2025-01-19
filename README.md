


# Astro Starter Kit: Basics  

A starter template built with an **atomic structure** and **optimized SEO configuration**.  
Features include **light/dark theme switching**, **dynamic layouts**, and integrated **OpenGraph support**.  

---

## 💡 Support the Creator  

If you find this template useful, consider supporting me:  

[![Donate with Ko-fi](https://img.shields.io/badge/Donate-Ko--fi-F16061?logo=ko-fi&logoColor=white&style=flat)](https://ko-fi.com/sofidev)  
[![Become a Sponsor](https://img.shields.io/badge/Sponsor-GitHub%20Sponsors-ff69b4?logo=github&logoColor=white&style=flat)](https://github.com/sponsors/SofiDevO)  

Every contribution helps me create more free resources like this one! ❤️  

---

## 📲 Connect with Me  

Find all my social media and portfolio links here:  
🔗 [My Social Links](https://linktr.ee/sofidev)  

---


## 🚀 Quick Start  

To create a new project using this template, run:  

```sh
npm create astro@latest -- --template basics
```  

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)  
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)  
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)  

---

## 📂 Project Structure  

This template follows the **Atomic Design methodology** to organize components into a clear, scalable structure:  

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── atoms/
│   │   │   └── Button.astro
│   │   ├── molecules/
│   │   │   └── Navbar.astro
│   │   ├── organisms/
│   │   │   └── Header.astro
│   │   └── templates/
│   │       └── MainTemplate.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```  

- **Atoms**: Basic building blocks (e.g., buttons, inputs).  
- **Molecules**: Combinations of atoms (e.g., form fields, navigation links).  
- **Organisms**: Groups of molecules forming distinct sections (e.g., headers, footers).  
- **Templates**: Page-level layouts with placeholder content.  

To learn more about the folder structure, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).  

---

## 🛠 Usage of Iconify  

This project includes **Iconify Icon** for easily adding scalable icons.  

### Adding an Icon  

To include an icon in your project:  

```html
<iconify-icon icon="mdi:home"></iconify-icon>
```

### Customize the Icon  

You can customize the icon's properties like color, size, and more.  
Here's an Astro component to make it reusable:  

```astro
---
import "iconify-icon";
const {
  IconName = "mdi:home",
  color = "#fff",
  width = "30",
  height = "30",
  className,
} = Astro.props;
---

<iconify-icon 
  icon={IconName} 
  width={width} 
  height={height} 
  style={`color: ${color}`} 
  class={className} 
  noobserver
></iconify-icon>
```

### Example Usage  

```astro
<IconifyIcon IconName="solar:sun-bold" className="sun" />
```

### Find More Icons  

Explore a vast library of icons at [Iconify Icon Sets](https://icon-sets.iconify.design/).  

---
## 🧞 Commands  

Run the following commands from the root directory:  

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Builds your production site to `./dist/`         |
| `npm run preview`         | Previews your build locally, before deploying    |
| `npm run astro ...`       | Runs CLI commands like `astro add`, `astro check`|
| `npm run astro -- --help` | Gets help using the Astro CLI                    |  

---

## 📦 Dependencies  

- **Astro**: `^5.0.7`  
- **Iconify Icon**: `^2.3.0`  

---

## 💌 Want to learn more?  

Check out [our documentation](https://docs.astro.build)
