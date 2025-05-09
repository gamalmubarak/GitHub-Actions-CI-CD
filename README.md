# GitHub Actions CI/CD Setup [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This project is a full-stack application for a tech quiz. It includes a React-based frontend and an Express-based backend, with MongoDB as the database. The application is integrated with a CI/CD pipeline using GitHub Actions to ensure quality and automate deployment to Render.


---

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Technologies Used](#Technologies-Used)
- [CI/CD Pipeline](#CI/CD-Pipeline)
- [Application Demo](#Application-Demo)
- [License](#license)
- [Contribution Guidelines](#contribution-guidelines)
- [Questions](#questions)


---

## Technologies Used

- **Frontend**: React, Vite, Bootstrap
- **Backend**: Express, MongoDB, Mongoose
- **Testing**: Cypress
- **CI/CD**: GitHub Actions
- **Deployment**: Render

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Install dependencies:
   ```bash
   npm run install
   ```

3. Seed the database:
   ```bash
   npm run seed
   ```

4. Start the development server:
   ```bash
   npm run develop
   ```

---

## CI/CD Pipeline

### Testing Workflow

- Triggered on pull requests to the `develop` branch.
- Runs Cypress component tests to ensure code quality.

### Deployment Workflow

- Triggered on pull requests merged into the `main` branch.
- Deploys the application to Render using a deploy hook.


---

## Application Demo

The application is deployed on Render. You can access it at:(https://github-actions-ci-cd-gfyd.onrender.com/)

see this screenshots of the app:
(https://1drv.ms/i/c/3b216777a5c674e6/EWUgPECsID1PliBDBuqdIQkBA115mceRKuTRGh52W42wxA?e=oi0rUa)
(https://1drv.ms/i/c/3b216777a5c674e6/EciyuFvnN1BKtl8vHH3ENmoBxn5yyvRNq6z_zX4WTo-TLw?e=YaRlRw)
(https://1drv.ms/i/c/3b216777a5c674e6/EZAD4n9peMZPrARFTyL_-K4BTVYjL5eBi0RY8kWUKt0Jvw?e=i5ckW2)
 
---

## License 
Project license: MIT

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## Contribution Guidelines

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so.

---

## Test Instructions

Tests will be added in the future.

---

## Questions
If you have any questions, please feel free to contact me at gamalmubarak87@gmail.com. You can also find more of my work at [gamalmubarak](https://github.com/gamalmubarak).