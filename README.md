```js

class SobreMim {
  constructor() {
    this.nome = 'Leonardo Carlos';
    this.trabalho = 'Monitor na Kenzie Academy Brasil';
    this.habilidades = ['HTML5', 'CSS3', 'JavaScript', 'TypeScript', 'NodeJS', 'React'];
    this.estudo = [
      {
        curso: 'Desenvolvedor Full Stack',
        instituicao: 'Kenzie Academy Brasil',
        status: 'cursando'
      },
      {
        curso: 'Engenharia Elétrica',
        instituicao: 'UniFOA - Centro Universitário de Volta Redonda',
        status: 'cursando'
      }
    ];
  }

  apresentar() {
    console.log(`Olá, meu nome é ${this.nome} e atualmente sou ${this.trabalho}.`);
  }

  mostrarHabilidades() {
    console.log('Minhas habilidades são:');
    this.habilidades.forEach(habilidade => console.log(`- ${habilidade}`));
  }

  mostrarCursos() {
    console.log('Meus cursos em andamento são:');
    this.estudo.forEach(curso => console.log(`- ${curso.curso} na instituição ${curso.instituicao} (${curso.status})`));
  }
}

export default SobreMim;
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
