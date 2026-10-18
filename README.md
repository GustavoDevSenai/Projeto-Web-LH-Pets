# 🐾 Projeto Web LH Pets

Projeto Web desenvolvido em **C# com ASP.NET Core** para gerenciamento e visualização de clientes de uma loja de pets.

O objetivo deste projeto é demonstrar a criação de uma aplicação web simples utilizando integração com banco de dados **SQL Server**, consultas SQL e geração de páginas HTML através de uma API ASP.NET Core.

---

## 🚀 Tecnologias utilizadas

- C#
- ASP.NET Core
- .NET
- SQL Server Express
- ADO.NET
- HTML
- CSS
- Git/GitHub

---

## 📋 Funcionalidades

- Conexão com banco de dados SQL Server
- Consulta de clientes cadastrados
- Leitura de dados utilizando `SqlConnection`, `SqlCommand` e `SqlDataReader`
- Exibição dos clientes em uma página HTML
- Integração entre aplicação Web e banco de dados

---

## 📂 Estrutura do projeto

```
Projeto-Web-LH-Pets
│
├── Banco.cs
├── Clientes.cs
├── Program.cs
├── Projeto_Web-Lh-Pets_Alunos.csproj
│
├── Properties/
│
├── wwwroot/
│   └── index.html
│
├── vendas.sql
│
├── appsettings.json
│
└── README.md
```

---

## 🗄️ Banco de dados

O projeto utiliza o SQL Server Express.

Banco utilizado:

```
vendas
```

Tabela principal:

```
tblclientes
```

O arquivo `vendas.sql` contém a estrutura do banco e os dados necessários para execução do projeto.

---

## ⚙️ Configuração do banco

Exemplo de conexão utilizando SQL Server Express:

```csharp
Server=localhost\SQLEXPRESS;
Database=vendas;
Trusted_Connection=True;
TrustServerCertificate=True;
```

Certifique-se que:

- O SQL Server Express esteja instalado.
- O serviço SQL Server esteja iniciado.
- O banco `vendas` exista.
- A tabela `tblclientes` esteja criada.

---

## ▶️ Executando o projeto

Clone o repositório:

```bash
git clone https://github.com/SEU_USUARIO/Projeto-Web-Lh-Pets.git
```

Entre na pasta:

```bash
cd Projeto-Web-Lh-Pets
```

Restaure as dependências:

```bash
dotnet restore
```

Execute o projeto:

```bash
dotnet run
```

A aplicação estará disponível no endereço informado pelo ASP.NET Core.

Exemplo:

```
http://localhost:5000
```

---

## 🌐 Rotas disponíveis

Página inicial:

```
/
```

Redirecionamento para página HTML:

```
/index
```

Lista de clientes:

```
/listaclientes
```

---

## 📚 Objetivos de aprendizagem

Este projeto foi desenvolvido para praticar:

- Estrutura de uma aplicação ASP.NET Core
- Classes e objetos em C#
- Conexão com banco de dados
- Consultas SQL
- Manipulação de dados
- Desenvolvimento Web

---

## 👨‍💻 Autor

Projeto desenvolvido para fins educacionais.

**Gustavo Rodrigues**

---

## 📄 Licença

Este projeto possui finalidade educacional e pode ser utilizado para estudos.
