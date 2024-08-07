# Study-Assistant: Create-Multi-Choice-Questions-from-a-Lecture

## Overview

### Amazon Bedrock: Overview and Study Assistant for Creating Multiple-Choice Questions from a Lecture

**Amazon Bedrock** is an advanced AI service designed to help users build and scale generative AI applications efficiently. It provides access to foundational models from top AI providers, enabling users to choose the best models suited to their needs. With seamless integration into other AWS services, Amazon Bedrock enhances businesses' capabilities to deploy robust AI solutions quickly and effectively.

**Study Assistant: Create Multi-Choice Questions from a Lecture**

The Study Assistant feature of Amazon Bedrock leverages its powerful generative AI capabilities to help educators and students create multiple-choice questions from lecture content. This tool transforms traditional study methods by automating the creation of high-quality, relevant questions that enhance learning and retention.

### Features

1. **Lecture Content Input:**
   - Upload lecture notes, transcripts, or audio recordings into Amazon Bedrock.
   - The system processes the input using advanced natural language understanding (NLU) techniques.

2. **Content Analysis:**
   - Amazon Bedrock analyzes the lecture content, identifying key topics, concepts, and important details.
   - Uses state-of-the-art machine learning algorithms to understand the context and significance of the information.

3. **Question Generation:**
   - Generates multiple-choice questions based on the analyzed content covering the essential points of the lecture.
   - Questions are designed to test comprehension, recall, and critical thinking skills.
   - Each question comes with multiple answer options, including one correct answer and several distractors.

4. **Customization and Review:**
   - Educators and students can review and customize the generated questions.
   - Adjust the difficulty level, phrasing, and focus of the questions to better suit the target audience.

5. **Output and Integration:**
   - Export finalized questions in various formats (PDFs, spreadsheets) or integrate them directly into learning management systems (LMS).
   - Supports seamless integration with popular educational platforms for easy distribution and use.

### Benefits

- **Efficiency:** Automates the time-consuming process of question creation, allowing educators to focus on teaching.
- **Quality:** Ensures that the questions are relevant, accurate, and aligned with the lecture content.
- **Adaptability:** Customizable to fit different educational needs and levels of difficulty.
- **Scalability:** Supports large volumes of content, suitable for both individual educators and large institutions.

Amazon Bedrock’s Study Assistant revolutionizes educational practices by blending AI innovation with practical teaching needs. It enhances the learning experience and supports educators in delivering high-quality education efficiently.

- [Amazon Bedrock](https://aws.amazon.com/bedrock/)
- [Claude 3](https://www.anthropic.com/news/claude-3-family)

### To View Demo and Sample Data:
- Access the `demo` folder for demo videos.
- Access the `samples` folder for sample data.

## Setup Instructions

### Prerequisites

- Install [Python](https://docs.python-guide.org/starting/install3/linux/)
- Set up a [Python Environment](https://docs.python-guide.org/starting/install3/env/)
- Install [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-quickstart.html)

### Steps

1. Clone the repository:
    ```sh
    git clone https://github.com/awsstudygroup/Create-Multi-Choice-Questions-from-a-Lecture
    ```

2. Navigate to the project directory:
    ```sh
    cd Create-Multi-Choice-Questions-from-a-Lecture
    ```

3. Install the required Python packages:
    ```sh
    pip3 install -r requirements.txt
    ```

4. Run the application using Streamlit:
    ```sh
    streamlit run Home.py --server.port 8080
    ```

## Architecture

![Architecture](./Architecture.png)

## Learn More about Prompts and Claude 3

- [Introduction to Prompt Design](https://docs.anthropic.com/claude/docs/introduction-to-prompt-design)
- [Model Card](https://www-cdn.anthropic.com/de8ba9b01c9ab7cbabf5c33b80b7bbc618857627/Model_Card_Claude_3.pdf)
