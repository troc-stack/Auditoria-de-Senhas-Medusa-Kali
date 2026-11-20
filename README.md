# Auditoria de Senhas com Medusa — Kali Linux

## Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio prático de cibersegurança, com o objetivo de estudar e demonstrar técnicas de auditoria de autenticação em um ambiente de laboratório controlado.

Foram utilizados o Kali Linux como máquina de auditoria e o Metasploitable 2 como alvo, executados no VirtualBox e conectados por uma rede Host-Only.

Os testes envolveram identificação de serviços, enumeração de usuários e tentativas automatizadas de autenticação.

## Ferramentas utilizadas

- **Kali Linux:** ambiente utilizado para executar as ferramentas de auditoria.
- **Metasploitable 2:** máquina virtual vulnerável utilizada como alvo.
- **VirtualBox:** software de virtualização.
- **Medusa:** ferramenta de testes de autenticação.
- **Hydra:** ferramenta utilizada nos testes de formulários HTTP.
- **Nmap:** identificação de portas e serviços.
- **enum4linux:** enumeração de informações relacionadas ao SMB.
- **DVWA:** aplicação web vulnerável utilizada nos testes de autenticação.

## Testes realizados

| Teste | Descrição |
|---|---|
| FTP | Identificação do serviço e teste de autenticação com Medusa. |
| DVWA | Testes de autenticação em formulário web com Medusa e Hydra. |
| SMB | Enumeração de usuários e testes de autenticação com Medusa. |

## Documentação

Os procedimentos, comandos, resultados e evidências estão organizados nos seguintes documentos:

- [Configuração do ambiente](docs/01-ambiente.md)
- [Auditoria FTP](docs\02-FTP.md)
- [Testes de autenticação no DVWA](docs\03-DVWA.md)
- [Password Spraying e enumeração SMB](docs\04-SMB.md)

## Objetivo de aprendizado

Durante o desenvolvimento do projeto, foram praticados conceitos de:

- Linux e utilização do terminal.
- Redes e identificação de serviços.
- Protocolos FTP, HTTP e SMB.
- Enumeração de usuários.
- Auditoria de autenticação.
- Identificação de riscos e medidas de mitigação.

## Obs

Todos os testes foram realizados em máquinas virtuais próprias, em um ambiente isolado e controlado, exclusivamente para fins educacionais.

Este projeto não tem como objetivo incentivar ou autorizar testes em sistemas de terceiros sem permissão.

## Autor (troc-stack)

Projeto desenvolvido como atividade prática de estudos em cibersegurança da DIO.