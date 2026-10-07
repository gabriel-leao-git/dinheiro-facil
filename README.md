# 💸 Dinheiro Fácil

Jogo web **incremental de mineração fictícia**, mobile-first. Monte sua fazenda de placas, veja os números subirem e "saque" seu saldo — tudo de mentirinha.

> ⚠️ **JOGO FICTÍCIO — SEM DINHEIRO REAL.**
> Nenhum valor exibido em R$ é real ou conversível. O jogo **não pede nenhum dado pessoal** (sem CPF, e-mail, telefone, banco ou senha) e **não transfere dinheiro** de verdade. É só entretenimento.

## Como jogar

1. Abra o `index.html` no navegador (celular ou PC).
2. Digite um nome ou apelido (sem cadastro, sem senha).
3. **Toque no rig** para minerar; o saldo também sobe sozinho, devagar.
4. Compre placas melhores na **Loja** para minerar mais rápido.
5. Aproveite os **pop-ups de turbo** (2x até 20x) por tempo limitado.
6. Bata as **metas** (dobram a cada conquista) e use o botão verde **SACAR** para registrar um saque simbólico com comprovante de brincadeira.

## Recursos

- ⛏️ Rig de GPU desenhado em SVG com **coolers girando** (a velocidade acompanha a mineração)
- 🌌 **Efeito parallax** com ponteiro e giroscópio
- 💾 Progresso salvo localmente (`localStorage`) — só neste aparelho
- 🛠️ Ganhos **offline** (até 8h) ao voltar
- ⚡ Pop-ups de multiplicador 2x→20x
- 🎯 Metas geométricas (dobram a cada objetivo)
- 📱 Mobile-first, sem dependências externas — **um único arquivo `index.html`**

## Rodando

É um arquivo estático. Basta abrir `index.html`, ou servir a pasta:

```bash
python -m http.server 8000
# acesse http://localhost:8000
```

Ou publicar direto no **GitHub Pages** (Settings → Pages → branch `main` / root).

## Tecnologia

HTML + CSS + JavaScript puro (vanilla), sem bibliotecas, sem build.

---

Feito para diversão. Se alguém te oferecer um app parecido prometendo **dinheiro real** por "mineração", desconfie: isso costuma ser golpe. Aqui é só jogo. 💛
