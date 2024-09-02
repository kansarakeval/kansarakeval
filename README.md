## Hi there 👋

<!--
**kansarakeval/kansarakeval** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# 👋 Hi, I'm Keval Kanasara!

### 🌍 About Me
I’m a passionate developer from India, specializing in Flutter and Android development. With a deep love for coding and problem-solving, I’ve worked on various projects that showcase my skills in building powerful, user-friendly mobile applications.

### 💻 Skills
- **Programming Languages:** C, C++, Java, Kotlin, Dart, PHP
- **Frameworks & Tools:** Flutter, Android Studio, VSCode
- **Backend & APIs:** Firebase, RESTful APIs
- **Design:** Figma
  
### 🚀 What I Do
I focus on crafting mobile applications with seamless user experiences. My work ranges from developing chat applications with Firebase integration to building AI-driven chatbot apps using APIs and creating dynamic quiz applications with PHP and API integrations.

### 🌱 Currently Learning
I’m continuously expanding my knowledge in mobile app development, exploring advanced Flutter features, and diving deeper into backend services.

### 📫 Let's Connect
Feel free to reach out if you want to collaborate on a project, need help with Flutter, or just want to chat about tech!

---

**Keval Kanasara**

from PIL import Image, ImageSequence

# Load images
images = [Image.open(image) for image in ['frame1.png', 'frame2.png', 'frame3.png']]

# Save as GIF
images[0].save('output.gif', save_all=True, append_images=images[1:], duration=500, loop=0)

