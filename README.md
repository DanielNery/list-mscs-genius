# List Musics From Genius

![GitHub language count](https://img.shields.io/github/languages/count/iuricode/README-template?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/iuricode/README-template?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/iuricode/README-template?style=for-the-badge)

https://user-images.githubusercontent.com/59855397/137046469-6c3b02d4-2cdf-479f-931f-0b6e7f89234f.mp4

> Busque pelas 10 músicas mais populares de seus artistas favoritos.
> Descubras novas músicas e novos cantores e bandas.
> /search/Eminem (Lista os conteúdos envolvendo a string informada)
> /artist/45/Eminem (Lista as 10 Músicas mais populares do artista)
> /artist/45/Eminem?cache=False (Faz uma nova requisição atualziando os dados)

![eminemapi](https://user-images.githubusercontent.com/59855397/137046580-9dce794c-502e-47e6-b295-349db9f951bb.png)

![list_music_with-genius](https://user-images.githubusercontent.com/59855397/137046126-d61508fb-9b32-4a54-ba49-8a29c29099e9.png)

### Ajustes e melhorias

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas nas seguintes tarefas:

- [x] Autenticar e consumir Genius API
- [ ] Testes com pytests
- [x] Armazenar dados em cache com Redis
- [x] Configurar o Amazon DynamoDB 
- [x] Armazenar dados no Amazon DynamoDB
- [x] Criar interface para usuário visualizar artistas e músicas
- [x] Deploy da API em na Amazon EC2 com Gunicorn e Nginx
- [x] Deploy da aplicação dem React na Netify com CI
- [ ] Criar Cluster com Redis para armazena os dados em cache usando o Amazon ElastiCache
- [ ] Https Na API
- [ ] Refatorar código com foco em segurança, tratar variáveis de ambiente.

> Armazenamento de dados no DynamoDB

![dynamodb](https://user-images.githubusercontent.com/59855397/137047208-23fd1281-3a63-4337-a9fc-cdcb33ddbedb.png)

> Sistema de cache com Redis

![redis](https://user-images.githubusercontent.com/59855397/137047309-d713f915-2a9c-49de-99cc-884ef7a82de6.png)

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:
* Ter instalado Python >= 3.8 e NodeJS >= 12.0
* Ter instalado as dependências da api com pip install -r requiriments.txt
* Ter instalado as dependências web com npm i
* Ter configurado as variáveis de ambiente
* Ter o Redis instalado em sua máquina.

## 🚀 Instalando o List Musics From Genius

Para instalar o List Musics From Genius, siga estas etapas:

```
git clone https://github.com/DanielNery/list-mscs-genius.git
git submodule update --init --recursive --remote
git submodule status
cd apis/listmsc
virtualenv venv
source venv/bin/activate
pip3 install -r requiriments.txt
python3 app.py

cd frontend/listmsc
npm i
npm start

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

