# Fala Comigo — prancha de comunicação

App de comunicação alternativa (CAA) para crianças não verbais. Botões grandes que falam
em português usando a voz do próprio iPhone. Tudo fica em um arquivo só: `index.html`.

## Como funciona

- **Tela inicial:** SIM e NÃO ocupando a tela inteira. Toque = o aparelho fala a palavra.
- **Arrastar para o lado:** troca de prancha. Já vêm três prontas — *Sim ou Não*,
  *Eu quero* (brincar, comer, água, banheiro, música, descansar) e *Como eu estou*
  (feliz, triste, bravo, com medo, cansado, dói).
- **Editar:** **segure o botão ⚙ no canto inferior direito por 1 segundo**. Ele abre a tela
  de edição. É segurado de propósito, para a criança não entrar sem querer mexendo na tela.
- **Na edição dá para:** criar novas pranchas, renomear, adicionar/remover/reordenar botões,
  escolher cor e emoji de cada botão, escrever um texto de fala diferente do rótulo
  (ex.: botão "Água", fala "Eu quero água"), escolher a voz e a velocidade.
- Tudo é salvo no próprio aparelho, e funciona sem internet depois de instalado.

## Instalar no iPhone 14

1. Abrir o link do app **no Safari** (não no Chrome — só o Safari instala na tela inicial).
2. Tocar no botão **Compartilhar** (quadrado com seta para cima).
3. **Adicionar à Tela de Início** → **Adicionar**.
4. Abrir pelo ícone criado: abre em tela cheia, sem barra de navegador.

### Se não sair som
- Conferir o **botão lateral de silencioso** e o volume.
- Ajustes › Acessibilidade › **Conteúdo Falado** › Vozes › Português (Brasil) — baixar uma
  voz (a "Luciana" é a padrão brasileira). Depois escolher essa voz na tela de edição do app.

## Endereço do app

**https://nibizu.github.io/fala-comigo/**

Hospedado no GitHub Pages, de graça e sem prazo. É esse link que ela abre no Safari do
iPhone para instalar. Já tem ícone próprio (as duas barras verde e vermelha) e abre em
tela cheia, sem barra de navegador.

Repositório: https://github.com/nibizu/fala-comigo (público, só o `index.html`, o ícone
e o manifesto).

### Para atualizar o app depois

Edite o `index.html` desta pasta e rode, no terminal, dentro de uma cópia do repositório:

    git add -A && git commit -m "ajustes" && git push

Em cerca de um minuto o site novo está no ar. Quem já instalou no iPhone recebe a versão
nova ao abrir com internet.

## Backup das pranchas

As pranchas ficam salvas no navegador do aparelho. Se o iPhone limpar os dados do site,
elas se perdem. Na tela de edição existe **Cópia de segurança › Copiar minhas pranchas**:
cole esse texto em uma nota ou e-mail. Para voltar tudo, use **Restaurar de um texto**.
Vale fazer isso sempre que ela montar pranchas novas.

## App nativo na App Store

Para virar um app nativo mesmo (instalado pela App Store), precisaria de um Mac com Xcode
e conta de desenvolvedor Apple (US$ 99/ano). Para uso clínico dela, a versão instalada na
tela inicial se comporta igual a um app e não custa nada.
