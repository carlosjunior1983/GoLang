# GoLang
Repositório como os resultados/fontes de estudos na Linguagem GoLang.

Instalação/Execução no VSCode:
- Instalar o pacote GO (microsoft) e depois ele irá solicitar para instalar os demais pacotes.(sim para todos.)
- Ctrl+Alt+n = Compilar no VSCode
- Ctrl+Alt+m = Parar execução no VSCode

no prompt: 
na pasta onde está seu arquivo .go, execute o comando.:
Execução:
go run *.go    ou
go run .

Para testes:
go test      ou 
go test ./...


Conferir variáveis de ambiente:
go env
go env VARIAVEL (onde VARIAVEL pode ser qualquer um do GO, ex: GOPATH ou GOROOT)


Pastas de fontes: 
- Fundamentos
    - Comandos
    - Constantes e variáveis
    - Conversões
    - funções (basicas)
    - Operações Aritiméticas
    - Operações de Atribuições
    - Operações Lógicos
    - Operações Relacionais
    - Operações Ternários (Não tem no GO)
    - Operações Unários
    - Ponteiros
    - Primeiro Exemplo
    - Prints
    - Tipos de variáveis
    - Zeros

- Estruturas de Controle
    - If/Else e If/init
    - For (Não existe while)
    - Switch

- Arrays
    - Array
    - For Range
    - Slice
    - Slice Make
    - Append Copy
    - Map

- Funções
    - Básicas
    - Pilha (Stack)
    - Retorno nomeado (Retorno limpo)
    - Função em Váriavel (Função Anonima)
    - Função como Parâmetro
    - Funções Variáticas
    - Closure
    - Recursividade
    - Defer
    - Ponteiros em funções
    - Função Init

- Tipos
    - Structs
    - Struct Aninhada
    - Métodos
    - Pseudo Herança
    - Personalizados
    - Interfaces
    - JSON

- Pacotes
    - Reta ( utilizando o comando go run .)

- Banco de Dados
    - MySql (Sql)
        - Create (Create e Drop)
        - Insert
        - Transação
        - Update e Delete
        - Select

- Http
    - Static (servidor estático) OBS: para funcionar vc precisará utilizar no prompt>> go run .
    - Dinamico
    - ServerDB (Rest + DB)

- Testes Unitários
    - Simples Teste
    - Dataset para Teste
 
