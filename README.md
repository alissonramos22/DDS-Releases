# DDS (Dynamic Display System) - Downloads Oficiais

Bem-vindo ao repositório de distribuição oficial do ecossistema DDS. Aqui você encontra os instaladores para as duas principais soluções do projeto.

Todos os arquivos estão disponíveis para download na aba **[Releases](../../releases)** deste repositório.

---

## 1. DDS Server (Solução Central)
*Arquivo: `DDS_Setup_v1.1.zip`*

O **DDS Server** é o coração do sistema, projetado para rodar no computador principal ou servidor da rede. Ele engloba:

*   **Backend & API:** Gerencia toda a lógica, banco de dados (SQLite) e comunicação.
*   **Web Admin (Client-Admin):** Painel de controle para gerenciar telas, playlists, agendamentos e mídias via navegador (`localhost:3000`).
*   **Web Display (Client-Display):** Player web que roda nos navegadores das SmartTVs ou equipamentos conectados.

**Ideal para:** O servidor central que comandará toda a operação de Digital Signage.

---

## 2. DDS Client Manager (App de Gerenciamento Remoto)
*Arquivo: `DDS_Client_Manager_Setup.exe` (ou nome similar na release)*

O **DDS Client Manager** (anteriormente *client-url-loader*) é uma ferramenta desktop independente para operadores e clientes.

*   **Objetivo:** Facilitar configurações remotas e acesso rápido sem depender apenas do navegador.
*   **Funcionalidades:**
    *   Carregamento de URLs de displays.
    *   Ferramentas utilitárias para o dia a dia da operação.
    *   Interface nativa Windows.

**Ideal para:** Operadores que precisam de acesso rápido ou configurações específicas nas pontas (clientes).

---

### 📥 Como Instalar

1.  Clique em **Releases** no menu lateral direito (ou no topo).
2.  Escolha a versão mais recente (ex: `v1.1`).
3.  Na seção "Assets", clique no arquivo desejado (`.zip` ou `.exe`) para baixar.

> **Nota:** Se o Windows ou Antivírus alertar sobre "arquivo desconhecido", isso ocorre porque o instalador é novo e ainda não possui reputação global. É seguro prosseguir clicando em "Mais informações" > "Executar assim mesmo".
