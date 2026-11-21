# BLENO NETWORK / BLENO HUB

Site: https://bleno.com.br/hub/

BlenoScan: https://bleno.com.br

# Documentação Técnica & Whitepaper

# 1. Arquitetura Técnica & Parâmetros da Rede

A Bleno Network é uma blockchain compatível com a Máquina Virtual Ethereum (EVM), otimizada para baixas taxas de gás, confirmação rápida de blocos e criação simplificada de ativos digitais.
Parâmetro	Configuração Oficial
Moeda Nativa	BLENO (18 casas decimais)
Endpoint RPC Público (EVM)	https://bleno.com.br/hub/rpc
Protocolo Nativo do Nó	JSON-RPC prefixo bleno_* (com tradutor automático eth_* ativo no Gateway)
Padrão de Contratos	Solidity v0.8.20 (EVM London / Optimizer 200 runs)

# 2. Economia de Diamantes & Níveis VIP

Os Diamantes (💎) são a unidade de utilidade e recompensas do ecossistema Bleno Hub. Eles podem ser obtidos gratuitamente pelo Faucet Diário, pelo Check-in Progressivo de 7 Dias, por indicações de amigos ou através do Staking de BLENO.
Patente VIP	Requisito em Staking	Multiplicador de Ganhos
🥉 Bronze	0 a 99 BLENO	1.00x (Taxa padrão)
🥈 Prata VIP	100 a 74.999 BLENO	1.15x (+15% no Staking e Check-in)
🥇 Ouro VIP	75.000 a 199.999 BLENO	1.30x (+30% no Staking e Check-in)
💎 Diamante VIP	200.000+ BLENO	1.50x (+50% no Staking e Check-in)

# 3. Transparência dos DApps & Jogos

    Roleta Dourada Pro: 10 posições equilibradas — Dourado (40% de chance, paga 2x), Preto (50% de chance, paga 2x) e Diamante (10% de chance, paga 14x).
    Bleno Slots Pro: Combinação de 2 símbolos iguais paga 1.5x; 3 símbolos iguais pagam 6x; triplo Coroa (👑) paga 12x; triplo Diamante (💎) paga 25x.
    Bleno Mines (5x5): Tabuleiro de 25 casas com multiplicador progressivo calculado matematicamente a cada casa segura revelada, permitindo saque (Cashout) a qualquer momento.
    Leilões (Auctions): Disputa transparente com reembolso instantâneo aos licitantes superados e extensão automática de +2 minutos para lances nos últimos 120 segundos.

# 4. Fábrica de Tokens BRC-20 (Token Factory)

A Fábrica de Tokens BRC-20 permite que qualquer criador, projeto ou comunidade lance seu próprio ativo fungível na Bleno Network sem precisar escrever uma única linha de código Solidity.

    Implantação Instantânea (1 Clique): O usuário define o Nome, Símbolo (Ticker), Supply Inicial e Casas Decimais (padrão 18), assinando a transação diretamente com sua Carteira Web3 nativa.
    Distribuição 100% ao Criador: Todo o suprimento inicial cunhado na criação é transferido automaticamente para a carteira do criador do contrato.
    Código-Fonte Verificado Automaticamente: Logo após a confirmação do bloco, o gateway envia o código Solidity padrão (BlenoToken.sol) e os argumentos do construtor ao explorador BlenoScan, garantindo o selo verde de contrato auditável (Read & Write Contract).
    Logotipo & Selo Oficial: Após o deploy, o criador pode enviar o logotipo do projeto (PNG/SVG) e links oficiais pelo painel do Bleno Hub para aprovação administrativa e exibição pública no explorador.

# 5. BlenoSwap DEX (Corretora Descentralizada AMM)

A BlenoSwap DEX é uma corretora descentralizada nativa que utiliza o modelo matemático AMM (Automated Market Maker — x ⋅ y = k), permitindo trocas instantâneas e sem intermediários entre BLENO e qualquer Token BRC-20 criado na rede.

    Criação Livre de Pools de Liquidez: Qualquer criador ou detentor de token BRC-20 pode inaugurar um mercado depositando liquidez inicial no par BLENO / TOKEN.
    Rendimento para Provedores (LP): Todas as negociações cobram uma taxa fixa de 0,3%, que permanece acumulada dentro das reservas do pool e valoriza proporcionalmente a cota dos provedores de liquidez.
    Contrato Inteligente Auditável: O contrato BlenoSwapDEX.sol possui código-fonte verificado no explorador BlenoScan, permitindo auditoria e resgate de liquidez a qualquer momento.

# 6. Gateway de Compra de BLENO (Pix, USD & Cross-Chain)

O Gateway Oficial facilita a entrada de novos participantes na Bleno Network sem necessidade de saldo prévio para taxas de rede:

    Pix Instantâneo (BRL): Geração dinâmica de QR Code padrão EMV (Pix Copia e Cola) com liquidação rápida direto para a carteira Bleno (0x...) do comprador.
    Dólar Internacional (USD / Cartão): Suporte a pagamentos internacionais em dólar com entrega automática on-chain pela Tesouraria.
    Ponte Cripto Cross-Chain (USDT / BNB / ETH / POL / TRC-20): Permite adquirir BLENO enviando stablecoins ou criptomoedas de redes externas (EVM ou TRON TRC-20) com rastreamento por hash da transação.

# 7. BlenoFlix (Streaming de Filmes & Séries Web3)

O BlenoFlix é a plataforma oficial de entretenimento e streaming sob demanda do ecossistema Bleno Network, integrando entretenimento digital diretamente à utilidade real da moeda nativa.

    Assinatura Paga em BLENO: Os usuários ativam e renovam sua assinatura mensal pagando diretamente com o token nativo BLENO (on-chain ou via saldo integrado), gerando demanda contínua e utilidade real para o ativo da rede.
    Catálogo Completo de Filmes & Séries: Acesso ilimitado a um acervo variado de filmes, séries, documentários e lançamentos organizados por categorias e com reprodução em alta definição.
    Liberação Automática via Blockchain: Assim que o pagamento em BLENO é confirmado na rede, o acesso da conta é liberado automaticamente pelo período contratado, sem burocracia ou intermediários bancários.

# 8. Segurança & Autocustódia

A Carteira Web3 nativa do Bleno Hub opera em regime de autocustódia: suas chaves privadas são geradas localmente no seu navegador e criptografadas com sua senha pessoal antes de qualquer sincronização de backup. Guarde sempre suas 12 palavras secretas em local seguro.

