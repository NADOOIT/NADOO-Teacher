# NADOO-Teacher

An AI Avatar Teacher with a Face and a Voice

## Introduction

NADOO-Teacher is an innovative AI-powered tutor designed to enhance the learning experience by integrating a human-like avatar with a face and voice into the teaching environment. Unlike traditional chatbots, NADOO-Teacher presents itself as a video avatar that can interact with students in real-time, responding to questions via both text and audio. The avatar is accessible through a local machine and can be streamed into virtual environments like Gather, creating a seamless and interactive educational experience.

## Key Features

1. **Interactive Video Avatar**:
   - NADOO-Teacher appears as a video-based AI tutor, creating a more engaging and personal interaction. 
   - Students can ask questions either via text or audio, and the AI responds with both spoken and written answers, making the experience feel more natural and dynamic.

2. **Real-Time Question and Answer System**:
   - Students interact with NADOO-Teacher through a chat interface or by using voice commands.
   - The AI generates real-time responses and logs the interaction, creating a searchable database of questions and answers.

3. **AI-Powered Knowledge Library**:
   - Every question asked by students is recorded, along with the AI's response, building a growing library of knowledge.
   - The system uses embeddings to categorize and retrieve the most relevant answers when similar questions are asked, allowing the AI to improve its responses over time.

4. **Intelligent Ticketing System**:
   - When a question is asked, the system generates a "ticket" that includes the question, the AI's answer, and any relevant metadata.
   - If the AI cannot answer a question, it escalates the ticket to a human instructor, who can provide a detailed response or create a new learning segment if needed.

5. **Continuous Learning and Curriculum Adaptation**:
   - The AI identifies gaps in students' knowledge based on the questions they ask.
   - Instructors can use this data to adjust the curriculum, ensuring that it meets the evolving needs and interests of the students.

6. **Automated Processes**:
   - Integrations for sending automated emails to institutions, generating completion certificates, and other administrative tasks based on the data collected during the course.

## Technology Stack

- **Programming Language**: Python
- **Avatar Technology**: Utilizing tools like the [Avatarify](https://www.youtube.com/watch?v=rlnjcRP4oVc) framework for real-time video manipulation.
- **NLP and Speech Recognition**: Python libraries such as Hugging Face Transformers for NLP and OpenAI's Whisper or Google Speech-to-Text for speech recognition.
- **Embeddings and Knowledge Management**: Implementation of sentence embeddings using models like BERT or Sentence-BERT for efficient question retrieval and answer matching.
- **Virtual Environment Integration**: Integration with platforms like Gather to provide a virtual classroom experience where students can interact with the AI tutor as if they were in the same room.

## Future Enhancements

- **Advanced Personalization**:
  - Customizing the avatar’s appearance and voice to match specific themes or preferences.
  - Personalized feedback based on individual student performance and interaction history.

- **Multilingual Support**:
  - Expanding the AI's capabilities to support multiple languages, making it accessible to a global audience.

- **Emotional Intelligence**:
  - Developing the avatar’s ability to detect and respond to students' emotions, providing encouragement or adjusting its tone to match the learner’s mood.

- **Integration with Learning Management Systems (LMS)**:
  - Connecting NADOO-Teacher with popular LMS platforms for seamless tracking of student progress and integration with existing educational infrastructure.

## Implementation Roadmap

1. **Phase 1: Core Development**:
   - Develop the initial chatbot functionality, speech recognition, and real-time video avatar integration.
   - Implement the ticketing system and knowledge library.

2. **Phase 2: Embedding and Search Optimization**:
   - Develop the embedding-based search and retrieval system to enhance response accuracy.
   - Create the integration for escalating unanswered questions to human instructors.

3. **Phase 3: Virtual Environment Integration**:
   - Integrate NADOO-Teacher into virtual classroom platforms like Gather.
   - Test and refine the user experience, focusing on interaction quality and ease of use.

4. **Phase 4: Automated Processes and Advanced Features**:
   - Implement automated email and certificate generation.
   - Introduce advanced personalization and emotional intelligence features.

5. **Phase 5: Pilot Testing and Feedback Loop**:
   - Conduct pilot tests with real students and gather feedback for further refinement.
   - Adjust the curriculum adaptation mechanism and finalize the integration of additional features.

## Contribution

We welcome contributions from the community! If you are interested in enhancing NADOO-Teacher, please feel free to submit pull requests or suggest new features.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Infos for building
https://www.youtube.com/watch?v=rlnjcRP4oVc
https://github.com/exo-explore/exo
https://github.com/fudan-generative-vision/hallo
