# Dynamic Form

A small React application that demonstrates a controlled, stateful form. Enter a value, see it update live with its current length, and submit it to a list of previously submitted values.

## Why use this project?

This project is a focused example for learning or demonstrating:

- Controlled React inputs with `useState`
- Live input previews and character counting
- Basic validation and user feedback
- Maintaining and rendering a collection of submitted values
- Resetting individual pieces of component state

Submitted values must contain between 3 and 20 characters. Empty or out-of-range values are rejected.

## Getting started

### Prerequisites

- Node.js and npm

### Installation

Clone the repository, enter the project directory, and install dependencies:

```bash
git clone https://github.com/VoidLance/course-files-javascript-react-dynamic-form.git
cd course-files-javascript-react-dynamic-form
npm install
```

### Run the application

Start the development server:

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in a browser. Type a value such as `Hello`, then select **Submit** to add it to the submitted values list.

The controls work as follows:

- **Submit** validates and records the current input.
- **Reset** clears the current input.
- **Reset Output** clears all submitted values.

## Available scripts

Run these commands from the project directory:

| Command | Purpose |
| --- | --- |
| `npm start` | Start the development server with live reload. |
| `npm test` | Run the test suite in watch mode. |
| `npm run build` | Create an optimized production build in `build/`. |
| `npm run eject` | Eject from Create React App configuration. This is irreversible. |

## Project structure

```text
src/
├── App.js          # Application shell
├── DynamicForm.js  # Form state, validation, and rendering
├── App.css         # Application layout styles
└── App.test.js     # Component tests
public/             # Static assets and application metadata
```

## Help and documentation

For questions or problems, [open an issue](https://github.com/VoidLance/course-files-javascript-react-dynamic-form/issues) with reproduction steps and relevant console output. You can also consult the official documentation:

- [React documentation](https://react.dev/)
- [Create React App documentation](https://create-react-app.dev/docs/getting-started/)
- [Testing Library documentation](https://testing-library.com/docs/)

## Maintainer and contributions

This project is maintained by [VoidLance](https://github.com/VoidLance).

Contributions are welcome. Before opening a pull request:

1. Create a focused branch for your change.
2. Make the smallest change that addresses the issue.
3. Run `npm test` and `npm run build`.
4. Describe the change and test results in the pull request.

For larger changes, open an issue first to discuss the proposed approach.
