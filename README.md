# Todo List Project

This project is a todo list application built with React, TypeScript, Redux, and XState. User authentication is implemented through Passport.js, enabling login with email and password, as well as with Google and Facebook.

## Features

- User management: registration, login, profile updating, and password recovery.
- Task management: add, complete, delete, and move tasks between collections.
- Task collections management: add, rename, delete, and sort collections.

## Quick Start

To get started with the project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/todo-list-project.git
   ```

2. Install dependencies:

   ```bash
   cd todo-list-project
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

Visit `http://localhost:3000` in your browser to view the application.

## Testing

To run the tests, use the following command:

```bash
npm test
```

## Building the Project

To build the project for production, use the following command:

```bash
npm run build
```

The build files will be saved in the `build` directory.

## Deployment

This project can be deployed on any server capable of serving static files. Make sure to serve the `index.html` file for any not found route to support client-side routing.

## Contributing

This project is open to contributions. Please open an issue or create a pull request if you want to contribute.

## License

This project is licensed under the MIT License.
