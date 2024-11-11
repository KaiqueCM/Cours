
# Oque é Git?

Git é um ***Sistema de Controle de Versão Distribuido***. Isso significa que ele é usado para rastrear mudanças em arquivos e colaborar em projetos, especialmente no desenvolvimento de **software**.

## Estrutura do Git:

- **Controle de Versão:** O Git permite que salve diferentes versões de seus arquivos ao longo do tempo. Sempre que você faz uma alteração e a "***`commita`***" (**ou gravar**), o Git registra essa mudança . Isso é util para voltar a versões anteriores se necessário, ou para entender como o projeto evoluiu.

- **Repositórios:** Um repositóro é onde seu projeto é armazenado. Você pode ter um repositório local no seu computador e um remoto em um serviço como **GitHub** ou **GitLab**.

- **Ramificações** **(** ***`Branches`*** **)**: Uma das características mais poderosas do Git é a capacidade de criar ***`breanches`***. Isso permite que você trabalhe em novas funcionalidades ou correções de bugs de forma isolada, sem interferir na versão principal do código, que geralmente está na ***`branch`*** "**main**" ou "**master**".

- **Mesclagem** **(** ***`Merge`*** **)**: Depois de trabalhar em uma ***`branch`*** e fazer as alterações necessárias, você pode mesclar essas mudanças de volta á ***`branch`*** principal. O Git oferece ferramentas para resolver conflitos que possam surgir durante esse processo.

- **Colaboração**: O Git facilita a colaboração entre desenvolvedores. Vários progamadores podem trabalhar simultaneamente em um projeto, e o sistema permite gerenciar as contribuições de cada um de forma organizada.

## Comandos Básicos

**Alguns comandos fundamentais que você deve conhecer incluem:**

***`git init`:*** Criam um novo repositório.

***`git clone`:*** Copia um repositório remoto para sua máquina local.

***`git add`:*** Adiciona arquivos ao índice para preparar uma nova versão.

***`git commit`:*** Salva as alterações no repositório.

***`git push`:*** Envie suas alterações para o repositório.

***`git pull`:*** Atualiza seu repositório local com as últimas alterações do remoto.

Com essas ferramentas e conceitos, você será capaz de gerenciar projetos de forma mais eficiente e elaborar efetivamente com outros desenvolvedores.
 
 ## Extra

 - **Pratica Recomendada:** Comece a usar Git em seus projetos pessoais. Crie um repositório, faça algumas alterações, e experimente comandos como ***`commit`***, ***`branch`*** e ***`merge`***. Com o tempo, você ficará mais confortável com o fluxo de trabalho do Git e suas funcionalidades.
 
## Breve História do Git

**2002:** O projeto núcleo (**Kernel**) do ***Linux***, que é **Open Source**, começa a utilizar o **BitKeeper**, um **DVCS** proprietário;

**2005:** Apos conflitos com a comunidade, o **BetKeeper** rescinde a licença gratuita. O que leva a **Linus Torvalds**, o criador do ***Linux***, e sua equipe, a desenvolverem sua própria ferramenta o **Git**.