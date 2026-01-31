# AI Creative Portfolio & Blog

A simple, clean portfolio and blog website for showcasing your AI creative projects. Built with pure HTML/CSS - no frameworks needed!

## 🚀 Deploying to GitHub Pages

1. **Create a new GitHub repository**
   - Go to GitHub and create a new repository
   - Name it `your-username.github.io` (replace `your-username` with your GitHub username)
   - Make it public

2. **Upload your files**
   - Upload all the files from this folder to your repository
   - Make sure to include: `index.html`, `projects.html`, `blog.html`, `styles.css`, and the `blog/` folder

3. **Enable GitHub Pages**
   - Go to your repository Settings
   - Scroll down to "Pages" section
   - Under "Source", select "main" branch
   - Click Save

4. **Visit your site!**
   - Your site will be live at `https://your-username.github.io`
   - It may take a few minutes to deploy

## ✏️ How to Add New Blog Posts

1. **Copy an existing post**
   - Go to the `blog/` folder
   - Copy `post-1.html` or `post-2.html`
   - Rename it (e.g., `post-3.html`)

2. **Edit the new post**
   - Open your new file
   - Update the `<title>` tag
   - Update the `<h1>` heading
   - Change the date in `<p class="post-meta">`
   - Write your content in the `<div class="post-content">` section

3. **Add it to your blog page**
   - Open `blog.html`
   - Add a new entry in the blog list:
   ```html
   <article class="blog-entry">
       <span class="date">Your Date</span>
       <h2><a href="blog/post-3.html">Your Post Title</a></h2>
       <p>Brief preview of your post...</p>
       <a href="blog/post-3.html" class="read-more">Read more →</a>
   </article>
   ```

4. **Update the homepage (optional)**
   - Open `index.html`
   - Add your latest post to the "Recent Blog Posts" section

5. **Commit and push**
   - Save all your changes
   - Commit and push to GitHub
   - Your site will automatically update!

## 📝 Customization Tips

- **Change colors**: Edit the gradient in `.hero` section in `styles.css`
- **Update your name**: Search and replace "Your Name" across all files
- **Add images**: Use `<img src="path/to/image.jpg" alt="description">` in your posts
- **Social links**: Add them to the footer in each HTML file

## 📁 File Structure

```
your-site/
├── index.html          # Homepage
├── projects.html       # Projects showcase
├── blog.html          # Blog index
├── styles.css         # All styles
├── blog/              # Blog posts folder
│   ├── post-1.html
│   ├── post-2.html
│   └── ...
└── README.md          # This file
```

## 💡 Tips

- Keep your posts organized with consistent naming (post-1.html, post-2.html, etc.)
- Write in Markdown first if you prefer, then convert to HTML
- Test locally by opening `index.html` in your browser before pushing
- Use descriptive titles and dates for better SEO

Happy blogging! 🎉
