# How to Embed a FoxyApp into Your Webflow Website

**Please note:** To follow this guide, you should have administrative access to your Webflow site.

### 1. Log in to Your Webflow Dashboard
- Go to your Webflow login page. Usually it looks like this: `https://webflow.com/dashboard`.
- Enter your email and password.

### 2. Create or Edit a Page
- Navigate to `Pages` in the left-hand side menu.
- Click `+ Create New Page` to create a new page. Alternatively, click on an existing page where you want to embed the iFrame and then click `Edit`.

### 3. Access the Embed Element
- In the page editor, click on the `+ Add Elements` button on the left side of the screen.
- Scroll down to the `Components` section and drag the `Embed` element into the desired location on your page.

### 4. Paste the iFrame Code
- Copy the iFrame code from FoxyApps platform.
- Paste the iFrame code in the `Embed Code` dialog box that appears after you drop the `Embed` element into your page.

Your iFrame code should look something like this:

\`\`\`
<iframe src="https://www.foxyapps.com/path/to/your/embed" width="100%" height="500" frameborder="0"></iframe>
\`\`\`

Remember to adjust the `width`, `height`, and `src` attributes as needed.

### 5. Preview the Page
- Click the `Preview` icon at the top of the Designer to ensure the iFrame appears correctly.

### 6. Publish the Page
- If everything looks fine, click the `Publish` button on the upper right side of the Designer to save and publish your changes.

**Please note** that some Webflow templates or elements may not support iFrames.
