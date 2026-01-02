# 🎵 musicpedia - Discover Your Music Easily

[![Download musicpedia](https://img.shields.io/badge/Download-musicpedia-blue.svg)](https://github.com/tuman06/musicpedia/releases)

## 🚀 Getting Started

This document will guide you on how to download and run the `musicpedia` application on your local computer for practice. You will find further instructions and code explanations in the **JOBSHEET.md** file after installation.

## 📋 Prerequisites

Make sure your system has the following software installed:

1. **Git**: This is necessary to download code from GitHub.
2. **PHP**: You need version 8.2 or newer.
3. **Composer**: This manages the dependencies for PHP.
4. **Node.js & NPM**: Required to manage and compile front-end assets (JavaScript & CSS).
5. **Local Web Server**: Options include Laragon, XAMPP, or similar software.

## 💾 Download & Install

To get the latest version of `musicpedia`, please visit the Releases page:

[Visit this page to download](https://github.com/tuman06/musicpedia/releases)

## 🛠️ Installation Steps

### 1. Clone the Project from GitHub

Open your terminal or command prompt. Navigate to the directory where you want to store the project. Then run the following command:

```bash
git clone https://github.com/madasepandri/musicpedia.git
```

Once the cloning is complete, enter the newly created project directory with this command:

```bash
cd musicpedia
```

### 2. Install Dependencies

Now, you need to install the project dependencies. Run the following command to do so:

```bash
composer install
```

This command will set up all the necessary PHP packages for `musicpedia` to work properly.

### 3. Install Frontend Dependencies

To manage the front-end assets, navigate to the front-end directory and run:

```bash
npm install
```

This will install all the JavaScript packages needed for the application.

### 4. Build the Frontend Assets

After installing the dependencies, build the frontend assets using:

```bash
npm run build
```

This command prepares the JavaScript and CSS files for use in the application.

### 5. Set Up the Local Web Server

Now, ensure your local web server is running. If you are using Laragon or XAMPP, start the server application.

### 6. Access the Application

Open your web browser and go to:

```
http://localhost/musicpedia/public
```

This URL will let you access the `musicpedia` application. You should see the application interface ready for use.

## 📝 Additional Resources

You can refer to the following files for more information and detailed instructions:

- **JOBSHEET.md**: This file contains explanations about the code and additional instructions.

Feel free to explore all the features `musicpedia` has to offer. Enjoy discovering new music!