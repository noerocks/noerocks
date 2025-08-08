## Hi there 👋
I am Noe Villamor, an aspiring full stack developer.

<!--
**noerocks/noerocks** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

```js
const aboutMe = {
  name: "Noe Villamor",
  birthday: new Date("2004-07-21"),
  get age() {
    return Math.floor(
      (Date.now() - this.birthday.getTime()) / (1000 * 60 * 60 * 24 * 365.25)
    );
  }, //outputs 21
  hobbies: ["Learning to code", "Music", "Gaming", "Reading documentations"],
  education: "BSIT - 4th year",
  techStack: {
    frontEnd: ["HTML", "CSS", "Tailwind", "Javascript", "Typescript", "React"],
    backEnd: ["NodeJS", "Express", "MongoDB"],
    devTools: ["Git/Github", "Postman", "VSCode"]
  },
};
