<div align="center">
  <img src="nexus_logo.png" width="150" alt="Nexus Agent Logo" />
  <h1>NEXUS AGENT PREMIUM</h1>
  <h3><i>Powered by Hermes Engine</i></h3>

  <p>
    <a href="#"><img src="https://img.shields.io/badge/Status-100%25%20Offline-success?style=for-the-badge&logo=shield" alt="Offline"></a>
    <a href="#"><img src="https://img.shields.io/badge/Engine-Hermes%20Quantum-purple?style=for-the-badge&logo=python" alt="Hermes Engine"></a>
    <a href="#"><img src="https://img.shields.io/badge/UI-PyQt6%20Advanced-informational?style=for-the-badge&logo=qt" alt="UI PyQt6"></a>
    <a href="#"><img src="https://img.shields.io/badge/Segurança-Extrema-black?style=for-the-badge&logo=security" alt="Sec"></a>
  </p>

  <p><b>Desenvolvido e Arquitetado por Moisés V Vanti</b></p>
</div>

<br>

---

## 🌌 Visão Geral

O **Nexus Agent** é uma Inteligência Artificial local de altíssimo nível, desenhada para atuar como um Arquiteto de Software Sênior e Operador de Sistemas autônomo. Rodando 100% offline em sua própria máquina (integrado ao motor do Ollama), o Nexus é blindado contra vazamentos de dados, oferecendo a você um assistente capaz não apenas de responder a perguntas, mas de assumir o controle total do ecossistema de arquivos do seu PC para projetar, codificar, auditar e implementar sistemas gigantescos de ponta a ponta sem interrupções.

O projeto embute o inigualável **Motor Hermes**, permitindo processamento lógico sequencial profundo com até 100 ciclos autônomos.

---

## ⚡ Capacidades de Extremo Avanço

O Nexus Agent **não é um chatbot.** É um Engenheiro Digital Autônomo com reflexo cognitivo. Eis do que ele é capaz:

- 🏗️ **Construção Integral e Implacável:** Peça *"crie um aplicativo web de finanças"* e o Nexus não te dará um esqueleto inútil. Ele assumirá o terminal, criará os diretórios, construirá o Frontend, codificará o Backend, injetará as lógicas de roteamento e os estilos, parando **apenas** quando todo o sistema estiver funcional e pronto para uso.
- 🎙️ **Comando por Voz Multithread (STT/TTS):** Abandone o teclado se quiser. Fale com o Nexus via microfone; o sistema usa reconhecimento de fala avançado (`speech_recognition`) para transcrever seu áudio e processa respostas audíveis via sistema `pyttsx3`, com fluxos multithreads que não congelam sua tela.
- 🧠 **Auto-Aperfeiçoamento Constante:** Equipado com diretrizes de aprimoramento nativo (`skill_manage`), o Nexus aprende com os próprios erros. Sempre que você o corrigir, ele gravará uma *Skill de Reflexão* permanentemente na própria base de dados do cérebro. O agente de hoje será menos inteligente que o de amanhã.
- 🛡️ **Modo CyberStrike Ofensivo:** Conta com uma suíte de conhecimentos hacker acoplada. Se instruído a caçar vulnerabilidades de redes, buscar brechas em sistemas web (XSS, SQL Injection) ou realizar Pentests locais, ele acessará seu arsenal e executará testes rigorosos.
- 🚀 **Instalador Launcher Inception:** O executável se instala sozinho. Ao ser rodado pela primeira vez, ele abre uma interface Premium Setup que copia si mesmo silenciosamente para o Desktop e levanta as configurações locais, transformando-se num Launcher definitivo na segunda vez.
- 📑 **Histórico Moderno e Fixo:** Gerencie suas conversas com menus suspensos avançados (os famosos "Três Pontinhos"). Renomeie, fixe `📌` seus papos mais importantes no topo, ou delete conversas para sempre do seu SSD em um clique.

---

## 🔒 Segurança Lógica: O Nexus pode deletar ou destruir meu PC?

A arquitetura de segurança do Nexus foi desenhada com diretrizes paranoicas.

> [!CAUTION]
> **Devo ter medo dele agir sem minha permissão ou apagar meu HD?**  
> **NÃO.** O Nexus opera sob restrições lógicas rigorosas.

1. **Isolamento de Área de Trabalho (Workspace):** O Agente é instruído e restringido à pasta do projeto que você definir. Ele atua como um trator *dentro daquele cercado*. 
2. **Validação Matemática Silenciosa:** Antes de lhe dizer que alterou um arquivo ou apagou um bug, o Nexus é obrigado pelo `sys_prompt` a realizar um ciclo de Engenharia Reserva: `write_file` -> `read_file` -> `diff check`. Ele lê novamente o arquivo no HD para confirmar com matemática computacional que o código está íntegro antes mesmo de te dar uma resposta no chat.
3. **Privacidade Absoluta:** O peso do raciocínio (Inferência LLM) ocorre na sua placa de vídeo ou processador local. Nenhum byte do seu projeto é enviado a servidores na nuvem. Você tem posse soberana e criptográfica da inteligência do robô.

---

## 🛠️ Arquitetura do Sistema e Fluxo Nervoso

```mermaid
graph TD;
    A[Usuário Moisés V Vanti] -->|Texto ou Voz / Mic| B(Nexus PyQt6 Premium UI)
    B -->|Thread Isolada Protegida| C(HermesWorker Engine)
    C <-->|Auto-Melhoria| H[Skills & Memórias Permanentes]
    C -->|Diretrizes Quânticas| D[Local Ollama Llama Models]
    D -->|Tool Use Autônomo| E{Ferramentas Nativas}
    E -->|Write/Read File| F[Disco Local SSD]
    E -->|Subprocess Exec| G[Terminal / PowerShell]
    E -->|Web Scrape| I[Internet]
    C -->|UI Delta Updates| B
```

---

## 💻 Como Instalar, Compilar e Rodar

1. **Geração do Executável Blindado**:
   - Dê dois cliques em `build_nexus.bat`.
   - O PyInstaller injetará dezenas de milhares de linhas de bibliotecas de voz, IA, UI e terminal num único arquivo binário compacto e pesado, sem janelas pretas incomodando (`--windowed` & `--onefile`).
2. **O Setup Inception**:
   - Com o arquivo `.exe` gerado em mãos, dê dois cliques. A tela inicial de *Setup* se abrirá.
   - Pressione **"⚙️ Instalar na Área de Trabalho"**. O sistema clonará a si próprio nativamente e salvará metadados de instalação em `%APPDATA%`.
3. **Produção**:
   - Clique em **🚀 Launch Nexus Agent**.
   - Defina sua Área de Trabalho (o laboratório dele).
   - Inicie o desenvolvimento quântico.

---

<br>

<div align="center">
  <p><i>"O limite do desenvolvimento é apenas o limite da sua comunicação com a máquina."</i></p>
  <b>— Moisés V Vanti</b>
</div>
