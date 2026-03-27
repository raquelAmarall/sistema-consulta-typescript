# 🏥 Sistema de Consultas em TypeScript

Projeto desenvolvido como parte das atividades de aprendizado em **TypeScript**.

---

## 📌 Objetivo

Simular um sistema básico de gerenciamento de consultas médicas, aplicando conceitos fundamentais de TypeScript como:

* Tipos personalizados (`type`)
* Interfaces (`interface`)
* Union Types
* Funções tipadas
* Organização modular de código

---

## 📁 Estrutura do Projeto

```
sistema-consultas-typescript/
│
├── src/
│   ├── types/
│   │   ├── especialidade.ts
│   │   ├── paciente.ts
│   │   └── statusConsulta.ts
│   │
│   ├── interfaces/
│   │   ├── medico.ts
│   │   ├── consulta.ts
│   │   └── usuarioAdmin.ts
│   │
│   └── index.ts
│
├── dist/
├── tsconfig.json
└── README.md
```

---

## Como Executar o Projeto

### 1. Clonar o repositório

```
git clone https://github.com/SEU-USUARIO/sistema-consultas-typescript.git
```

### 2. Acessar a pasta do projeto

```
cd sistema-consultas-typescript
```

### 3. Compilar o projeto

```
tsc
```

### 4. Executar o projeto

```
node dist/index.js
```

---

## 💻 Funcionalidades

* Criar consultas médicas
* Confirmar consultas
* Cancelar consultas (com regra de validação)
* Exibir dados formatados no console

---

## 📄 Exemplo de Saída

```
=== CONSULTA CONFIRMADA ===

Consulta #1
Médico: Dr. Roberto Silva
Paciente: Carlos Andrade
Especialidade: Cardiologia
Data: 26/03/2026
Valor: R$ 350,00
Status: confirmada
```

---
