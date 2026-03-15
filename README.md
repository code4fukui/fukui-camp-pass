# fukui-camp-pass

A web application that allows users to explore and learn about various municipal areas in Fukui Prefecture, Japan through a quiz-like experience.

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

## Demo
The application is deployed at: https://takameron-fukui-camp-pass.deno.dev

## Features
- Interactive map of Fukui Prefecture
- Quiz-style questions to test user knowledge about the municipalities
- Randomized question order and choices
- Immediate feedback on correct/incorrect answers
- Option to retry the quiz

## Requirements
This project is built using Deno, a modern, secure, and fast runtime for JavaScript and TypeScript. To run the project, you will need to have Deno installed on your system.

## Usage
1. Clone the repository:
```
git clone https://github.com/your-username/fukui-camp-pass.git
```
2. Change into the project directory:
```
cd fukui-camp-pass
```
3. Start the server:
```
deno run --allow-net --allow-read --watch serve.ts
```
4. Open your web browser and navigate to `http://localhost:8000` to access the application.

## Data / API
The application uses local data files to generate the quiz questions and display the map. The data files are located in the `assets/data` directory.

## License
This project is licensed under the [MIT License](LICENSE).