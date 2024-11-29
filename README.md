# #2 - INGRESSO BUY - Sistema de Compra de Ingressos
**IngressoBuy** é uma plataforma online para compra de ingressos para cinemas. O sistema permite aos usuários fazerem login, visualizar filmes disponíveis e comprar ingressos de maneira interativa.

## Objetivo do Projeto
O projeto acadêmico foi desenvolvido com o objetivo de oferecer uma plataforma simples e eficiente para a compra de ingressos de cinema. As funcionalidades principais incluem:
- Login de usuário pré estabelecidos: "**Paulo**" ou "**Maria**"
  Senha: "**1234**" ou "**4567**", respectivamente.
- Visualização e interação com banners de filmes.
- Compra de ingressos.
- Gerenciamento de sessões de usuários para manter o estado do login.

## Funcionalidades
1. **Login de Usuário**:
   - Permite o registro e login dos usuários, com controle de sessão para manter o estado de login ativo.
   
2. **Página de Filmes**:
   - Exibe filmes disponíveis, permitindo aos usuários interagir com banners e obter mais detalhes sobre cada filme.

3. **Compra de Ingressos**:
   - Após o login, o usuário pode acessar uma página exclusiva de compra de ingressos (`Compra.php`).

4. **Uso de Sessões**:
   - Através da função `session_start()`, os dados do usuário são armazenados na sessão, permitindo a navegação sem a necessidade de fazer login novamente.
   - O usuário pode se deslogar utilizando `session_destroy()`.

## Tecnologias Utilizadas
- **PHP**: Para o controle de sessões e manipulação de dados no servidor.
- **HTML/CSS**: Para a estruturação e estilização das páginas.
- **JavaScript**: Para animações e interatividade na página de compra, como as setas de navegação na página de compras.
- **MySQL** (provavelmente): Para o armazenamento de dados dos filmes e usuários.

## Estruturas Utilizadas no Código
- **PHP**: Estruturas condicionais como `if`, `switch`, e operadores lógicos (`&&`, `||`) para controle de fluxo e validação de formulários.
- **Variáveis Superglobais**: Como `$_GET` e `$_POST`, usadas para capturar e processar os dados dos formulários.
- **JavaScript**: Para adicionar interatividade nas páginas, como animações e navegação.

## Como Rodar o Projeto
1. Faça o clone deste repositório.
2. Certifique-se de que o seu ambiente tem PHP e MySQL configurados.
3. Abra os arquivos PHP no seu servidor local (ex: WAMP).
4. Acesse o projeto no navegador.

## Layout
**Seguem fotos do layout:**
![home.PNG](https://github.com/user-attachments/assets/64177ba5-958e-462e-9c6f-f9277b25bf45)
![home1.PNG](https://github.com/user-attachments/assets/91f8bdf9-390d-4a20-8bc8-e5dc12fa1ca2)
![compra.PNG](https://github.com/user-attachments/assets/6a6ba916-6e87-4cf5-bb09-4221321caeac)
![contate-nos.PNG](https://github.com/user-attachments/assets/a9c9ae0c-c92b-474b-a50f-86ed27d59a39)
![sobre-nos.PNG](https://github.com/user-attachments/assets/8295aafd-cf6a-469f-a67f-5fb8f08f235c)

## Contribuições
Contribuições são bem-vindas! Se você tiver sugestões ou melhorias, fique à vontade para abrir uma *issue* ou enviar um *pull request*.
