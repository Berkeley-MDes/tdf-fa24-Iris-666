# Hello!
This is Tian Qin. Welcome to my TDF repository :)

# Menu
[week 13](#week-13-Final-Project) \
[week 12](#week-12-Final-Project-Ideation) \
[week 11](#week-11-Zerowidth) \
[week 10](#week-10-Mini-Me) \
[week 9](#week-9-Exploring-LLM) \
[week 8](#week-8-Project2) \
[week 7](#week-7-Project2-Experiments) \
[week 6](#week-6-Photon2-Stemma) \
[week 5](#week-5-Photon2) \
[week 4](#week-4-my-interaction-ecosystems) \
[week 3](#week-3-building-lampshade-with-grasshopper) \
[week 2](#week-2-experiment-with-rhino-and-grasshopper) \
[week 1](#week-1-laser-cutting)


---

# Week 13 Final Project

# Week 12 Final Project Ideation


# Week 11 Zerowidth



# Week 10 Mini Me
## Reflections
### What I Learned
* This week was dedicated to refining the AI agent’s behavior and exploring the nuances of prompt engineering. A major focus was on designing prompts that could guide the agent to adopt specific roles, such as an interviewer or creative consultant. I discovered how slight variations in phrasing could significantly impact the agent’s tone, depth of response, and ability to engage in role-specific conversations. This process highlighted the importance of precision and clarity in prompt design, as these factors directly influence the agent’s performance.
<p align="center">
  <img width="700" src="assets/week10/week10_1.png">
</p>
<p align="center">
  <img width="700" src="assets/week10/week10_2.png">
</p>
* Another area of exploration was the adjustment of temperature settings, which control the randomness of the model’s responses. Higher temperatures resulted in more creative and diverse outputs, while lower temperatures produced more consistent and predictable answers. Through systematic experimentation, I gained a deeper understanding of how to strike a balance between creativity and coherence, tailoring the agent’s behavior to suit different scenarios. For instance, higher temperatures were useful for brainstorming sessions, while lower temperatures were more appropriate for professional interviews or technical explanations.

<p align="center">
  <img width="700" src="assets/week10/week10_3.png">
</p>

### How I Learned

I employed an iterative approach, conducting multiple rounds of testing to evaluate how different prompts and temperature settings influenced the agent’s responses. By embedding contextual variables—such as specific locations, professional roles, and project details—I was able to observe how these factors enhanced the agent’s ability to deliver scenario-specific answers. For example, when prompted with questions about my experiences in Shanghai, the agent was able to draw on relevant information from the knowledge base to provide detailed and contextually accurate responses. This iterative process also involved analyzing the trade-offs between response quality and generation speed, particularly when experimenting with higher temperature settings.

### State of Work
By the end of this week, the agent demonstrated significant improvements in its ability to adapt to different scenarios and roles. It could effectively balance creativity and precision, delivering responses that were both engaging and contextually relevant. However, challenges remain in ensuring the accuracy of responses when handling particularly complex prompts, which will be a focus for future iterations.
<p align="center">
  <img width="700" src="assets/week10/week10_4.png">
</p>

## Diagrammatic Analysis of My Experiments
<p align="center">
  <img width="700" src="assets/week9/week9_6.png">
</p>
The system is designed around a Knowledge Base that stores core documents and experiences relevant to the interview process. In this case, I uploaded:

* Resume: Highlights professional experience, skills, and educational background.
* Project Reports (TDF Project 1 & TDF Project 2): Detailed documentation of past project work.
* Personal Statement: Provides insights into my personal motivations, career goals, and relevant experiences.
These files form a centralized repository of information that the agent can reference, enabling it to generate contextually relevant and accurate responses based on comprehensive knowledge about my background.

### Process Flow
The agent flow proceeds through a series of steps to generate responses:
1. Conversational Input: The user provides an input, which could be an interview question or request for specific information.
2. Search Knowledge: The agent searches the knowledge base for relevant content that matches the conversational input. This step allows it to identify and retrieve the most pertinent information from the documents uploaded.
3. Prompt: A predefined prompt guides the LLM in how to respond. 
4. LLM Processing: The prompt is then processed by a Claude 3.5 Sonnet LLM, which generates a response based on the prompt and the information from the knowledge base. This step leverages the LLM’s capacity to interpret and respond with human-like language.
5. Output: Finally, the system outputs the response, providing an answer that is both relevant and coherent, based on the knowledge stored in the base.

## Final Experiments
### What is your purpose?
“My purpose is to represent and share information about my professional experience as Tian Qin. I'm here to discuss my work as a creative technologist, engineer, and artist, as well as my academic background and career goals.
I see myself as a "wanderer" in the fields of technology and art, always exploring new possibilities and seeking creative inspirations. My journey has taken me through various disciplines, from economics to computer science, before settling on Interactive Media Arts.
I aim to turn everyday observations and interests into meaningful subjects of study, research, and creation. For example, I've developed games inspired by simple things like leaves swirling in the wind or people's reliance on navigation apps.
More recently. I've become passionate about art education and creating projects that can impact more people. I've taught game design to middle school students and led workshops on AI in art.
Is there a specific aspect of my experience or work you'd like to know more about?”

### Who are you representing?
“I am representing Tian Qin, a creative technologist, engineer, and artist. Tian has a background in Interactive Media Arts from New York University Shanghai and is currently pursuing a Master of Design at the University of California, Berkeley. Tian's work spans various fields including R/AR development, interactive installations, game design, and physical computing. Is there a particular aspect of Tian's background or work you'd like to know more about?”

### What projects have you worked on this semester?
“This semester, I've worked on two main projects as part of my studies at UC Berkeley:
1. WaveGlow: This was my project for the Technology Design Foundation course. It's a computational design project where I created a parametric lampshade using Rhino and Grasshopper. This was my first time using 3D modeling tools, so it was quite challenging but rewarding. The lampshade was designed to diffuse light while maintaining a minimal, simple aesthetic. I used white PLA filament for 3D printing, though I faced some structural challenges that required multiple printing attempts.
2. Echoes of the Earth: This was a team project for the same course, where I collaborated with Chuhua Ding. We created an interactive installation that responds to hand gestures and temperature changes. The installation uses Particle Photon 2 microcontrollers, various sensors, servos, and neopixels. It also integrates with a web interface using Socket.io, allowing remote interaction. The project aims to represent the dynamic nature of ecosystems and our impact on the environment.
Both projects allowed me to explore new technologies and apply my skills in creative ways.
They also challenged me to think about user experience, environmental impact, and the integration of physical and digital elements in design.
Is there a specific aspect of either of these projects you'd like to know more about?”

### Can you mention a challenge faced in one of the projects and how it was overcome?
“Certainly! One significant challenge I faced was during the WaveGlow project, specifically with the 3D printing process. The complex wavy bottom design of the lampshade proved to be particularly problematic.
The main issue was that the wavy design at the bottom made it difficult for the 3D printer to create a stable base. This resulted in several failed printing attempts. It was frustrating because each attempt consumed time and materials, increasing both waste and energy consumption.
To overcome this challenge, I had to go through a process of trial and error. After two unsuccessful attempts, I finally managed to successfully print the model on the third try. However, even with this success, the high printing temperature made it challenging to remove the support structure without damaging the piece.
This experience taught me a valuable lesson about understanding tool constraints and adapting designs accordingly. I learned that in 3D printing, it's generally much easier to print objects with a flat bottom as they provide a stable base and reduce the likelihood of printing failures.
Moving forward, I plan to consider these fabrication constraints earlier in the design process. For future projects, I might modify designs to include a flatter base or explore alternative printing orientations to minimize support structures. This challenge highlighted the importance of not just creating aesthetically pleasing designs, but also ones that are practical to fabricate.
This experience also emphasized the value of persistence and problem-solving in design work.
Despite the setbacks, I was able to achieve my design goals by adjusting my approach and learning from each attempt.”

### Given the new set of technical skills you have, what would make an exciting final project to showcase and extend these skills?
“Given the new set of technical skills I've acquired this semester, particularly in computational design, physical computing, and interactive installations, an exciting final project could be an immersive, interactive AR (Augmented Reality) experience that bridges the physical and digital worlds. This project would allow me to showcase and extend my skills while aligning with my interests in AR, education, and public engagement.
Here's an idea for such a project:
"Living History: An Interactive AR Museum Experience"
This project would combine:
1. Computational Design: Using tools like Rhino and Grasshopper to create parametric 3D models of historical artifacts or environments. These models could be adjusted in real-time based on user interaction or new historical data.
2. Physical Computing: Incorporating sensors and actuators in the physical space to create a responsive environment. For example, proximity sensors could trigger different AR experiences as visitors move through the space.
3. AR Development: Using Unity or another AR development platform to create the augmented reality layer. This would involve 3D modeling, animation, and interactive programming.
4. Web Development: Creating a companion web application that allows remote users to interact with the installation, similar to the Socket.io integration we used in the Echoes of the Earth project.
5. Data Visualization: Incorporating real-time data visualization to show how historical events or artifacts connect to current issues or other historical periods.
The installation could be set up in a museum or public space, where visitors use their smartphones or provided AR glasses to explore.
As they move through the space, they would see historical scenes overlaid on the physical environment, interact with 3D models of artifacts, and trigger different narratives or data visualizations.
For example, pointing their device at a physical model of an ancient city might cause an AR overlay to show the city coming to life, with animated figures and buildings. Gestures could be used to fast-forward through time, showing how the city changed over centuries.
This project would extend my skills by:
1. Combining physical and digital design in a more complex way
2. Explaining more advanced AR development techniques
3. Integrating real-time data processing and visualization
4. Addressing the challenges of creating engaging, educational experiences for a public audience
It would also align with my interest in using technology to make knowledge more accessible and engaging, particularly in educational and museum contexts. This project could serve as a prototype for how AR can be used to create more immersive, interactive learning experiences in public spaces.
What do you think about this idea? Does it seem like a good way to showcase and extend the skills I've developed?”


Then, I put this answer into the Interview Question Generator agent that I created with a simple prompt with RAG. It generated many valuable questions. 

Question: “Thank you for providing that information about your projects, Tian. Both WaveGlow and Echoes of the Earth sound like fascinating and innovative projects. I'd like to focus on Echoes of the Earth for a moment, as it seems to involve a complex integration of various technologies.
Could you elaborate on your specific role in the Echoes of the Earth project? What were your main responsibilities, and what challenges did you face in integrating the different components (such as the Particle Photon 2 microcontrollers, sensors, and the web interface)? How did you overcome these challenges?”

I then put the question generated by the agent put back to the former agent which represents me. The answer it generated is:
“Thank you for your interest in the Echoes of the Earth project. I'm glad to elaborate on my role and experiences.
As one of two team members on this project, I had significant responsibilities across multiple aspects of the installation. My primary focus was on the technical integration and programming of the various components.
Specifically, I was responsible for:
1. Programming the Particle Photon 2 microcontroller to interface with the sensors (temperature and gestures) and control the actuators (servos and neopixels).
2. Setting up the communication between the Particle Cloud and our Socket.io server to enable real-time data exchange.
3. Developing the web interface that allowed remote users to interact with the installation. 
4. Integrating all these elements into a cohesive, responsive system.
One of the main challenges I faced was ensuring smooth, real-time communication between all components. Latency issues between the web interface, Particle Cloud, and physical installation initially caused noticeable delays in the system's responsiveness. To overcome this, I implemented an optimized data transmission protocol and created a queuing system for web interactions.
This significantly reduced lag and improved the overall user experience.
Another challenge was coordinating the movements of multiple servos to create natural, wave-like motions in the rubber surface. This required careful timing and synchronization to avoid jerky or unnatural movements. I addressed this by developing a coordinated timing mechanism that ensured smooth, synchronized motion across all servos.
Integrating the temperature sensor data with the neopixel lighting also presented some difficulties in terms of creating a natural, gradual color change that accurately reflected temperature fluctuations. I solved this by implementing a more nuanced mapping between temperature readings and color values, resulting in subtle, organic transitions.
Throughout the project, I had to continuously test and refine the system, often making real-time adjustments during our integration phase. This iterative process was crucial in achieving the seamless interaction we were aiming for.
Overall, while challenging, this project significantly enhanced my skills in IoT integration, real-time data processing, and creating responsive physical-digital interfaces. It reinforced my passion for creating immersive, interactive experiences that bridge the digital and physical worlds.” 

The next question it generated was:
“The project seems to have required a balance between technical implementation and creative design. How do you approach finding this balance, and how important do you think it is in the field of creative technology?”

The answer to this question was:
“Finding the balance between technical implementation and creative design is absolutely crucial in creative technology, and it's a challenge I'm passionate about tackling in my work.
In my approach, I view technical skills and creative vision as equally important and deeply intertwined. I don't see them as separate phases, but rather as parallel, iterative processes that inform each other throughout a project's development.
For Echoes of the Earth, this balance was critical. The creative concept - an interactive installation representing ecosystem dynamics - drove many of our technical decisions. At the same time, our technical capabilities and constraints shaped the creative possibilities.
Here's how I typically approach this balance:
1. Start with a strong creative concept: I begin by clearly defining the experience we want to create and the emotions or ideas we want to evoke. For Echoes of the Earth, we wanted to convey the interconnectedness of ecosystems and human impact.
2. Explore technical possibilities: I then research and experiment with various technologies that could bring the concept to life. This often involves rapid prototyping to test different approaches.
3. Iterate between creative and technical: As technical realities become clear, I refine the creative vision. Likewise, creative breakthroughs often inspire new technical solutions. This back-and-forth is constant throughout development.
4. Prioritize the user experience: When faced with tradeoffs, I always prioritize what will create the best experience for users.
Sometimes this means simplifying a technical implementation to make an interaction more intuitive.
5. Embrace constraints: I've found that technical limitations can often spark creative solutions. For example, when we faced challenges with servo motor coordination, it led us to explore more organic, wave-like movements that enhanced the installation's aesthetic.
6. Collaborate across disciplines: Working closely with team members who have different strengths - whether more technical or more design-focused - is invaluable for maintaining this balance.
In the field of creative technology, I believe this balance is not just important, but essential. The most impactful and innovative work in this field often comes from a deep integration of technical prowess and creative vision. It's about using technology not just as a tool, but as a medium for expression and experience design.”

The last question was:
“Lastly, considering the challenges you faced and overcame in this project, how has this experience shaped your approach to problem-solving in complex technical environments?”


And the answer was:
“The Echoes of the Earth project significantly shaped my approach to problem-solving in complex technical environments. This experience reinforced some existing strategies and taught me new ones that I now apply to all my work.
Firstly, it emphasized the importance of systems thinking. When dealing with multiple interconnected components like we had in this project, I learned to always consider the ripple effects of any change or solution. For instance, optimizing the data transmission between the web interface and Particle Cloud had implications for the responsiveness of the physical installation.
This experience taught me to map out entire systems before diving into specific problems, ensuring I understand how each part affects the whole.
Secondly, I developed a stronger appreciation for iterative development and rapid prototyping. The challenges we faced, particularly with real-time responsiveness, couldn't be solved in one go. I adopted a more agile approach, implementing small changes, testing them quickly, and refining based on results. This iterative process not only solved immediate issues but often led to unexpected improvements in other areas of the project.
The project also reinforced the value of cross-disciplinary collaboration. When facing complex issues, I found that combining perspectives from different fields often led to more innovative solutions. For example, when struggling with the natural movement of the servos, insights from studying fluid dynamics helped create more organic motion patterns. This experience has made me more proactive in seeking diverse viewpoints when tackling complex problems.
Additionally, I learned the importance of prioritization and knowing when to pivot. With multiple challenges and limited time, I had to constantly assess which issues were most critical to the core experience we were trying to create.
Sometimes, this meant simplifying certain aspects to ensure the most important features worked flawlessly. This has made me more strategic in my problem-solving approach, always keeping the end goal in sight.
Lastly, this project highlighted the value of thorough documentation and knowledge sharing.
As we solved each challenge, I made sure to document our process and solutions clearly. This not only helped my teammate and me stay aligned but also created a valuable resource for future projects. Now, I make documentation an integral part of my problem-solving process, which has proven invaluable in complex, long-term projects.
Overall, Echoes of the Earth sharpened my ability to navigate complexity, fostered a more holistic and flexible approach to problem-solving, and reinforced the importance of collaboration and continuous learning in tackling technical challenges. These lessons continue to influence my work as a creative technologist, enabling me to take on increasingly complex and innovative projects with confidence.”

The experiments with the LLM agent revealed unique, insightful aspects about how it could assist in interview preparation and answer formulation, helping me articulate my experience in creative technology. Some of the answers were too long, but provided many novel aspects that I’ve never thought about to answer those questions. The agent provided in-depth answers that brought out novel aspects of my work, some of which I hadn’t previously considered. For example, it reflected on “Echoes of the Earth” by emphasizing specific skills, like real-time data processing and IoT integration, highlighting not only technical mastery but also the creative problem-solving involved. This allowed me to articulate my role with more precision and confidence.


## Speculations
### Future of Tools:
I envision a future where AI tools seamlessly integrate with professional platforms like LinkedIn and GitHub, automating the creation and updating of dynamic resumes, portfolios, and project showcases. These tools could also offer real-time feedback and suggestions, enhancing their utility for professionals across various industries. Additionally, the development of adaptive AI systems that can adjust their behavior based on user preferences and contextual cues will likely become a key area of focus.

### Future of My Work:
Moving forward, I plan to optimize the agent’s token usage to streamline its responses and improve efficiency. Another goal is to explore the use of temporal variables, enabling the agent to contextualize its answers based on time-specific data. This would enhance its ability to provide relevant and timely insights, particularly in dynamic professional environments.



# Week 9 Exploring LLM
## Reflections
### What I Learned
* This week, I delved into the basics of working with large language models (LLMs) like Claude 3.5 Sonnet and explored the Retrieval-Augmented Generation (RAG) technique. I learned how to integrate a knowledge base into an AI agent, enabling it to provide personalized, context-specific answers.
<p align="center">
  <img width="700" src="assets/week9/week9_1.png">
</p>

* Experimenting with embedding variables, I realized the importance of using specific professional data to create highly customized and accurate responses.
* Working with the RAG technique taught me to leverage external knowledge sources to enhance the agent’s generative capabilities. This significantly improved the agent's ability to represent my personal and professional identity.

<p align="center">
  <img width="700" src="assets/week9/week9_2.png">
</p>
<p align="center">
  <img width="700" src="assets/week9/week9_3.png">
</p>

### How I Learned:
To gain this knowledge, I engaged in a series of practical experiments with different AI models. My primary focus was on comparing the response quality and speed between Claude 3.5 Sonnet and Claude 3 Opus. Through these comparisons, I was able to identify the strengths and limitations of each model. Additionally, I uploaded various project documents—such as my resume, personal statement, and past project reports—into the AI’s knowledge base. By observing how the agent utilized these documents, I gained insights into the interplay between the knowledge base and the agent’s response mechanism. These hands-on activities, combined with iterative testing and prompt adjustments, provided a strong foundation for understanding how to build and refine AI systems.
<p align="center">
  <img width="700" src="assets/week9/week9_4.png">
</p>
<p align="center">
  <img width="700" src="assets/week9/week9_6.png">
</p>

### State of Work:
By the end of the week, I successfully created a prototype agent capable of delivering detailed and accurate representations of my professional identity. This agent effectively utilized RAG to generate context-specific responses, making it a valuable tool for applications like interview preparation and professional storytelling. The initial experiments also highlighted areas for potential improvement, such as optimizing prompt design and enhancing conversational adaptability.
<p align="center">
  <img width="700" src="assets/week9/week9_5.png">
</p>

## Speculations
### Future of Tools:
As I reflect on the potential of RAG-enabled AI systems, I envision a future where these tools redefine how individuals interact with technology on a personal and professional level. By offering unparalleled customization, such systems could transform into integral components of education and career development. For instance, AI agents could serve as personalized mentors, providing real-time feedback, or as interview coaches, helping users craft and refine their professional narratives. The ability to integrate vast amounts of contextual data seamlessly will likely position these tools as indispensable assets in both academic and professional settings.

### Future of My Work:
Looking ahead, I plan to enhance the agent’s capabilities further. Specifically, I aim to optimize token usage to enable the generation of concise yet comprehensive responses. Another area of focus will be exploring conversational adaptability by integrating role-specific prompts. This will allow the agent to simulate various professional roles and scenarios with greater authenticity and realism, thereby expanding its utility.

# Week 8 Project2 
<p align="center">
  <img width="700" src="assets/week8/project2.png">
</p>

## Project Title: Echoes of the Earth  
**Team Name**: Fuller Team  
**Team Members**: Tian Qin, Chuhua Ding  
**Link to Presentation Video**: [https://youtu.be/nMcBBjLFRlk](https://youtu.be/nMcBBjLFRlk)  

## Diagrammatic Analysis

### Ecosystem Architecture

<p align="center">
  <img width="700" src="assets/week8/diagram1.png">
</p>

The ecosystem architecture diagram provides an overview of the interconnected components and data flow within our interactive installation:

- At the center of the system, Particle Cloud Services acts as a mediator, enabling communication between physical components and external users. It receives requests from Socket.io, which manages user interactions on the web interface. The web-based connection allows users to influence the installation remotely, with user data transmitted to the Particle Cloud as an output, and response data fed back to Socket.io as an input.
- Two Particle Photon 2 microcontrollers manage the core sensory and response functions of the installation. The first Photon processes analog inputs from the Gesture Sensor (Stemma QT) and Temperature Sensor (Stemma QT), which track user gestures and ambient temperature, respectively. This Photon then sends data to the Particle Cloud, facilitating real-time interaction.
- The second Particle Photon 2 receives data from the Particle Cloud via Wi-Fi, interpreting inputs to control physical outputs. It drives the Servos, producing analog outputs that create motion, and adjusts the Neopixel color and brightness. These elements work in concert to simulate the shifting, wave-like behavior of a natural ecosystem.

### Ecosystem Process
<p align="center">
  <img width="700" src="assets/week8/diagram2.png">
</p>

This process diagram provides a clear, step-by-step view of the interactions and data flow within our installation’s ecosystem.

- The left side of the diagram starts with User Interactions, such as gesture inputs and web page interactions. These interactions are picked up by Sensors—the Temperature Sensor and Gesture Sensor—which continually monitor environmental conditions and user gestures. This initial stage reflects how data from the physical environment is captured and relayed for processing.
- The diagram then shows how data moves into the Microcontroller stage. The Photon 2_1 microcontroller reads sensor data and sends it via Wi-Fi to the Particle Cloud Service. The Particle Cloud then transmits this data to Socket.io, connecting with the external web interface, allowing user interactions from the web page to influence the installation. Additionally, the Photon 2_2 microcontroller handles actuator responses, sending signals to the Neopixels and Servos based on received data. These responses manifest physically, with changes in light and the dome structure’s movement, providing feedback to the users.

## Prototype Demonstration

<p align="center">
  <img width="350" src="assets/week8/project2.png">
  <img width="350" src="assets/week8/project2_2.png">
</p>
<p align="center">
  <img width="350" src="assets/week8/project2_3.png">
  <img width="350" src="assets/week8/project2_4.png">
</p>

*Echoes of the Earth* is an interactive installation that captures the dynamic and fluid nature of ecosystems. Its rubber surface, animated by servos, undulates in response to hand gestures, evoking the movement of sand dunes or ripples on water when touched by wind or living creatures. As the room temperature shifts, the installation’s light adjusts, representing how temperature changes can impact natural habitats. Through its web integration, Echoes of the Earth extends beyond physical space, allowing remote audiences to influence the installation’s movements, underscoring the global impact of local actions. This piece serves as a reminder of the intricate connections that shape our environment, inviting contemplation of our role in sustaining or disturbing the delicate balance of nature.

---

### Development Process

1. **Individual Component Testing: Neopixels and Servos**: We began by testing individual components to ensure they worked as intended. This included lighting up neopixels and controlling the rotation of servos to verify that each part was responsive and adjustable.
2. **Sensor Data Logging and Calibration**: Next, we experimented with the Temperature Sensor and Gesture Sensor, logging data to calibrate them. This step allowed us to understand sensor sensitivity and ensure they could accurately capture environmental changes and user gestures.
3. **Potentiometer-Controlled Brightness and Servo Movement**: To further refine control, we conducted experiments using a potentiometer to adjust the brightness of the neopixels and the rotation of the servos. This provided insights into analog input adjustments, helping us balance the interaction flow.
4. **Cloud Integration and Data Synchronization via Particle Photons**: We connected two Particle Photons to the Particle Cloud, experimenting with sending sensor data from one Photon to another. This integration enabled real-time data synchronization, laying the foundation for remote user interaction.
5. **Socket.io Webpage Connection**: Using Socket.io and a Node.js server hosted on Glitch, we tested interactions between the web page and the Particle Cloud. Each time a new user accessed the page, the server logged their connection, creating a glowing dot to represent the user’s presence.
6. **Full System Integration and Stress Testing with Four Servos and Two Neopixels**: After ensuring each component functioned independently, we combined all elements, including four servos and two neopixels, for full system integration. This step involved stress-testing to ensure stable operation without signal interference or power issues.
7. **Physical Fabrication Prototyping with Grasshopper**: Before constructing the physical structure, we used Grasshopper to experiment with different patterns and structural layouts. This ensured that movable parts would not interfere with each other and provided a visualization of the dome’s potential movement.

---
## Speculations

### Human Experiences
Our project illustrates how systems thinking could reshape cultural expectations in the Anthropogenic Environment, encouraging individuals to see their actions as part of a larger network. Just as gestures influence the installation’s movement and lighting, people might become more aware of their impact on the environment, leading to more mindful, ecologically conscious behaviors. This project experience suggests a shift toward valuing sustainable technologies that respond to human actions within environmental limits.


### Engineering
Our project’s interconnected components showcase how engineering in Digital Ecosystems goes beyond isolated products, creating responsive, adaptive systems. By syncing sensors, cloud services, and actuators, we designed an installation that dynamically responds to users. This approach could shift engineering expectations, with future systems designed to adapt in real time to users and environments. Engineers might increasingly be seen as creators of flexible, sustainable systems rather than static products.


### Role of AI in the Design Process
AI could enhance projects like ours by predicting user behavior and adapting responses for a seamless experience. In broader Digital Ecosystems, AI might continuously analyze data to maintain balance, such as optimizing resource use in response to environmental changes, as with our temperature-sensitive LEDs. This could lead to AI-driven ecosystems that balance human needs and ecological health, mediating interactions for sustainable, adaptive environments.


# Week 7 Project2 Experiments
This week, we conducted a variety of experiments for Project 2 following our group meeting with TJ. These experiments not only advanced our technical understanding but also paved the way for future creative applications.

**Diagrams Update** \
First, we updated our proposal, system architecture, and process diagram based on TJ's feedback and suggestions. We added one more Photon to explore how to facilitate communication between two Photons.  This addition not only strengthens our project’s communication framework but also introduces a new layer of complexity that will allow us to investigate multi-node interactions.

<p align="center">
  <img width="700" src="assets/week7/diagram1.png">
  <img width="700" src="assets/week7/diagram2.png">
</p>

**Dynamixel Servo** \
As suggested by TJ, we acquired three Dynamixel XL320 servos from Sudhu, which are significantly more powerful than standard servos and can provide torque and status data. However, we encountered challenges finding a compatible library for Particle. Despite trying various methods, we were unsuccessful and ultimately decided to revert to standard servos for our ongoing experiments.

<p align="left">
  <img width="700" src="assets/week7/dynamixel.jpg">
</p>

**Linear Actuator** \
Initially, we considered purchasing linear actuators from Amazon, but found them to be prohibitively expensive. Instead, we opted to create our own using standard servos and 3D printing. Chuhua designed the 3D model, which we printed with promising results.

<p align="center">
  <img width="350" src="assets/week7/linear1.jpg">
  <img width="350" src="assets/week7/linear2.jpg">
</p>

The actuator's performance exceeded our expectations, inspiring us to experiment with varying the disk's shape in the coming days. This DIY approach not only reduced costs but also provided valuable hands-on experience in mechanical design and prototyping.

**Neopixel** \
We faced significant difficulties with the Neopixel, even in lighting it up. Initially, the Neopixel library was incompatible with Particle, resulting in compilation errors despite correctly importing the library. After consulting ChatGPT, I wrote code to light up the Neopixel without a library, which confirmed that the Neopixel was functional.

Thanks to TJ and Sudhu, we finally managed to use the Neopixel library to control the Neopixel.

<p align="center">
  <img height="300" src="assets/week7/neopixel.jpg">
  <img height="300" src="assets/week7/neopixel1.gif">
</p>

I further modified the code to create fading effects and controlled the lights with a potentiometer.
<p align="center">
  <img height="300" src="assets/week7/neopixel2.gif">
  <img height="300" src="assets/week7/neopixel3.gif">
</p>

Additionally, we made the potentiometer control the servo.
<p align="center">
  <img width="700" src="assets/week7/neopixel4.gif">
</p>

**Physical Structure** \
We purchased rubber material to laser cut an auxetic structure. Our initial plan was to create an arched face, but after some experimentation, we realized it was challenging to achieve a well-formed arch. Consequently, we adjusted our design to create a flat surface instead. This is a very interesting part for me, since I get to know these architecture related concepts for the first time. This kind of structure is very challenging but I feel excited to learn about it. 

<p align="center">
  <img width="700" src="assets/week7/auxetic.jpg">
</p>

**Sensors** \
We tested our gesture and temperature sensors, building on our previous experiences, which made this phase of the experiment relatively smooth. Chuhua also designed the container for the sensors in our installation.

<p align="center">
  <img width="350" src="assets/week7/sensor.gif">
  <img width="350" src="assets/week7/sensor.jpg">
</p>

**Future Directions** \
Looking ahead, we foresee several avenues for development. The integration of more advanced communication protocols between the Photons could lead to more sophisticated interactions and data sharing capabilities. Additionally, experimenting with different shapes and mechanisms for our linear actuator may yield innovative movement patterns that enhance the overall project design.

Moreover, our recent success with the Neopixel demonstrates the potential for integrating visual elements more effectively into our installations, offering an engaging experience for users. This opens the door to exploring more complex lighting sequences and color patterns that can react to user input or environmental changes.

# Week 6 Photon2 Stemma


<p align="center">
  <img width="1000" src="assets/week6/solder.jpg">
  <img width="1000" src="assets/week6/solder.gif">
</p>

**Soldering** \
This is not the first time for me to solder, so it didn't take long to accomplish this. I was originally worried about sticking two pins together when soldering, but it actually went smoothly. 

**Stemma Modules** \
The APDS9960 is a digital RGB, ambient light, proximity and gesture sensor. The proximity data ranges from 0 to 255, where 0 represents the farthest object from the sensor and 255 represents the closest object. If there is no object within the range, it just return 0. I think the proximity data from the sensor is quite accurate, but I'm not sure about the RGB data. I tried putting objects with different colors above the sensor, but the RGB value didn't change accordingly. For example, as is shown in the image below, when I put a red object above the sensor, the "red" data didn't really become bigger.

<p align="center">
  <img width="350" src="assets/week6/gesture_sensor.gif">
  <img width="350" src="assets/week6/color_sensor.gif">
</p>

The Acceleration sensor works better and is very sensitve. By rotating the sensor, I can see how different data is changing accordingly. I also added a delay in the loop function to slower the data logged in the serial monitor. 

<p align="center">
  <img width="350" src="assets/week6/acc_sensor.gif">
  <img width="350" src="assets/week6/acc_sensor2.gif">
</p>

One of the major achievements this week was the completion of the Project 2 proposal. We created both a Draft System Architecture and a Process Diagram, which significantly helped us clarify the various components and interactions involved in the project. These diagrams allowed us to visualize the workflow from sensors to actuators, cloud services, and user interactions.

<p align="center">
  <img width="700" src="assets/week6/diagram1.png">
  <img width="700" src="assets/week6/diagram2.png">
</p>
The architecture involves key components like a Particle Photon 2, connected sensors (such as Temperature and Gesture Sensors), and actuators (LED Lights, Linear Actuator, and Motor Drive).
Data from the sensors is processed by the Photon 2 and then sent to the cloud via Particle Cloud Services, which is connected to an external API, Socket.io. This ensures continuous communication between the hardware and the web interface, enabling real-time responses to user inputs.

Having these diagrams in place early in the project has been instrumental for better planning and anticipating potential bottlenecks. They provided a clear framework for how data moves through the system and how users interact with it, ensuring the project is on track with technical feasibility and user experience.

These diagrams not only helped in the current project’s planning but could also serve as templates for future projects involving IoT and interactive systems. The architecture shows a scalable framework that could easily be adapted to other types of sensors and actuators. For instance, replacing gesture sensors with other interaction modes (such as sound or pressure sensors) would require minimal changes to the core architecture, making it highly adaptable for diverse applications.

Additionally, the integration of Socket.io with Particle Cloud Services suggests potential use in future multi-user interactive installations. We could extend this to projects where real-time user collaboration or interaction across different locations is essential, enabling a more robust, distributed network of users interacting with physical objects or virtual systems.

# Week 5 Photon2

First of all, I think one of the most effective ways to address errors appeared during flashing, is unplug the board and plug it in again, if all the other settings are ok. I struggled with errors popped up during flashing several times, and simply replug the board solve most issues. 

I started with modifying the example code we did last thursday. I played around the code and made a simple timer. 

<p align="center">
  <img width="700" src="assets/week5/timer.gif">
  <img width="700" src="assets/week5/timer2.gif">
</p>

Then I started to put the circuit together. The first question I encountered was how to recognize the value of the resistors we got in the kit. I could only find one resistor that looks the same with the one on the circuit diagram. Baurzhan told me that I can calculate the value with [this website](https://www.digikey.com/en/resources/conversion-calculators/conversion-calculator-resistor-color-code). Also in many cases, the value doesn't need to be exactly the same to the diagram. 

<p align="left">
  <img height="500" src="assets/week5/circuit1.gif">
</p>


After completing the first four steps, I encountered another problem. The LED didn't blink. I noticed that the positive and negative poles of the LED are reversed in the circuit diagram. After changing the connection, the LED successfully blinked with the periodicity.

<p align="left">
  <img height="500" src="assets/week5/circuit2.gif">
  <img height="500" src="assets/week5/circuit1.jpg">
</p>

Then I started to experiment on the other tutorials. I first tried the servo. It was surprisingly easy to connect the circuit. However, I don't have the accelerometer in my kit, so I modified the code to just rotate around the servo. This actually gave me a chance to look deeper into the code, instead of simply copy and paste. I really like the servo colored the three wires so it's easier for users to connect the circuit. 

<p align="left">
  <img height="500" src="assets/week5/servo.gif">
</p>

Next, I tried the button send-on-change example. This is not a complicated example, but I see a lot of potentials from it. For example, I can make physical installations that enable people from different continents to interact with each other through sending interaction data to the cloud. That will give people a sense of connection more than just texting or doing facetime.

<p align="left">
  <img height="500" src="assets/week5/send.gif">
</p>

Finally, it's the fsr (force sensitive resistor) -> RGB-led color fader. After pasting the example code, I noticed that there are some errors when compiling the code. 

<p align="left">
  <img height="500" src="assets/week5/error.png">
</p>

It shows that setTarget and setColor are not declared in the scope, and I think it's an issue related with the function prototype Jeff mentioned during Monday's class. Therefore I modified the code and added function prototypes for those two functions, and it resolved the errors successfully. Now I get to understand that although in the example we did during class, it still works without the function prototypes, there are still cases where function prototype is necessary. So it's just always nice to have it.

After solving the code problem, it works! However, I think the fsr sensor is not very stable. Sometimes it's triggered when I'm not touching it while sometimes it doesn't respond even if I'm touching it really hard. I'm not sure if it's the issue with the unstable connection.

<p align="left">
  <img height="300" src="assets/week5/fsr.gif">
</p>

Regarding the question what kinds of ecosystems are missing in your daily life, I think the Financial & Banking Ecosystems is missing. As I don't have any background in finance, the financial and banking system always looks complicated for me. It would be great if some AI assistants can help to explain and guide users with no knowledge in finance to learn about the wealth management process. 


# Week 4 My Interaction Ecosystems
<p align="center">
  <img height="500" src="assets/week4/map.png">
</p>

I created a network map of my entertainment & media ecosystem, which visualize the devices, applications, and platforms I used in my daily life for entertaining purposes. <br />

I started my map with listing out all the devices or objects I used daily for entertainment. The ones that I used most often are definitely mobile phone, laptop, and ipad. These are my primary devices that serve multiple purposes beyond just entertainment. The overlapping of applications between these devices (e.g., Netflix, WeChat) offer cross-device functionality, allowing for seamless transitions between devices depending on the environment (e.g., using Instagram on mobile phone outside or watching YouTube on the iPad when relaxing at home). <br />

There are some other devices that have specialized roles in the entertainment ecosystem. Switch is primarily for gaming with games like Super Mario Odyssey and Animal Crossing, while Oculus supports VR experiences like Beat Saber. These two devices are highly immersive, focusing specifically on gaming and virtual reality, respectively.<br />

Between devices and platforms, content flows smoothly. Photos captured on the camera may end up edited on Photoshop and then shared via Instagram. Similarly, media consumption across Netflix, YouTube, and podcasts happens seamlessly across my devices, showing a well-connected media ecosystem. <br />

I believe in the future, there will be more content flowing between difference devices and platforms. Or there will be less devices serving just for one single purpose, like gaming. Switch, PS5, and other gaming devices may be merged together with our laptop, computer, and finally to an XR device like Meta Orion.

<p align="center">
  <img height="400" src="assets/week4/print.gif">
</p>

This week, I also continued exploring 3D printing in Studio Foundation class. I tried the bambu lab 3D printer at the Citris Invention Lab, and the result turned out really delicate. We also learned how to use metal threaded inserts to assemble the 3D printed part and the ccrylic board. 

<p align="center">
  <img height="300" src="assets/week4/print1.jpg">
  <img height="300" src="assets/week4/print2.jpg">
</p>

# Week 3 Building Lampshade with Grasshopper

After exploring Rhino and Grasshopper last week, I started trying to build my own model with grasshopper. I chose to create a lampshade cause the small ikea lamp on my desk is very dazzling, as the light bulb is directly facing the eyes. 

I firstly sketched out the shape of my lamp and the lampshade. 
<p align="center">
  <img height="250" src="assets/week3/sketch2.PNG">
  <img height="250" src="assets/week3/sketch1.PNG">
</p>

Based on a grasshopper tutorial of a [parametric vase](https://www.youtube.com/watch?v=jGIqvAQRXEc), I also sketched out the rough process in grasshopper to make it easier. 
<p align="center">
  <img height="300" src="assets/week3/sketch3.PNG">
</p>

I learned many new components during the process. For example, the Revolution component is used to create a surface by rotating the curve around an axis, so I can create an annular surface as the basic shape of the lampshade. Weave takes two input lists and combines them into one single output list, so it combines the two sets of curves together to make a wavy pattern. Then I use loft to create a surface by connecting those curves. 

To make the shade perfectly fit my lamp, I imported a side photo of my lamp into rhino to check. I also measured the perimeter of each part of my lamp carefully to make sure the size of the model matches the lamp. 

<p align="center">
  <img height="250" src="assets/week3/lampshade1.gif">
  <img height="250" src="assets/week3/lampshade2.gif">
</p>

<p align="center">
  <img height="250" src="assets/week3/lampshade4.png">
  <img height="250" src="assets/week3/lampshade5.png">
</p>
I encountered many challenges during the process, for example trying to understand what each component is doing and a lot of debugs. However, it turns out the biggest challenge is printing this model out. It failed several times because the shape of the bottom is very wavy and tortuous. And finally, it succeeded on the third try! Although the printing temperature was set too high, makes it very difficult to take off the support. 

<p align="center">
  <img height="250" src="assets/week3/lampshade3.gif">
  <img height="250" src="assets/week3/lampshade3.jpg">
</p>

From this project, I noticed that I should learn about the constrains of the tools and medium that I’m using, and design the project based on that. For example with 3d printer, it would be much easier to print something with a flat bottom instead of a curly bottom.

<p align="center">
  <img height="250" src="assets/week3/lampshade6.gif">
  <img height="250" src="assets/week3/lampshade7.gif">
</p>

# Week 2 Experiment with Rhino and Grasshopper  #

This week I started with going through a rhino 8 beginner [tutorial](https://www.youtube.com/watch?v=mAXknDTPULE&list=PLWIvZT_UEpWXs6niI0BiWz2xMg0bHbEfs&index=4) to get familiar with the interface and functions of rhino. The tutorial was only 1 hour, but it took me more than one afternoon to follow the tutorial to finally build a chair. I managed to understand some basic but seems to be important rhino concepts during the process, like c plane, planar curves, osnap, pushpull, mirror, inset, scale1D.

<p align="center">
  <img height="400" src="assets/week2/chair1.png">
  <img height="400" src="assets/week2/chair4.png">
</p>
<p align="center">
  <img height="250" src="assets/week2/chair2.png">
  <img height="250" src="assets/week2/chair3.png">
</p>

I also learned grosshopper with this [tutorial](https://www.youtube.com/watch?v=CzmZjo2_3-M) and successfully built a box with a lid. It was interesting to learn and really helpful for understanding the grasshopper graph we got in class. 

<p align="center">
  <img height="400" src="assets/week2/gh2.png">
</p>

One very useful concept from grasshopper is brep. It appears a lot in the example file and I was so confused at first. Later I noticed that brep can be anything and in many cases it’s used for make the diagram clearer and more organized. 

Another useful trick that I learned from Chuhua is that by clicking this little green button in the upper right corner, I can easily preview what I selected in grasshopper. This really helps me to understand what each part of the grasshopper file is doing.

<p align="center">
  <img height="400" src="assets/week2/gh1.png">
</p>

So with help of that, I drew out the diagram of the steps building the shape of the phone stand. 
<p align="center">
  <img height="400" src="assets/week2/diagram1.jpg">
</p>

And then I started to modify the example file to replace some nodes and change the shape of the phone stand.
<p align="center">
  <img height="400" src="assets/week2/gh3.png">
</p>
---

# Week 1 Laser Cutting #

This week, I went through the laser cutting and 3d printing tutorials and quiz. I design and laser cut a coaster with the photo of my dog. It was an interesting experience to custom make something useful by myself. 

I used 3mm plywood to make the cut and the result was really satisfying. This was also a very helpful refresh for using those machines. 

<p align="center">
  <img width="200" alt="a Cool Coaster" src="assets/week1/coaster1.jpg">
  <img width="200" alt="a Cool Coaster" src="assets/week1/coaster2.jpg">
  <img width="200" alt="a Cool Coaster" src="assets/week1/coaster3.jpg">
<img width="200" alt="a Cool Coaster" src="assets/week1/coaster_cutting.gif">
</p>
<p align = "center">
  <img width="500" alt="a Cool Coaster" src="assets/week1/coaster4.png">
</p>

---
## Quick Links: ##

- [TDF Wiki](https://github.com/Berkeley-MDes/24f-desinv-202/wiki) - the ultimate source for truth and information about the course and assignments
- [Google Drive Folder](https://drive.google.com/drive/u/0/folders/1DJ1b6sSDwHXX6NRcQYt10ivyQSgU0ND6) - slides and other resources
- [bCourses](https://bcourses.berkeley.edu/courses/1537533) - where the grading happens
