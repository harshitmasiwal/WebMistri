# WebMistri

**WebMistri** is an AI-powered website builder that transforms a single line of text into a fully functional, styled website in seconds. Built as a hackathon project, it leverages the Gemini API to generate HTML, CSS, and JavaScript code, providing users with a seamless experience to create and deploy websites effortlessly.

## ✨ Key Features

- **AI Website Generation**: Input a simple prompt, and WebMistri generates a complete website with HTML, CSS, and JavaScript.
- **Real-Time Preview**: Instantly preview the generated website before downloading.
- **Download as ZIP**: Export the generated website as a ZIP file for easy deployment.
- **History Tracking**: Automatically saves previously generated websites for future access.
- **Customizable Output**: Edit, tweak, and regenerate parts of your website as needed.

## 🛠️ Tech Stack

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express
- **AI Integration**: Gemini API
- **Database**: MongoDB (for storing history of generated websites)

## 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/harshitmasiwal/WebMistri.git
   cd WebMistri
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Add your **Gemini API key** in the `.env` file:

   ```
   GEMINI_API_KEY=your_api_key_here
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

## 📂 Project Workflow

1. Enter a prompt (e.g., “Portfolio website with navbar, hero section, and contact form”).
2. Gemini API generates the **HTML, CSS, and JavaScript** files.
3. The generated site is displayed in real-time preview.
4. You can **save**, **download as ZIP**, or **deploy** to hosting platforms.

## 📜 Future Enhancements

- Drag-and-drop editor for customization.
- Multi-page website generation.
- Direct deployment integration (GitHub Pages, Vercel, Netlify).

---

⚡ Built with by **Harshit**
