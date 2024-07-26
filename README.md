const express = require('express'); // 'express' should be in quotes
const app = express(); // Add parentheses to call the function

const port = 18178;

app.get('/', (req, res) => {
    res.send("hello world");
});

app.listen(port, () => {
    console.log(`Server running on port ${port}`);
});

