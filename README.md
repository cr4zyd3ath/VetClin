# VetClin

1. Desenvolve uma aplicação Web do tipo CRUD na framework Laravel que permita gerir uma
clínica veterinária - VetLaranjeiras. O sistema de gestão (VetLaranjeiras) é composto pelos itens
Clientes, Veterinários, Especialidades, Animais e Raças. Contudo, apenas os três primeiros itens
(Clientes, Veterinários e Especialidades) devem ser codificados.

2. Crie Models + Migrations (make:model -m) para todas as três tabelas: Clientes, Veterinários e
Especialidades.

3. Crie Controllers + Rotas Resource (make:controller -r) para todas as três tabelas: Clientes,
Veterinários e Especialidades.

4. Crie a Base de Dados, através das migrations, com o nome vetclinica. A base de dados tem de
ser desenhada a pensar em todos os itens (Clientes, Veterinários, Especialidades, Animais e
Raças).

a. A tabela clientes tem, pelo menos, os seguintes campos: id, nome, telefone, email.
b. A tabela veterinarios tem, pelo menos, os seguintes campos: id, nome, omv,
especialidade_id.
c. A tabela especialidades tem, pelo menos, os seguintes campos: id, nome, descricao.
d. A tabela racas tem, pelo menos, os seguintes campos: id, nome, descricao.
e. A tabela animais tem, pelo menos, os seguintes campos: id, nome, data_nascimento,
raca_id.

5. Crie os seguintes relacionamentos (ORM):
a. Raças <-> Animais (1 para muitos)
b. Especialidades <-> Veterinários (1 para muitos)
c. Clientes <-> Animais (muito para muitos)

6. A nossa aplicação deve permitir inserir, consultar, atualizar e eliminar nas tabelas: Clientes,
Veterinários e Especialidades.
7. Cria todos os formulários necessários para interagir com as nossas tabelas.
8. Validação dos formulários (Validation do Laravel):

a. Clientes: “nome” é obrigatório, tamanho mínimo 3, tamanho máximo 50; “telefone”
é obrigatório, tamanho mínimo 9, tamanho máximo 13; “email” é obrigatório, campo
único na tabela clientes.
b. Veterinários: “nome” é obrigatório, tamanho mínimo 3, tamanho máximo 50; ”omv”
é obrigatório, tamanho mínimo 4, tamanho máximo 6, campo único na tabela
veterinários.
c. Especialidades: “nome” é obrigatório, tamanho mínimo 3, tamanho máximo 50;
“descricao”, tamanho mínimo 5 e tamanho máximo 250.

9. A nossa aplicação deve permitir efetuar várias pesquisas (filtros). Por exemplo, nome, telefone,
etc.
10. Cria um template para as tuas páginas e utiliza o bootstrap para melhorar o aspeto visual da tua
aplicação.
