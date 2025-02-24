# 📌 Nomes de Variáveis e Funções

### ✒️ Evite más práticas:
- Evite nomes genéricos como `i, j, k, x, y, z`.
- Evite nomes que não explicam o que representam, como `buga, foo, bar`.
- Evite nomes muito genéricos, como `contador` (contador do quê?).
- Evite nomes longos e complexos, como `CorAzulDoCeuDasNuvensDaTerra`.
- Evite nomes inconsistentes em diferentes partes do código, como `CorAzul`, `corAzul`, `cor_azul`.
- Sempre prefira nomes que expliquem a função da variável ou método.
- **Use nomes descritivos e consistentes** (código autoexplicativo).

---

# 📌 Convenções de Nomenclatura

## ✅ CamelCase
📌 **Descrição:** Primeira palavra minúscula, as seguintes com inicial maiúscula. 
🔹 **Usado para:** Funções, variáveis e métodos. 

🛠️ **Linguagens:** JavaScript, Java, C#, C++, Swift, Go, Ruby, PHP.

💡 **Exemplos:**
```js
minhaVariavel
calcularSoma()
```

---

## ✅ PascalCase
📌 **Descrição:** Similar ao CamelCase, mas a primeira letra também é maiúscula.
🔹 **Usado para:** Classes e tipos de dados.

🛠️ **Linguagens:** C#, Java, C++, Swift, TypeScript, JavaScript (classes).

💡 **Exemplos:**
```js
Pessoa
ContaBancaria
```

---

## ✅ snake_case
📌 **Descrição:** Palavras separadas por `_`, todas em minúsculas.
🔹 **Usado para:** Variáveis, funções e arquivos.

🛠️ **Linguagens:** Python, Ruby, PHP, Elixir, Perl.

💡 **Exemplos:**
```py
minha_variavel
calcular_soma()
```

---

## ✅ UPPER_CASE
📌 **Descrição:** Letras maiúsculas com `_` separando palavras.
🔹 **Usado para:** Constantes.

🛠️ **Linguagens:** C, C++, JavaScript, Python, Go.

💡 **Exemplos:**
```js
PI = 3.14159
MAX_VALOR = 100
```

---

## ✅ kebab-case
📌 **Descrição:** Letras minúsculas separadas por `-`.
🔹 **Usado para:** Arquivos, URLs.

🛠️ **Linguagens:** JavaScript, Ruby, CSS.

💡 **Exemplos:**
```
nome-do-arquivo.js
minha-aplicacao
```

---

# 📌 Estrutura de Pastas 📁
Boas práticas na organização do código-fonte.

```
📦 meu-projeto
 ┣ 📂 src ➜ Código-fonte principal
 ┃ ┣ 📂 components ➜ Componentes reutilizáveis
 ┃ ┣ 📂 services ➜ Requisições e regras de negócio
 ┃ ┣ 📂 utils ➜ Funções auxiliares
 ┃ ┣ 📂 styles ➜ Arquivos de estilo (CSS, SASS, etc.)
 ┃ ┗ 📜 index.js ➜ Arquivo principal
 ┣ 📂 assets ➜ Imagens, fontes e outros recursos estáticos
 ┣ 📂 tests ➜ Testes unitários e de integração
 ┣ 📂 public ➜ Arquivos estáticos (HTML, imagens, etc.)
 ┣ 📂 config ➜ Configurações e variáveis de ambiente
 ┣ 📜 README.md ➜ Documentação do projeto
 ┣ 📜 package.json ➜ Dependências e scripts
 ┣ 📜 .gitignore ➜ Arquivos ignorados pelo Git
```
# **Boas Práticas de Nomes de Pastas 📁**

## **1. Use Nomes Descritivos e Claros 📜**

Evite nomes vagos ou genéricos para as pastas. O nome da pasta deve refletir claramente o seu conteúdo ou propósito.

**Exemplo ruim:**

```plaintext
/pasta1
/docs
```

**Exemplo bom:**

```plaintext
/src
/tests
```

---

## **2. Utilize Convenções Consistentes 🎯**

Escolha uma convenção de nomenclatura (como `camelCase`, `kebab-case` ou `snake_case`) e mantenha-a consistente em todo o projeto.

