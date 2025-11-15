
# PRIFLIX 2000

![Logo do Projeto](https://tm.ibxk.com.br/2025/07/29/29130308679229.jpg?ims=1600x900/filters:format(jpg)) 

Um site front-end interativo inspirado no universo de **Rick and Morty**, focado em desenhos animados dos anos 90 e 2000. O projeto consome dados em tempo real da API pública do Rick and Morty para exibir personagens icônicos, com animações, rolagem horizontal e funcionalidade de busca.

## 🚀 Funcionalidades

- **Página Inicial (Hero)**: Vídeo de fundo com chamada para ação.
- **Seção de Curiosidades**: Texto histórico sobre desenhos animados.
- **Personagens Icônicos**: Cards dinâmicos com imagem, nome, status e espécie.
- **Destaques (Movies)**: Lista de personagens de uma página diferente da API.
- **Preferidos da TV (Series)**: Outra lista variada de personagens.
- **Busca**: Filtre personagens por nome em tempo real.
- **Responsivo**: Layout adaptável para desktop e mobile.
- **Animações**: Fade-in ao rolar e hover nos cards.

## 🛠 Tecnologias Utilizadas

- **HTML5**: Estrutura do site.
- **CSS3**: Estilização com tema escuro, molduras de livro e responsividade.
- **JavaScript (Vanilla)**: Consumo da API via Fetch, manipulação do DOM e interatividade.

## 📋 Como Executar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seuusuario/priflix-2000.git
   cd priflix-2000
   ```

2. **Abra o arquivo**:
   - Abra `index.html` diretamente em um navegador (Chrome recomendado).
   - Não há dependências externas além da API pública.

3. **Teste**:
   - Os cards serão carregados automaticamente da API.
   - Use a barra de busca para filtrar personagens.
   - Role horizontalmente nas seções para ver mais.

## 📁 Estrutura do Projeto

```
priflix-2000/
├── index.html          # Arquivo principal com HTML, CSS e JS inline
├── rickvideo.mp4       # Vídeo de fundo (adicione ao repositório se não estiver)
└── README.md           # Este arquivo
```

- Todo o código está em um único arquivo `index.html` para simplicidade.
- O vídeo `rickvideo.mp4` deve ser adicionado à raiz (não incluído aqui por tamanho).

## 🌐 API Utilizada

- **Rick and Morty API** (https://rickandmortyapi.com/): Gratuita, sem token. Fornece dados de personagens como nome, imagem, status e espécie.
- Endpoints usados: `/api/character?page=1`, `/api/character?page=2`, `/api/character?page=3` para variar o conteúdo.

## 🎥 Vídeo Pitch

Assista à apresentação do projeto: [Link do YouTube](https://youtu.be/hWBLEQO8qDg)) 

## 🤝 Contribuições

Contribuições são bem-vindas! Abra uma issue ou pull request para melhorias.

## 📄 Licença

Este projeto é para fins educacionais. Não possui licença específica.

---

**Desenvolvido por Vitória Gomes** - Parte do trabalho de desenvolvimento web front-end.
```
