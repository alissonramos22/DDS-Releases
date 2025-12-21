# DDS (Dynamic Display System) - Releases

Este repositório é destinado exclusivamente à distribuição dos instaladores e releases oficiais do **DDS (Dynamic Display System)**.

## 📦 Versão Atual: DDS v1.1

A versão 1.1 é a release estável mais recente, trazendo melhorias de performance, correção de bugs e o novo painel de gerenciamento.

### 🚀 O que está incluído no pacote:

O instalador `DDS_Setup_v1.1.zip` contém a solução completa "All-in-One":

1.  **DDS Server (Backend)**
    *   Servidor local robusto em Python/FastAPI.
    *   Gerenciamento automático de banco de dados (SQLite).
    *   API RESTful para comunicação entre dispositivos.

2.  **DDS Client Manager (Painel Administrativo)**
    *   Interface web intuitiva para gerenciamento de todo o sistema.
    *   Controle de grupos de telas e dispositivos.
    *   Upload e gerenciamento de mídias (Vídeos, Imagens).
    *   Agendamento de playlists e monitoramento em tempo real.

3.  **DDS Client Display (Player)**
    *   Aplicação player otimizada para reprodução contínua.
    *   Suporte a cache offline (o conteúdo continua tocando mesmo sem internet/rede).
    *   Renderização suave de vídeos e HTML.

---

### 📋 Requisitos de Sistema

*   **Sistema Operacional:** Windows 10 ou Superior (64-bit).
*   **Rede:** Conexão local (LAN) para comunicação entre Manager e Players (ou funcionamento local na mesma máquina).

### 🛠️ Como Instalar

1.  Baixe o arquivo `DDS_Setup_v1.1.zip` na aba **Releases** deste repositório.
2.  Descompacte o arquivo em uma pasta de sua preferência.
3.  Execute o `Setup.exe` (ou instalador correspondente) como Administrador.
4.  Após a instalação, o serviço iniciará automaticamente.
5.  Acesse o **Client Manager** através do atalho na área de trabalho ou pelo navegador em `http://localhost:3000` (ou a porta configurada).
