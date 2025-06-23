## Localhost305

#### 5º Semestre - [Repositório](https://github.com/Localhost-305/LocalHost305)

Parceiro Acadêmico: [Pro4tech](https://www.pro4tech.com.br/)

O objetivo da aplicação é um dashboard interativo que centraliza e visualiza dados do processo de recrutamento e seleção da empresa. A plataforma permite uma análise em tempo real de métricas como número de candidatos, tempo médio de contratação e custos, gerando relatórios dinâmicos que apoiam decisões estratégicas. Além disso, os usuários podem personalizar relatórios conforme suas necessidades, filtrando informações por critérios relevantes. A ferramenta visa a otimização do processo de recrutamento, identificando padrões e tendências para melhorar a eficiência e alocação de recursos.

### Contribuições Pessoais

<details>

<summary> Visualizar Contribuições como Desenvolvedor </summary> 

<br>

Exemplos de Códigos:

![image](https://github.com/user-attachments/assets/3def0af2-89ac-423b-9b5a-b16b70a31659)

Este trecho do código lida com a autenticação do usuário e o controle de acesso com base em permissões. Os dados (token, nome e permissões) são armazenados no localStorage para uso durante a navegação.

🔑 Permissões armazenadas (como "allowed_to_change") são usadas para restringir ações sensíveis, como edição e exclusão de dados de usuários. Essa abordagem garante que somente usuários autorizados executem essas ações.

A função verifyLoggedIn garante que apenas usuários autenticados possam acessar o sistema. Em caso de token inválido ou ausência de usuário, redireciona para a tela de login.

<br>

![image](https://github.com/user-attachments/assets/5a8f7a92-741f-4e2d-b799-8fca6aef5731)

Este trecho trata da autenticação do usuário e do armazenamento local dos dados essenciais para navegação e controle de acesso
Após o login bem-sucedido, os dados do usuário são salvos no localStorage, incluindo as permissões, que definem o que ele pode acessar ou modificar dentro da aplicação.

<br>

![image](https://github.com/user-attachments/assets/273d4fa0-f117-4c3f-a62b-c3356e6249a6)

Este código representa a lógica aplicada na tela de usuários, responsável por:

- Carregar os dados da API
- Controlar a exibição do modal de edição
- Verificar permissões antes de permitir alterações

Antes de abrir o modal de edição, a aplicação verifica se o usuário logado possui a permissão "allowed_to_change".
Se não tiver, uma mensagem de erro é exibida e a ação é bloqueada, evitando modificações indevidas em dados pessoais.

<br>

</details>

### Lições Aprendidas

Durante o desenvolvimento do projeto Localhost305, tive a oportunidade de crescer tecnicamente e profissionalmente, explorando novas tecnologias e atuando de forma mais ativa na colaboração e suporte entre membros da equipe. Essa experiência foi marcante por me permitir aplicar conhecimentos em React e TypeScript, além de participar da integração com ferramentas de DevOps e contribuir para o desenvolvimento coletivo da equipe.

Aprendizado Técnico Colaborativo:
- Aprender React foi um dos grandes marcos desse projeto. Trabalhei em estreita colaboração com um colega mais experiente, o que acelerou meu entendimento sobre componentes, estados e boas práticas no desenvolvimento de interfaces. Esse aprendizado colaborativo foi essencial para minha evolução como desenvolvedor front-end e reforçou a importância da troca de conhecimento dentro da equipe.

Desenvolvimento da Comunicação Técnica:
- Conforme fui ganhando confiança no uso das tecnologias, comecei a ajudar membros que enfrentavam dificuldades. Ensinar colegas me levou a uma comunicação mais clara e, além de consolidar meu próprio entendimento. Essa troca fortaleceu o trabalho em equipe e contribuiu para um ambiente mais colaborativo e produtivo.

Integração com DevOps
- Outra experiência relevante foi a realização de testes de integração em conjunto com a equipe de DevOps. Entender como as aplicações se comportam no ambiente de entrega contínua ampliou minha visão sobre o ciclo de vida de um software. Passei a compreender melhor a importância da estabilidade, testes automatizados e integração contínua para garantir entregas mais confiáveis.

Flexibilidade e Adaptação
- O projeto exigiu adaptações constantes, tanto em termos técnicos quanto organizacionais. A necessidade de lidar com diferentes demandas, ferramentas e fluxos de trabalho me forçou a sair da zona de conforto e a exercitar a flexibilidade, característica essencial para ambientes de desenvolvimento ágil.

### Hard Skills e Soft Skills

<table>
      <th>Hard Skills</th>
      <th>Soft Skills</th>
      </thead>
      <tbody>
        <tr>
         <td>Java</td>
         <td>Escuta ativa</td>
        </tr>
        <tr>
         <td>DevOps</td>
         <td>Trabaho em equipe</td>
        </tr>
        <tr>
         <td>Teste de Integração</td>
         <td>Análise Crítica</td>
        </tr>
        <tr>
         <td>React</td>
         <td>Criatividade</td>
        </tr>
        <tr>
         <td>TypeScript</td>
         <td>Flexibilidade</td>
        </tr> 
        <tr>
         <td>MySQL</td>
         <td>Colaboração</td>
        </tr>
      </tbody>
</table>

### Tecnologias Utilizadas

<br>

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" target="_blank"><img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" target="_blank"><img src="https://shields.io/badge/react-black?logo=react&style=for-the-badge"><img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"><img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" target="_blank">
