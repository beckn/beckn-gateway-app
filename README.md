## Project Introduction

Beckn Gateway application
This is  skeletal [succinct](https://github.com/venkatramanm/swf-all) application. that uses the plugin 
[beckn-gateway](https://github.com/venkatramanm/beckn-gateway). 


## Release Notes

| Version | Release Date |
|---------|--------------|
| 1.0     | 2024-02-02   |


## Installation/Setup Guide 
You need to Clone and build the following repositories (using mvn install in each of the directories) in sequence
1. [Common](https://github.com/venkatramanm/common) 
2. [Beckn SDK for Java](https://github.com/venkatramanm/beckn-sdk-java) 
3. [Succinct Web Framework](https://github.com/venkatramanm/swf-all)
4. [Beckn plugin for Succinct](https://github.com/venkatramanm/swf-plugin-beckn)
5. [Beckn gateway plugin](https://github.com/venkatramanm/beckn-gateway). 


Then clone [this repo you are reading ](https://github.com/venkatramanm/beckn-gateway-app); 

1. Go into the cloned folder. 
    cd beckn-gateway-app

2. Copy sample overrideProperties.sample to overrideProperties;
    cp -R overrideProperties.sample overrideProperties 

3. Locate swf.propeties file in overrideProperties and edit the section pertaining to "Beckn Gateway configurations". 

4. from the base directory for beckn-gateway-app , run bin/swfstart 


*Your gateway will be up.  check logs in tmp/ folder to see if there are any issues and resolve them*


## User Guide


## Link to Experience Center

[Beckn gateway](https://gateway.becknprotocol.io/login)


## Contributing guidelines

1. Fork the repository in your repository.
2. Clone the forked repository to your local machine.
3. Create a new branch for your contribution: `git checkout -b feature/your-feature-name`
4. Make your changes and commit them: `git commit -m "Your commit message"`
5. Push to the branch: `git push origin feature/your-feature-name`
6. Submit a pull request to the main repository.

### Code Style and Standards

- Follow the coding style and standards used in the project.
- Use meaningful variable and function names.
- Write clear and concise comments when necessary.
- Ensure your code is well-documented.

### Testing

- Ensure your changes pass all existing tests.
- Write additional tests if necessary to cover your changes.
- Run the test suite before submitting a pull request.

### Reporting Bugs

If you find a bug, please report it by opening an issue on GitHub. Include as much detail as possible, such as the steps to reproduce the bug and your environment details.

### Feature Requests

If you have an idea for a new feature or improvement, feel free to open an issue to discuss it. Provide a clear description of the feature and why it would be beneficial.

### Pull Request Guidelines

- Provide a clear and descriptive title for your pull request.
- Include a detailed description of the changes you've made.
- Reference any related issues in your pull request.
- Ensure your code is properly tested.
  
