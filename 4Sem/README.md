## B1nary Inspec

#### 4º Semestre - [Repositório](https://github.com/B1nary-Devs/JAIA-SOFTWARE)

Parceiro Acadêmico: [Jaia Software](https://www.jaia.software/)

O sistema tem o objetivo de controlar anomalias identificadas em um Laudo de Inspeção Predial, com funcionalidades-chave como diferenciação de segmentos específicos de um edifício, cadastro de prestadores de serviço, geração eficiente de ordens de serviço e criação de relatórios detalhados. Esse sistema é crucial para melhorar a gestão e eficácia na correção de anomalias, promovendo a preservação do patrimônio e tomada de decisões informadas.

A equipe desenvolveu um sistema web abrangente que simplifica a gestão de prestadores de serviço, segmentos e ordens de serviço. Como parte deste projeto, foi realizado uma landing page intuitiva que facilita a solicitação de novas ordens de serviço para os nossos novos clientes por meio de um simples formulário. Além disso poderão acessar facilmente suas ordens de serviço anteriores, baixar laudos e fornecer feedbacks, incluindo sugestões e reclamações. Além disso, eles também tem a opção de fazer novas solicitações de ordens de serviço. <br>

### Contribuições Pessoais

<details>

<summary> Visualizar Contribuições como Desenvolvedor </summary> 

<img width="476" alt="image" src="https://github.com/user-attachments/assets/a86190e1-ce18-4f2e-b2cf-f0667b7d46d1">

O código apresentado é uma função assíncrona chamada salvarAlteracoes, que tem como objetivo atualizar os dados de uma ordem de serviço. Dentro do try, o código busca executar uma operação. Caso algo dê errado durante a execução, o erro será capturado no bloco catch, permitindo que haja tratamento do erro e evite que a aplicação quebre. 

A função faz uma requisição HTTP do tipo PUT utilizando a biblioteca axios para enviar dados para o servidor. O objetivo é atualizar uma ordem de serviço no backend. A URL da requisição é dinâmica, incluindo o idOrdem.value que é o identificador da ordem de serviço a ser editada.

O corpo da requisição contém os dados a serem atualizados e o cabeçalho da requisição inclui um token de autorização no formato Bearer ${token}, que é utilizado para autenticar a requisição no servidor. 
<br>

</details>

### Lições Aprendidas

- Primeira Experiência com Vue.js: Este projeto marcou o primeiro contato com o framework Vue.js. O processo envolveu entender a estrutura de componentes, o uso de diretivas, reatividade e comunicação entre componentes. Apesar dos desafios iniciais, o framework se mostrou eficiente e produtivo para construção de interfaces dinâmicas.

- Integração com APIs: Aprender a realizar requisições HTTP com a biblioteca Axios, especialmente utilizando métodos como PUT para atualizar dados, foi essencial. A manipulação correta de URLs dinâmicas e o envio de tokens de autenticação no cabeçalho também reforçou conhecimentos sobre segurança e boas práticas em APIs RESTful.

- Valor da Experiência do Usuário: A criação de uma landing page simples e funcional para novos clientes mostrou como uma interface acessível pode facilitar a interação, incentivar o uso e permitir feedbacks valiosos.

### Hard Skills e Soft Skills

<table>
      <thead>
        <th>Hard Skills</th>
        <th>Soft Skills</th>
      </thead>
      <tbody>
        <tr>
         <td>Java</td>
         <td>Comunicação</td>
        </tr>
        <tr>
         <td>TypeScript</td>
         <td>Adaptabilidade</td>
        </tr>
        <tr>
         <td>Vue.js</td>
         <td>Análise</td>
        </tr>
        <tr>
         <td>Oracle</td>
         <td>Responsabilidade</td>
        </tr>   
      </tbody>
</table>

### Tecnologias Utilizadas

<br>

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" target="_blank"><img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D"><img src="https://img.shields.io/badge/axios.js-854195?style=for-the-badge&logo=axios&logoColor=5A29E4"><img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" target="_blank"><img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=Oracle&logoColor=white">
