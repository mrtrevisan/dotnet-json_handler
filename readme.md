## Dotnet JSON Handler

- converte XML para JSON
- valida o JSON usando JSON-Schema
- aplica queries no JSON usando JSON-Query
- extrai dados do JSON

#### Trabalho desenvolvido no âmbito da disciplina de <b>Linguagens de marcação extensíveis<b/>
#### Prof. Giovani Librelotto 
#### Universidade Federal de Santa Maria - 2023b
  
## Dependências:
- Dotnet core versão 8

### Executando com outra versão do .NET:

* Pode-se executar o programa usando outra versão do dotnet, mas isso pode gerar resultados indesejados...

* Edite as linhas `<TargetFramework>` e `<LangVersion>` no arquivo .csproj na pasta /App:

## Como usar:

1- Clone este repositório

2- No root, rode os comando:
```
cd App
dotnet run
```

* Deve-se poder visualizar a saída do programa no terminal, demonstrando o passo a passo da execução do programa e os resultados das queries.

### Estrutura do projeto:

* O código driver está no arquivo /App/Program.cs e as classes, na pasta /App/class.

* Os arquivos xml de entrada estão na pasta /App/xml

* Os arquivos Json e o Json Schema serão gerados na pasta /App/json após a execução do programa.

* Os arquivos html serão gerados na pasta /App/html e o index.html na pasta /App.
