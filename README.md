# Amazon-Q-Prompts-2025

Prompting hint from https://www.linkedin.com/posts/hamna-aslam-kahn_this-is-wild-someone-shared-how-you-can-activity-7336004027135975424-UDxf/?utm_source=share&utm_medium=member_ios&rcm=ACoAAAFXfeMBCS5zL7B2hBcKE2k_A3YgyCWxlH8 :

Step 1: Generate a Prompt Engineering Guide
Ask the AI:
“Generate a detailed prompt engineering guide. The audience is <insert role>.”
(Examples of roles: "book authors", "software developers", or "customer support reps")

Step 2: Feed It Examples
Paste in 5 examples of how you want your prompt to work.
(Use few-shot examples: input + expected output)

Step 3: Improve the Prompt
Tell the AI:
“Generate a prompt that could have generated the examples’ outputs. Also include a better set of examples.”
Submit and review.

Step 4: Evaluate the Prompt
Start a new chat and say:
“Generate a detailed prompt evaluation guide. The audience is <insert role>.”

Step 5: Paste the Prompt for Evaluation
Copy the prompt from step 3 and ask:
“Evaluate this prompt.”
The AI will break it down and offer feedback.

Step 6: Ask for Better Versions
Tell the AI:
“Generate 3 improved alternative prompts.”
You now have options to choose from.

Step 7: Pick and Polish
Choose the best prompt and edit it if needed to match your use case.

## Concrete Prompt examples:
```
Create a CloudFormation template that builds the following infrastructure:

* An S3 bucket containing web app code which allows users to upload files to S3.
* The web app code is deployed to and hosted via AWS Amplify
* An S3 bucket which stores the uploaded files.
* File upload is done via an S3 pre-signed URL, created by a Lambda function.
* The Lambda function is invoked via API Gatway, and the API Gateway api is called from the web app.
```

```
Make a suggestion by creating a README.md file which explains an AWS service based infrastructure, implementing these requirements:
* A web app which can be used both by a desktop computer, but also by a smartphone
* The web app allows for recording a message up to 2 minutes.
* This message is sent to Amazon Transcribe to have it transcribed to text.
* The text is stored in an existing S3 bucket.
```
Raspi project idea:
```
Smart Home Assistant with Voice-Controlled Generative AI
Project Overview:
Create a voice-activated smart home assistant using a Raspberry Pi that leverages Amazon Bedrock's generative AI capabilities to provide intelligent responses and control smart home devices.
Key Components:
Hardware:
•	Raspberry Pi (latest model recommended)
•	USB microphone
•	Speaker
•	Optional: Camera module for computer vision tasks

AWS Services:
•	Amazon Bedrock for generative AI capabilities
•	AWS IoT Core for device connectivity
•	Amazon Transcribe for speech-to-text conversion
•	Amazon Polly for text-to-speech conversion
•	AWS Lambda for serverless compute functions

Implementation Steps:
1.	Set up the Raspberry Pi with the necessary peripherals and install required software.
2.	Use AWS IoT Core to securely connect the Raspberry Pi to AWS cloud services.
3.	Implement a voice activation trigger using a wake word (custom or pre-defined).
4.	Use Amazon Transcribe to convert spoken commands into text.
5.	Send the transcribed text to an AWS Lambda function, which will interact with Amazon Bedrock to generate appropriate responses or actions.
6.	Use Amazon Bedrock's generative AI capabilities to:
o	Answer questions
o	Generate creative content
o	Provide recommendations
o	Control smart home devices through AWS IoT integration
7.	Convert the generated response to speech using Amazon Polly and play it through the Raspberry Pi's speaker.
8.	Optionally, integrate computer vision using the Raspberry Pi camera module and Amazon Rekognition for facial recognition or object detection.
Key Features:
•	Natural language interaction with your smart home
•	Personalized responses and recommendations
•	Voice control of IoT devices
•	Continuous learning and improvement through Amazon Bedrock's AI capabilities
```
