<div align="center">
    <a href="https://microtica.com">
        <img src="https://mk0microtica2di3k2co.kinstacdn.com/wp-content/uploads/2020/04/logo-color-1.svg" alt="microtica" height="60">
    </a>
    <br>
    <br>
    <p>
        <b>Microtica - Build infrastructure and ship applications in the cloud with a single tool</b>
    </p>
    <p>
        <i>Microtica dramatically simplifies cloud setup and brings DevOps automation closer to developers - <a href="https://microtica.com/blog">Subscribe on our Blog</a></i>
    </p>
    <p>
</div>

<br>
<br>

# What is Microtica
Microtica is a DevOps automation platform that enables companies and individuals to adopt cloud much faster.

We do that by standardizing the way you build infrastructure and ship applications in the cloud. With a single tool built by developers for developers.

Some of the benefits:
- You don’t need to integrate dozens of different tools to achieve the same level of automation
- Zero maintenance cost
- No need to write custom integration scripts to be able to interact with the cloud
- Integrated with Kubernetes. From production-ready infrastructure to delivery automation for your applications
- Free and ready to use infrastructure components to setup a complete infrastructure without writing any custom code
- Rich CI/CD functionalities

# Documentation
The developers' documentation is available at https://microtica.com/docs.

# Code of Conduct
Read out [Code of Conduct](https://github.com/microtica-components/mic-cloudformation-hub/blob/master/CODE_OF_CONDUCT.md) before contributing.

# Contributing
Thank you for the interest in [Microtica](https://microtica.com) and taking the time to contribute on this project!

**By contributing on this project you help developers around the world to quickly start building their solutions in the cloud.**

One of the core concepts in Microtica are [infrastructure components](https://microtica.com/docs/components) which allow developers to create and release their cloud infrastructure in a standardized way. Once the component is created, it can be reused in any number of projects and environments.

Microtica provides the following open-source components:
- [Serverless MySql](https://github.com/microtica-components/component-aws-serverless-mysql)
- [AWS EKS](https://github.com/microtica-components/component-aws-eks)
- [AWS Elasticache](https://github.com/microtica-components/component-aws-elasticache)
- [AWS VPC](https://github.com/microtica-components/component-aws-vpc)
- [AWS DynamoDB](https://github.com/microtica-components/component-aws-dynamodb)
- [AWS S3](https://github.com/microtica-components/component-aws-s3)

We are constantly growing the catalogue of open-source components which are also available in Microtica portal to **use for free**.

## How can I contribute?
You can contribute on this project by commiting your CloudFormation templates that represent a reusable cloud infrastructure.

Don't limit yourself, commit any type of infrastructure.

After you submit a pull request, we will review the templates, deploy them on our AWS account and perform all necessery functional and security tests.

Finally, when we accept the pull request, we will publish the component in a separate GitHub repository and make you a contributor. Also we will make it available in the Microtica portal for **free usage**.

## Coding guidelines
CloudFormation templates should follow [AWS CloudFormation best practices](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/best-practices.html).

## Git Flow
We use Github Flow, so all code changes happen through pull requests.

Pull requests are the best way to propose changes to the codebase and get them reviewed by maintainers.
- Fork the repo and create your branch from master branch
- Create a separate folder in the root path for your templates. The name of the folder should start with `component-` (e.g. `component-mongodb`)
- Add tests for each CloudFormation template
- Ensure the test suite passes all the time
- Open a pull request
- Create an issue referencing the pull request. This ensures that we can track the bug being fixed or feature being added easily

# License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) - see the [LICENSE](https://github.com/microtica-components/mic-cloudformation-hub/blob/master/LICENSE) file for details.
