> **Vaga**: Desenvolvedor Full-stack

# O Desafio

O desafio consiste em criar um pequeno e simples catálogo de filmes, separados por gêneros onde o usuário possa realizar alguns filtros (use a imaginação) :wink:

## Requisitos Obrigatórios - Back-end
* Construir uma API REST
* O retorno dos dados deve ser no formato JSON. 
* Todos os filtros devem ser aplicados na API
* Usar PHP >= 7.1
> **Obs.**: Pode usar ou não qualquer framework, fica a sua escolha.

## Requisitos Obrigatórios - Front-end
* Construir uma interface gráfica com HTML, css e JavaScript
> **Obs.**: Caso opte por usar framework / template engine, dê preferências aos seguintes: ReactJS / TWIG ou Blade.

## Diferenciais - Não necessário
* Trabalhar com Container.
* Trabalhar com Composer.
* Colocar uma autenticação JWT.
* Criar um cache para consulta.
* Cobertura de testes.
* Documentação técnica.

## Orientações
* Procure fazer uma API sucinta e documentada.
* Os arquivos necessários estão no repositório.
* Pense em escalabilidade.
* Seja claro e objetivo na descricao do seu commit
* Coloque seu projeto em um repositório GIT, deixe-o público e envie o link no e-mail ``dev@valesulshopping.com.br`` com o título ``Desafio Vale Sul Shopping - `${SEU_NOME_AQUI}` ``
* Todas as alterações efetuadas após o envio serão descartadas, então, tenha certeza que está tudo OK antes de enviar.
* Descreva no **README** todo o processo necessário para fazer o setup e o start do seu projeto.

#### Exemplo do formato do arquivo de data/movies.json
```bash
[
  {
    "id": "id-example",
    "name": "name-example",
    "description": "description-example",
    "image": "image-example", 
    "genres": ["genres-example-1", "...", "genres-example-n"], 
    "year_publication": 2020, 
    "featured": false
  }
]
```
#### Descrição dos dados e suas respectivas propriedades
| Propriedade        | Tipo   | Descrição           |
| -------------------|:-------:|--------------------|
| `id`               | UUID    | Id do filme        |
| `name`             | String  | Nome do filme      |
| `description`      | String  | Descrição do filme |
| `image`            | String  | Link da imagem     |
| `genres`           | Array   | Gêneros do filme   |
| `year_publication` | Year    | Data de publicação |
| `featured`         | Boolean | Filme de destaque  |

## Avaliação
O que vamos avaliar:
* Desempenho;
* Raciocínio lógico;
* Escalabilidade/Manutenabilidade;
* Organização;
* Boas práticas.

Te desejamos boa sorte e caso surja alguma dúvida, entre em contato conosco.

Vale Sul Shopping :copyright: 2020 