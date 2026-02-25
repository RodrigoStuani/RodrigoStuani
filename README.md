# Rodrigo Stuani

[![Linkedin Badge](https://img.shields.io/badge/-Rodrigo%20Stuani-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/rodrigo-stuani/)](https://www.linkedin.com/in/rodrigo-stuani/)
[![Gmail Badge](https://img.shields.io/badge/-stuani.developer@gmail.com-red?style=flat-square&logo=Gmail&logoColor=white&link=mailto:stuani.developer@gmail.com)](mailto:stuani.developer@gmail.com)

```js
// Typescript version
const calculateAge = (birthdate: string): number => {
  const birthdateDate = new Date(birthdate);
  const currentDate = new Date();
  const ageInMilliseconds = currentDate - birthdateDate;
  const ageInYears = ageInMilliseconds / (1000 * 60 * 60 * 24 * 365.25);
  return Math.floor(ageInYears);
};

const myResume = (): void => {
  const name: string = 'Rodrigo Stuani';  
  const birthday: string = '1988-06-22T12:05:00';
  const from: string = 'Brazil';
  const age: number = calculateAge(birthday);
  let level: string = 'Software Developer';
  let job: string = 'Sesc-SC';
  let currentStudy: string = 'SRE - observability and monitoring';
  const social: { network: { name: string } }[] = [{
    network: {
      name: "https://www.linkedin.com/in/rodrigo-stuani/"
    }
  }];

  console.log(`Hello, my name is ${name}. I'm ${age} years old and I'm from ${from}. 
               I work as a ${level} at ${job} and currently I'm studying ${currentStudy}. 
               You can find me on LinkedIn at ${social[0].network.name}.`);
};

myResume();

```
<!-- | <a href="https://github-readme-stats.vercel.app"><img align="center" src="https://github-readme-stats.vercel.app/api?username=RodrigoStuani&show_icons=true&theme=dracula&hide_border=true" alt="Rodrigo Stuani github stats" /></a> | <a href="https://github-readme-stats.vercel.app"><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RodrigoStuani&layout=compact&theme=dracula&hide_border=true" /></a> |
| ------------- | ------------- | -->

<!--[![Switch between light and dark mode to see the difference. Click to see the source](https://github.com/pedroor/pedroor/blob/output/github-contribution-grid-snake.svg)](https://github.com/pedroor/pedroor/blob/output/github-contribution-grid-snake.svg)-->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1e90ff,100:00bfff&height=120&section=footer"/>
