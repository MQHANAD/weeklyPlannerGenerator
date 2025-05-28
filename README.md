# 📅 Weekly Planner | مخطط أسبوعي

This is a responsive **Weekly Planner** web application that allows users to generate a printable planner grid between two dates and download it as a PDF. The interface supports theme switching and RTL (Right-to-Left) layout.

## 🌟 Features

- 🗓 Select custom start and end dates to generate weekly planner
- 📄 Export planner as a high-quality PDF
- 🎨 Multiple modern, pastel, and dark UI themes
- 🔁 Responsive design for both desktop and mobile
- ✨ Smooth animations and user-friendly interface

## 🔧 Technologies Used

- HTML5 + CSS3
- JavaScript (Vanilla)
- ChatGPT
- [html2pdf.js](https://github.com/eKoopmans/html2pdf) for PDF generation
- Google Fonts: [Tajawal](https://fonts.google.com/specimen/Tajawal), [Roboto](https://fonts.google.com/specimen/Roboto)

## 📦 Setup & Usage

### 1. Clone the repository

```bash
git clone https://github.com/MQHANAD/weeklyPlannerGenerator.git
cd weeklyPlannerGenerator
```

### 2. Open the `index.html` file

You can simply open the file in any modern web browser:

```bash
open index.html
```

Or click the following link: https://mqhanad.github.io/weeklyPlannerGenerator/

### 3. Use the app

- Choose the **start** and **end** dates.
- Click **"إنشاء"** (Generate) to build the planner.
- Click **"تحميل PDF"** (Download PDF) to export your weekly planner.

## 🖼 Themes

Switch between 5 built-in themes:

- Default (Blue)
- Dark
- Pastel
- Nature (Green tones)
- Modern (Cool tones)

## 📥 PDF Export Notes

- Each week is printed as a row, and the tool automatically paginates long planners (e.g. 52+ weeks).
- Avoid using extremely long date ranges if you want a single-page export, due to browser canvas height limits.

## 📝 Customization

- You can customize the theme colors in the CSS using the `--primary-color`, `--secondary-color`, etc.
- Add more themes by duplicating the `.theme-*` blocks.
- You can easily internationalize it further using JavaScript.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---
