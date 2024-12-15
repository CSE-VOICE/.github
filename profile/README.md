# 🗣️ VOICE: A Multimodal Routine Recommender for Any Circumstances
> ### **Excellence Award(2nd Place), LG Electronics Hanyang University IC-PBL Project**

> ### 한양대학교 2024-2 소프트웨어공학/인공지능및응용 프로젝트 (SWE/ITE Project in Hanyang Univ. 2024-2)

![VOICE-viewpage](https://github.com/user-attachments/assets/aab920e3-7c06-4637-9b51-f6c4dba10795)
<br/><br/>

## 💁🏻‍♂️ Proposal
We propose a multimodal AI service that recommends optimal smart home routines tailored to diverse user circumstances. Our approach integrates generative AI and multimodal interaction capabilities to deliver context-aware automation. To do so, we divided our service into two phases.

In the initial phase, we developed a generative AI model fine-tuned to deliver optimal smart home routines based on textual descriptions of user circumstances. To train the model, we constructed a robust dataset containing approximately 10,000 examples in the format (situation: routine). The dataset was generated using state-of-the-art generative AI models like ChatGPT, MS Copilot, Google Bard, and Claude. To ensure the recommendations are robust and contextually relevant, we included diverse and even unconventional circumstances in the dataset, expanding its versatility across realistic and imaginative scenarios. Once the dataset was prepared, we fine-tuned a transformer-based model, specifically the paust-t5-chat-large, optimized for Korean conversational contexts.

In the second phase, our service extends from text-based interaction to voice-based commands using SKT NUGU. By integrating speech recognition, the system will translate verbal request to text with Google Speech-To-Text API, while capturing extra verbal details such as emotional tone, urgency, and the speed of speech using Hume AI. These voice-derived textual and nuanced details will then be combined to enhance the model’s ability to generate more contextually optimized smart home routine recommendations, further tailoring responses to the user’s specific circumstances. Furthermore, our service keeps track of users’ conversation so that it can capture context, keywords and extra information like urgency and provide optimal smart home routine.
<br/><br/>

## ⚒️ Architecture Design
![VOICE-architecture](https://github.com/user-attachments/assets/dd50616e-3f9b-46cb-bdfa-e2591a75bb55)
<br/><br/>

## 🎥 Videos
<div align="center">

**⬇️ Click below image to watch our demo video! ⬇️**

<a href="https://www.youtube.com/watch?v=RquS2jUlkmU">
<img width="960" alt="voice-demo-frontpage" src="https://github.com/user-attachments/assets/1920d919-d9b1-496e-8be7-1ad4c9bb3479" />
</a>
</div>
<br/><br/>

## 🔗 Links
#### [VOICE-TechBlog](https://bit.ly/cse2024-voice-blog)
#### [VOICE-Documentation.pdf](https://github.com/user-attachments/files/18139578/VOICE-Documentation.pdf)
#### [VOICE-PPT.pdf](https://github.com/user-attachments/files/18139592/VOICE-PPT.pdf)
<br/><br/>

## 👫🏻 Contributors
| Role | Name | Organization | Email |
|------|-------|-------|-------|
| AI Developer | Jaehwi Song | Dept. of Information Systems, College of Engineering, Hanyang University | wotns0319@naver.com |
| Software Developer (Backend) | Hyeonseo Yu | Dept. of Information Systems, College of Engineering, Hanyang University | daina192939@gmail.com |
| Data Engineer | Seungjin Lee | Dept. of Information Systems, College of Engineering, Hanyang University | cookjin@hanyang.ac.kr |
| Software Developer (Frontend) | Hyungrak Choi | Dept. of Information Systems, College of Engineering, Hanyang University | hrgr0711@naver.com |
