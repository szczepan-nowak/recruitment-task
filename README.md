# JavaScript Recruitment Task

## Add Numbers

**Estimated time:** 15–20 minutes

Implement the existing `add` function so that the
provided test passes.

The function should add two numbers and return the result.

## Setup

Clone the repository and install its dependencies:

```bash
git clone https://github.com/szczepan-nowak/recruitment-task.git
cd recruitment-task
npm install
```

## Task

Open the existing implementation file:

```text
foundations/data_types_and_conditionals/02_addNumbers/addNumbers.js
```

Implement the existing exported `add` function.

Do not create a new task or replace the existing test.

## Requirements

The function must:

- Accept two numbers.
- Return the sum of the two numbers.
- Correctly handle positive numbers.
- Correctly handle negative numbers.
- Correctly handle zero.
- Correctly handle decimal numbers.
- Not print the result to the console.
- Return the result instead of modifying external state.

## Run the Test

The test must be run while your terminal is inside the exercise's test
directory.

First, navigate to the exercise directory:

```bash
cd foundations/data_types_and_conditionals/02_addNumbers
```

Confirm that the current directory contains the exercise files:

```bash
ls
```

You should see files including:

```text
addNumbers.js
addNumbers.spec.js
README.md
```

Run only the existing Add Numbers test:

```bash
npm test addNumbers.spec.js
```

Do not run the test command from the repository root.

The task is complete when all tests in `addNumbers.spec.js` pass.

## Rules

- Modify only `addNumbers.js`.
- Do not modify, remove, or skip tests.
- Do not install additional dependencies.
- Do not look at the solution file.
- Do not change the exported function name.
- Do not change the function signature.
- No other Odin Project exercises are required.

## Evaluation

The solution will be evaluated on:

- Correct addition of two numbers.
- Handling of positive and negative values.
- Handling of zero.
- Handling of decimal values.
- Returning the result correctly.
- Keeping the change focused and readable.
