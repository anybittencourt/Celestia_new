Nosso site é dedicado à venda de astros celestes, e com isso surgiu a ideia do nome Celestia. Criamos uma logo com uma meia-lua e optamos por usar a cor azul escuro para estilizar o site e fizemos um esboço do layout no Figma para guiar nosso desenvolvimento.
Na parte superior do site, o header inclui a logo, uma barra de pesquisa, três ícones com imagens e um botão para adicionar produtos. Você pode navegar pelo site sem precisar de uma conta. Caso queira se cadastrar ou fazer login, há uma opção de registro, onde serão solicitados nome, e-mail e senha. Depois de preencher os dados e clicar em "cadastrar" ou "entrar", suas informações serão salvas no banco de dados. Você também pode sair e se desconectar a qualquer momento.
No corpo do site, você encontrará os produtos à venda, com seus respectivos nomes, descrições, preços, um coração para favoritá-los e um botão para adicioná-los ao carrinho. Ao clicar no coração, ele ficará vermelho, isso significa que o produto foi adicionado aos favoritos. Portanto, se clicar no ícone de coração no canto superior direito do site, todos os ítens que foram favoritados aparecerão em uma lista, podendo removê-los quando quiser. Ao clicar no botão de adicionar ao carrinho, uma mensagem confirmará que o produto foi adicionado ao carrinho. O ícone de carrinho no canto superior direito exibe todos os produtos adicionados, com a opção de removê-los. Neste mesmo modal, há um botão para finalizar a compra, que abrirá uma nova página onde você poderá inserir informações como nome completo, endereço, cidade, CEP e meio de pagamento para concluir a compra.
Para os administradores, existe a opção de incluir novos produtos no catálogo. Ao clicar em 'Adicionar Produto' no canto superior direito, um modal será exibido, solicitando o nome, descrição, preço e a possibilidade de escolher um arquivo para adicionar a imagem do produto.

Instruções para Configuração e Teste do Banco de Dados e APIs:
1. Acesse a pasta pelo Git Bash.
2. Execute `npm start`.
3. Para testar as APIs relacionadas ao cadastro de novos usuários:
Cadastrar Novo Usuário: POST para http://localhost:3002/cadastro/cadastrar
Listar Usuários: GET para http://localhost:3002/cadastro/listar
Editar Usuário: PUT para http://localhost:3002/cadastro/editar/:id
Deletar Usuário: DELETE para http://localhost:3002/cadastro/deletar/:id
4. Para o cadastro de novos produtos, substitua “cadastro” por “produtos” nos endpoints e ajuste as informações no "request body".
