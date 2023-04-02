### Hello World! 👋 I am Yiling

<!--
**610yilingliu/610yilingliu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

- Bachelor of Applied Math, Xiamene University; Master of Information Technology, the University of Western Australia
- Game player -> Game designer -> Programmer. Game is fun -> Designing game for players to play is fun -> Coding makes me like a God to create what I want!
- she/her
- Chinese/English
- ByteDance E-commerce Data Scientist(Hangzhou 2021.8.20-2023.4.11) -> Findex Data Scientist(Perth 2023.4.24-)

Script (Windows) for UWA students to merge audio file and video file downloaded from Lecture Recording System(needs ffmpeg):
```
@set  /p aname=Enter Audio File Name: 
@set  /p vname=Enter Video File Name: 
@set  /p outname=Enter Compounded File Name: 
ffmpeg -i %aname% -i %vname% -vcodec copy -acodec copy %outname%
pause
```
