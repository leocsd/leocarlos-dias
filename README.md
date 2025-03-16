```ts
// Olá, eu sou o Leonardo Carlos!
// Aqui está um pouco sobre mim:

interface AboutProps {
    name: string;
    job: string;
    skills: string[];
    educations: { course: string; institution: string; status: string }[];
}

const me: AboutProps = {
        name: "Leonardo Carlos",
        job: "Software Developer at Embeddo Computação Aplicada",
        skills: [
            "HTML5", "CSS3", "React", "JavaScript", "TypeScript", "Next.js", "Node.js",
            "Express.js", "NestJS", "PostgreSQL", "MongoDB", "Redis", "SQL", "NoSQL",
            "TypeORM", "Prisma", "Jest", "Java", "Spring Boot", "PHP", "Laravel", "Docker",
            "Kafka", "RESTful", "GraphQL", "AWS"
        ],
        educations: [{
            course: "Electrical Engineering",
            institution: "UniFOA - Volta Redonda University Center",
            status: "completed"
        },
        {
            "course": "Industrial Automation Technician",
            "institution": "SENAI",
            "status": "completed"
        }]
};

class About {
    constructor(private props: AboutProps) {
        Object.assign(props, this);
    }
};

const aboutMe = new About(me);
```
