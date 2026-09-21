# 📱 Sistema de Celular com POO em C#

Projeto desenvolvido durante a **Trilha .NET — Programação Orientada a Objetos**, da [DIO](https://www.dio.me/).

O projeto consiste na criação de um sistema de console em **C#**, utilizando conceitos de **Programação Orientada a Objetos (POO)** para abstrair o funcionamento de diferentes tipos de celulares.

## 📋 Sobre o projeto

O sistema utiliza uma classe abstrata `Smartphone` como modelo base para diferentes marcas de celulares.

A partir dela, foram implementadas as classes:

* **Nokia**
* **Iphone**

Cada classe possui seu próprio comportamento para a instalação de aplicativos, demonstrando o uso de **herança, abstração e sobrescrita de métodos**.

## ⚙️ Funcionalidades

O sistema possui:

* Classe abstrata `Smartphone`;
* Classes `Nokia` e `Iphone` herdando de `Smartphone`;
* Instalação de aplicativos específica para cada tipo de celular;
* Sobrescrita do método `InstalarAplicativo()`;
* Reutilização de código através de herança;
* Aplicação de conceitos de Programação Orientada a Objetos.

## 🧩 Conceitos de POO utilizados

### Abstração

A classe `Smartphone` é definida como **abstrata**, servindo como modelo para as classes específicas e não podendo ser instanciada diretamente.

### Herança

As classes `Nokia` e `Iphone` herdam características e comportamentos da classe `Smartphone`.

```text
Smartphone
   ├── Nokia
   └── Iphone
```

### Polimorfismo

O método `InstalarAplicativo()` é sobrescrito pelas classes `Nokia` e `Iphone`, permitindo que cada tipo de celular tenha seu próprio comportamento.

## 🛠️ Tecnologias utilizadas

* C#
* .NET
* Programação Orientada a Objetos
* Git
* GitHub

## ▶️ Como executar

### Pré-requisito

É necessário ter o **.NET SDK** instalado.

Verifique a instalação:

```bash
dotnet --version
```

### Executando o projeto

Clone o repositório:

```bash
git clone https://github.com/mariayasmim2904-alt/Sistema-de-Celular-POO.git
```

Entre na pasta:

```bash
cd Sistema-de-Celular-POO
```

Execute o projeto:

```bash
dotnet run
```

Para verificar se o projeto compila corretamente:

```bash
dotnet build
```

## 📚 Aprendizados

Durante o desenvolvimento deste projeto, foram praticados conceitos fundamentais de Programação Orientada a Objetos em C#, incluindo:

* Classes;
* Classes abstratas;
* Herança;
* Polimorfismo;
* Métodos abstratos;
* Sobrescrita de métodos;
* Encapsulamento;
* Reutilização de código.

## 🎯 Objetivo

Este projeto faz parte da minha jornada de estudos em **C# e .NET**, com o objetivo de consolidar os conceitos de Programação Orientada a Objetos através da construção de projetos práticos.

---

### 📖 Referência

Desafio proposto pela **DIO — Digital Innovation One**, na Trilha .NET — Programação Orientada a Objetos.

🌐 [DIO](https://www.dio.me/)
