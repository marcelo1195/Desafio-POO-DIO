Desafio de Projeto sobre Java e POO - DIO Bootcamp
Sobre o Projeto
Este repositório contém a solução de um desafio de projeto proposto na plataforma Digital Innovation One (DIO) como parte do bootcamp de programação orientada a objetos (POO) com Java.

O projeto simula uma plataforma de bootcamp que permite a criação e gestão de cursos, mentorias e inscrições de desenvolvedores (Devs). Cada Dev pode se inscrever em um bootcamp, progredir ao completar os conteúdos inscritos e acumular experiência (XP) com base na conclusão de cursos e participação em mentorias.

Funcionalidades
Criação de Bootcamp: Permite configurar um bootcamp com uma lista de cursos e mentorias.
Inscrição de Devs: Devs podem se inscrever no bootcamp e ter acesso ao conteúdo disponível.
Progressão e Conclusão de Conteúdo: Devs podem avançar no conteúdo inscrito, acumulando XP e marcando conteúdos como concluídos.
Gestão de Cursos e Mentorias: Cada curso e mentoria tem seu próprio tempo e descrição, influenciando no cálculo de XP.
Controle de Conclusão de Bootcamp: Mantém o controle dos Devs que concluíram o bootcamp.
Tecnologias Utilizadas
Java 8
POO (Classes, Herança, Polimorfismo, Encapsulamento)
Collections Framework (especialmente LinkedHashSet para ordenação e unicidade)
Como Executar
Para rodar o projeto, você precisará ter o Java instalado em sua máquina. Clone o repositório, navegue até a pasta raiz do projeto e compile os arquivos fonte com o seguinte comando:

bash
Copy code
javac -d . src/br/com/dio/desafio/dominio/*.java
Em seguida, execute a classe Main com o comando:

bash
Copy code
java br.com.dio.desafio.dominio.Main
Licença
Distribuído sob a licença MIT. Veja LICENSE para mais informações.
