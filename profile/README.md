# Welcome to Encircle Marketing

Welcome to the GitHub organization of Encircle Marketing. We primarily work with private repositories; hence, to access 
them, you must be added to the organization.

## Key Repositories

- **API Repository**: This repository serves as the cornerstone for our API development. You can find it [here](https://github.com/Encircle-Marketing/halfords).
- **Python Template Repository**: This repository provides a template for Python projects within our organization. 
  You can find it [here](https://github.com/Encircle-Marketing/python-template).

## Team Organization

We utilize GitHub teams to organize and structure our organization. Teams can be tagged within repositories for pull request reviews, ensuring a streamlined and efficient code review process.

## Versioning and Naming Conventions

- **Semantic Versioning**: We enforce semantic versioning across all repositories to ensure proper version management and compatibility. For more details, refer to [Semantic Versioning](https://semver.org/).
- **Semantic Naming for Pull Requests**: All pull requests must follow semantic naming conventions to maintain consistency and clarity.

## Machine User: EncircleMarketing

We have configured a machine user, named **EncircleMarketing**, for automated tasks and integration purposes.

### Purpose

- **GitHub Automation**: EncircleMarketing is responsible for executing various automation tasks within our GitHub 
  organization, including automated testing, deployment, and continuous integration processes.
- **Private Access**: The machine user has been granted the necessary permissions to access all private 
  repositories. This setup allows our CI/CD pipelines and AWS services to interact efficiently with the codebase without manual intervention.

## Package Management

Our organization uses the GitHub Package Registry to host all private and public packages, including Docker, npm, and Python packages.

### Installing Python Packages

To install our Python packages using SSH, follow these steps:

1. Ensure you have set up SSH keys with your GitHub account. For more information, see [GitHub SSH Key Setup](https://docs.github.com/en/authentication/connecting-to-github-with-ssh).
2. Use the following command to install the package:

    ```sh
    pip install git+ssh://git@github.com:encirle-marketing/[RepositoryName].git
    ```

### Installing Node Packages

To install our Node packages using `.npmrc`, follow these steps:

1. Create or open your `.npmrc` file in your home directory.

2. Add the following lines to your `.npmrc` file:

    ```plaintext
    @EncirleMarketing:registry=https://npm.pkg.github.com
    //npm.pkg.github.com/:_authToken=YOUR_GITHUB_TOKEN
    ```

3. Install the package using npm:

    ```sh
    npm install @EncirleMarketing/[PackageName]
    ```

## Contact

If you have any questions or need further assistance, please contact the senior developer.

Thank you for being a part of Encircle Marketing!