# ERYNDOR A Ascensão dos Reinos

RPG para Android e Windows. Este repositório contém os downloads; o código-fonte e as credenciais privadas permanecem fora dele.

[Baixar o jogo](https://github.com/cabralsoares/meu-rpg-downloads/releases/tag/v0.11.1) · [Conteúdo v25 disponível](https://github.com/cabralsoares/meu-rpg-downloads/releases/tag/atualizacao-v25)

O conteúdo **25** está publicado e ativo no canal automático para Android e Windows desde **13/10/2026**, com conversa compacta e balões de fala. O servidor oficial permanece v24/protocolo 8, com os dados preservados.

A conversa usa um compositor pequeno, aberto por **Enter**, **T** ou pelo **ícone prateado de conversa**, sem o texto Chat no botão. **Enter/Enviar** envia a mensagem e fecha o campo imediatamente, devolvendo os controles ao herói; se o servidor recusar o envio, o compositor reabre com o rascunho e informa o motivo. **Esc** fecha preservando o rascunho. Não há seletor de destinatários, janela grande, painel de histórico, contador de mensagens, prévia no HUD nem fundo escurecido.

Somente jogadores a **até 20 m** do autor recebem a fala, que aparece em balões acima dos heróis por **6 a 12 segundos**, acompanha a montaria e respeita paredes. Durante a digitação, os controles do herói e da câmera ficam bloqueados sem pausar a partida dos outros jogadores. O servidor determina autor, nível, posição e destinatários, limita cada mensagem a **180 caracteres** e um envio por segundo. A entrada tardia não reproduz balões antigos. O histórico temporário do protocolo continua limitado a 40 falas locais, sem painel na interface, gravação em perfis ou logs.

Nome e **Lv.** permanecem acima da cabeça dos jogadores, inclusive o próprio herói. A v25 altera somente os clientes e usa **protocolo 8**, compatível com o servidor v24 da VPS, sem nova implantação do servidor. Clientes v23 ou anteriores precisam atualizar para entrar.

No Android, instale **ERYNDOR-mobile-v12.apk** por cima da instalação anterior, sem desinstalar. No Windows, extraia **ERYNDOR-Windows-v12.zip** e execute **ERYNDOR.exe**. Instalações do antigo canal privado precisam deste instalador uma vez para migrar ao canal público.

O instalador atual é **v0.11.1**, com versão nativa **11** e APK código **12**. O jogo baixa as atualizações e aplica ao reabrir, preservando os saves. Abra com internet, aguarde o download e reabra para aplicar o conteúdo 25.

Faça **login → escolha o herói → Multiplayer** para conectar diretamente ao servidor oficial, sem informar IP ou porta. Valdoria mantém o HUD da aventura local, joystick, minimapa, inventário, equipamentos, habitantes, lojas, missões, saque, baús e fauna.

As casas permitem entrada e saída automáticas, descanso, baú e seleção de herói. As ampliações custam **500**, **1.000** e **2.000 moedas**, sem materiais. Cavalos permitem combate montado, com equipamentos e montaria visíveis para os outros jogadores, inclusive quem entra depois.

Os cavalariços Ramiro, Bento, Joaquina, Olavo, Zilda e Valentim oferecem cinco pelagens comuns por **10.000 moedas** e o cavalo dourado por **50.000 moedas**, exposto na baia de honra. Mantém os ajustes de animação e rédeas dos cavalos e o desvio de obstáculos dos passeantes. Fome e sede aparecem no HUD; comidas, bebidas e fontes repõem as necessidades. O servidor simula seus efeitos, valida o consumo e mantém seus valores no perfil das identidades verificadas.

O progresso online das identidades verificadas fica salvo no servidor e é independente da aventura local. Convidados usam progresso temporário. Uma instalação em outro aparelho não transfere automaticamente a chave de identidade da conta.

O proprietário mantém **Painel do administrador [F1] → Jogadores** para consultar presença e perfis, atribuir Jogador/VIP/Moderador, conceder moedas, definir nível, curar e ampliar a casa. A credencial privada permanece no aparelho do proprietário, fora dos downloads. O envio no chat com o nick reservado do proprietário também exige autenticação administrativa. As abas gerais do F1, incluindo Economia, atuam na aventura individual; a gestão online recebe confirmação da VPS pela aba Jogadores.

Os testes locais v25 de chat passaram com **42 verificações, sem falhas**, e o cenário ENet com servidor e três clientes confirmou proximidade, autoria, limites, entrega e histórico sem reativar balões. A interface compacta e a regressão da partida passaram nos testes headless e renderizados; as capturas foram conferidas em tamanhos de tela de desktop e celular. Os pacotes Android e Windows v25 e a inicialização no executável Windows foram conferidos. O cliente v25 validou autenticação do proprietário, lista e acesso do convidado na VPS v24 em modo somente consulta, sem conceder benefícios, e recebeu aviso privado do limite de chat. Os dois pacotes e o manifesto v25 foram conferidos anonimamente, incluindo tamanho, SHA-256 e acesso público. Uma prévia renderizada com mundo, HUD e avatar reais da fixture local também passou. O teste do atualizador confirmou o download real do conteúdo **25**, com exit 0 e candidato 25.0. Os downloads públicos distribuem somente conteúdo Android e Windows; o pacote dedicado permanece privado.

Mantém os 14 personagens, com versões masculinas e femininas das sete classes, trajes e vozes próprios, brados de batalha, pegadas das armas e máscaras ajustadas.

## Histórico: v24

A [v24, versão anterior](https://github.com/cabralsoares/meu-rpg-downloads/releases/tag/atualizacao-v24), foi publicada e ativada em **13/10/2026**, introduzindo conversa por proximidade e balões com protocolo 8. Seu botão Chat e painel de histórico visível são substituídos na v25 pelo ícone prateado e pelo compositor pequeno. A VPS mantém o servidor v24 e seus dados. Na implantação anterior, o cliente exportado confirmou autenticação do proprietário, concessões ao convidado, reconexão e o RPC do chat com aviso privado de limite. Hashes, tamanhos e download real v24 foram conferidos naquela publicação.
