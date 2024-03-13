# React Vite Vitest

This project is a React application bootstrapped with Vite, configured with initial testing setup, path aliasing, and ESLint adjustments.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository:

    ```bash
    git clone [repository_url]
    ```

2. Navigate to the project directory:

    ```bash
    cd react-vite-vitest
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Start the development server:

    ```bash
    npm run dev
    ```

    This command will start the development server. Open [http://localhost:5173](http://localhost:5173) in your browser to view the application.

## Running Tests

To run tests, use the following command:

```bash
npm run test
```

There is no tests created.

## Additional Configurations

ESLint and PropTypes: ESLint is configured to work seamlessly with React projects, and PropTypes validation is disabled to avoid conflicts. These configurations are already set up in the project's ESLint configuration file.

Alias Paths: Alias paths are configured in the vite.config.js file, allowing you to import files from the root of the project without using relative paths.