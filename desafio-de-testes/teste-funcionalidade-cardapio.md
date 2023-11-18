
## Funcionalidade 1 -  Cadastro de cardápios

**Variaveis**
input = caixa de entrada;


### Cenário de Teste: Funcionalidade na pagina de cadastro cardápio


### passos:
  **1. O avaliador verifica se a pagina está no endereço certo:**
        verifica se a pagina está no endereço do painel de administração do sistema;
  **2. O avaliador buscará a opção de cadastro do cardápio:**
        verifica se existe algum elemento da pagina com o rotulo "Cadastro de cardapios";
  **3. O avaliador buscará por o elemento para seleção do restaurante desejado:**
        verifica se existe algum elemento da pagina com o rotulo "restaurantes";
  **6. O avaliador buscará por elementos fundamentais aos demais testes:**
        verifica se existe input para "nome do cardapio"
        verifica se existe input para "decrição do cardapio"
        verifica se existe input para "nome do item";
        verifica se existe input para "descrição do item";
        verifica se existe input para  "preço do item";
  **7. O avaliador buscará o botão:**
        verifica se existe botão com o rotulo "salvar";




### Cenário de Teste: Cadatro bem-sucedido


**1. O avaliador verifica o elemento "nome do cardapio":**
        verifica se o input com o rotulo "nome do cardapio" está preenchido;
        verifica se o valor do input com o rotulo "nome do cardapio" não existe no banco de dados;
**2. O avaliador verifica o elemento "descrição do cardapio":**
        verifica se o input com o rotulo "descrição do cardapio" está preenchido;

**3. O avaliador verifica o elemento "nome do item":**
        verifica se o input "nome do item" está preenchido;
**4. O avaliador verifica o elemento "descrição do item":**
        verifica se o input "descrição do item" está preenchido;
**5. O avaliador verifica o elemento "preço do item":**
        verifica se o input "preço do item" está preenchido;
        verifica se o valor do input "preço do item" é valido;
**6. O avaliador verifica click do botão "Salvar":**
        verifica se existe um elemento com o rotulo " mensagem de confirmação";
    **6.1 O avaliador navegará para o endereço de " lista de cardápios cadastrados":**
            verifica se a pagina redirecionada é "lista de cardápios cadastrados";


### Resultado Esperado:
  * Existencia dos elementos essenciais para realizar o cadastro do cardapio
  * O sistema exibe uma mensagem de confirmação.
  * O usuário é redirecionado para a lista de cardápios cadastrados.



### Cenário de Teste: Cadastro Mal-Sucedido


**1. O avaliador verifica o elemento "nome do cardapio":**
  Verifica se o input "nome do cardapio" está vazio;
  verifica se o sistema exibe erro para input "nome do cardapio" vazio;
  verifica se o sistema exibe erro se  valor do input com o rotulo "nome do cardapio" já existir no banco de dados;
**2. O avaliador verifica o elemento "descrição do cardapio":**
    Verifica se o input "descrição do cardapio" está vazio;
    verifica se o sistema exibe erro para input "descrição do cardapio" vazio;
**3. O avaliador verifica o elemento "nome do item":**
    Verifica se o input "nome do item" está vazio;
    verifica se o sistema exibe erro para input "nome do item" vazio;
**4. O avaliador verifica o elemento "descrição do item":**
    Verifica se o input "descrição do item" está vazio;
    verifica se o sistema exibe erro para input "descrição do item" vazio;
**5. O avaliador verifica o elemento "preço do item":**
    Verifica se o input "preço do item" está vazio;
    verifica se o sistema exibe erro para input "preço do item" vazio;
    Verifica se o valor input "preço do item" é invalido;
    verifica se o sistema exibe erro para input "preço do item" invalido;
**6. O avaliador verifica do botão "Salvar":**
    verifica se ao clicar no elemento botão "salvar" o sistema retorna erro informando a existencia de dados vazios;
    verifica se ao clicar no elemento botão "salvar" o sistema retorna erro informando a existencia de dados invalidos;
    verifica se a pagina permanece na pagina "painel de administração do sistema"

### Resultado Esperado:
   * O sistema exibe uma mensagem de erro para cada valor invalido.
   * O sistema exibe uma mensagem de erro para cada valor vazio.
   * Em casos de valores invalidos a pagina permanece no mesmo endereço de pagina
