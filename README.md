# 🌟 Chat Translator Project 🌟

Welcome to the **Chat Translator Project**! 🚀 This project is an **incredible** chat application that allows users to send messages in one language and receive translations in another language in **real-time**. The application leverages **cutting-edge** translation models from Hugging Face to provide **accurate** and **fast** translations between multiple languages. 🌍

## Features ✨

- **Real-time Translation**: Translate messages between multiple languages **instantly**. ⚡
- **WebSocket Integration**: Receive new messages and updates in **real-time** without constant reloading. 🔄
- **User-Friendly Interface**: A **clean** and **intuitive** interface for seamless user experience. 🖥️
- **Error Handling**: **Robust** error handling to ensure smooth operation. 🛠️
- **Responsive Design**: Fully responsive design for **optimal viewing** on any device. 📱

## Technologies Used 💻

### Backend

- **Node.js**: A JavaScript runtime built on Chrome's V8 JavaScript engine. 🟢
- **Express.js**: A minimal and flexible Node.js web application framework. 🌐
- **Socket.IO**: Enables real-time, bidirectional and event-based communication. 🔄
- **PostgreSQL**: A powerful, open-source object-relational database system. 🗄️
- **Hugging Face API**: State-of-the-art machine learning models for translation. 🤖
- **Render**: A unified cloud to build and run all your apps and websites with free SSL, a global CDN, private networks, and auto deploys from Git. ☁️

### Frontend

- **HTML5**: The standard markup language for creating web pages. 🌐
- **CSS3**: A style sheet language used for describing the presentation of a document. 🎨
- **JavaScript**: A programming language that conforms to the ECMAScript specification. 📜
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development. 🛠️
- **Font Awesome**: A font and icon toolkit based on CSS and LESS. 🌟
- **Vercel**: The platform for frontend developers, providing the speed and reliability innovators need to create at the moment of inspiration. 🚀

## Installation 🛠️

### Backend

1. Clone the backend repository:
   ```bash
   git clone https://github.com/Alemmanuel/backendChatAI.git
   cd backendChatAI
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Set up the environment variables:
   Create a `.env` file in the root directory and add the following:
   ```env
   DB_HOST=localhost
   DB_USER=root
   DB_PASSWORD=Alemmanuel0412
   DB_NAME=chat
   PORT=3000
   HUGGINGFACE_API_TOKEN=your_huggingface_api_token
   ```

4. Initialize the database:
   ```bash
   psql -U your_postgres_user -d chat -f init-db.sql
   ```

5. Start the server:
   ```bash
   npm start
   ```

### Frontend

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Open `index.html` in your preferred web browser.

## Usage 🚀

1. Open the frontend application in your web browser. 🌐
2. Enter your name in the prompt. ✍️
3. Select the source and target languages from the dropdown menus. 🌍
4. Type your message and click "Send". 📤
5. Watch as your message is translated and displayed in **real-time**! 🎉

## Contributing 🤝

We welcome contributions to the **Chat Translator Project**! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request. 🛠️

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements 🙏

- [Hugging Face](https://huggingface.co/) for providing state-of-the-art machine learning models. 🤖
- [Socket.IO](https://socket.io/) for enabling real-time communication. 🔄
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework. 🎨
- [Font Awesome](https://fontawesome.com/) for the icon toolkit. 🌟
- [Render](https://render.com/) for providing a unified cloud to build and run all your apps and websites. ☁️
- [Vercel](https://vercel.com/) for providing the platform for frontend developers. 🚀

## Backend Repository 📂

You can find the backend repository here: [https://github.com/Alemmanuel/backendChatAI](https://github.com/Alemmanuel/backendChatAI)

## Contact 📧

If you have any questions or need further assistance, feel free to contact us at: [alemmanuel0412@gmail.com](mailto:alemmanuel0412@gmail.com)

Thank you for checking out the **Chat Translator Project**! We hope you enjoy using it as much as we enjoyed building it. 🎉
