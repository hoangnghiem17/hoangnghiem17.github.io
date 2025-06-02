# Page Structure
-posts/: Contains all blog posts (in Markdown format)
-layouts/: Contains the HTML templates for different page types
-includes/: Contains reuseable HTML components
-sass/: Contains CSS files for styling
-assets/: Contains static files like images, CSS and JS
-data/: Contains YAML data files for site configuration

# Main Pages
- index.md: Homepage
- about.md: About Page
- 404.md: Custom 404 error page
- tags.html: Page showing all tags used in posts
- archive.html: Page showing all posts in chronological order

# Building Pages
- default.html: Base layout that all other layouts extend from
- post.html: Template for blog posts
- page.html: Template for regular pages (like About)
- home.html: Template for the homepage
- 404.html: Template for error page

# New Pages
1. Create a new .md file in root directory
2. Add front matter at the top file specifying the layout
3. Write your content in Markdown