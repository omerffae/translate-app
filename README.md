# Çeviri + (Translation Plus)

A modern, user-friendly translation application built with React and Redux. This application allows users to translate text between multiple languages with a clean and intuitive interface.

## 🌟 Features

- Real-time text translation
- Support for multiple languages
- Automatic language detection
- Language swap functionality
- Responsive design
- Dark mode interface
- Loading states for better UX

## 🛠️ Technologies Used

- React.js
- Redux Toolkit for state management
- React Select for language selection
- Tailwind CSS for styling
- Modern JavaScript (ES6+)

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/omerffae/translate-app.git
```

2. Navigate to the project directory:
```bash
cd translate_app
```

3. Install dependencies:
```bash
npm install
# or
yarn install
```

4. Start the development server:
```bash
npm run dev
# or
yarn dev
```

## 📱 Usage

1. Select the source language (or use "Dili algıla" for automatic detection)
2. Select the target language
3. Enter the text you want to translate in the left text area
4. The translated text will appear in the right text area
5. Use the "Değiş" button to swap languages

## 🏗️ Project Structure

```
src/
├── components/
│   ├── button.jsx
│   ├── language-select.jsx
│   ├── loader.jsx
│   └── text-container.jsx
├── redux/
│   ├── actions.js
│   ├── slices/
│   │   └── translateSlice.js
│   └── store.js
├── utils/
├── App.jsx
├── main.jsx
└── index.css
```

## 🙏 Acknowledgments

- Thanks to all contributors who have helped shape this project
- Special thanks to the open-source community for the amazing tools and libraries