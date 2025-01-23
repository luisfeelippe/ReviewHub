# ReviewHub - Plataforma de Correção de Redações
### A ReviewHub é uma plataforma inovadora em desenvolvimento, que utiliza inteligência artificial para oferecer correções detalhadas e personalizadas de redações, totalmente alinhadas às competências avaliadas no ENEM.

## Principais Funcionalidades do Sistema

### Módulo de Início:
O módulo inicial apresenta informações sobre como o sistema utiliza os mesmos critérios de avaliação do ENEM.

input de Tema: Campo obrigatório onde o usuário digita o tema da redação. Caso o tema esteja desalinhado, pontos serão descontados, assim como na prova oficial.

Sugestão de Tema: Para usuários indecisos, há um botão que ativa a IA para sugerir temas relevantes, auxiliando na escolha.

![ReviewHub 001](https://github.com/user-attachments/assets/f20aac69-fa63-490a-86d1-39f4d0d916bf)
![ReviewHub 002](https://github.com/user-attachments/assets/17467af4-d2ce-4a24-8884-53954c1ec3b4)



### Módulo de Envio de Redação:
Após definir o tema, o sistema oferece duas opções para envio da redação:

![ReviewHub 003](https://github.com/user-attachments/assets/eafef64f-f456-4520-874e-6a495eef2fcb)

### Upload de Arquivo: (Print do Figma) 

Aceita formatos PDF, Word ou TXT.
![ReviewHub 007](https://github.com/user-attachments/assets/93483493-d738-4fa1-8e17-f7117bcad430)


### Prosseguir:

a opção de prosseguir do sistema oferece uma interface interativa com os seguintes campos:

- Título (opcional)
- Introdução (obrigatório)
- Desenvolvimento 1 (obrigatório)
- Desenvolvimento 2 (opcional, mas sua ausência impacta na nota)
- Conclusão (obrigatório)
O sistema valida os campos obrigatórios antes de prosseguir.

![ReviewHub 004](https://github.com/user-attachments/assets/5823bfaa-e9af-444e-9d72-dcedad83efeb)
![ReviewHub 005](https://github.com/user-attachments/assets/85c65e5d-9555-4141-b3ee-c00d16661081)
![ReviewHub 006](https://github.com/user-attachments/assets/59f088b4-4377-48d6-aeaf-72b94e8fa997)


### Tela de Login:

Caso o usuário não esteja logado, uma tela de login é exibida com as opções:

Caso o usuario não queira digitar o email e a senha ele poderar acessar usando a conta dele do google:

![ReviewHub 008](https://github.com/user-attachments/assets/f4845633-66c9-4219-9ea4-38bc4c9a1a89)

### Tela de Cadastro:

Caso o usuario não tenha conta e não queira acessar com o google ele poderar criar uma conta no sistema preenchendo os seguintes campos:

![ReviewHub 009](https://github.com/user-attachments/assets/61f269bd-396a-494c-88f0-227b7b0013a6)

os campos tem algumas validações: 
- Nome e sobrenome
- e-mails com domínio permitido
- validação de senha forte e confirmação de idade (entre 08 e 100 anos).
- Aceitação de Termos: Modal explicativo com os termos de uso.
- Google reCAPTCHA: Garantindo segurança contra bots.
  
![ReviewHub 012](https://github.com/user-attachments/assets/b5f7cd03-25a2-4644-bfe2-62b12a9564eb)

![ReviewHub 013](https://github.com/user-attachments/assets/c329d999-19b6-4252-8829-441dc94d547c)

![ReviewHub 014](https://github.com/user-attachments/assets/905508a2-85b9-40a2-940e-2451ff21b495)

![ReviewHub 010](https://github.com/user-attachments/assets/09b14831-dc35-44e2-bc1e-7d8cec4484e8)

![ReviewHub 011](https://github.com/user-attachments/assets/7f7d6a5a-1f44-49d6-946c-e6f8b3e68650)


### Dashboard: (Print do Figma)

O dashboard do sistema é intuitivo, com opções de tema claro ou escuro, exibindo:

- Botões de Escrever Redação ou Fazer Upload.

![ReviewHub 015](https://github.com/user-attachments/assets/aadbd47c-499c-4beb-b4bb-ef82c438a2b1)



### Perfil do Usuário: (Print do Figma)

- Alteração de foto de perfil.
- Visualização da melhor nota, média de notas, e redações enviadas.
- Modal com gráfico de desempenho detalhado das notas.

![ReviewHub 016](https://github.com/user-attachments/assets/111520e8-8aa9-45d2-8417-8d31710d7e57)


## Em Desenvolvimento:
### O sistema ainda está em fase de evolução, com novos módulos e recursos planejados para serem implementados. Prints do protótipo no Figma estão sendo usados para guiar o desenvolvimento das próximas etapas.

## Tecnologias Utilizadas:

### Front-End: 
HTML, CSS, JavaScript, AJAX

### Back-End: 
PHP, MySQL

### Integrações: 
Cohere AI (análise de redações), Google reCAPTCHA
Gestão de Projetos: Git/GitHub
