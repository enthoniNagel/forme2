# Componente React: App

O código a seguir define um componente React chamado `App`, que é um formulário simples para capturar informações do usuário. O formulário inclui campos para nome, email, senha e sexo.

## Estrutura do Componente

### 1. Importação e Definição da Classe

```jsx
import React, { Component } from 'react';

class App extends Component {
  constructor(props) {
    super(props);
    this.state = {
      form: {
        nome: '',
        email: '',
        senha: '',
        sexo: ''
      }
    };
    this.dadosForm = this.dadosForm.bind(this);
  }
