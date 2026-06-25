# App Classificador de Faixa Etária — Android

Aplicativo Android desenvolvido na disciplina de **Programação para Dispositivos Móveis (PDM)**

---

## Descrição

O app permite classificar a **faixa etária** de uma pessoa a partir da idade informada. Ao clicar no botão, o resultado é exibido na tela indicando se a pessoa é criança, adolescente ou adulto.

---

## Funcionalidades

- Entrada da idade pelo usuário
- Classificação automática da faixa etária conforme a tabela abaixo:

| Idade | Classificação |
|-------|--------------|
| 1 a 12 anos | Criança |
| 13 a 17 anos | Adolescente |
| 18 anos ou mais | Adulto |

---

## Estrutura do projeto

```
app/
├── src/
│   └── main/
│       ├── java/com/example/appfaixaetaria/
│       │   └── MainActivity.java   # Lógica principal e eventos
│       └── res/
│           └── layout/
│               └── activity_main.xml  # Layout da tela
```

---

## Como executar

1. Clone este repositório
2. Abra o projeto no **Android Studio**
3. Conecte um dispositivo físico ou inicie um emulador
4. Clique em **Run** (`Shift + F10`)