**Exemplo ruim:**

```plaintext
/MyFolder
/my_folder
/my-folder
```

**Exemplo bom:**

```plaintext
/my-folder
```

---

## **3. Evite Nomes de Pastas Completamente Abstratos 🔍**

Nomes como `misc`, `others`, `temp` não são informativos o suficiente. Seja específico sobre o conteúdo ou finalidade da pasta.

**Exemplo ruim:**

```plaintext
/misc
/other
/temp
```

**Exemplo bom:**

```plaintext
/assets
/docs
/temp-images
```

---

## **4. Use Nomes de Pastas no Plural para Coleções 📚**

Quando uma pasta contém uma coleção de arquivos, use o plural para indicar isso de forma clara.

**Exemplo ruim:**

```plaintext
/images
/document
```

**Exemplo bom:**

```plaintext
/images
/documents
```

---

## **5. Evite Caracteres Especiais e Espaços 🚫**

Evite o uso de caracteres especiais como `@`, `#`, `$`, `%`, ou espaços. Isso pode causar problemas em diferentes sistemas operacionais e dificultar o acesso aos arquivos.

**Exemplo ruim:**

```plaintext
/my folder
/my@folder
```

**Exemplo bom:**

```plaintext
/my-folder
/my_folder
```

---

## **6. Mantenha a Hierarquia Simples e Lógica 🧑‍💻**

A estrutura de pastas deve ser lógica e fácil de entender. Evite criar profundidades desnecessárias e complexas de pastas.

**Exemplo ruim:**

```plaintext
/project/src/components/ui/buttons
/project/src/components/ui/buttons/large-buttons
```

**Exemplo bom:**

```plaintext
/project/src/components/buttons
/project/src/components/buttons/large
```

---

## **7. Use Nomes que Facilitem a Navegação Rápida 🔄**

Pasta bem nomeadas ajudam a navegação rápida e tornam o projeto mais organizado, economizando tempo durante o desenvolvimento.

**Exemplo ruim:**

```plaintext
/xyz
/123
```

**Exemplo bom:**

```plaintext
/components
/helpers
/assets
```

# 📌 Nomes que NÃO podem ser usados 🚫

- **Palavras reservadas da linguagem:** `class`, `function`, `return`, `if`, `else`, etc.
- **Caracteres especiais não permitidos:** Evite caracteres como `@, #, $, %, &, *` em nomes de variáveis.
- **Espaços em branco:** Use `_` ou `-` em vez de espaços.
- **Nomes duplicados:** Evite nomes idênticos em diferentes partes do código, o que pode causar conflitos.

---

📌 **Referências:**

🔗 [Manual de Boas Práticas para Gestão de Pastas e Arquivos Digitais](https://www.legiscompliance.com.br/images/pdf/Boas-praticas-para-pastas-e-arquivos-digitais.pdf?utm_source=chatgpt.com)  
🔗 [9 Boas práticas de gestão de documentos e arquivos digitais](https://www.jusbrasil.com.br/artigos/9-boas-praticas-de-gestao-de-documentos-e-arquivos-digitais/116967219?utm_source=chatgpt.com)  
🔗 [Convenção de Nomenclatura de Pastas e Arquivos – 10 Regras](https://www.reddit.com/r/datacurator/comments/r71io5/folder_and_file_naming_convention_10_rules_for/?tl=pt-br&utm_source=chatgpt.com)  
🔗 [8 boas práticas de gestão de documentos e arquivos digitais](https://acervonet.com.br/blog/8-boas-praticas-de-gestao-de-documentos-e-arquivos-digitais/?utm_source=chatgpt.com)  
🔗 [Normas de nomenclatura e terminologia dos arquivos](https://suporte.museudapessoa.org/docs/normas-de-nomenclatura-e-terminologia-dos-arquivos/?utm_source=chatgpt.com)
🔗 [Clean Code: A Handbook of Agile Software Craftsmanship](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
🔗 [Self-Documenting Code](https://en.wikipedia.org/wiki/Self-documenting_code)


🚀 **Mantenha seu código limpo, organizado e fácil de entender!**
