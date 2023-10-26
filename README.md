# Test with Jest

Welcome to the "test-with-jest" project! This is a simple project that demonstrates the basics of unit testing with Jest. If you're new to unit testing or just getting started with Jest, this project serves as an excellent introduction.

## Getting Started

To run the tests for this project, you'll need to have Node.js and npm (Node Package Manager) installed. If you haven't already installed them, you can download and install them from [nodejs.org](https://nodejs.org/).

Once you have Node.js and npm set up, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/test-with-jest.git
   ```

2. Change to the project directory:

   ```bash
   cd test-with-jest
   ```

3. Install the project dependencies using npm:

   ```bash
   npm install
   ```

4. Run the tests with the following command:

   ```bash
   npm test
   ```

## Project Structure

The project structure is quite simple. Here's a quick overview:

- `add-five.js`: This file contains a simple function, `addFive`, which takes a number and returns that number plus 5.

- `index.test.js`: This is the test file for the `addFive` function. It includes a single test case that ensures the function behaves as expected.

- `package.json`: The project's package file lists the dependencies and scripts. In this case, it includes Jest as a development dependency and a "test" script that runs Jest.

## Example Test

Here's an example of the test in `index.test.js`:

```javascript
const addFive = require('./add-five');

test('returns the number plus 5', () => {
    expect(addFive(1)).toBe(6);
});
```

This test checks if the `addFive` function correctly adds 5 to the input value and returns the expected result.

## About the Course

This project is based on the course "Advanced React," which covers various advanced React concepts and features. While this project is relatively simple, it serves as a starting point for understanding unit testing with Jest and can be a helpful companion to the course.

Access the course **[here](https://www.coursera.org/learn/advanced-react/home/info)**.
