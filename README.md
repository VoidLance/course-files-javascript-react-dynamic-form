# Dynamic Form

A small React application that demonstrates a controlled, interactive form. Users can type a value, see it update live, validate it on submission, and keep a list of values submitted during the current session.

## Why use this project?

This project is a focused example for learning React state and event handling:

- Controlled text input managed with `useState`
- Live display of the current value and its character count
- Submission validation for required input and a 3–20 character length
- A session-only list of submitted values
- Separate controls for clearing the current input and submitted values
- Create React App tooling for local development, testing, and production builds

## Getting started

### Prerequisites

- Node.js and npm

### Installation

1. Clone the repository and enter the project directory:

   ```bash
   git clone https://github.com/VoidLance/course-files-javascript-react-dynamic-form.git
   cd course-files-javascript-react-dynamic-form
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

   Open [http://localhost:3000](http://localhost:3000) in a browser. The app reloads automatically as source files change.

## Using the form

Type a value in the input and select **Submit**. Values must contain 3–20 characters and cannot be blank. Valid submissions appear under **Submitted Values** and the input is cleared.

```text
Input: "React"
Result: React is added to the submitted values list
```

- **Reset** clears the current input.
- **Reset Output** clears all submitted values.
- **Current Input** and **Input Length** update as you type.

The main form implementation is in [`src/DynamicForm.js`](src/DynamicForm.js), and it is rendered by [`src/App.js`](src/App.js).

## Available commands

Run commands from the project directory:

| Command | Description |
| --- | --- |
| `npm start` | Start the development server. |
| `npm test` | Run the test suite in watch mode. |
| `npm run build` | Create an optimized production build in `build/`. |
| `npm run eject` | Copy Create React App configuration into the project. This is irreversible and usually unnecessary. |

## Project structure

```text
src/
├── App.js              # Application shell
├── DynamicForm.js      # Form state, validation, and rendering
├── App.css              # Component styles
├── index.css            # Global styles
└── App.test.js         # App test
public/                 # Static assets and HTML entry point
```

## Help and documentation

For project-specific questions or bug reports, [open an issue](https://github.com/VoidLance/course-files-javascript-react-dynamic-form/issues).

Useful references:

- [React documentation](https://react.dev/)
- [Create React App documentation](https://create-react-app.dev/docs/getting-started/)
- [npm documentation](https://docs.npmjs.com/)

## Contributing

The project is maintained by [VoidLance](https://github.com/VoidLance). Contributions are welcome:

1. Open an issue to describe a bug or proposed improvement.
2. Create a focused branch and make the smallest change that addresses it.
3. Run the relevant tests and production build before opening a pull request.
4. Include a clear description of the behavior changed and how it was verified.

## License

This project does not currently include a license file. Contact the maintainer before redistributing it.
