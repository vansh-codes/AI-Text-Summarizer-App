<h1 align="center">AI Text Summarizer</h1>

![AI-Text-Summarizer-App](https://socialify.git.ci/vansh-codes/AI-Text-Summarizer-App/image?name=1&owner=1&theme=Dark)

<div align="center">

<img src="https://forthebadge.com/images/badges/built-with-love.svg" height=40px/> <img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fvansh-codes%2FAI-Text-Summarizer-App
&label=visitors&countColor=%2337d67a&style=for-the-badge&labelStyle=upper" height=40px /> <img src="https://img.shields.io/github/last-commit/vansh-codes/AI-Text-Summarizer-App?style=for-the-badge" height=40px />
<img src="https://img.shields.io/github/repo-size/vansh-codes/AI-Text-Summarizer-App?style=for-the-badge" height=40px> <br/> <br/>
<img src="https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white" height=30px /> <img src="https://vercelbadge.vercel.app/api/vansh-codes/AI-Text-Summarizer-App?style=for-the-badge" height=30px />

</div>

<div align="center">
<h2>🎉 Welcome to the AI Text Summarizer Web App repository! This application leverages the power of artificial intelligence to provide concise summaries of long texts. Whether you have a lengthy article, research paper, or any other text document that you want to summarize quickly, this app can assist you.</h2>
</div>

## 📍Table of Contents
1. [Features](#Features)
2. [Technology Stack](#Technology-Stack)
3. [Getting Started](#Getting-Started)
4. [Web Application](#Web-Application)
5. [Usage](#Usage)
6. [Contributing](#Contributing)
7. [License](#License)
8. [Contact](#Contact)
9. [Links](#Links)

## ✨Features

- **Text Summarization**: Paste any text into the text area and get a concise summary.
- **Default Text**: Use the default text button to add dummy text for testing.
- **Responsive Design**: The app is responsive and works well on various devices.
- **Loading State**: The submit button shows a loading spinner while the text is being summarized.

## 💻Technology Stack

### **FrontEnd:** ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) &nbsp; ![CSS5](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) &nbsp; ![JAVASCRIPT](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### **BackEnd:** ![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white) &nbsp; ![ExpressJS](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)

### **API:** Hugging Face BART model for text summarization


## Getting Started

### Prerequisites

- Node.js and npm installed on your machine
- Hugging Face API token

### Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/vansh-codes/AI-Text-Summarizer-App.git
   ```
2. Create a `.env` file in the root directory and add your Hugging Face API token:
   ```bash
   ACCESS_TOKEN=your_hugging_face_api_token
   ```
3. run `node index.js`
4. Open `localhost:3000` in your web browser to start using the application.

## 🌐Web Application
1. Access here: [AI-Text-Summarizer](https://ai-text-summarizer-app-gold.vercel.app/)

## Usage

1. Open the application in your browser.
2. Paste your text into the "Paste in some text to summarize" text area. Ensure that the text length is between 200 and 100,000 characters.
3. Click the "Summarize" button to get a concise summary of the text.
4. Optionally, click the "Add Default Text" button to insert dummy text into the text area for testing purposes.
   
```bash
.
├── public
│   └── index.html        # HTML for the app
│   └── stylesheet.css    # CSS styles for the app
│   └── script.js         # script for the app
│── index.js         
│── summarize.js         
├── .env                  # Environment variables (not committed to version control)
├── .gitignore            # Files and directories to ignore in git
├── package.json          # Project dependencies and scripts
└── README.md             # Project documentation
```

### **API Integration**
The app uses the Hugging Face BART model for text summarization. The API call is made using the `axios` library in the `script.js` file. Ensure that your Hugging Face API token is set correctly in the `.env` file.


## Contributing

Contributions are welcome! Please create a issue and wait until assigned. When assigned fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


## 📞Contact

For any questions or feedback, please contact [vansh-codes](https://github.com/vansh-codes).

### - Created by **Vansh Chaurasiya** 
Show some ❤️ by starring this repository !


## 🔗Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vanshchaurasiya24)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://www.twitter.com/vanshchaurasiy4) <p align="right"><a href="#top">BACK TO TOP</a></p>
