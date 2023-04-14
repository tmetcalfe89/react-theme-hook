# react-theme-hook

Adds a hook to detect whether or not the user is in an environment where dark mode is the preferred system theme.

## Installation

`npm i tmetcalfe89/react-theme-hook`

## Usage

```JavaScript
import useThemeDetector from "react-theme-hook";

function App() {
  const isDarkMode = useThemeDetector();

  return <div>{isDarkMode ? "Dark mode" : "Light mode"}</div>;
}

export default App;
```

## Notes

Taken from [this Medium article](https://medium.com/hypersphere-codes/detecting-system-theme-in-javascript-css-react-f6b961916d48) and tuned up to use modern standards.
