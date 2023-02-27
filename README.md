```js

class AboutMe {
  constructor() {
    this.name = 'Leonardo Carlos';
    this.job = 'Monitor at Kenzie Academy Brasil';
    this.skill = ['HTML5', 'CSS3', 'JavaScript', 'TypeScript', 'NodeJS', 'Java', 'React'];
    this.education = [
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
    this.studies.forEach(course => console.log(`- ${course.course} at ${course.institution} (${course.status})`));
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
