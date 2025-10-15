
````markdown
# 🎉 Página de Aniversário

Este projeto é uma página estática em HTML que celebra o aniversário da Suane com **animações de confete, balões, fogos de artifício** e uma **mensagem secreta cifrada**.  
A mensagem só pode ser revelada digitando a **chave correta**, que é a **slug** (nome) da página no link.

---

## 🚀 Como funciona
- A página exibe animações festivas (confetes, balões e brilhos).
- No centro, há uma **mensagem cifrada** (Vigenère).
- Para desbloquear, a pessoa deve digitar a **slug** (a última parte do link, ex.: `meu-docinho-minha-alegria`).
- Ao acertar, a mensagem é revelada com efeito de digitação e um **burst de confetes + fogos de artifício**.

---

## 🗂 Estrutura do Projeto
- `index.html` → Página final publicada (contém a mensagem cifrada).  
- `encryptor.html` → Ferramenta local para cifrar sua carta usando a slug como chave.

---

## 🔑 Fluxo de Uso
1. Abra `encryptor.html` no navegador.
2. Digite a **slug** escolhida (ex.: `meu-docinho-minha-alegria`).
3. Cole sua carta no campo de texto.
4. Clique em **Cifrar** → copie o texto gerado.
5. No `index.html`, substitua o placeholder do `cipherBox` pelo texto cifrado.
6. Certifique-se de que a **slug** está igual no `<title>` e no link final.
7. Suba no **GitHub** e publique pelo **Vercel**.

---

## ✨ Demonstração
- Link publicado:  
  ```text
  https://seu-projeto.vercel.app/meu-docinho-minha-alegria
````

* Chave correta: `meu-docinho-minha-alegria`.

---

## 🎇 Animações

* **Confete contínuo**: chuva sutil de fundo.
* **Balões**: sobem lentamente pelo cenário.
* **Brilhos**: partículas discretas animadas.
* **Burst (ao acertar a chave)**: explosão única de confetes e fogos.

---

## ⚙️ Tecnologias

* HTML5
* CSS3 (gradientes, animações, blur)
* JavaScript Vanilla (Canvas API para confete/fogos, cifra Vigenère)

---

## 🧭 Personalização

* **Slug** → escolha uma frase curta/intimista em `kebab-case` (sem acentos).
* **Carta** → escreva no `encryptor.html` e cifre.
* **Paleta** → altere cores em `:root` (CSS).
* **Mensagem de dica** → edite no HTML.

---

## 🛡 Observações

* O texto cifrado fica seguro no código (ninguém lê sem a chave).
* Não há backend: tudo roda localmente no navegador.
* Ideal para surpresas íntimas (pistas, cartas pessoais, etc).

---

💛 Feito com dedicação para algo inesquecível.

```

---

👉 Quer que eu já prepare também um **`LICENSE`** (MIT, por exemplo) para acompanhar o repositório, ou prefere deixar fechado/intimista sem licença pública?
```
