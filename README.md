# ERYNDOR A Ascensão dos Reinos

## Áudio e saída no PC v28 — publicada e ativa

O [conteúdo **28**](https://github.com/cabralsoares/meu-rpg-downloads/releases/tag/atualizacao-v28) foi publicado e ativado no canal automático em **14/10/2026**. Os gatilhos de passos, pulo, pouso, água, assobio e efeitos de ações foram integrados ao cliente multiplayer a partir dos estados e eventos atuais. O banco do PCK27/APK13 contém **97 grupos**; a decodificação dos **295 arquivos distintos** do APK confirmou PCM diferente de zero. Os testes do cliente passaram em **38 verificações**, incluindo renderização/driver Dummy, e o servidor dedicado passou em **2 verificações**, sem leaks nessas suítes.

O cliente também inclui **Saída de áudio** nas configurações local e online do PC, para escolher explicitamente o fone ou os alto-falantes e guardar somente a preferência `audio/saida`. Volumes e outras preferências são preservados; o padrão do Windows não será alterado. O seletor passou em **16 verificações Dummy e 20 WASAPI**, com volumes, mute e padrão do Windows preservados. A inspeção digital da saída atual não comprova a audição no equipamento; a saída que o usuário quer ouvir depende da sua escolha.

Mantém **Godot 4.7.2**, versão nativa **11**, protocolo **8** e servidor **v24**, sem novo RPC nem reinício da VPS. Os instaladores permanecem **Android v0.11.2 / APK13** e **Windows v0.11.1 / v12**; o APK13 continua sendo o instalador mais recente.

As regressões pós-integração passaram: interface online, casa/montaria, administração (**80 headless e 84 renderizadas**) e chat ENet com servidor e três clientes no reteste. A primeira corrida de encerramento do chat permanece registrada.

A exportação confirmou **1.538 recursos em cada PCK**, com tamanho e SHA-256 conferidos. O boot nativo confirmou **conteúdo ativo 28**. A consulta do cliente exportado à VPS passou para proprietário e convidado em modo somente leitura; serviço, PID e hash do servidor v24 foram preservados.

Os dois PCKs foram publicados e conferidos anonimamente: **HTTP 200**, tamanhos e SHA-256 iguais aos arquivos validados. O canal estável foi ativado para **Android e Windows 28**, com todos os campos iguais ao manifesto local.

O atualizador confirmou **download real do conteúdo 28**, SHA-256 e tamanho iguais ao pacote público, com **6.528 quadros** durante o download. O executável nativo Windows reabriu e confirmou **conteúdo ativo 28**, sem boot pendente ou versão rejeitada. **Android físico não testado.** Os históricos v27 e APK13 abaixo conservam suas provas originais.

## Instalador Android v0.11.2 / APK v13 — publicado

O [**instalador Android v0.11.2**](https://github.com/cabralsoares/meu-rpg-downloads/releases/tag/v0.11.2) foi publicado em **13/10/2026**, contendo somente [**ERYNDOR-mobile-v13.apk**](https://github.com/cabralsoares/meu-rpg-downloads/releases/download/v0.11.2/ERYNDOR-mobile-v13.apk). O download público anônimo respondeu **HTTP 200**, com tamanho e SHA-256 iguais ao APK verificado. O Windows continua usando [**ERYNDOR-Windows-v12.zip**, da v0.11.1](https://github.com/cabralsoares/meu-rpg-downloads/releases/download/v0.11.1/ERYNDOR-Windows-v12.zip).

No Android, **instale o APK novo por cima do anterior, sem desinstalar**, para aplicar o nome **ERYNDOR A Ascensão dos Reinos** e o ícone da heroína do jogo. O APK inclui ícones normais, adaptáveis e temáticos. Atualizar somente o conteúdo dentro do jogo não muda o nome nem os recursos do atalho instalados pelo sistema. O launcher pode abreviar o nome e adaptar a forma ou as cores do ícone; o nome completo pode ser conferido nas configurações do aplicativo.

O APK usa código **13**, versão exibida **0.11.2**, engine **Godot 4.7.2** e compatibilidade nativa **11**. Conteúdo **27**, protocolo **8** e servidor **v24** permanecem. O pacote **com.jadson.meurpg** e o certificado de assinatura foram preservados para permitir atualizar sobre o APK v12. O canal alterou somente a URL do instalador Android; URL do instalador Windows, versões, hashes, tamanhos e URLs dos dois PCKs permanecem iguais à publicação v27.

A identidade passou em **20 verificações, 0 falhas**, incluindo nome padrão/pt-BR, manifesto, launcher, assinatura **v2/v3** e **24 variantes de imagem**. Os **1.548 assets** do APK foram extraídos e passaram em **69 verificações de boot** na engine Windows, com exit 0, dados isolados, sem carregar os fontes locais, sem saves e sem consulta do atualizador. Esse teste **não equivale à execução em um Android físico**, que ainda não foi testado.

O jogo conserva a abertura do conteúdo 27 e a música [**Crusade**, de **Kevin MacLeod / Incompetech**](https://incompetech.com/music/royalty-free/index.html?isrc=USUAN1100884), sob [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/), com loop, entrada gradual, botão para silenciar e créditos. O histórico abaixo preserva os resultados da publicação do conteúdo 27 e os instaladores usados naquela ocasião.

Provas do instalador: `build/releases/instalador-v13/{identidade-verificada,validacao-boot-apk13,apk-publico-verificado,canal-publico-verificado}.json`. A finalização documental preserva snapshots, rascunhos e hashes em `build/releases/instalador-v13/documentacao-finalizada.json`.

RPG para Android e Windows. O [conteúdo **27**](https://github.com/cabralsoares/meu-rpg-downloads/releases/tag/atualizacao-v27) está publicado e ativo no canal automático desde **13/10/2026**. Abra o jogo com internet, aguarde o download e reabra para aplicar.

[Baixar o Windows v12, mantido na v0.11.1](https://github.com/cabralsoares/meu-rpg-downloads/releases/download/v0.11.1/ERYNDOR-Windows-v12.zip). [Baixar o APK Android v13, na v0.11.2](https://github.com/cabralsoares/meu-rpg-downloads/releases/download/v0.11.2/ERYNDOR-mobile-v13.apk).

No Android, instale **ERYNDOR-mobile-v13.apk** por cima do anterior, sem desinstalar, para aplicar o nome e o ícone. No Windows, extraia **ERYNDOR-Windows-v12.zip**, da **v0.11.1**, e execute **ERYNDOR.exe**. Quem usa um instalador do antigo canal privado precisa instalar um cliente do canal público uma vez para receber atualizações. A versão nativa continua **11**; o APK Android usa código **13** e versão exibida **0.11.2**.

## Histórico da abertura v27 — conteúdo ativo

A arte medieval foi adaptada da referência fornecida com **imagegen** e mantém o título **ERYNDOR A Ascensão dos Reinos** sobre o castelo. Continuar, Entrar, Criar conta, Multiplayer e Sair continuam funcionais nas plataformas que oferecem essas ações. O menu se adapta à tela, com rolagem em telas curtas. Três tecidos vermelhos ondulam ao vento; o lampião balança até **±0,6°**, com chama e luz animadas. O castelo fica estável.

A faixa [**Crusade**, de Kevin MacLeod / Incompetech](https://incompetech.com/music/royalty-free/index.html?isrc=USUAN1100884), acompanha o menu em loop, com entrada gradual, volume moderado, botão para silenciar e créditos acessíveis. A música termina ao entrar na partida e respeita os volumes do jogo. É uma alternativa orquestral épica; a trilha oficial de Game of Thrones não foi incluída.

Crusade — Kevin MacLeod (incompetech.com), sob [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/). Adaptação: reprodução em loop e fade para ERYNDOR.

## Multiplayer e funções preservadas

Entre na conta, escolha o herói e toque em **Multiplayer** para conectar diretamente à VPS. Os jogadores mostram nome e nível acima da cabeça. O ícone prateado, Enter ou T abre um compositor pequeno; as falas aparecem em balões somente para jogadores a até **20 m**. Enviar fecha o compositor e devolve os controles ao herói.

A administração introduzida na v26 continua disponível somente para o proprietário autenticado por senha e autorizado pela VPS. Ícone de escudo com coroa e F1 abrem o mesmo painel. A aba Jogadores permite consultar presença e atribuir Jogador/VIP/Moderador, moedas, nível, cura e melhoria de casa, com confirmação do servidor.

Heróis masculinos e femininos, equipamentos, inventário, missões, combate, montaria, casas, fome e sede permanecem. Casas recebem ampliações por **500**, **1.000** e **2.000 moedas**, sem outros materiais.

O **cliente 27 usa protocolo 8** e é compatível com o **servidor v24 já instalado na VPS**. O pacote do servidor permanece inalterado. O progresso online das identidades verificadas é salvo na VPS e é independente da aventura local; contas e chaves continuam próprias de cada aparelho. Os downloads públicos contêm somente os clientes; código, dados do servidor e credenciais privadas permanecem privados.

## Verificação da publicação

A abertura passou em **260 verificações headless** e **316 renderizadas**; a música passou em **22 verificações, sem falhas**. Login salvo, entrada Multiplayer e Créditos/Voltar em desktop e celular passaram. Capturas em **1152×648**, **1672×941**, **390×844** e **844×390** foram conferidas. **Um aparelho Android físico ainda não foi testado**; as telas móveis foram verificadas no Windows.

Os dois pacotes têm **1.534 recursos**, com tamanhos e SHA-256 confirmados. O executável Windows confirmou **conteúdo ativo 27**, inclusive ao reabrir com o mesmo pacote baixado pelo atualizador. O cliente exportado confirmou autenticação do proprietário, lista e acesso do convidado na **VPS v24**, em modo somente consulta, sem concessões. A consulta SSH confirmou serviço ativo e SHA-256 do servidor v24 preservado. Os downloads públicos responderam **HTTP 200**, e o canal público foi conferido com os hashes do manifesto. O atualizador confirmou download real, **candidato 27** e **6591 quadros** durante o download.

A [v26](https://github.com/cabralsoares/meu-rpg-downloads/releases/tag/atualizacao-v26) foi publicada e ativada em **13/10/2026**, antes da v27, com as melhorias do painel administrativo. A [v25](https://github.com/cabralsoares/meu-rpg-downloads/releases/tag/atualizacao-v25) introduziu o compositor compacto; a [v24](https://github.com/cabralsoares/meu-rpg-downloads/releases/tag/atualizacao-v24) introduziu a conversa por proximidade e permanece no servidor.
