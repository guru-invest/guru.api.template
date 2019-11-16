# /vendor

### Diretório de bibliotecas terceiras <br/>

Este diretório é responsável por armazenar a versão válida da biblioteca adicionada. Quaisquer atualizações devem ser feitas manualmente bilioteca por biblioteca.  
Seu uso substitui o "go get" padrão, evitando assim a quebra de compatibilidade com a aplicação.

## **Uso** <br/>

Para adicionar uma nova biblioteca terceira no projeto, utilize o seguinte comando no diretório:

**git submodule add <url-repositorio>** - no diretório "vendor" <br/>
**git submodule add <url-repositorio> vendor/<nome-da-biblioteca>** - no diretório raiz <br/>

