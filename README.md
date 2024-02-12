# SQL-model-Oficina
Modelando sistema de ordem de serviço de uma oficina com MySQL Workbench


## Naratiava:
<p> É um sistema de controle de gerenciamento de execução de ordens de serviço em uma oficina mecânica.</p>

<p> Os clientes levam voeículos à oficina para serem consertados ou passarem por uma revisão periódica.</p>

![image](https://github.com/the1ander/SQL-model-Oficina/assets/151629165/8b36a440-a10f-4082-9ad4-d74a7ddcc42d)

<p>Cada veículo é desigbnado a uma equipe de mecanicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.</p>
<p>A partir da OS, calcula-se o vlaor de cada serviço, consultando-se uma tabela de referencia de mão de obra.</p>


![image](https://github.com/the1ander/SQL-model-Oficina/assets/151629165/94f46834-1b1c-417d-a92d-8420af94c73b)


<p>O valor da peça também irá compor a OS.</p>

![image](https://github.com/the1ander/SQL-model-Oficina/assets/151629165/725f0dcd-5608-4453-a859-90c7287dd533)

<p>A mesma equipe avalia e executa o serviço.</p>

## Atribuos citados:

<p>Os mecânicos possúem código, nome, endereço e especialidade.</p>

![image](https://github.com/the1ander/SQL-model-Oficina/assets/151629165/d6d1c31b-fade-4fce-9ae1-c8ea6c26cadc)

<p>Cada OS possúi, numero, data de emissão, um valor, status e uma data para conclusão do trabalho.</p>

![image](https://github.com/the1ander/SQL-model-Oficina/assets/151629165/e0b682ae-622d-4945-bb16-f560149403af)

## Relacionamentos:

<p>Uma os pode compor vários serviços e um mesmo serviço pode estar contido em mais de uma OS.</p>

![image](https://github.com/the1ander/SQL-model-Oficina/assets/151629165/fd6a79b9-7b1c-47f7-9bac-b322d2cb44a0)

<p>uma OS pode ter vários tipos de peça e uma peça pode estar presente em mais de uma OS.</p>

![image](https://github.com/the1ander/SQL-model-Oficina/assets/151629165/e2e05b41-1026-4fde-811a-78d2ba081fbf)

# MODELO COMPLETO:
[modeloOficina.pdf](https://github.com/the1ander/SQL-model-Oficina/files/14237505/modeloOficina.pdf)







