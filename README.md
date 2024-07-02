# Enunciado

Literalura é um software desenvolvido em Java com Spring que faz consultas na API Gutendex, armazena as informações dos livros, autores e idiomas, e permite diversas operações locais sobre esses dados.

## Funcionalidades

- API Gutendex (Consulta livros) (https://gutendex.com).
- Armazena informações de livros, autores e idiomas.
- Lista livros salvos localmente.
- Lista autores salvos localmente.
- Busca livros por idioma localmente.
- Busca autores vivos por ano informado.

## Requisitos mínimos

- Java 17

## Configuração das variáveis de ambiente:

- DB_HOST=localhost
- DB_NAME=literalura
- DB_PASSWORD=docker
- DB_USER=docker


O parâmetro -d faz com que o container execute em background.

## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/literalura.git
```

2. Navegue até o diretório do projeto:

```bash
cd literalura
```
3. Compile e execute o projeto:

```bash
mvn spring-boot:run
```

## Uso na linha de comando

O software realiza consultas na API Gutendex para obter informações sobre livros, autores e idiomas, e armazena esses dados em um banco de dados local. 

O software roda em linha de comando, não sendo uma API completa, mas é um primeiro passo pois a mesma está parcialmente organizada com Services e Repositories.

---

### Autor: Rodrigo Duarte

| [Linkedin](https://www.linkedin.com/in/rodrigoduar-te/) | [GitHub](https://github.com/rodrigoduartesilva/) | [Link do Repositório](https://github.com/rodrigoduartesilva/literalura-challenge-alura) |