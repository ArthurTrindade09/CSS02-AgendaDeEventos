# CSS 2 - Agenda de Eventos

Crie uma página HTML chamada "Agenda de Eventos", apresentando informações sobre **três eventos** que acontecerão na sua cidade/escola. Os eventos podem ser reais ou fictícios, como shows, campeonatos, feiras culturais, festivais ou palestras.

A página deverá conter:

- Um título principal e um parágrafo de apresentação.
- Três seções, cada uma apresentando um evento, com título, descrição, data e local.
- Uma lista com pelo menos três atrações ou atividades de um dos eventos.
- Um link para um site externo relacionado a um dos eventos.
- Uma seção final com informações de contato.

### Requisitos de estilização CSS

Utilize CSS interno, por meio da tag `<style>` dentro de `<head>`, e aplique as seguintes formatações:

| Elemento | Formatação exigida |
| --- | --- |
| Corpo da página (`body`) | Fonte `Arial, sans-serif` e fundo `#f5f5f5` |
| Título principal (`h1`) | Cor `#1b4f72`, tamanho `36px`, peso `bold` e alinhamento centralizado |
| Subtítulos (`h2`) | Cor `#8e44ad`, tamanho `24px` |
| Parágrafos (`p`) | Tamanho `16px`, entrelinhas `1.6` e alinhamento justificado |
| Descrição inicial | Fundo `#d6eaf8`, texto centralizado e tamanho `18px` |
| Títulos dos eventos | Espaçamento entre letras de `2px` |
| Datas dos eventos | Cor `#c0392b` e peso `bold` |
| Lista de atrações (`li`) | Tamanho `18px` e entrelinhas `1.8` |
| Seção de contato | Fundo `#d5f5e3` e texto centralizado |
| Links (`a`) | Cor `#21618c`, alterando para `#e74c3c` ao passar o mouse |

### Regras adicionais

1. Utilize pelo menos um seletor por elemento, um seletor por ID e dois seletores por classe.
2. Utilize as três formas de representar cores no CSS: nome da cor, código hexadecimal e `rgb()`. Você pode substituir alguns valores da tabela por representações equivalentes.
3. A classe utilizada para destacar as datas deverá ser aplicada nos três eventos.
4. Utilize `font-family` para escolher uma fonte diferente para o título principal.
5. Todo o CSS deverá estar dentro da tag `<style>`, sem utilizar bibliotecas externas.

### Regra adicional

Escolha um dos eventos e crie uma classe chamada `evento-destaque`, que deverá:

- Aplicar uma cor de fundo diferente ao evento escolhido.
- Alterar a cor e o tamanho do texto da descrição.
- Deixar o texto em negrito.

Entrega: salve a página como `agenda.html`, publique no GitHub Pages e envie o link da página funcionando.

**OBS: atividade em dupla!**
