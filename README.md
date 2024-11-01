# jogo tetrix

# Configuração de Ambiente Virtual em Python

Este guia fornece instruções completas sobre como configurar um ambiente virtual em Python usando o módulo `venv`. Ambientes virtuais são úteis para isolar dependências de projetos Python, garantindo que as bibliotecas específicas do projeto não interfiram com outras instalações no sistema.

## O que é um Ambiente Virtual?

Um ambiente virtual é um diretório autocontido que inclui uma instalação independente de Python, juntamente com uma cópia do gerenciador de pacotes `pip`. Ele permite que você instale pacotes Python em um espaço isolado, separado do Python base do sistema. Isso é essencial para:

- Evitar conflitos de dependências entre diferentes projetos.
- Manter o projeto portátil e replicável em diferentes sistemas.
- Testar diferentes versões de pacotes sem afetar o sistema global.

## Pré-requisitos

Antes de criar um ambiente virtual, certifique-se de que você tem o seguinte:

- **Python 3**: A versão mais recente do Python 3 instalada no seu sistema.
- **pip**: O gerenciador de pacotes Python, que geralmente vem junto com o Python.
- **venv**: Módulo para criar ambientes virtuais, incluído por padrão no Python 3.3 e versões posteriores.

## Passos para Criar um Ambiente Virtual

### 1. Verificar a Instalação do Python

Verifique se o Python está instalado corretamente no seu sistema. No terminal, execute:

```bash
    python3 --version
```
### 2. criar o ambiente  virtual (obs): entrar no diretorio ou pafrao do vs
```bash 
    python -m venv myvenv
```
### 3.  Ativar o Ambiente Virtual
```bash
    source  myvenv/bin/activate (linux)
    myvenv/bin/activate (windows)
```
### 4. Instalar Dependências
```bash 
    pip install <nome da depedencia>
```
- `python -m venv`: Usa o módulo `venv` para criar um ambiente virtual.
- `myvenv`: Nome do ambiente virtual. Você pode escolher qualquer nome.
