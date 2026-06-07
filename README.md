# Implantação de TACACS+ para Centralização da Autenticação AAA
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Linux](https://img.shields.io/badge/Linux-Ubuntu%2024.04-orange)
![TACACS+](https://img.shields.io/badge/TACACS+-AAA-blue)
![License](https://img.shields.io/badge/license-MIT-green)

Projeto de implantação de servidor TACACS+ para centralização da autenticação administrativa em equipamentos de rede, com foco em segurança, controle de acesso e rastreabilidade de ações.

> Status: Em desenvolvimento

## Objetivo

Implementar uma solução TACACS+ para autenticação centralizada AAA em dispositivos de rede, permitindo maior controle sobre acessos administrativos, validação de autenticação e registro de ações realizadas no ambiente.

## Escopo

- Configuração de ambiente Linux para o servidor TACACS+
- Instalação de dependências necessárias
- Compilação e implantação do serviço TACACS+
- Configuração inicial do arquivo `tac_plus.conf`
- Integração com dispositivos de rede
- Configuração de políticas AAA
- Implementação de fallback local
- Validação de autenticação e logs administrativos

## Roadmap

- [x] Configuração da VM
- [x] Instalação de dependências
- [x] Compilação do TACACS+
- [x] Configuração inicial
- [x] Validação operacional
- [ ] Integração com switches
- [ ] Configuração AAA
- [ ] Validação de autenticação
- [ ] Implementação de fallback local
- [ ] Validação de logs administrativos

## Tecnologias e Conceitos

- Linux
- Ubuntu Server 22.04 LTS
- TACACS+
- AAA
- Redes de Computadores
- Infraestrutura de TI
- Segurança da Informação
- Troubleshooting
- Documentação Técnica

## Arquitetura Proposta

```text
Administrador
     |
     | SSH
     v
Switch / Roteador
     |
     | TACACS+
     v
Servidor TACACS+
     |
     v
Logs Administrativos
