# Personal developer portfolio

A one-page portfolio for InternCircle Project 01. Unzip the download and open `index.html` in a browser. Keep the stylesheet and the `images/` folder next to it. The page needs no build step, JavaScript, or external services.

## Personalize

1. Edit `index.html`. Search for `Your Name` and update the page title, navigation, introduction, and footer. Update the five skills to reflect your experience.
2. Replace the two sample projects with your own. Update the names, summaries, technology tags, and images. Edit each image's `alt` to describe the replacement and update its `width` and `height` to match the file. Remove the sample-project note after replacing both projects.
3. In Contact, replace each bracketed placeholder span with your real link. Use a `mailto:` link for email and full `https://` profile URLs for social links. Keep only the channels you want to publish. Example markup with reserved placeholder values:

   ```html
   <a href="mailto:your-address@example.com">your-address@example.com</a>
   <a href="https://github.com/YOUR-USERNAME">View my GitHub profile</a>
   <a href="https://www.linkedin.com/in/YOUR-SLUG/">View my LinkedIn profile</a>
   ```

## Publish and submit

1. Create a public GitHub repository. Upload `index.html`, `style.css`, `README.md`, and the entire `images/` folder to the root of `main`. Upload the extracted files and folders individually, keeping their structure.
2. In the repository, open **Settings → Pages**. Set **Source** to **Deploy from a branch**, choose **main** and **/(root)**, then save. [GitHub Pages publishing instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
3. After deployment, open the URL shown in Pages. Check it on your phone and at 360px, 768px, and 1280px in browser developer tools. Tab through navigation and confirm your contact links open the intended destinations.
4. In **My Tasks** on the InternCircle dashboard, submit your public GitHub Pages URL, the repository URL, and a short note about a design decision.

**Design note to adapt:** I used a two-column project grid on wider screens and stacked the cards below 700px. On a phone each preview and description gets the full available width, so readers can scan the projects without zooming.
