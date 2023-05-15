
```ts
interface IAbout {
    name: string,
    job: string,
    skills: string[],
    educations: { course: string, institution: string, status: string }[]
};

const me: IAbout = {
        name: "Leonardo Carlos",
        job: "Monitor at Kenzie Academy Brasil",
        skills: [
            "HTML5", "CSS3", "React", "JavaScript", "TypeScript", "NodeJS",
            "Express.js", "Nest.js", "PostgreSQL", "TypeORM", "Prisma", "Jest",
            "Java", "Spring Boot"
        ],
        educations: [{
            course: "Full Stack Developer",
            institution: "Kenzie Academy Brasil",
            status: "enrolled"
        },
        {
            course: "Electrical Engineering",
            institution: "UniFOA - Volta Redonda University Center",
            status: "enrolled"
        }]
    };

class About {
    constructor(private props: IAbout) {
        Object.assign(props, this);
    };
};

const aboutMe = new About(me);
`);
```
