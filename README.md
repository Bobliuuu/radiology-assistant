# radiology-assistant

## Inspiration

80 million CT scans are performed every year in the US according to Harvard Medical School.

With CT scan report writing and result appointments taking up to 1hr and 30 minutes, that's 120 million Physician Hours spent on analyzing scans.

Given the average [Radiology Physician makes $217 ](https://www.salary.com/research/salary/benchmark/physician-radiology-hourly-wages) per hour, which means that's 26.04 Billion USD spent every year on CT scan result analysis.

With healthcare getting more expensive and more backlogged with physicians increasingly experiencing burn out, our team has come together with an exciting vision - to develop an AI-driven radiology assistant. As we began our discussions, we explored several innovative ideas, including wildfire prevention, text-to-movie conversions, and AI ultrasound detection. After a few deliberations, we felt most inclined toward the AI ultrasound detection concept.

## Objective:
The project is intended to serve as an AI-powered radiology assistant that analyzes ultrasound images to provide insights. The primary goal is to "replace" the need for a doctor to interpret ultrasounds, offering a first-line analysis and guiding users to a doctor if there are any serious issues. However, the emphasis is on recognizing and providing insights about the ultrasound images, particularly focusing on the health of the baby and parent.

### Here's the general flow of our proposed solution:

Users are introduced via a landing page and directed to a Voiceflow interface.
Users then upload ultrasound images.
An AI model, which we are actively developing, will then analyze these ultrasound images.
Insights drawn from the images will be processed and presented through a chatbot. This is where the Language Model (LLM) comes into play, converting the AI's findings into comprehensive insights.
The objective is to provide a simplified overview of the ultrasound's findings, focusing primarily on the health of the carrier, potentially eliminating the immediate need for a doctor unless a serious issue is detected.
We've also discussed possible expansions like gestational time estimation, baby size predictions, and recommendations (like whether a C-section might be advisable).

## Features:

A user-friendly landing page for users to access the system.
Voiceflow interface for user interaction.
Capability to upload ultrasound images.
An AI model that analyzes the uploaded ultrasound images.
A chatbot (LLM) that uses the insights generated by the AI to answer user queries.
Possibility of a mobile app for added convenience.
Potential features discussed include:
Descriptions of ultrasound images.
Baby health insights.
Information about the carrier's health.
Possible recommendations (e.g., whether the host should consider a c-section).

## Roles and Tasks:

**Jerry:** Focuses on model training, potentially using QLoRa. He will also port the model onto platforms like GCP, help with the fine-tuning of the LLM, and conduct research for the project pitch.
**William:** Tasked with setting up the LLM using voiceflow, defining the workflow, and minting an NFT of the ultrasound. He might also work on developing a mobile app.
**Sujata**: Will be responsible for creating Flask endpoints, connecting them to Next.js, and setting up a base page for image uploading and interaction with the GPT chatbot.
**Skylar:** Entrusted with designing a visually appealing landing page and adding various frontend components to enhance the user experience.
We also discussed the feasibility of expanding the scope to include other radiology images like X-rays or body scans and deliberated on the specific insights the system should offer.

## Next Steps

As we progress, we are considering making a mobile version, leveraging Voiceflow's mobile optimization. Our overarching goal is to participate in and potentially win multiple categories in an ongoing competition: Best Use of API, ML/AI Hack, Web, and Catalyst.

## Challenges

However, there have been certain points of confusion and challenges. For instance, Skylar pointed out that usually, ultrasounds are usually conducted in the doctor's office, where the doctor then reviews and informs the patient about any findings. We need to identify the precise gap our solution will fill in the current medical process. Also, fine-tuning the AI's capability to understand and interpret ultrasound images is something we're continuously working on.

## Conclusion

Regardless of the challenges, we're excited and are actively dividing tasks, setting up the technical stack (next tailwind), and ensuring we have a clear direction to move forward. Let's bring our vision of an AI radiology assistant to life!
