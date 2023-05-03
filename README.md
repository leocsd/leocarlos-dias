
```ts
interface AboutInterface {
  name: string,
  job: string,
  skills: string[],
  educations: { course: string, institution: string, status: string }[]
};

class About {
  constructor(private props: AboutInterface) {
    Object.assign(props, this);
  };

  introduce(): string {
    return `Hello, my name is ${this.props.name} and I'm currently a ${this.props.job}.`;
  };

  showSkills(): string {
    const skills: string = this.props.skills.join(", ");
    return `My skills are:\n${skills}`;
  };

  showCourses(): string {
    const courses: string = this.props.educations.map(education => `${education.course} at ${education.institution} (${education.status})`).join(",\n");
    return `My current courses are:\n${courses}`;
  };
};

const me: AboutInterface = {
    name: "Leonardo Carlos",
    job: "Monitor at Kenzie Academy Brasil",
    skills: [
      "HTML5", "CSS3", "React", "JavaScript", "TypeScript", "NodeJS", 
      "PostgreSQL", "TypeORM", "Prisma", "Java", "Spring Boot"
    ],
    educations: [
      {
        course: "Full Stack Developer",
        institution: "Kenzie Academy Brasil",
        status: "enrolled"
      },
      {
        course: "Electrical Engineering",
        institution: "UniFOA - Volta Redonda University Center",
        status: "enrolled"
      }
    ]
}

const AboutMe = new About(me);

console.log(`
${aboutMe.introduce()}\n
${aboutMe.showSkills()}\n
${aboutMe.showCourses()}
`);
```
