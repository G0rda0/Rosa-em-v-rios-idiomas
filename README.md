# Rosa-em-varios-idiomas
# 🌹 Rosa de Palavras

Uma rosa feita inteiramente de **"eu te amo" escrito em dezenas de idiomas**. Cada palavra surge de baixo para cima e vai montando as pétalas, as folhas e o caule, até a flor ficar completa.

Um arquivo só, sem instalar nada e **sem depender de internet**. É só abrir no navegador.

> 🔗 **Demo ao vivo:** `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`
---

## ✨ O que tem na animação

- 🌍 **35 expressões de "eu te amo"**: português, inglês, japonês, árabe, russo, hebraico, hindi, tailandês, coreano, esperanto e muito mais
- 🌹 Rosa em estilo 🌹, com pétalas de **tons diferentes** (do vinho escuro ao rosa claro no miolo)
- 🍃 Folhas e caule verdes, também escritos com palavras
- 🎲 **Cada rosa é única**: as palavras são sorteadas e encaixadas de um jeito diferente a cada vez
- ✨ Palavras que **sobem e ganham cor** enquanto aparecem, com um leve brilho

---

## 🎮 Como interagir

| Ação | O que acontece |
|---|---|
| Clicar / tocar na rosa | Faz uma **nova rosa** crescer do zero |
| `Enter` ou `Espaço` (com a rosa selecionada) | Também reinicia |

Funciona no computador e no celular, e a rosa se ajusta ao tamanho da tela.

---

## ▶️ Como usar

**Opção 1: abrir direto**
1. Baixe o arquivo `index.html` (ou `Rosa_de_Palavras.html`).
2. Dê dois cliques nele. Ele abre no seu navegador.
---

## 🧠 Como funciona

A parte mais curiosa é como o código **sabe onde cabe cada palavra**:

1. **Mapa de cores escondido.** O código pinta cada parte da rosa (pétala de trás, pétala externa, miolo, folha...) numa cor diferente, num canvas invisível. Depois, para saber em qual pétala um ponto está, basta olhar a cor daquele pixel, como num mapa em que cada país tem a sua cor.
2. **Mapa de ocupação.** Uma grade marca os espaços que já têm palavra, para uma não encostar na outra.
3. **Destaques primeiro.** As palavras grandes são sorteadas em lugares aleatórios das pétalas.
4. **Preenchimento linha por linha.** Depois, palavras cada vez menores tapam os buracos, como quem escreve num caderno.
5. **Crescimento de baixo para cima.** As palavras entram em ordem (com um pouco de bagunça), então parece que a rosa está brotando.

As palavras que já terminaram de aparecer ficam guardadas numa imagem pronta, e só as que estão se movendo são redesenhadas a cada quadro. Isso mantém a animação leve.

**Tecnologias:** HTML, CSS e JavaScript puro (Canvas 2D). Nenhuma biblioteca externa.

---

## 🛠️ Personalize

Tudo fica no próprio arquivo, no começo do `<script>`:

| O que mudar | Onde |
|---|---|
| Idiomas e frases | `LOVE` (lista principal), `MID` (frases curtas) e `STEM` (palavras do caule) |
| Cores das pétalas e folhas | `C` |
| Velocidade da rosa nascendo | `DURATION` (em milissegundos) |
| Tempo de cada palavra aparecer | `ANIM` |
| O quanto cada palavra sobe | `LIFT` |
| Fonte | `FONT` |
| Formato da rosa | `REGIONS` (caminhos das pétalas, folhas e caule) |

**Ideia para presente:** troque os textos de `LOVE` por frases e nomes do casal (por exemplo, o nome dos dois e a data especial) e a rosa passa a ser personalizada.

---

## ♿ Acessibilidade

- Respeita a configuração **"reduzir movimento"** do sistema: nesse caso a rosa já aparece pronta, sem animação.
- A rosa pode ser selecionada pelo teclado e tem descrição para leitores de tela.

---

## 💡 Inspiração

Inspirado na ideia de uma rosa formada por palavras de amor em vários idiomas, vista em um vídeo de **NOME DO CRIADOR**. Esta versão foi reescrita para a web, com formato de rosa e animação próprios.

---

## 📄 Licença

Distribuído sob a licença **MIT**. Sinta-se livre para usar e adaptar, mantendo o crédito.

Feito por **gordaoprojetos** · [Instagram](https://www.instagram.com/gordaoprojetos/)
