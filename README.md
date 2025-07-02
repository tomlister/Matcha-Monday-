# 🧾 Matcha Monday Website

This is the landing page for the Matcha Monday community meetup at Parami Cafe in Sydney.

## 🌱 What is Matcha Monday?

We meet every Monday at 8am to share ideas, projects, and matcha. Builders, founders, artists, and curious minds welcome.

## 🏆 Adding a Member Achievement

To add your achievement to the website:

1. Create a new `.json` file in the `achievements/` folder.
2. Use this format:

```json
{
  "name": "Your Name",
  "desc": "Short description of your achievement",
  "url": "https://link-to-project-or-post.com",
  "img": "https://your-thumbnail-image.com/image.png"
}
```

3. Save your file with a unique name (e.g. `danielle.json`).
4. Add the file name to the list in `index.html` under the `<script>` section:
```js
const achievementFiles = [
  'achievements/alex.json',
  'achievements/jamie.json',
  'achievements/priya.json',
  'achievements/danielle.json' // <-- your new one
];
```

## 🛠 Hosting

This site works great with [GitHub Pages](https://pages.github.com/). Just push your repo and enable Pages in the settings.

---

🧃 First matcha’s on you!
