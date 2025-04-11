# 🎵 Spotify Clone Menu

Clone funcional da página inicial do Spotify com foco em interface e experiência do usuário. O projeto simula a navegação, busca e exibição de artistas usando **HTML**, **CSS** e **JavaScript**. Também foi utilizado o JSON Server para simular uma API REST e integrar dados dinâmicos, como nome e imagem de artistas, permitindo que os resultados mudem conforme o usuário digita.

## 🚀 Demonstração

Acesse o projeto online:  
🔗 [https://matheusiyoshida.github.io/Spotify-clone-menu/](https://matheusiyoshida.github.io/Spotify-clone-menu/)

## 🛠 Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- JSON

## 📁 Como usar

### 📁 Pré-requisitos

- Node.js instalado: [https://nodejs.org](https://nodejs.org)

Clone o repositório:

```bash
git clone https://github.com/MatheusIYoshida/Spotify-clone-menu.git
```

Abra o terminal e instale o JSON Server globalmente (caso ainda não tenha):
```bash
npm install -g json-server@0.17
```

Com o terminal aberto na raiz do projeto, execute o seguinte comando:
```bash
json-server --watch api-artists/artists.json --port 3000
```

Após instalar e iniciar o JSON Server, abra o arquivo `index.html` no seu navegador:
```bash
cd Spotify-clone-menu
open index.html
```
