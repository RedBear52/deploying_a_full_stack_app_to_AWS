### CI/CD Pipeline Breakdown

1. Setup and Connection: The pipeline is set up and connected with the GitHub repository in CircleCI.
2. Install Dependencies: Orbs are used to install Node.js, the AWS CLI, and the EB CLI.
3. Code Checkout: The pipeline checks out the code from the repository.
4. Front-End & Back-End Installation: Dependencies for both the front-end and back-end applications are installed.
5. Front-End & Back-End Testing: Tests are executed for both the front-end and back-end applications to ensure code quality and functionality.
6. Front-End & Back-End Building: The front-end and back-end code are built, resulting in executable artifacts.
7. Front-End & Back-End Deployment: The built artifacts of the front-end and back-end applications are deployed to the desired environment (e.g., staging or production).