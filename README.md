# Transylvania para Fujitsu FM-7

Localização experimental para inglês da edição japonesa de **Transylvania** para Fujitsu FM-7, publicada pela StarCraft em 1983. A aventura gráfica original foi criada por Antonio Antiochia.

## A história

Você chega à Transilvânia à meia-noite. A princesa Sabrina está prisioneira do conde Drácula, mergulhada num sono encantado. Explore a floresta, leia as pistas e descubra como despertá-la e levá-la de volta ao rei. Fique atento ao lobisomem e à passagem do tempo.

## Como jogar

Você vai precisar de um **emulador XM7 configurado para FM-7**, com as ROMs de sistema exigidas pela sua instalação, e da **imagem de disco D77**. As ROMs do emulador são obtidas separadamente.

1. Baixe o arquivo [Transylvania FM-7 - English controls.d77](https://github.com/benicasa2/TRANSYLVANIA_FM7-ENG/releases/download/v0.2.0-beta/Transylvania.FM-7.-.English.controls.d77) na [pré-release v0.2.0-beta](https://github.com/benicasa2/TRANSYLVANIA_FM7-ENG/releases/tag/v0.2.0-beta). Use o arquivo `.d77` na seção **Assets**.
2. No XM7, monte o D77 em **Drive 0 → Open** e reinicie em **File → Reset** ou com **F12**.
3. Aguarde a abertura e pressione uma tecla quando o jogo pedir. Quando solicitado, informe um nome de até dez caracteres.
4. No prompt do jogo, digite um comando em inglês e pressione **Enter**.

## Comandos em inglês

Digite uma instrução por vez. Para interagir com um objeto, comece com **verbo + objeto**.

| Comando | Ação pretendida |
| --- | --- |
| `NORTH`, `SOUTH`, `EAST`, `WEST` | Seguir pela direção indicada |
| `UP`, `DOWN` | Subir ou descer |
| `INVENTORY` | Consultar os itens que você carrega |
| `LOOK AT TREE` | Examinar uma árvore |
| `TAKE THE GARLIC` | Pegar o alho |
| `READ LETTERS` ou `READ INSCRIPTION` | Tentar ler uma inscrição |
| `KNOCK STUMP` | Bater no toco |

Se um comando não funcionar, confira se o objeto está na sala ou no seu inventário e tente uma frase curta com o nome mostrado na descrição. Anote as saídas e os lugares onde deixou objetos.

## Salvar, restaurar e alternar cores

| Comando | Função |
| --- | --- |
| `SAVE GAME` | Salvar a partida |
| `RESTORE GAME` ou `LOAD GAME` | Restaurar uma partida gravada |
| `COLOR ON` | Ativar a exibição em cores |
| `COLOR OFF` | Desativar a exibição em cores |

Os comandos aceitam maiúsculas e minúsculas. Quando o jogo pedir um número para salvar ou restaurar, use um compartimento de 0 a 9.

## Manual e arquivos do projeto

- [Manual ilustrado em português](https://github.com/benicasa2/TRANSYLVANIA_FM7-ENG/releases/download/v0.2.0-beta/Transylvania-FM7-Manual-v0.2.0-beta.pdf) com a história, dicas sem solução completa e tabelas de verbos e vocabulário.
- [Catálogo das respostas traduzidas](Transylvania%20FM-7%20-%20English%20responses%20catalog.tsv) com o texto em inglês e os endereços no disco.
- [Vocabulário global](Transylvania%20FM-7%20-%20global%20vocabulary.tsv) com os equivalentes em inglês.

## Estado da tradução

A versão beta inclui textos em inglês, um adaptador de comandos e a revisão de respostas de leitura, inventário, combate e erros. A v0.2.0-beta também traduz a fala do sapo sobre `IJNID` e inclui os comandos de sistema em inglês. O encaminhamento desses comandos foi validado no Ghidra. O ciclo completo de gravação e restauração ainda precisa ser testado no XM7. Uma compilação anterior chegou à abertura em inglês no XM7. A conversão de comandos como `READ LETTERS` e `READ INSCRIPTION` foi conferida no Ghidra. A execução de todas as ações e a aventura completa ainda precisam de validação no emulador.

Projeto de tradução não oficial. Créditos do jogo original a Antonio Antiochia e da edição japonesa para FM-7 à StarCraft.
