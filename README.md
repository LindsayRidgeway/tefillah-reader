# Tefillah Reader

**Tefillah Reader** is a lightweight, browser-based tool designed to help users of all ages and backgrounds practice reading Biblical Hebrew prayers aloud—at their own pace, without pressure. Whether you're preparing for a Bar/Bat Mitzvah, relearning after many years, or simply brushing up on your pronunciation, Tefillah Reader provides a simple, self-paced learning experience.

## 🌟 Key Features

- **Pure HTML/CSS/JavaScript** – no dependencies, no server-side code  
- **No installation required** – runs locally or via [Netlify](https://tefillah-reader.netlify.app)  
- **Supports multiple categories of Jewish prayers and blessings:**
  - *Shema Prayers*
  - *Amidah Blessings*
  - *Sabbath Blessings*
  - *Food Blessings*
  - *Grace After Meals*
  - *Ritual Items (miscellaneous)*
  - *Tehillim*
- **Simple practice controls:**
  - Toggle between *Normal* and *Challenge* mode
  - Show optional paragraph- or verse-level English translations
  - Set how many words appear at once
  - Step forward and backward through each prayer
- **Ashkenazi transliteration** throughout, suitable for most North American learners

## 📦 Project Structure

This is a single-page app. All logic and data reside in the following files:

- `index.html` – Main user interface and logic  
- `shema-prayers.js` – Word-by-word structure for Shema-related prayers  
- `amidah-blessings.js` – Word-by-word Amidah blessings  
- `sabbath-blessings.js` – Prayers for Sabbath meals and rituals  
- `food-blessings.js` – Food blessings and common after-blessings
- `ritual-items.js` – Hebrew words for ritual objects (educational/fun category)  
- `psalm27-prayers.js` – Word-by-word Psalm 27 reading
- `translations.js` – Optional paragraph- and verse-level English translations

## 🔧 Customization & Extensions

The app is designed for clarity and ease of use, so no user-facing customization is required. That said, the code is open and simple—other developers are welcome to fork the repository and extend it. Ideas include:

- Adding Sephardic transliterations  
- Including new prayer categories  
- Implementing Text-to-Speech (TTS)  
- Offering translations or explanations  

## 🚀 Running Locally

To run locally, simply:

```bash
git clone https://github.com/YOUR_USERNAME/tefillah-reader.git
cd tefillah-reader
open index.html

(You can also double-click the file in Finder or open it in any modern browser.)

💡 Why It Matters

Many people want to improve their Hebrew reading without being enrolled in a class or using complicated language apps. Tefillah Reader offers a low-pressure, non-judgmental way to grow confidence and fluency. There are no scores, no logins, no ads—just practice.

🤝 Contributions

You’re welcome to use or adapt this tool however you like. Feel free to open a pull request if you’d like to improve or extend the project in meaningful ways. No pressure, no obligations.

📬 Contact

This app was created and is maintained by Lindsay Ridgeway.

If you’re a rabbi, teacher, or learner who finds this helpful, please consider sharing it with your community or linking to it from your website.

⸻

Live site: https://tefillah-reader.netlify.app
