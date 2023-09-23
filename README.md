# **👋 Bem-vindo Desenvolvedor Flow!**

> Certifique-se de conferir a documentação de Custódia Híbrida para mais informações e o repositório original para o código completo e histórico de contribuições. Se você encontrar algum problema com este scaffold, por favor, crie um problema aqui.

Este scaffold foi criado para ajudar desenvolvedores de aplicativos a começar a construir e explorar um projeto de Custódia Híbrida. Nele, você encontrará um template simplificado dos conteúdos em **[@onflow/hybrid-custody](https://github.com/onflow/hybrid-custody)**.

# **🔨 Começando**

Começar pode parecer avassalador, mas estamos aqui para ajudar. Dependendo do quanto você está acostumado com o Flow, aqui está uma lista de recursos que você pode achar útil:

- **[Documentação de Cadence](https://developers.flow.com/cadence/language)**: aqui você encontrará referências de linguagem para Cadence, que será a linguagem na qual você desenvolverá seus smart contracts.
- **[Visual Studio Code](https://code.visualstudio.com/?wt.mc_id=DX_841432)** e **[Extensão de Cadence](https://marketplace.visualstudio.com/items?itemName=onflow.cadence)**: sugerimos o uso do IDE Visual Studio Code para escrever em Cadence com a extensão de Cadence instalada, que oferecerá realce de sintaxe e recursos inteligentes adicionais.
- **[SDKs](https://developers.flow.com/tools#sdks)**: aqui você encontrará uma lista de SDKs que você pode usar para facilitar a interação com a rede Flow (enviando transações, buscando contas, etc),
- **[Ferramentas de Desenvolvimento](https://developers.flow.com/tools#development-tools)**: ferramentas de desenvolvimento que você pode usar para facilitar seu desenvolvimento.
- **[Inspeção de Conta](https://emulator.flowview.app/)**: Inspeção de conta para todas as redes, incluindo sua localnet!

# **📦 Estrutura do Projeto**

Seu projeto vem com algumas pastas padrão que têm um propósito especial:

- **`cadence/`** aqui é onde vive o código dos seus smart contracts Cadence
    - **`contracts/`** local para os contratos Cadence
    - **`scripts/`** local para os scripts Cadence
    - **`transactions/`** local para as transações Cadence
- **`flow.json`** arquivo de configuração do seu projeto, você pode pensar nele como um package.json.

# **🤔 O que é Custódia Híbrida?**

> :books: Leia a documentação completa em developers.flow.com/hybrid-custody

O modelo de Custódia Híbrida no Flow permite que desenvolvedores ofereçam experiências de integração e in-app contínuas enquanto empoderam usuários com propriedade real e auto-soberania. Com este novo modelo de custódia, desenvolvedores podem entregar os benefícios de ambos, custódia de aplicativo e auto-custódia, em uma experiência unificada.

# **👨‍💻 Comece a Desenvolver**

> :warning: Note que os contratos neste scaffold ainda estão em desenvolvimento e podem sofrer alterações incompatíveis. Você pode se manter atualizado sobre avanços e mudanças seguindo o repositório original.

**[Instale o Flow CLI](https://developers.flow.com/tooling/flow-cli/install)**

Do diretório da sua área de trabalho, configure seu projeto Flow a partir de um scaffold

```
flow setup <NOME_DO_SEU_PROJETO> --scaffold
```

Você será solicitado a selecionar o número do scaffold para este projeto

Vá em frente e digite o número do scaffold para o Projeto de Custódia Híbrida: **`[4] Projeto de Custódia Híbrida`**

```
✔ Digite o número do scaffold: 4
```

Agora, para iniciar o emulador e implantar contratos. Mude para o diretório do seu projeto

```
cd <NOME_DO_SEU_PROJETO>
```

Inicie o emulador

```
flow emulator --contracts
```

> :information_source: Usamos a flag --contracts para incluir contratos adicionais que podemos facilmente referenciar em nossos testes.

Em uma nova janela do terminal, implante os contratos

```
flow deploy
```

Agora você está pronto para começar a desenvolver!

# **📚 Recursos Adicionais**

- **[Flow Playground](https://playground.flow.com/)**: um ambiente online para escrever, testar e visualizar contratos Cadence.
- **[Flow Discord](https://discord.gg/flow)**: junte-se à comunidade Flow no Discord para fazer perguntas, compartilhar seu trabalho e colaborar com outros desenvolvedores.
- **[Flow YouTube](https://www.youtube.com/c/FlowBlockchain)**: tutoriais, webinars e mais para ajudá-lo a se familiarizar com o Flow.
