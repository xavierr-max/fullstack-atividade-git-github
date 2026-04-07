# Convenção da Atividade

## 1) Nome da pasta da função

A pasta deve representar o nome da função e seguir estas regras:

- Usar `kebab-case`.
- Apenas letras minúsculas, números e hífen.
- Sem espaços, sem acentos, sem caracteres especiais.

Exemplos válidos:

- `media-aritmetica`
- `calcular-imc`
- `area-circulo`

Exemplos inválidos:

- `MediaAritmetica`
- `média aritmética`
- `calcular_imc`

## 2) Estrutura mínima por aluno

Cada aluno cria uma pasta em `funcoes/`:

```txt
nomealuno/
  nome-do-arquivo/
    index.js
```

`README.md` dentro da pasta é opcional para explicar a lógica.

## 3) Padrão da implementação

No `index.js`, usar:

- Uma função com o nome correspondente.
- Os parâmetros na ordem indicada na atividade.
- Exportação com `module.exports`.

Exemplo de padrão:

```js
function nomeDaFuncao(param1, param2) {
  return 0;
}

module.exports = nomeDaFuncao;
```

## 4) Boas práticas obrigatórias

- Validar entradas quando fizer sentido.
- Não alterar pastas de outros colegas.
- Um commit principal por função implementada.
- Mensagem de commit clara.

## 5) Convenção de branch e commit

### Branch

```txt
feat/seu-nome-nome-da-funcao
```

Exemplo:

```txt
feat/ana-area-circulo
```

### Commit

```txt
feat(nome-da-funcao): implementa funcao
```

Exemplo:

```txt
feat(area-circulo): implementa calculo da area
```
