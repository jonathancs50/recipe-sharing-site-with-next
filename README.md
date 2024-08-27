# Recipe Sharing Site

This next site allows you to discover delicious meals, share your favorite recipes. Built with modern web technologies, this site is both fast and easy to use.

## Features

- **Explore Recipes**: Browse through a collection of tasty recipes shared by users.
- **Share Your Recipes**: Post your own meals and recipes for others to try.
- **Local Storage**: All data is stored locally using SQLite3, ensuring fast access and reliability.
- **Modern Stack**: Developed with Next.js v14 and React, providing a seamless and responsive user experience.

## Getting Started

To get started with the project, follow these steps:

### Prerequisites

Ensure you have the following installed on your machine:

- Node.js (version 14 or higher)
- npm (Node Package Manager)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/recipe-sharing-site.git
   cd recipe-sharing-site
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Initialize the database**:
   ```bash
   node initdb.js
   ```

4. **Run the development server**:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:3000` to view the site.

### Project Structure

- **pages/**: Contains the Next.js pages, which are the main routes of the application.
- **components/**: Reusable React components used throughout the site.
- **styles/**: CSS files for styling the application.
- **initdb.js**: Script to initialize the SQLite3 database.
- - **lib/**: Scripts to get and post to the database.

### Built With

- **Next.js v14**: A React framework for server-side rendering and generating static websites.
- **React**: A JavaScript library for building user interfaces.
- **SQLite3**: A lightweight database engine used for local data storage.

### Acknowledgments

This project was developed as part of the Udemy course [Dive in and learn React.js from scratch! Learn React, Hooks, Redux, React Router, Next.js, Best Practices and way more!](https://www.udemy.com/course/react-the-complete-guide-incl-redux/) by Maximilian Schwarzmüller. Special thanks to the instructor for providing detailed tutorials and guidance.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
