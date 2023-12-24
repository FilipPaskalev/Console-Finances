# Console-Finances

The repository contains an assignment (to build financial analysts console application) and is part of the University of Birmingham Skills BootCamp in Front-End Web Development &amp; UX 2023.

## Overview

Task is to creating code for analyzing the financial records of a company. You have been provided with a financial dataset in the `starter/index.js` file.

## Instructions

1. Create a new GitHub repo called `Console-Finances`. Then, clone it to your computer.

2. Copy the starter files in your local git repository.

You have been given a dataset composed of arrays with two fields, Date and Profit/Losses.

Your task is to write JavaScript code that analyzes the records to calculate each of the following:

* The total number of months included in the dataset.

* The net total amount of Profit/Losses over the entire period.

* The average of the **changes** in Profit/Losses over the entire period.
  * You will need to track what the total change in Profit/Losses are from month to month and then find the average.
  * (`Total/(Number of months - 1)`)

* The greatest increase in Profit/Losses (date and difference in the amounts) over the entire period.

* The greatest decrease in Profit/Losses (date and difference in the amounts) over the entire period.

When you open your code in the browser your resulting analysis should look similar to the following:

  ```text
  Financial Analysis 
  ----------------
  Total Months: 86
  Total: $38382578
  Average Change: -2315.12
  Greatest Increase in Profits/Losses: Feb-2012 ($1926159)
  Greatest Decrease in Profits/Losses: Sep-2013 ($-2196167)
  ```

Your final code should print the analysis to the console.

## Technical Acceptance Criteria:

* Satisfies all of the above acceptance criteria.

### Deployment:

* Application deployed at live URL.

* Application loads with no errors.

* Application GitHub URL submitted.

* GitHub repository contains application code.

### Repository Quality:

* Repository has a unique name.

* Repository follows best practices for file structure and naming conventions.

* Repository follows best practices for variable naming conventions, indentation, quality comments, etc.

* Repository contains multiple descriptive commit messages.

* Repository contains quality README file with description, screenshot, and link to deployed application.

### Application Quality:

* Application resembles the mock-up functionality provided in the Challenge instructions.

## Installation

### Option 1 - Download

<!-- To set correct link to project -->
1. Download the project from [GitHub repository](https://github.com/FilipPaskalev/Console-Finances) on your local machine.
2. Unzip the project.
3. Open project with VS Code or other IDE.

### Option 2 - Clone project from [GitHuB](https://github.com/)

```git clone https://github.com/FilipPaskalev/Console-Finances.git```

## Demo

### Live demo

<!-- To set correct link to project -->
You can find deployed version of the project on [Here](https://filippaskalev.github.io/Console-Finances/).

## License

MIT License

Copyright (c) 2023 Filip

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Copyright

© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.