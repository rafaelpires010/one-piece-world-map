# One Piece World Project — mapa para o mod One Piece

Este repositório **não tem código**: ele só hospeda, nas *Releases*, os arquivos do mapa
**One Piece World Project**, criado por **The_Varian** (publicado no PlanetMinecraft),
distribuídos **com a autorização do autor** para uso com o mod.

Todo o crédito pelo mapa — as ilhas, as cidades e a Reverse Mountain — é do The_Varian e da comunidade
One Piece que ajudou a construí-lo.

## Como funciona

O mod usa o mapa como modelo para todo mundo novo (o tipo de mundo "Mapa One Piece"). Ninguém precisa baixar
o mapa inteiro: quando o jogo precisa de uma região, o mod baixa só aquele arquivo daqui, confere o sha1 e guarda em
`.minecraft/optimusprime/templates/one_piece_world_project/`. O mar aberto o próprio mod gera, por isso só as regiões
com terra, construções ou relevo no fundo do mar estão aqui (cerca de 2,7 GB, contra 8,9 GB do mapa original).

No jogo, `/mapa` mostra quanto falta baixar e `/mapa baixar` baixa tudo de uma vez (para jogar sem internet depois).

## Arquivos

- Release `mapa-v1`: `manifest.json` (lista de arquivos, tamanho e sha1) e o primeiro lote de regiões.
- Releases `mapa-v1-b` e `mapa-v1-c`: o resto das regiões (o GitHub aceita até 1000 arquivos por release).
