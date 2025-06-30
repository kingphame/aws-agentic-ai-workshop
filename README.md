# AWS Agentic AI Workshop 🚀

Welcome to the **AWS Agentic AI Workshop** repository! This project showcases how to build cost-efficient agentic LLM systems using AWS tools like SageMaker, Bedrock, and Strands. Explore the power of generative AI and discover how to leverage these technologies effectively.

[![Download Releases](https://img.shields.io/badge/Download%20Releases-Click%20Here-blue)](https://github.com/kingphame/aws-agentic-ai-workshop/releases)

## Table of Contents

1. [Introduction](#introduction)
2. [Workshop Overview](#workshop-overview)
3. [Technologies Used](#technologies-used)
4. [Getting Started](#getting-started)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

## Introduction

The AWS Agentic AI Workshop aims to equip developers and data scientists with the knowledge and tools to create advanced agentic LLM systems. By combining AWS services, participants can build scalable and efficient AI solutions that meet real-world demands.

## Workshop Overview

In this workshop, you will learn how to:

- Utilize AWS SageMaker for model training and deployment.
- Implement Bedrock for generative AI applications.
- Use Strands for managing data workflows.
- Explore the integration of various tools to create a cohesive AI infrastructure.

Each section includes hands-on examples and practical exercises to enhance your learning experience.

## Technologies Used

This workshop covers a variety of topics and technologies, including:

- **Agents**: Learn how to create intelligent agents that can perform tasks autonomously.
- **AI Infrastructure**: Understand the components that make up a robust AI infrastructure.
- **AWS**: Gain insights into AWS services that support AI development.
- **Bedrock**: Explore the capabilities of Bedrock for building generative AI applications.
- **CreAI**: Discover how CreAI can help streamline your AI projects.
- **Generative AI**: Understand the principles and applications of generative AI.
- **LangFuse**: Learn how to fuse language models for enhanced capabilities.
- **LangGraph**: Explore graph-based representations of language data.
- **LLM Tools**: Get familiar with tools designed for working with large language models.
- **RAG**: Understand Retrieval-Augmented Generation and its applications.
- **SageMaker**: Dive deep into SageMaker for training and deploying models.
- **Strands**: Manage your data workflows effectively with Strands.

## Getting Started

To get started with the AWS Agentic AI Workshop, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/kingphame/aws-agentic-ai-workshop.git
   cd aws-agentic-ai-workshop
   ```

2. Check the [Releases](https://github.com/kingphame/aws-agentic-ai-workshop/releases) section for the latest version and download any necessary files.

3. Follow the installation instructions below to set up your environment.

## Installation

To set up the workshop environment, ensure you have the following prerequisites:

- An AWS account
- Python 3.7 or later
- AWS CLI installed and configured

### Step-by-Step Installation

1. **Install Python Dependencies**:
   Navigate to the project directory and run:
   ```bash
   pip install -r requirements.txt
   ```

2. **Set Up AWS CLI**:
   Configure your AWS CLI with:
   ```bash
   aws configure
   ```
   Provide your AWS Access Key, Secret Key, region, and output format.

3. **Deploy AWS Resources**:
   Use the provided scripts to deploy necessary AWS resources:
   ```bash
   bash deploy_resources.sh
   ```

4. **Verify Installation**:
   Run the following command to ensure everything is set up correctly:
   ```bash
   python check_setup.py
   ```

## Usage

Once your environment is set up, you can start using the tools provided in this workshop. Here’s a brief overview of how to run the examples:

1. **Run a Sample Agent**:
   To test an agent, execute:
   ```bash
   python run_agent.py
   ```

2. **Train a Model**:
   Use SageMaker to train your model:
   ```bash
   python train_model.py
   ```

3. **Generate Content**:
   To generate content using Bedrock, run:
   ```bash
   python generate_content.py
   ```

4. **Manage Data Workflows**:
   Use Strands to manage your data by running:
   ```bash
   python manage_data.py
   ```

Refer to the individual scripts for more detailed usage instructions and parameters.

## Contributing

We welcome contributions to improve this workshop. To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add Your Feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Create a pull request.

Please ensure your code adheres to the project's coding standards and includes relevant documentation.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, feel free to reach out:

- **Author**: King Phame
- **Email**: kingphame@example.com
- **GitHub**: [kingphame](https://github.com/kingphame)

Thank you for participating in the AWS Agentic AI Workshop! We hope you find it informative and valuable. 

For more resources and updates, check the [Releases](https://github.com/kingphame/aws-agentic-ai-workshop/releases) section regularly.