<h1 align="center" style="font-weight: bold;">O Blog</h1>

<p align="center">
 <a href="#tech">Tecnologies</a> • 
 <a href="#started">Getting Started</a> • 
 <a href="#colab">Colaborators</a>
</p>

<p align="center">
    <b>Projeto desenvolvido com intuito de colocar em prática os meus conhecimentos com o framework Django e ambiente Docker.</b>
</p>

<h2 id="tecnologias">💻 Technologies</h2>

### Backend
- Python 3.12
- Django
- PostgreSQL
- Django Axes

### Frontend
- HTML5
- CSS3
- Font Awesome
- Django Summernote

<h2 id="started">🚀 Getting started</h2>

Para executar o projeto localmente:

### Pré-requisitos

Você terá que ter instalado em sua máquina:

- [Docker](https://www.docker.com/)
- [Python](https://www.python.org/)
- [Git](https://git-scm.com/downloads)

### Clonar o repositório

Para clonar o repositório:

```bash
git clone https://github.com/luccasocastro/meu-blog.git
```

### "Startando" o projeto

Antes de mais nada, precisamos setar algumas configurações

```bash
cd dotenv_files # entre na pasta dotenv_files

cp .env-example .env # faça uma cópia do .env-example e substitua os dados
```

Agora podemos buildar a imagem e subir os containers

```bash
# na raiz do projeto...
docker compose up --build
```

Os containers serão criados e a aplicação estará disponível em http://localhost:8000

### Execução de comandos

Para executar comandos dentro do container:

```bash
docker exec -it djangoapp <comando>

# por exemplo, utilizando os comandos da pasta /script

docker exec -it djangoapp migrate.sh
```

<h2 id="colab">🤝 Colaborators</h2>

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://avatars.githubusercontent.com/u/83096803?v=4" width="100px;" alt="Fernanda Kipper Profile Picture"/><br>
        <sub>
          <b>Luccas Souza</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

### 📚 Documentações que podem ajudar

- [📝 Como criar um Pull Request](https://www.atlassian.com/br/git/tutorials/making-a-pull-request)
- [💾 Padrões de Commit](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)