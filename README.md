# 📚 NoteVault

**NoteVault** is a beautifully designed, interactive PDF reader and study material hub for 4th semester engineering students. Browse, search, and read organized notes, question banks, MCQs, and slides — all in one place with a sleek dark-themed UI featuring ambient background animations.

## 🚀 Features

- **Organized by Subject**: Browse materials for DAA, DBMS, M4, MP & ES, and SEPM — neatly categorized with subcategories.
- **In-Browser PDF Viewer**: Read PDFs directly in the app without downloading, with full-screen support.
- **Smart Search**: Instantly search across all subjects and files to find exactly what you need.
- **Question Banks**: Access complete question banks and previous year papers for exam preparation.
- **MCQ Collections**: Subject-wise MCQ banks for quick revision and self-assessment.
- **Lecture Slides**: View PowerPoint slides and study guides alongside notes.
- **Responsive Sidebar**: Collapsible sidebar with subject navigation and file stats.
- **Ambient UI**: Floating gradient orbs and glassmorphism effects for a premium study experience.
- **Share Links**: Copy shareable links to specific PDFs for easy collaboration.

## 🛠️ Technology Stack

- **HTML5**: Semantic structure with embedded PDF viewer
- **CSS3**: Custom properties, glassmorphism, ambient orb animations, responsive design
- **JavaScript (ES6)**: Dynamic content rendering, search filtering, sidebar navigation
- **Fonts**: Google Fonts (Inter)

## ⚙️ Getting Started

### Prerequisites

- A modern web browser

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/vardhan23v/NoteVault.git
   cd NoteVault
   ```

2. **Open in Browser**

   Simply open `index.html` in your browser, or use a local server:
   ```bash
   # Using Python
   python3 -m http.server 8000

   # Using Node.js
   npx http-server -p 8000
   ```

   Then visit `http://localhost:8000`

## 📁 Project Structure

```
NoteVault/
├── DAA/                          # Design & Analysis of Algorithms
│   ├── mcq/                      # MCQ question banks
│   ├── 1,2,3 units notes/        # Unit-wise notes
│   └── sslides/                  # Lecture slides
├── DBMS/                         # Database Management Systems
├── M4/                           # Mathematics IV
├── MP & ES/                      # Microprocessor & Embedded Systems
├── SEPM/                         # Software Engineering & Project Management
├── index.html                    # Main application page
├── style.css                     # Design system with ambient animations
├── app.js                        # File data structure and app logic
├── 4TH SEM 2025 QP.pdf          # Previous year question paper
└── COMPLETE_QUESTION_BANK.pdf    # Complete question bank
```

## 📋 Available Subjects

| Subject | Full Name | Materials |
|---------|-----------|-----------|
| DAA | Design & Analysis of Algorithms | Notes, MCQs, Slides |
| DBMS | Database Management Systems | Notes, MCQs, Slides |
| M4 | Mathematics IV | Notes, MCQs |
| MP & ES | Microprocessor & Embedded Systems | Notes, MCQs |
| SEPM | Software Engineering & Project Management | Notes, MCQs |

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/vardhan23v/NoteVault/issues).

## 📄 License

This project is licensed under the MIT License.
