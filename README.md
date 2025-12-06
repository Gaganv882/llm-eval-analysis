# LLM Eval Analysis 🚀

![GitHub Release](https://img.shields.io/badge/Release-v1.0-blue)

Welcome to the **LLM Eval Analysis** repository! This project focuses on the automatic multi-metric evaluation of human-bot dialogues using large language models (LLMs) like Claude and GPT-4o. It aims to provide insights into chatbot performance across various datasets and settings. This project is part of the Artificial Intelligence course at the University of Salerno.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Metrics](#metrics)
- [Datasets](#datasets)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Releases](#releases)

## Features 🌟

- **Multi-Metric Evaluation**: Evaluate dialogues based on various metrics to ensure a comprehensive assessment.
- **Multiple LLM Support**: Utilize different large language models for analysis, including Claude and GPT-4o.
- **Dataset Compatibility**: Work with multiple datasets to test and validate chatbot performance.
- **User-Friendly Interface**: Designed for ease of use, making it accessible for both students and researchers.
- **Detailed Reporting**: Generate detailed reports on chatbot performance to facilitate improvements.

## Getting Started 🛠️

To get started with the LLM Eval Analysis, follow these steps:

1. **Clone the Repository**: Use the following command to clone the repository to your local machine:

   ```bash
   git clone https://github.com/Gaganv882/llm-eval-analysis.git
   ```

2. **Install Dependencies**: Navigate to the project directory and install the required packages:

   ```bash
   cd llm-eval-analysis
   pip install -r requirements.txt
   ```

3. **Download the Latest Release**: Visit our [Releases section](https://github.com/Gaganv882/llm-eval-analysis/releases) to download the latest version. Make sure to execute the necessary files as instructed in the release notes.

## Usage 📊

To evaluate dialogues, you can use the following command:

```bash
python evaluate.py --input your_dialogue_file.json --model gpt-4o
```

Replace `your_dialogue_file.json` with the path to your dialogue data. You can choose between different models by adjusting the `--model` parameter.

### Example

Here’s a simple example of how to structure your input file:

```json
[
    {
        "user": "Hello, how are you?",
        "bot": "I'm fine, thank you! How can I assist you today?"
    },
    {
        "user": "What is the weather like?",
        "bot": "It's sunny and warm today!"
    }
]
```

### Output

The evaluation will generate a report detailing the performance metrics of the chatbot based on the provided dialogues.

## Metrics 📈

The evaluation includes several key metrics:

- **Response Accuracy**: Measures how accurately the bot responds to user queries.
- **Engagement Score**: Assesses how engaging the conversation is.
- **Sentiment Analysis**: Evaluates the sentiment of both user and bot responses.
- **Turn-Taking Efficiency**: Analyzes how well the conversation flows.

These metrics provide a comprehensive view of chatbot performance, allowing for targeted improvements.

## Datasets 📚

This project supports multiple datasets for evaluation. You can find datasets in the `datasets` folder. Feel free to add your own datasets as needed.

### Example Datasets

- **Conversational Dataset**: A collection of dialogues between users and bots.
- **Customer Support Dataset**: Simulated customer interactions for support scenarios.
- **General Chat Dataset**: A mix of casual conversations to evaluate engagement.

## Contributing 🤝

We welcome contributions to improve the LLM Eval Analysis project. If you would like to contribute, please follow these steps:

1. **Fork the Repository**: Click on the "Fork" button in the top right corner.
2. **Create a New Branch**: Create a new branch for your feature or fix.

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Changes**: Implement your changes and commit them.

   ```bash
   git commit -m "Add your message here"
   ```

4. **Push Changes**: Push your changes to your forked repository.

   ```bash
   git push origin feature/your-feature-name
   ```

5. **Open a Pull Request**: Go to the original repository and open a pull request.

We appreciate your contributions and feedback!

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact 📧

For questions or suggestions, feel free to reach out:

- **Author**: Gagan V
- **Email**: gagan@example.com
- **LinkedIn**: [Gagan's LinkedIn](https://www.linkedin.com/in/gagan)

## Releases 📦

To stay updated with the latest features and improvements, visit our [Releases section](https://github.com/Gaganv882/llm-eval-analysis/releases). Here, you can download the latest files and follow the release notes for guidance on execution.

## Conclusion 🎉

Thank you for exploring the LLM Eval Analysis project. We hope it serves as a valuable tool for evaluating human-bot dialogues. Your feedback and contributions are essential for making this project even better. Happy coding!