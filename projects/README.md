# Projects Directory

This directory contains the portfolio's project showcase pages.

## Structure

- `index.html` - The projects landing page with project cards
- `template.html` - A reusable template for creating new project pages
- Individual project pages (e.g., `roblox-game.html`, `web-dashboard.html`)

## How to Add a New Project

### Step 1: Create the Project Page

1. Copy `template.html` to a new file with a descriptive name (e.g., `my-new-project.html`)
2. Open the new file and update the following sections:
   - **Title and Meta Description** (lines 7-9): Change the project name and description
   - **Breadcrumb** (line 65): Update the project name
   - **Project Header** (lines 68-82): Add your project title, status, date, and role
   - **Project Description** (lines 86-98): Describe your project
   - **Technologies Used** (lines 103-111): List the technologies you used
   - **Key Features** (lines 116-126): List the main features
   - **Media Gallery** (lines 133-157): Add screenshots or replace placeholders
   - **Project Links** (lines 162-174): Add links to live demo, GitHub, etc.

### Step 2: Add a Card to the Projects Page

1. Open `index.html`
2. Find the projects grid section (around line 89)
3. Copy an existing project card block (lines 97-111 for example)
4. Paste it before the closing `</div>` of the projects-grid
5. Update the card:
   - Change the image or placeholder emoji
   - Update the project title (h3)
   - Update the description (p)
   - Update the tags
   - Update the link href to point to your new project page

### Step 3: Test

1. Open `index.html` in a browser to see your new project card
2. Click the card to navigate to your project page
3. Test on mobile (you can use browser dev tools to simulate mobile)

## Card Template Example

```html
<article class="project-card">
    <div class="project-card-image">
        <div class="placeholder">🚀</div>
        <!-- OR use an actual image: -->
        <!-- <img src="path/to/image.jpg" alt="Project Name"> -->
    </div>
    <div class="project-card-content">
        <h3>Your Project Title</h3>
        <p>A brief description of your project that explains what it does.</p>
        <div class="project-tags">
            <span class="tag">Tech 1</span>
            <span class="tag">Tech 2</span>
            <span class="tag">Category</span>
        </div>
        <a href="your-project-page.html" class="project-card-link">View Project</a>
    </div>
</article>
```

## Design Guidelines

- Use consistent styling with the existing cards
- Keep descriptions concise (2-3 sentences)
- Use relevant emojis or actual project screenshots
- Include 2-4 technology tags
- Ensure all links are functional

## Mobile Responsiveness

All pages are designed to be mobile-responsive:
- Cards stack into a single column on screens under 810px
- Touch-friendly buttons (44px minimum height)
- Readable text sizes on small screens
- Navigation adapts for mobile devices

## Need Help?

If you need assistance or want to suggest improvements, please contact the site maintainer.
