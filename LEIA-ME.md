# Site do Delibera: como publicar

Esta pasta é o site completo. Os arquivos que vão para a hospedagem:

- `index.html`: a página
- `og-delibera.png`: imagem que aparece na prévia do link no WhatsApp e no e-mail
- `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png`: ícones da aba do navegador e do celular

(Este `LEIA-ME.md` pode ir junto, não atrapalha.)

## 1. Registrar o domínio

1. Acesse registro.br e entre com o CNPJ da Performance.
2. Pesquise `deliberaconselhos.com.br` e conclua o registro (cerca de R$ 40 por ano).

## 2. Publicar no Netlify (gratuito)

1. Crie uma conta em netlify.com.
2. Vá em **Add new site → Deploy manually** e arraste esta pasta `site` inteira para a área indicada.
3. Em poucos segundos o site fica no ar em um endereço provisório, do tipo `nome-aleatorio.netlify.app`.

## 3. Ligar o domínio

1. No Netlify, abra o site e vá em **Domain management → Add a domain**. Digite o domínio registrado.
2. O Netlify mostra os servidores DNS (algo como `dns1.p01.nsone.net`). Copie-os.
3. No registro.br, abra o domínio, vá em **DNS → Alterar servidores DNS** e cole os servidores do Netlify.
4. A ativação leva de algumas horas até 1 dia. O Netlify cria o certificado de segurança (https) sozinho.

## 4. Prévia do link

O `index.html` já aponta para `https://deliberaconselhos.com.br`. A imagem de prévia aparece no WhatsApp quando o domínio estiver ligado ao Netlify. Se o domínio mudar, peça ao Claude para trocar o endereço.

## Link personalizado por município

Funciona igual: `https://deliberaconselhos.com.br/#presidente-bernardes`.
