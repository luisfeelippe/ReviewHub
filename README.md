# ReviewHub - Plataforma de Correção de Redações
### A ReviewHub é uma plataforma inovadora em desenvolvimento, que utiliza inteligência artificial para oferecer correções detalhadas e personalizadas de redações, totalmente alinhadas às competências avaliadas no ENEM.

## Principais Funcionalidades do Sistema

### Módulo de Início:
O módulo inicial apresenta informações sobre como o sistema utiliza os mesmos critérios de avaliação do ENEM.

input de Tema: Campo obrigatório onde o usuário digita o tema da redação. Caso o tema esteja desalinhado, pontos serão descontados, assim como na prova oficial.

Sugestão de Tema: Para usuários indecisos, há um botão que ativa a IA para sugerir temas relevantes, auxiliando na escolha.

![ReviewHub 001](https://github.com/user-attachments/assets/d082967f-7b63-4a5c-bcb7-96fac17e5ce9)
![ReviewHub 002](https://github.com/user-attachments/assets/313e9a30-3fb2-4a33-8d76-39a184b4a33c)


### Módulo de Envio de Redação:
Após definir o tema, o sistema oferece duas opções para envio da redação:

![ReviewHub 003](https://github.com/user-attachments/assets/a94c345d-f443-4463-a644-b2e0bd754bdd)


### Upload de Arquivo: (Print do Figma) 

Aceita formatos PDF, Word ou TXT.

![ReviewHub 007](https://github.com/user-attachments/assets/9e4d9ba2-d954-420e-91b1-6a701c337698)


### Prosseguir:

a opção de prosseguir do sistema oferece uma interface interativa com os seguintes campos:

- Título (opcional)
- Introdução (obrigatório)
- Desenvolvimento 1 (obrigatório)
- Desenvolvimento 2 (opcional, mas sua ausência impacta na nota)
- Conclusão (obrigatório)
O sistema valida os campos obrigatórios antes de prosseguir.

![ReviewHub 004](https://github.com/user-attachments/assets/68f34473-a5b1-469c-9948-57cb6848142b)
![ReviewHub 005](https://github.com/user-attachments/assets/c4b780cd-df85-45c7-b665-2930b3908ad5)
![ReviewHub 006](https://github.com/user-attachments/assets/6adac8e0-80ba-4a8c-936e-b5547945bd76)


### Tela de Login:

Caso o usuário não esteja logado, uma tela de login é exibida com as opções:

Caso o usuario não queira digitar o email e a senha ele poderar acessar usando a conta dele do google:

![ReviewHub 008](https://github.com/user-attachments/assets/8b5ca069-c604-4206-bab7-684c047bcf58)


### Tela de Cadastro:

Caso o usuario não tenha conta e não queira acessar com o google ele poderar criar uma conta no sistema preenchendo os seguintes campos:

![ReviewHub 009](https://github.com/user-attachments/assets/21053864-ba48-43e3-b0f5-271fef9a4e5d)

os campos tem algumas validações: 
- Nome e sobrenome
- e-mails com domínio permitido
- validação de senha forte e confirmação de idade (entre 08 e 100 anos).
- Aceitação de Termos: Modal explicativo com os termos de uso.
- Google reCAPTCHA: Garantindo segurança contra bots.
  
![ReviewHub 012](https://github.com/user-attachments/assets/dfa9e6cb-0839-4064-87ef-2198c92c0851)

![ReviewHub 013](https://github.com/user-attachments/assets/b9700d41-4c92-4901-a99d-1eb86c57d2f7)

![ReviewHub 014](https://github.com/user-attachments/assets/e1e05b1b-8919-45b2-96ce-f65706033348)

![ReviewHub 010](https://github.com/user-attachments/assets/b2979e3b-72db-4bde-9bc0-93e38b9733b8)

![ReviewHub 011](https://github.com/user-attachments/assets/3ebfb360-eba1-43c7-b9c9-979c0e386b91)

### Dashboard: (Print do Figma)

O dashboard do sistema é intuitivo, com opções de tema claro ou escuro, exibindo:

- Botões de Escrever Redação ou Fazer Upload.

![ReviewHub 015](https://github.com/user-attachments/assets/3c5a98d2-d98f-4c3f-98cb-a50be3c8ed54)



### Perfil do Usuário: (Print do Figma)

- Alteração de foto de perfil.
- Visualização da melhor nota, média de notas, e redações enviadas.
- Modal com gráfico de desempenho detalhado das notas.

![ReviewHub 016](https://github.com/user-attachments/assets/46ac2629-72ab-4f33-914e-8db7e39ba2d4)


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
