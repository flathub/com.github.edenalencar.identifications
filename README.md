# Identifications

English
-------
A simple app to generate Brazilian identification numbers (CPF, CNPJ and state IE). Useful for QA teams, developers and integration tests.

This repository contains the Flatpak packaging for Identifications. Upstream source: https://github.com/edenalencar/identifications
Available on Flathub: https://flathub.org/apps/details/com.github.edenalencar.identifications

Note: the application generates identification numbers but does not perform validation.

Main features
- Generate CPFs (formatted or plain)
- Generate CNPJs
- Generate Inscrição Estadual (IE) numbers for supported states
- Lightweight GUI for quick testing and copy/paste into test suites

Installation (Flathub)
- Install:
  flatpak install flathub com.github.edenalencar.identifications
- Run:
  flatpak run com.github.edenalencar.identifications

Usage
- Open the app and choose the identification type (CPF, CNPJ, IE).
- Generate random values and copy them for use in automated or manual tests.

Development
- Upstream repository: https://github.com/edenalencar/identifications
- This repo contains the Flatpak manifest and packaging only.
- For changes to the application itself, contribute to the upstream repo; for packaging issues, open an issue or PR here.

Contributing
- Found a packaging issue? Open an issue or submit a pull request in this repository.
- For application-level changes, contribute at the upstream repository linked above.
- When reporting bugs, include steps to reproduce and relevant logs or screenshots if possible.

License
- See LICENSE in this repository or in the upstream project for license details.

Maintainer / Contact
- Maintainer: edenalencar (GitHub). Please open issues in this repository for packaging questions.

Suggestions
- Add a screenshot to the README to show the UI.
- Add badges (Flathub, license) at the top for visibility.
- Document which states are supported for Inscrição Estadual (IE), if applicable.

---

Português
---------
Aplicativo simples para gerar números de identificação usados no Brasil (CPF, CNPJ e Inscrição Estadual — IE). Útil para equipes de QA, desenvolvedores e testes de integração.

Este repositório contém o empacotamento Flatpak do Identifications. Código-fonte upstream: https://github.com/edenalencar/identifications
Disponível no Flathub: https://flathub.org/apps/details/com.github.edenalencar.identifications

Observação: o aplicativo gera números de identificação, mas não faz validação.

Principais funcionalidades
- Gerar CPFs (formatados ou sem formatação)
- Gerar CNPJs
- Gerar Inscrição Estadual (IE) para os estados suportados
- Interface leve para testes rápidos e copiar/colar em suítes de teste

Instalação (Flathub)
- Instalar:
  flatpak install flathub com.github.edenalencar.identifications
- Executar:
  flatpak run com.github.edenalencar.identifications

Uso
- Abra o aplicativo e selecione o tipo de identificação (CPF, CNPJ, IE).
- Gere valores aleatórios e copie-os para uso em testes automatizados ou manuais.

Desenvolvimento
- Repositório upstream: https://github.com/edenalencar/identifications
- Este repositório contém apenas o manifesto e metadados do Flatpak.
- Para modificar o aplicativo, contribua no repositório upstream; para problemas de empacotamento, abra uma issue ou PR aqui.

Contribuindo
- Encontrou um bug ou problema no empacotamento? Abra uma issue ou faça um pull request neste repositório.
- Para alterações no aplicativo em si, contribua no repositório upstream (link acima).
- Ao reportar problemas, inclua passos para reproduzir e, se possível, logs ou capturas de tela.

Licença
- Consulte o arquivo LICENSE neste repositório ou no projeto upstream para detalhes da licença.

Contato / Mantenedor
- Mantenedor: edenalencar (GitHub). Abra issues neste repositório para dúvidas sobre empacotamento.

Sugestões
- Incluir uma captura de tela no README para mostrar a interface.
- Adicionar badges (Flathub, licença) no topo para melhor visibilidade.
- Documentar os estados suportados para Inscrição Estadual (IE), se aplicável.
