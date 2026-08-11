# Baralho das Emoções — Landing Page

Landing page estática (HTML + CSS puro, sem build) inspirada no visual lúdico
do material "Emoções em Jogo" (EduRecorta), promovendo o produto **Baralho
das Emoções**.

## Estrutura

- `index.html` — todo o conteúdo da página
- `styles.css` — estilos (cores, tipografia, layout)

Sem dependências, sem passo de build. Os cartões/caixa do baralho na seção
inicial são mockups feitos só com CSS/emoji — troque por fotos reais do seu
produto quando tiver (basta substituir o bloco `.mock-box` / `.mock-card` em
`index.html` por `<img>` apontando para suas próprias imagens).

## Antes de publicar

- Os links de checkout (`#planos`) apontam para os links de pagamento reais
  informados — confirme se são os corretos antes de divulgar.
- Troque os mockups de carta/caixa por fotos/artes originais suas.

## Rodar localmente

Basta abrir `index.html` no navegador, ou servir a pasta com qualquer
servidor estático (ex.: extensão "Live Server" do VS Code).

## Deploy no GitHub

```bash
git init
git add .
git commit -m "Landing page Baralho das Emoções"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
git push -u origin main
```

## Deploy no Vercel

1. Acesse https://vercel.com/new
2. Importe o repositório do GitHub que você acabou de criar
3. Como é um site estático (sem framework), deixe o "Framework Preset" como
   **Other** — não é necessário build command nem output directory
4. Clique em **Deploy**

Alternativa via CLI:

```bash
npm i -g vercel
vercel
```
