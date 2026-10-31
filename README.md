# Daily Words

Abra `index.html` diretamente no navegador. Não é necessário instalar dependências.

A página exibe uma palavra iniciante, uma intermediária e uma avançada por dia, com tradução, exemplo e pronúncia pelo sintetizador de voz do navegador. A pronúncia depende das vozes disponíveis no dispositivo.

As palavras são selecionadas pela data local do visitante, permanecem iguais durante o dia e mudam à meia-noite, inclusive com a página aberta. São 62 palavras em cada nível aproximado; o ciclo se repete a cada 62 dias. Para ampliá-lo, adicione entradas às listas `beginner`, `intermediate` e `advanced` no HTML.

Ao abrir “Definição em inglês”, a página consulta a [Free Dictionary API](https://dictionaryapi.dev/), sem chave. A API não determina o nível das palavras. A seleção, as traduções e os exemplos são locais e funcionam sem conexão; as definições adicionais exigem internet e permitem nova tentativa ao fechar e reabrir a seção.
