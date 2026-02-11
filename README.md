# 💕 Will You Be My Valentine? 💕



## ✨ What It Does

- Asks "Will You Be My Valentine?"
- The "Yes" button grows bigger and more tempting with each click
- The "No" button? It vanishes when clicked (sneaky, right?)
- After 5 clicks on "Yes", reveals a the custom celebration message
- Background turns pink.

## 🎮 How It Works

1. Your valentine sees the question with two buttons
2. If they click "No" → button disappears (oops!)
3. If they click "Yes" → button asks "Are you sure?" and gets BIGGER
4. After 5 "Yes" clicks → 🎉 Celebration time with a custom message!

## 🛠️ Files Included

- `valentine.html` - The main page (use this for your own customization)
- `valentine-for-mom.html` - Example customized version
- `valentine.css` - All the styling magic
- `valentine-question.gif` - Adorable asking dog GIF
- `valentine-celebration.gif` - Happy celebration dog GIF

## 💝 How to Customize for Your Special Someone

### Step 1: Clone the Repository in VS Code
1. Open VS Code
2. Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac) to open the Command Palette
3. Type "Git: Clone" and select it
4. Paste the repository URL when prompted
5. Choose a location on your computer to save the project
6. Click "Open" when VS Code asks if you want to open the cloned repository

### Step 2: Edit the Message
Open `valentine.html` and find this section around line 22:

```html
<h2>I love you</h2>
```

Replace "I love you" with your custom message! Examples:
- `<h2>I love you [Their Name]! 💕</h2>`
- `<h2>You make my heart smile ❤️</h2>`
- `<h2>Best decision ever! 🎉</h2>`

### Step 3: (Optional) Change the GIFs
The project already includes cute dog GIFs (`valentine-question.gif` and `valentine-celebration.gif`), so you can skip this step if you like them!

Want to use your own? Find these lines in the HTML:

```html
<img src="valentine-question.gif" alt="Will you be my valentine?" class="gif">
```
and
```html
<img src="valentine-celebration.gif" alt="Celebration!" class="gif">
```

Replace the `src` values with your own GIF URLs or local file paths. Pro tip: Find cute GIFs on [Giphy](https://giphy.com)!

### Step 4: Test It Out
1. Save your changes (Ctrl+S or Cmd+S)
2. Right-click `valentine.html` in VS Code
3. Select "Open with Live Server" (install Live Server extension if you don't have it)
   - OR just double-click the file to open in your browser

## 🎨 Customization Ideas

Want to go further? Here are some ideas:

### Change Colors
In `valentine.css`, modify the pink theme:
```css
h1 {
    color: #ff69b4; /* Change this hex code to your favorite color */
}
```

### Adjust Button Growth
Make the "Yes" button grow faster or slower by editing the click counter in the JavaScript:
```javascript
if (clickCount < 5) {  // Change this number (try 3 for faster, 10 for slower)
```

### Add More Messages
Make the button text change more creatively on each click by editing:
```javascript
yesBtn.textContent = 'Are you sure?'; // Add different messages for each click!
```

## 📱 Mobile Friendly

The page automatically adjusts for phones and tablets, so your valentine can say yes from anywhere! 💕

## 🚀 Deployment Tips

Want to send this as a link? Host it for free on:
- [GitHub Pages](https://pages.github.com/)
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)

Just upload your files and share the link!

## 💡 Tips

- Test it yourself first (click through all the stages)
- Make sure your GIFs are appropriate and load quickly
- Send the link with a cute text message for extra points
- Screenshot the celebration screen as a keepsake!

## Need Help?

Stuck on customization? Remember:
- Save your files after editing (Ctrl+S / Cmd+S)
- Refresh your browser to see changes
- Check the browser console (F12) if something breaks
- When in doubt, copy the original files before experimenting!

---

Made with 💕 for making Valentine's Day special. Good luck! 🍀
