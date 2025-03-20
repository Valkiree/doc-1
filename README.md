<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>React Demo</title>
  </head>
  <body>
    <div id="root"></div>
  </body>
</html>
import React from 'react';

function App() {
  return <h1>Hello, World!</h1>;
}

export default App;

import React from 'react';
import ReactDOM from 'react-dom';
import App from './App';

ReactDOM.render(<App />, document.getElementById('root'));
