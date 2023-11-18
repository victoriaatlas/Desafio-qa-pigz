
## Funcionalidade 1 - Cadastro de novos restaurantes

**Variaveis**
input = caixa de entrada;


### Cenário de Teste: Funcionalidades na pagina de cadastro restaurantes


#### passos:
  **1. O avaliador verifica se a pagina está no endereço certo:**
    verifica se a pagina está no endereço do  painel de administração do sistema;
  **2. O avaliador buscará elemento com a opção de cadastro:**
    verifica se existe algum elemento da pagina com o rotulo "Cadastro de restaurantes";
  **3. O avaliador buscará pelos elementos fundamentais aos cadastro:**
    verifica se existe input para para "nome";
    verifica se existe input para para "endereço";
    verifica se existe input para para "telefone";
    verifica se existe input para para "CNPJ";
  **4. O avaliador buscará pelos elementos de endereço:**
    verifica se existe input para "rua";
    verifica se existe input para "número";
    verifica se existe input para "complemento";
    verifica se existe input para "bairro";
    verifica se existe input para "cidade";
    verifica se existe input para "estado";
    verifica se existe input para "CEP";
  **5. O avaliador buscará o botão para submeter informações:**
    verifica se existe botão com o rotulo "salvar";



### Cenário de Teste: Cadatro bem-sucedido


#### passos:
  **1. O avaliador verifica input "nome":**
    verifica se o input "nome" está preenchido;
  **2. O avaliador verifica input "endereço":**
    verifica se o input "endereço" está preenchido;
     **2.1 O avaliador verifica os elementos de "endereço":**
        verifica se o input "rua" está preenchido;
        verifica se o input "número" está preenchido;
        verifica se o input "complemento" está preenchido;
        verifica se o input "bairro" está preenchido;
        verifica se o input "cidade" está preenchido;
        verifica se o input "estado" está preenchido;
        Verifica se o input "CEP" está preenchido;

  **3. O avaliador verifica input "telefone":**
    verifica se o input "telefone" está preenchido;
    verifica se o valor do input  "telefone" é valido;
  **4.O avaliador verifica input "CNPJ":**
    verifica se o input "endereço" está preenchido;
    verifica se o input "endereço" está preenchido corretamente;
    verifica se existe dois restaurantes com o mesmo CNPJ;
  **5. O avaliador verifica do botão "Salvar":**
    verifica se ao clicar no elemento botão "salvar" osistema retorna um elemento com o rotulo " mensagem de confirmação";
    **5.1 O avaliador navegará para o endereço de "lista de restaurantes cadastrados":**
        verifica se a pagina redirecionada é "lista de restaurantes cadastrados";
       


### Resultado Esperado:
  * Existencia dos elementos essenciais para realizar o cadastro restaurantes
  * O sistema exibe uma mensagem de confirmação.
  * O usuário é redirecionado para a lista de restaurantes cadastrados.




### Cenário de Teste: Cadatro mal-sucedido



**1. O avaliador verifica input "nome":**
    verifica se o input "nome" está vazio;
    verifica se o sistema exibe erro para input "nome" vazio;
**2. O avaliador verifica input "endereço":**
    verifica se o input "endereço" está vazio;
    verifica se o sistema exibe erro para input "endereço" vazio;
     **2.1 O avaliador verifica os elementos de "endereço":**
        verifica se o input "rua" está vazio;
        verifica se o sistema exibe erro para input "rua" vazio;

        verifica se o input "número" está vazio;
        verifica se o sistema exibe erro para input "número" vazio;

        verifica se o input "complemento" está vazio;
        verifica se o sistema exibe erro para input "omplemento" vazio;

        verifica se o input "bairro" está vazio;
        verifica se o sistema exibe erro para input "bairro" vazio;

        verifica se o input "cidade" está vazio;
        verifica se o sistema exibe erro para input "cidade" vazio;

        verifica se o input "estado" está vazio;
        verifica se o sistema exibe erro para input "estado" vazio;

        Verifica se o input "CEP" está vazio;
        verifica se o sistema exibe erro para input "CEP" vazio;
**3. O avaliador verifica input "telefone":**
    verifica se o sistema exibe erro se o input "telefone" estiver vazio;
    verifica se o sistema exibe erro se valor do input  "telefone" for invalido;
**4. O avaliador verifica input "CNPJ":**
    verifica se o sistema exibe erro se o input "CNPJ" está vazio;
    verifica se o sistema exibe erro se valor do input  "CNPJ" for invalido;
    verifica se o sistema exibe erro se valor do input "CNPJ" for encontrato no banco de dados;
**5. O avaliador verifica do botão "Salvar":**
    verifica se ao clicar no elemento botão "salvar" o sistema retorna erro informando a existencia de dados vazios;
    verifica se ao clicar no elemento botão "salvar" o sistema retorna erro informando a existencia de dados invalidos;
    verifica se a pagina permanece na pagina "painel de administração do sistema"

### Resultado Esperado:
  * O sistema exibe uma mensagem de erro para cada valor invalido.
   * O sistema exibe uma mensagem de erro para cada valor vazio.
   * Em casos de valores invalidos a pagina permanece no mesmo endereço de pagina




