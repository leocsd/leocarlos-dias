```js

class AboutMe {
  constructor() {
    this.name = 'Leonardo Carlos';
    this.job = 'Monitor at Kenzie Academy Brasil';
    this.skills = ['HTML5', 'CSS3', 'React', 'JavaScript', 'TypeScript', 'NodeJS', 
                   'PostgreSQL', 'TypeORM', 'Prisma', 'Java', 'Spring Boot'];
    this.educations = [
      {
        course: 'Full Stack Developer',
        institution: 'Kenzie Academy Brasil',
        status: 'enrolled'
      },
      {
        course: 'Electrical Engineering',
        institution: 'UniFOA - Volta Redonda University Center',
        status: 'enrolled'
      }
    ];
  }

  introduce() {
    console.log(`Hello, my name is ${this.name} and I'm currently a ${this.job}.`);
  }

  showSkills() {
    console.log('My skills are:');
    this.skills.forEach(skill => console.log(`- ${skill}`));
  }

  showCourses() {
    console.log('My current courses are:');
    this.educations.forEach(course => console.log(`- ${course.course} at ${course.institution} (${course.status})`));
  }
}

export default AboutMe;
```
<div>
<a href="https://www.linkedin.com/in/leonardocsdias/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
<a/>

<a href="mailto:leonardocsd.developer@gmail.com" target="_blank">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
<a/>

<a href="https://www.codewars.com/users/leocarlos-dias" target="_blank">
  <img src="https://img.shields.io/badge/Codewars-B1361E?style=for-the-badge&logo=Codewars&logoColor=white" />
<a/>
</div>

<div>
  <a href="https://github.com/seu-usuário-aqui">
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=leocarlos-dias&layout=compact&langs_count=7&theme=dracula"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=leocarlos-dias&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
</div>
