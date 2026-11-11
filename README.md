# PrjIMV-MVC-CORE

Aplicação web em **ASP.NET Core MVC (.NET 6)** para cadastro de usuários e pacientes, com cálculo de IMC (Índice de Massa Corporal), login com perfis de acesso e persistência em arquivos JSON.

## Funcionalidades

- Login e fluxo de primeiro acesso
- Cadastro e manutenção de usuários (com perfis de acesso)
- Cadastro e manutenção de pacientes
- Cálculo de IMC
- Validação de CPF e e-mail

## Requisitos

- [.NET 6 SDK](https://dotnet.microsoft.com/download/dotnet/6.0) ou superior
- Visual Studio 2022 (opcional)

## Como executar

```bash
git clone https://github.com/SEU-USUARIO/PrjIMV-MVC-CORE.git
cd PrjIMV-MVC-CORE
dotnet run
```

Depois acesse `https://localhost:7163` (ou `http://localhost:5090`).

## Dados

Os arquivos `usuarios.json` e `Pacientes.json` são criados/lidos na pasta do projeto em tempo de execução e **não são versionados** (estão no `.gitignore`), pois contêm dados pessoais.

## Estrutura

```
Controllers/   Controladores MVC
Models/        Modelos de domínio (Pessoa, Paciente, Usuario, IMC...)
Views/         Views Razor
wwwroot/       Arquivos estáticos (CSS, JS, Bootstrap, jQuery)
```
