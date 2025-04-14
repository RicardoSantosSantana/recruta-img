# 🎯 Recruta Assets

Este repositório contém os arquivos de imagem estáticos utilizados para customizar a interface de autenticação do Keycloak no projeto **Recruta**.

## 📦 Conteúdo

As imagens hospedadas aqui são servidas via CDN utilizando o [jsDelivr](https://www.jsdelivr.com/), garantindo alta performance e disponibilidade global.

### Exemplos de arquivos incluídos:

- `logo.svg` – Logotipo principal usado na tela de login
- `bg-login.png` – Imagem de fundo customizada
- `favicon.png` – Ícone do navegador
- `loader.gif` – Ícone de carregamento personalizado

## 🌐 Acesso via CDN

Para utilizar as imagens em ambientes externos (ex: Keycloak), utilize os links no seguinte formato:

```
https://cdn.jsdelivr.net/gh/<seu-usuário>/recruta-assets@latest/<nome-do-arquivo>
```

### Exemplo:

```
https://cdn.jsdelivr.net/gh/seunome/recruta-assets@latest/logo.svg
```

> **Dica**: Para evitar cache antigo, você pode usar `@latest` ou referenciar um commit específico se preferir controle de versão.

## 🛠️ Uso no Keycloak

No arquivo `theme.properties` do seu tema personalizado:

```properties
projectLogo=https://cdn.jsdelivr.net/gh/seunome/recruta-assets@latest/logo.svg

https://cdn.jsdelivr.net/gh/RicardoSantosSantana/recruta-img@latest/recruta-write-light-green.svg

https://cdn.jsdelivr.net/gh/RicardoSantosSantana/recruta-img@latest/pimentaGROUP.svg
```

---

## 🔒 Observações

- Este repositório é **público** para permitir o uso via CDN.
- Nenhuma informação sensível deve ser armazenada aqui.


 