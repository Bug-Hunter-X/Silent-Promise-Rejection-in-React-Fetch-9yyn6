This repository demonstrates a common but subtle bug in React applications involving unhandled promise rejections.  The `bug.js` file showcases code with a missing `.catch()` block in a `fetch` call.  This can lead to errors not being displayed to the user, making debugging difficult.  The `bugSolution.js` file provides the corrected code with proper error handling.