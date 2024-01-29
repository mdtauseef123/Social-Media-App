# Snapgram Social App
Snapgram is a full-stack social networking application built to connect users through shared images. With Snapgram, users can discover, share, and engage with captivating visual content in a vibrant community.

# Features
- User Authentication: Secure authentication system using Appwrite for user authentication, allowing users to sign up, log in, and manage their accounts securely.
- CRUD Operations: Create, Read, Update, and Delete operations for posts, enabling users to share and manage their images effortlessly. Appwrite is also utilized for database management.
- Sharing and Liking: Share images with friends and followers, and engage with the community by liking posts.
- Infinite Scroll: Seamlessly browse through images with the infinite scroll feature, providing a smooth and uninterrupted user experience.
- UI Components: Utilizes shadcn/ui for building UI components, ensuring consistency and ease of development.
- Styling: Styling is done using Tailwind CSS, offering a utility-first approach for rapid development and customization.

# Tech Stack
- Frontend: React.js for building dynamic user interfaces.
- Backend: Node.js and Express.js for server-side logic and RESTful API development.
- Database & Authentication: Appwrite for user authentication and database management.
- UI Components: shadcn/ui for building UI components.
- Styling: Tailwind CSS for styling components and layouts.
  
# Getting Started
To get started with Snapgram locally, follow these steps:

1. Clone the repository:
'git clone https://github.com/yourusername/Snapgram.git'
2. Navigate to the project directory:
'cd Snapgram'
3. Install dependencies:
'npm install'
4. Start the development server:
'npm run dev'
Visit http://localhost:3000 in your browser to use Snapgram locally.

# Contributing
Contributions are welcome! If you have any ideas for improvements or new features, feel free to open an issue or submit a pull request.

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
