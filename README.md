![image](https://github.com/ahmadalis2016/Iridium-AI-Image-Analysis/assets/130319416/3590b637-b72a-4a41-86ba-a556e9c22016)

# Iridium AI: AWS Bedrock


## Overview
This project leverages the AWS Bedrock platform to generate text using a Generative AI model. The script llama2.py interacts with the Bedrock runtime to invoke the Generative AI model and generate text based on a given prompt.

## Prerequisites
Before running the script, ensure that you have the following prerequisites:

Python installed on your machine.
AWS credentials configured with necessary permissions to access the Bedrock service.
Boto3 library installed (pip install boto3).
## Usage
Open the llama2.py script in a Python environment.
Modify the prompt_data variable with your desired prompt. For example, you can provide a prompt to generate a poem on a specific topic.
Ensure that the model_id variable is set to the correct Generative AI model identifier.
Run the script.
## Script Details
The script llama2.py sends a request to the Bedrock runtime with the provided prompt data.
It specifies parameters such as max_gen_len, temperature, and top_p to control the generation process.
The response from the Bedrock runtime contains the generated poetry in JSON format, which can be further processed or displayed as needed.

## Example Prompt

prompt_data="""
Compose a symphony of silence, capturing the beauty of moments between heartbeats
"""
AWS Bedrock Platform
The AWS Bedrock platform provides a scalable and efficient environment for running machine learning models. It abstracts away the infrastructure complexities, allowing developers to focus on building and deploying models with ease.

For more information about the AWS Bedrock platform, refer to the official documentation.

## Disclaimer
This project is for educational and demonstration purposes only. Ensure compliance with AWS terms of service and usage policies when using the Bedrock platform and associated services.

## Author
Ahmad A Shaik, Ph.D.
## License
This project is licensed under the MIT License.
