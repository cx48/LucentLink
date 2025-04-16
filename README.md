# Lucent Link

A clean, customizable, and responsive Linktree-style landing page built using HTML, TailwindCSS, and Font Awesome. It allows you to showcase your links, social profiles, and personal branding in one beautiful page.

## Live Demo

**Live Site Demo:** [Lucent Link](https://cx48.github.io/LucentLink)

## Features

- Responsive and mobile-friendly layout
- Font Awesome icons for social/media links
- Floating animated background
- Customizable link cards
- Messaging etiquette guidelines
- Optional About Me section

## Tech Stack

- HTML5
- TailwindCSS
- Font Awesome (for icons)
- JavaScript (for background animation)

## Fork and Edit Locally

1. **Fork this repo** to your GitHub account using the "Fork" button at the top right.
2. **Clone it to your machine**:

```bash
git clone https://github.com/your-username/LucentLink.git
cd LucentLink
```

3. **Open with VS Code**:

```bash
code .
```

> You can use any code editor of your choice

4. (Recommended) Install the **Live Server** extension in VS Code for real-time preview:
   - Open VS Code Extensions sidebar
   - Search for "Live Server"
   - Click Install, then right-click `index.html` → **"Open with Live Server"**

## Deployment

### GitHub Pages

1. Push your code to GitHub.
2. Go to **Repository Settings > Pages**
3. Under **Source**, select:
   - Branch: `main`
   - Folder: `/root`
4. Click **Save**
5. GitHub will provide a live URL like:  
   `https://your-username.github.io/LucentLink`
6. Set a **custom domain** under Pages settings if needed *(Optional)* 

---

### Vercel

1. Go to [https://vercel.com](https://vercel.com)
2. Click **"Add New Project"** and import your GitHub repo
3. Leave all default settings (since this is a static site)
4. Click **Deploy**
5. Your site will be live at:  
   `https://your-project-name.vercel.app`

## Customization Guide

#### Profile Info

- Change name, bio, and profile picture in the profile section

```html
<h1 class="text-3xl font-bold">cx48</h1>
<p>Security Analyst | Frontend Developer | Content Writer</p>
<img src="img.png" alt="Profile Picture">
```

#### Adding New Links

Copy any existing `<a>` block inside the `.link-card` section and change:

- Icon class (`<i class="fas fa-icon">`)
- Title
- Description
- Href

#### Customize CSS

Edit Tailwind classes (e.g., `bg-white`, `text-sm`, etc.) or tweak `style.css` for advanced customization.

## License

This project is licensed under the [MIT License](LICENSE)

## Acknowledgments

- [Tailwind CSS](https://tailwindcss.com/)
- [Font Awesome](https://fontawesome.com/)
- Inspiration from Linktree styled profile pages
