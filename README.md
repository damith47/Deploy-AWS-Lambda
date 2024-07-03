# serverless

This YAML script automates the deployment of a serverless application using Serverless Framework when changes are pushed to the `stage`, `dev`, or `test` branches in GitHub. It sets up Node.js, installs dependencies, configures AWS credentials securely via GitHub Secrets, and deploys the application using Serverless Framework. This ensures consistent and automated deployment of the serverless application on AWS Lambda and related services in the `us-east-1` region.
