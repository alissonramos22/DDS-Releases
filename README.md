# DDS (Dynamic Display System) - Downloads Oficiais

Bem-vindo ao repositório de distribuição oficial do ecossistema **DDS (Dynamic Display System)**. Aqui você encontra os instaladores e pacotes de distribuição para as soluções do projeto.

Todos os arquivos compilados e instaladores estão disponíveis para download na aba **[Releases](../../releases)** deste repositório.

---

## 📦 1. DDS Server (Solução Central - v1.3.6)
*Arquivo: `DDS_Setup_v1.3.6.exe` (ou `DDS_Setup.exe`)*

O **DDS Server** é o núcleo do sistema, projetado para execução no servidor local ou computador principal da rede corporativa/industrial. Ele integra:

*   **Backend & API de Alta Performance:** API REST FastAPI compilada em binário seguro nativo (Cython), banco de dados local SQLite com migrações automáticas e WebSockets de baixa latência.
*   **Web Admin (`client-admin`):** Painel de controle responsivo para gestão de dispositivos, grupos, playlists, ciclos, agendamentos, modelos especiais e envio de dados em tempo real.
*   **Web Display (`client-display`):** Player inteligente SDUI (Server-Driven UI) com suporte a reprodução contínua, transição de slides, cache local IndexedDB e áudio neural.
*   **Motor Neural TTS (Edge-TTS):** Síntese de voz com qualidade humana em português com cache em disco para chamadas e alertas instantâneos.

**Ideal para:** Servidor central que orquestra toda a operação de Digital Signage, painéis industriais Andon e dashboards de produtividade.

---

## 🖥️ 2. DDS Client Manager (Gestor Remoto Desktop)
*Arquivo: `DDS_Client_Manager_Setup.exe`*

Ferramenta desktop nativa para operadores e administradores de TI:
*   Carregamento rápido e pareamento de URLs de displays.
*   Gerenciamento de licenças e utilitários de rede.
*   Interface Windows simplificada.

---

## 📥 Como Instalar e Atualizar

1. Acesse a aba **[Releases](../../releases)** no GitHub.
2. Localize a versão mais recente (**`v1.3.6`**).
3. Na seção **Assets**, baixe o instalador `DDS_Setup_v1.3.6.exe` (ou `DDS_Setup.exe`).
4. Execute o instalador como Administrador e siga os passos na tela.
5. Acesse o painel de gerenciamento via navegador em `http://localhost:3000` (ou IP da máquina na rede).

> **Nota:** Se o Windows SmartScreen exibir aviso de "aplicativo não reconhecido", clique em **"Mais informações"** e depois em **"Executar assim mesmo"**.
