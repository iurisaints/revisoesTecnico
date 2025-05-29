
---

# Review React Native – **Do Setup aos Desafios Reais**

---

### 🔧 **Questão 1 – Setup Inicial do Projeto**

Crie um novo projeto React Native usando **Expo CLI**.

* Comando esperado:

```bash
npx create-expo-app MinhaMaratona --template blank
```

* Rode o projeto em emulador ou no celular com o **Expo Go**.
* Substitua o conteúdo da tela inicial por um `Text` com o nome do seu app.

---

### 📱 **Questão 2 – Criando Componentes Básicos**

Crie um componente `Cabecalho` com um fundo colorido e um título centralizado.

* O componente deve ser reutilizável e aceitar o texto como prop.
* Renderize esse componente na tela principal.

---

### 🔣 **Questão 3 – Trabalhando com Estados**

Crie um botão que conta o número de vezes que foi clicado.

* Use `useState`.
* Mostre o número em tempo real na tela.
* O botão deve mudar de cor quando o número for par.

---

### 🧮 **Questão 4 – Pequeno Formulário**

Crie um formulário com `TextInput` para nome e idade.
Ao clicar em "Enviar", exiba abaixo uma frase como:
`Olá, Maria! Você tem 18 anos.`

* Use `KeyboardAvoidingView` para não ser coberto pelo teclado.

---

### 🔍 **Questão 5 – Desafio: Nome em Maiúsculo**

Implemente uma função que transforma automaticamente o nome digitado no `TextInput` da questão anterior para **letras maiúsculas** em tempo real.

* Dica: `toUpperCase()` com `onChangeText`.

---

### 🔄 **Questão 6 – Lista com Scroll**

Crie um array de objetos com tarefas (`id`, `descricao`, `feita`).
Liste-as com `FlatList`.

* Mostre um botão “Concluir” em cada item.
* Ao clicar, risque o texto com `textDecorationLine: 'line-through'`.

---

### 🗃️ **Questão 7 – AsyncStorage**

Salve e carregue as tarefas da questão anterior usando `@react-native-async-storage/async-storage`.

* As tarefas devem persistir após fechar e abrir o app.
* Faça isso com `useEffect`.

---

### 🧩 **Questão 8 – Bug de Scroll Fantasma**

Seu `FlatList` está com um espaço gigante no final da lista.
**Desafio**: descubra por que isso acontece e corrija.

* Dica: revise se `ScrollView` está envolvendo algo desnecessariamente ou se o estilo tem `flex: 1` indevido.

---

### 🌐 **Questão 9 – Consumindo API Externa**

Use `fetch()` para obter uma piada aleatória da [API oficial do Chuck Norris](https://api.chucknorris.io).

* Mostre a piada na tela ao clicar em um botão.
* Enquanto carrega, exiba "Carregando...".

---

### 🎨 **Questão 10 – Desafio de Estilo Responsivo**

Estilize seu app para que funcione bem em dispositivos diferentes.

* Use `Dimensions` e `StyleSheet` responsivo.
* Centralize os elementos e teste no modo escuro (usando o tema do sistema com `useColorScheme()`).

---
