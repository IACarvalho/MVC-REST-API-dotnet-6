# Requisitos
1. A Api deve ser escrita utilizando C#
2. Usar uma biblioteca de validação (ex.: FluentValidation)
3. Usar Injeção de Dependência nas Controllers e Repositórios
4. As operações de acesso a dados devem passar por um repositório (usar o REPOSITORIO PATTERN)
  a. Deve haver um repositório base, utilizando o conceito de GENERIC
  b. Os repositórios específicos das entidades devem herdar desse repositório base.
5. Usar o ORM de sua preferência
6. O(s) endpoint(s) de busca devem usar o AUTOMAPPER para retornar um DTO para o frontend