# WhatsApp Msgstore Web Viewer

A modern, high-performance web viewer for unencrypted WhatsApp `msgstore.db` files. Built with **React**, **Vite**, and **SQL.js**.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Open%20App-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://trevordixon.github.io/whatsapp-msgstore-web-viewer/)

Download the sample msgstore.db from this repository to test.

## 🔒 Privacy First

**Your data never leaves your computer.** 

This application runs entirely in your browser. The database file is processed locally using WebAssembly (SQL.js). No data is uploaded to any server, ensuring your conversations remain private.

## ✨ Features

*   **Modern UI:** A clean interface inspired by WhatsApp Web.
*   **Fast & Local:** instant loading and querying of SQLite databases directly in the browser.
*   **Search:** Filter conversations by contact name or phone number.
*   **Date Grouping:** Messages are intuitively grouped by "Today", "Yesterday", and specific dates.
*   **Responsive:** Works on desktop and mobile.

## 🚀 How to Use

1.  **Obtain your database:** You need an *unencrypted* `msgstore.db` file.
    *   *Note: Standard backups found in Android/WhatsApp/Databases are usually encrypted (e.g., `msgstore.db.crypt14`). This viewer currently only supports unencrypted SQLite files.*
2.  **Open the App:** Go to the [Live Demo](https://trevordixon.github.io/whatsapp-msgstore-web-viewer/).
3.  **Upload:** Click the upload box and select your `.db` file.
4.  **Browse:** Select a chat from the sidebar to view history.

## 📸 Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/a2f878a2-e34d-47da-8a34-54f9b48b073a" alt="Landing Page" width="45%">
  &nbsp; &nbsp;
  <img src="https://github.com/user-attachments/assets/685b372c-985e-4e68-8063-3cd5d465dd2b" alt="Chat View" width="45%">
</p>

## 🛠️ Running Locally

Pull requests are welcome! If you want to contribute or run this on your own machine:

1.  **Clone the repository**
    ```bash
    git clone https://github.com/trevordixon/whatsapp-msgstore-web-viewer.git
    cd whatsapp-msgstore-web-viewer
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Start the dev server**
    ```bash
    npm run dev
    ```

4.  **Build for production**
    ```bash
    npm run build
    ```

## 📄 License

Open source. Feel free to fork and improve!
