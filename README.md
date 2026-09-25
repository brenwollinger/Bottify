# Bottify — configurador Base + Cartela

## Como abrir
Abra `index.html` no navegador.

## Imagens das garrafas
As imagens já estão em `assets/bases/`.

## Como inserir as cartelas reais
1. Coloque seus PNG/JPG em `assets/cartelas/`.
2. O `index.html` já espera estes nomes de arquivo:

### Universos
- universos-orbita-lilas.png
- universos-jardim.png
- universos-cafe-afeto.png
- universos-sessao-azul.png

### Movimento
- movimento-impulso-coral.png
- movimento-forca-marinho.png
- movimento-rota-turquesa.png
- movimento-match-grafite.png

### Mood
- mood-sunny.png
- mood-cherry-pop.png
- mood-disco-roxo.png
- mood-fire.png

### Essencial
- essencial-noite.png
- essencial-aco.png
- essencial-neve.png
- essencial-floresta.png

### Filmes
- filmes-classicos.png
- filmes-cena-vermelha.png
- filmes-outro-mundo.png
- filmes-lendas.png

### Séries
- series-ultimo-episodio.png
- series-comfort-show.png
- series-proxima-pista.png
- series-so-mais-um.png

### Collab fitness
- fitness-power-black.png
- fitness-hot-training.png
- fitness-graphite-set.png
- fitness-flash-white.png

Se seus arquivos tiverem outros nomes, altere apenas o campo `image` do array `CARTELAS` no final do `index.html`.

## Fluxo implementado
1. Cliente escolhe a cor/base da garrafa.
2. O site libera as cartelas.
3. Cliente filtra as cartelas por linha.
4. Cliente escolhe uma cartela.
5. O resumo mostra a combinação escolhida.

O botão de finalizar hoje apenas mostra/copía o resumo. Ele pode ser ligado depois a carrinho, WhatsApp, formulário ou checkout.
