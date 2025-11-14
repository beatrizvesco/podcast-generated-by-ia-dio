

<p align="center">
    preview do podcast
</p>

<div align="center">
    <audio src="output/podcast_EP1.mp3" controls title="Podcast Ep.1"></audio>
</div>

# Projeto Podcast Gerado por I.A.s

 > ℹ️ **NOTE:** Este repositório foi desenvolvido durante o curso "Fundamentos da IA generativa" da [DIO](https://dio.me)

 > ⚠️ **OBSERVAÇÃO:** Este conteúdo foi gerado com fins didáticos de construção; não foi realizada uma validação humana cuidadosa e pode conter erros gerados por IA.


Projeto com o objetivo de gerar um podcast utilizando ferramentas de IA disponíveis atualmente.

## 🎙️ Sobre o Podcast

**Código Moral: Quando a inteligência artificial encontra a consciência humana**

Um podcast que explora os dilemas éticos e filosóficos da inteligência artificial de forma acessível e reflexiva.

### 📻 Episódio Piloto - "Criatividade ou Reprodução? O dilema das IAs generativas"

Neste primeiro episódio, Carlos nos guia por uma jornada reflexiva sobre as IAs generativas e seu impacto na criatividade humana. O episódio aborda questões fundamentais: As IAs realmente criam ou apenas reproduzem? Qual é o papel do ser humano nesse processo? Como equilibrar a inovação tecnológica com a ética?

Com uma linguagem descomplicada e exemplos do cotidiano, o episódio convida o ouvinte a refletir sobre o futuro da criatividade na era da inteligência artificial.

**📁 Arquivos do Projeto:**
- 🎵 Áudio final: `podcast_EP1.mp3`
- 🖼️ Capa: `capa_podcast.png`
- 🎼 Trilha sonora: `phonk-phonk-music-beat-419315.mp3` - Music by <a href="https://pixabay.com/users/hitslab-47305729/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=419315">Ievgen Poltavskyi</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=419315">Pixabay</a>
- 🔊 Áudio bruto (ElevenLabs): `ElevenLabs_podcast_ep1.mp3`



### 🎨 Resultado da Capa Gerada

<p align="center">
  <img src="capa_podcast.png" alt="Capa do Podcast Código Moral" width="600"/>
</p>


## 💻 Tecnologias utilizadas no projeto

- [ChatGPT](https://chat.openai.com/) 
- [Podcastle](https://podcastle.ai/)
- [ElevenLabs](https://elevenlabs.io)
- [Pixabay](https://pixabay.com/music/)

## 🛠️ Instruções de execução

Siga o passo a passo para criar um podcast de maneira automatizada:

- 🤖 1. Use os prompts de roteiro e design no `ChatGPT`
- 🤖 2. Use o roteiro gerado para gerar áudio no `ElevenLabs`
- 🤖 3. Edite o áudio gerado adicionando trilha sonora, transições etc., usando o `Podcastle`


# 🧠 Prompts


ChatGPT：

### Título

```md
Você é um roteirista de podcast, e vamos criar um podcast de tecnologia, focado em ética e IAs e eu gostaria de uma ajuda sua para criar 5 sugestões de nomes criativos para um podcast simples e educativo, que remeta a IA. O podcast vai falar sobre os aspectos éticos do uso das IAs generativas.
{REGRAS}
- O nome deve ser enxuto, um nome e um subtítulo
- O nome transmitir profissionalismo e autoridade
- O nome deve conter alguma palavra forte que remeta a inteligência artificial
{REGRAS NEGATIVAS}
- Não quero que o título contenha palavras em inglês
```

### Conteúdo

```md
# Episódio de Podcast

Você é um roteirista de podcast, e vamos criar um  roteiro de um podcast de tecnologia, ética e IA  cujo o nome é "Código Moral: Quando a inteligência artificial encontra a consciência humana" e tem   com o público alvo leigos e pessoas interessadas nos avanços da inteligência artificial. o episódio piloto é sobre o tema: "Criatividade ou reprodução? O dilema das IAs generativas"
o formato do roteiro deve ser
[INTRODUÇÃO]
[BLOCO 1] 
[BLOCO 2] 
[FINALIZAÇÃO]
{REGRAS}
- no bloco [INTRODUÇÃO] substitua por uma introdução animada e divertida do narrador: Carlos 
- no bloco [BLOCO 1] substitua por uma contextualização do assunto. 
- no bloco [BLOCO 2] substitua por reflexões mais profundas sobre o tema
- no bloco [FINALIZAÇÃO] substitua por uma despedida cool do narrador 
- use termos de fácil explicação
- O podcast vai ser apresentado somente por uma pessoa, chamada Carlos 
- O podcast deve ser curto

{REGRAS NEGATIVAS}
- Não use muitos termos técnicos
- Não ultrapasse 5 minutos de duração
```

### Design

```md
Crie uma capa para o podcast, contendo um rosto dividido ao meio: de um lado, pele e expressão humana; do outro, circuitos, códigos ou luzes artificiais. As cores devem ser uma combinação azul petróleo / ciano + Dourado ou âmbar suave, representando a dualidade homem-máquina. O título do podcast em destaque: "Código Moral" em fonte geométrica e moderna (ex: Montserrat Bold, Orbitron, Exo 2) e o subtítulo "Quando a inteligência artificial encontra a consciência humana" em fonte fina e clara.
```


⌨️ com 💜 por [Beatriz Vesco Diniz](https://github.com/beatrizvesco)
