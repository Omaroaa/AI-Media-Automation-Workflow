🚀 Features

Generate Image Prompts: Uses GPT-4.1 mini to create detailed prompts.

Generate Images: Automatically generates and retrieves AI images.

Generate Videos: Creates AI-generated videos via external APIs.

Generate Audio: Produces audio files with AI and uploads them to Google Drive.

Render & Log: Combines all outputs, renders final video, sends it, and logs results in a sheet.

🛠️ Workflow Overview

Generate Prompts → GPT-4.1 mini creates prompts.

Images & Videos → APIs generate visual content.

Audio → AI generates sound and saves it to Drive.

Rendering → Final video is merged and rendered.

Logging → Output stored and logged for tracking.
🔧 Requirements

n8n installed and configured.

API access to:

OpenAI (GPT-4.1 mini)

Image/Video generation APIs (e.g., Pika, Runway)

Audio generation API

Google Drive integration for file storage.

▶️ Usage

Import the workflow.json into your n8n instance.

Configure API keys in environment variables.

Execute the workflow manually or via trigger.

Access outputs in Google Drive and logs in sheets.
