# Sessions
### Manipulação de Sessões em PHP

Este repositório contém exemplos de como manipular sessões em PHP para armazenar, modificar e excluir variáveis de sessão. Sessões permitem armazenar dados do usuário de forma persistente durante a navegação, sem depender de cookies diretamente. Este projeto aborda diferentes aspectos do uso de sessões, incluindo criação, modificação, exclusão e finalização de sessões.

#### Funcionalidades:

1. **Criação de Sessões**:
   - Os exemplos mostram como iniciar uma sessão com `session_start()` e definir variáveis de sessão, como nome de usuário e e-mail.
   - Exemplo: `$_SESSION['username'] = 'Rodolfo';`.

2. **Modificação de Sessões**:
   - As variáveis de sessão podem ser modificadas durante a execução do código. Em um dos exemplos, o nome de usuário é alterado de `'Jony Bravo'` para `'Francisvaldo'`.

3. **Exclusão de Variáveis de Sessão**:
   - O projeto mostra como remover variáveis de sessão específicas usando `unset($_SESSION['username']);`, e como verificar se a variável foi excluída.

4. **Exibição de Variáveis de Sessão**:
   - As variáveis de sessão podem ser exibidas diretamente no HTML, facilitando a interação com o usuário e o armazenamento de informações como o país visitado pelo usuário, como no exemplo em que o valor `'França'` é adicionado à sessão.

5. **Finalização de Sessões**:
   - As sessões podem ser completamente encerradas com `session_destroy()`, removendo todos os dados da sessão, e `session_unset()` é usado para limpar as variáveis da sessão sem destruí-la.

#### Aplicações:
- **Autenticação de Usuário**: Sessões são amplamente usadas para manter usuários logados entre diferentes páginas de uma aplicação web.
- **Persistência de Dados Temporários**: Permite que informações como preferências do usuário sejam armazenadas durante a navegação no site, sem a necessidade de salvar em um banco de dados imediatamente.
  
Esses exemplos são uma base simples e eficaz para aprender e implementar sessões em aplicações PHP, garantindo que os dados do usuário sejam gerenciados de maneira segura e eficiente.
