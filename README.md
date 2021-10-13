# List Musics From Genius

<!---Esses são exemplos. Veja https://shields.io para outras pessoas ou para personalizar este conjunto de escudos. Você pode querer incluir dependências, status do projeto e informações de licença aqui--->

![GitHub language count](https://img.shields.io/github/languages/count/iuricode/README-template?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/iuricode/README-template?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/iuricode/README-template?style=for-the-badge)

<img src="exemplo-image.png" alt="exemplo imagem">

> Busque pelas 10 músicas mais populares de seus artistas favoritos.

### Ajustes e melhorias

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas nas seguintes tarefas:

- [x] Autenticar e consumir Genius API
- [ ] Testes com pytests
- [x] Armazenar dados em cache com Redis
- [x] Configurar o o Amazon DynamoDB 
- [x] Armazenar dados no Amazon DynamoDB
- [x] Criar interface para usuário visualizar artistas e músicas
- [x] Deploy da API em na Amazon EC2 com Gunicorn e Nginx
- [x] Deploy da aplicação dem React na Netify com CI
- [ ] Criar Cluster com Redis para armazena os dados em cache usando o Amazon ElastiCache
- [ ] Https Na API
- [ ] Refatorar código com foco em segurança, tratar variáveis de ambiente.

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:
* Ter instalado Python >= 3.8 e NodeJS >= 12.0
* Ter instalado as dependências da api com pip install -r requiriments.txt
* Ter instalado as dependências web com npm i
* Ter configurado as variáveis de ambiente
* Ter o Redis instalado em sua máquina.

## 🚀 Instalando <nome_do_projeto>

Para instalar o List Musics From Genius, siga estas etapas:

```
git clone https://github.com/DanielNery/list-mscs-genius.git
git submodule update --init --recursive --remote
git submodule status

```

## ☕ Usando List Musics From Genius

Para usar List Musics From Genius, siga estas etapas:

```
Após ter iniciado as aplicações, informe o nome do artista de sua preferência na barra da pesquisa.
Clique em "Pesquisar" e será listado as músicas e artistas corrêspondentes a sua pesquisa.
Escolhe a música ou o artista que deseja visualizar as músicas mais populares e serão listadas as 10 músicas mais populares.  
```

Adicione comandos de execução e exemplos que você acha que os usuários acharão úteis. Fornece uma refer

## 📫 Referências

1. https://flask-restful.readthedocs.io/en/latest/
2. https://docs.genius.com/
3. https://pt-br.reactjs.org/
4. https://docs.aws.amazon.com/
5. https://redis.io/documentation


[⬆ Voltar ao topo](#List Musics From Genius)<br>

