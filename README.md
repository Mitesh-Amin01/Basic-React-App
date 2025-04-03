# React App

This is a basic React application demonstrating component creation and importing.

## Installation

To set up the project, follow these steps:

1. Clone the repository:

   ```sh
   git clone https://github.com/Mitesh-Amin01/Basic-React-App.git
   ```

2. Navigate to the project directory:

   ```sh
   cd React-Basic
   ```

3. Install dependencies:

   ```sh
   npm install
   ```

## Running the Application

To start the development server, run:

```sh
npm run start
```

The app will be available at `http://localhost:3000/`.

## Project Structure

```
my-app/
│-- src/
│   │-- home.js
│   │-- App.js
│   │-- index.js
│-- public/
│-- package.json
│-- README.md
```

## Creating a Component

A basic React component example:

```jsx
import React from 'react'

export default function home() {
  return (
    <>
    <h1>Mitesh Amin</h1>
    </>
  )
}
```

## Importing a Component

To use `MyComponent` inside `App.js`:

```jsx
import Home from './home'
function App() {
  return (
    <>
      <div style={{width: "100%", height: "100vh", justifyContent: "center", alignItems: "center", display: 'flex', flexDirection: 'column'}}>
        <h1>Hello I Am Back</h1>
        <Home />
      </div>
    </>
  );
}

export default App;
```

## License

This project is licensed under the Mitesh Amin License.
