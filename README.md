# Text Narrator using Amazon Polly on AWS

This project implements a text narrator using Amazon Polly, AWS Identity and Access Management (IAM) roles, Amazon S3 bucket, and AWS Lambda. The system converts text input into lifelike speech, allowing users to generate audio narrations from textual content programmatically.

_Amazon Polly_ : Polly is used to synthesize natural-sounding speech from the provided text input. It offers a variety of voices and speech synthesis markup language (SSML) for customization.

_IAM Role_ : An IAM role is assigned to the Lambda function, granting it permission to access Amazon Polly and write the generated audio to an S3 bucket.

_Amazon S3 Bucket_ : An S3 bucket is utilized to store the generated audio files. The audio files can be accessed and retrieved later for playback or distribution.

_AWS Lambda_ : Lambda functions are responsible for invoking Amazon Polly to synthesize speech from the provided text input. Once the audio is generated, Lambda writes the audio file to the designated S3 bucket.


<img width="615" alt="Screenshot 2024-04-01 at 12 09 36" src="https://github.com/mohsn13/Text-Narrator-Amazon-Polly/assets/157317409/d355c206-b34c-45f3-bebf-67ffe5c87e35">
