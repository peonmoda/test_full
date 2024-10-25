## **Desafio**

Este desafio tem o objetivo de avaliar melhor suas skills como desenvolvedor, não apenas raciocínio lógico, mas também organização, capacidade de resolver problemas, engenhosidade, clareza do código, detalhamento visual, etc.

O que esperamos é que seja desenvolvido um pequeno projeto contendo os elementos básicos de front-end/back-end, porém que aplique o máximo do seu conhecimento em conceitos e padrões.

Fica ao critério do desenvolvedor em qual stack utilizar, podendo realizar apenas front-end ou back-end, ou ambos.


## **Front-end:** 

O desafio proposto consiste em implementar uma aplicação onde temos uma listagem de pessoas e uma tela de cadastro e seus endereços, onde podemos criar, visualizar, editar e remover (CRUD) e podem ser encontrados por uma pesquisa feita com base em seu nome ou identificação, os dados devem ser mockados ou feito o backend em Java.

**Instruções:**
Queremos que nos mostre todo seu conhecimento, com isso, toda regra de negócio, fluxo de navegação, validações de formulários, noções de usabilidade, infra e layout ficarão a seu critério.

Use e abuse de seus conhecimentos e sugestões.

**Link do protótipo:**
Encontra-se no repositorio do teste.
Não se apegue ao protótipo acima, ele é só uma referência, Use sua criatividade, sugestões ou novas opções será um diferencial.

**Requisito:**
Utilizar Angular 15+, Typescript;
Formulário reativo;
Utilize a api de CEP (https://viacep.com.br/) para pegar os dados, tratar e preencher os campos de endereço;

**Validações:**
Campos obrigatorios são marcados com *;
CPF deve ser válido;
Data de nascimento não pode ser data futura;
Validar sintaxe do email do contato;
A pessoa deve ter ao menos um endereço;

## **Back-end:**

O desafio proposto consiste em implementar uma API RESTful que possua CRUD de pessoas.

**Requisito:**

 - CRUD de pessoas;
 - A pesssoa deve possuir ao menos um endereço;
 - Os dados devem ser persistidos utilizando um banco de dados relacional;
 - Utilizar Java 11+;
 - Validar identificação, Data nascimento, email e telefone;
 - Criar testes unitários e integração;

##

- **Pessoa**
  
| Atributos         | Valor                   | Obrigatório |
| ----------------- | ----------------------- | ----------- |
| `Identificação`   | 15642042009             | true        |
| `Nome`            | Fulado da silva         | true        |
| `Email`           | fulano.silva@peon.moda  | true        |
| `Data nascimento` | 01/01/2024              | false       |
| `Telefone`        | 4430333000              | true        |
| `Endereço`        | Lista                   | true        |

- **Endereço**

| Atributos       | Valor                         | Obrigatório |
| :-------------- | :---------------------------- | :---------- |
| `Tipo endereço` | Principal, entrega, comercial | true        |
| `Código postal` | 87050130                      | false       |
| `Logradouro`    | Avenida Paiçandu              | true        |
| `Número`        | 718                           | true        |
| `Complemento`   | 1º andar                      | false       |
| `Bairro`        | Zona 03                       | true        |
| `Município`     | Maringá                       | true        |
| `Estado`        | Paraná                        | true        |

## **Entrega do desafio:**
1. Crie um repositorio privado com nome da sua aplicação;
2. Adicione o usuario `@gitprodutec` como colaborador;
3. Adicione seu currículo na raiz do repositório;
4. Adicione todo o codigo e instruções de como rodar o projeto;
5. Envie o link do repositório para o seu recrutador e avise que finalizou o teste;
6. Aguarde o feedback, boa sorte!
