# AvatarSpeech Project

## Overview

Welcome to the AvatarSpeech project! This project combines image processing, text-to-speech, and avatar creation to transform a user's profile photo and introduction text into a dynamic avatar video. The process involves utilizing the [photo2cartoon](https://github.com/minivision-ai/photo2cartoon) repository for avatar creation and the [tortoise-tts](https://github.com/jnordberg/tortoise-tts) repository for text-to-speech synthesis with personalized accents. The final step involves using the GOOEY.AI API to merge the generated avatar image and audio file into a captivating video.

## Getting Started

Follow these steps to set up and run the AvatarSpeech project:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Manikanta-7342/AvatarSpeech.git
   cd avatarspeech

2. **Install Dependencies:**
Ensure that you have all the required dependencies installed. You can refer to the documentation of the individual repositories (photo2cartoon and tortoise-tts) for specific installation instructions.

3. **Upload Profile Photo and Introduction Text:**
Place your profile photo in the designated folder and create a text file with your introduction text.

4. **Generate Avatar:**
Run the avatar generation script using the photo2cartoon repository. This script will convert your profile photo into a cartoon avatar.
![cartoon](https://github.com/Manikanta-7342/AvatarSpeech/assets/92366177/a9edd04c-7ee1-4f9f-9689-66e1113a26b6)

6. **Train Text-to-Speech Model:**
Utilize the tortoise-tts repository to train the text-to-speech model with your personalized accents and audio files.
```bash
Hi, I am Manikanta and I'm a passionate coder with expertise in Machine Learning, Deep Learning, Computer Vision, and MLOps concepts.
I enjoy playing cricket and watching movies during my free time.With a strong teamwork mindset,
I excel at collaborating with others to achieve common goals.
My dedication to continuous learning drives me to stay updated with the latest technological advancements.
```

8. **Generate Avatar Video:**
Use the GOOEY.AI API to merge the generated avatar image and audio file into a video. Obtain your API key from GOOEY.AI and replace YOUR_API_KEY in the script with your actual API key.


https://github.com/Manikanta-7342/AvatarSpeech/assets/92366177/072b9b92-2dc5-458a-92f1-ec940424bac4

