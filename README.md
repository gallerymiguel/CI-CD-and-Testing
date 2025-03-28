
# Python Quiz CI/CD Pipeline with GitHub Actions and Render

## Description
This project demonstrates a continuous integration and continuous deployment (CI/CD) pipeline using GitHub Actions and Render. It includes automated Cypress tests that run on pull requests to the `develop` branch and automatic deployment to Render when changes are merged to the `main` branch.

## Features
- **CI/CD Pipeline**: Automates testing and deployment, ensuring high code quality and seamless integration.
- **Automated Tests**: Integrates Cypress tests to validate all new features and fixes.
- **Deployment**: Uses Render for hosting, showcasing real-world application deployment.

## Technologies Used
- **Cypress**: For writing and executing end-to-end tests.
- **GitHub Actions**: For automating tests and deployment.
- **Render**: As the deployment platform.
- **CircleCi**: More testing and deploying.
- [Other technologies used in the project, e.g., React, Node.js, etc.]

## Getting Started

### Prerequisites
- Node.js [version]
- npm
- Any other specific dependencies or global installations.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gallerymiguel/CI-CD-and-Testing
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up local environment variables needed.

### Running Locally
To run the application locally:
```bash
npm start
```

### Running Tests
To execute tests using Cypress:
```bash
npm run test
```

## CI/CD Pipeline

### GitHub Actions
- **Test Workflow**: Runs on pull requests to `develop`. Validates all changes by running Cypress tests.
- **Deployment Workflow**: Triggers on merge to `main`. Automatically deploys the application to Render.

### Render Deployment
- **URL**: [https://film-tracker-ci-cd-and-testing.onrender.com/](https://film-tracker-ci-cd-and-testing.onrender.com)
- Deployment is triggered via GitHub Actions upon code merge.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)

