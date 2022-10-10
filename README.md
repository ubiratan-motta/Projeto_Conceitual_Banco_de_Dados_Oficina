**In Portuguese**
# Projeto de Banco de Dados de Oficina

	- Contexto: Levantamento de requisitos
	- Projeto Conceitual: Modelo Entidade Relacionamento
	- Projeto Lógico: Modelo Relacional

# Modelando Oficina:
## Ordem de serviço:
	- Deve ser vinculada a um tipo de trabalho a ser executado (conserto ou revisão).
	- Valor do serviço.
	- Cada peça tambem irá compor a OS
	- Numero, data de emissão, valor, status e data para conclusão dos trabalhos.
	- Pode ser composta por vários serviços e um mesmo serviço pode estar contido em mais de uma OS.
	- Uma OS pode ter vários tipos de peças e uma peça pode estar presente em mais de uma OS.

## Cliente:
	- O cliente pode ter mais de um veiculo 
	- Autoriza a execução dos serviços

## Veiculo:
	- O veiculo pode ser consertado ou ter revisão periodica
	
## Equipe:
	- Possui um numero de funcionarios
	- Cada um executa uma tarefa
	- Preencher OS com data de entrega
	- Avalia e Executa

## Mecânicos:
	- Código, nome, endereço e especialidade
	
## Tabela de Serviços
	- Tipo de serviço a ser executado, valor do serviço, peças utilizadas, tempo de entrega do serviço, 

## Entidades: 
- Ordem de Serviço, Cliente, Veiculos, Equipes, Funcionarios (mecânicos), Tabela de Serviços, Serviços, Estoque de Peças

# Refinamento:
	- Cliente pode: PJ e PF, possuir mais de um veiculo, formas de pagamento, 
	- Veiculo: Tipo do veiculo (carro, moto, caminhão), proprietário ou responsavel, Placa, Marca, Modelo, ano de fabricação.

## Software usado para modelagem
**MySQL Workbench**


**In English**
# Workshop Database Project

	- Context: Requirements gathering
	- Conceptual Project: Entity Relationship Model
	- Logical Design: Relational Model

# Modeling Workshop:
## Order of Service:
	- Must be linked to a type of work to be performed (repair or overhaul).
	- Service value.
	- Each piece will also compose the OS
	- Number, issue date, value, status and date for completion of the works.
	- It can be composed of several services and the same service can be contained in more than one OS.
	- An OS can have several types of parts and a part can be present in more than one OS.

## Client:
	- The customer can have more than one vehicle
	- Authorizes the execution of services

## Vehicle:
	- The vehicle can be repaired or have a periodic review

## Team:
	- Has a number of employees
	- Each performs a task
	- Fill in OS with delivery date
	- Evaluate and Execute

## Mechanics:
	- Code, name, address and specialty

## Table of Services
	- Type of service to be performed, service value, parts used, service delivery time,

## Entities:
	- Work Order, Customer, Vehicles, Teams, Employees (mechanics), Service Table, Services, Parts Inventory

# Refinement:
	- Customer can: PJ and PF, have more than one vehicle, payment methods,
	- Vehicle: Vehicle type (car, motorcycle, truck), owner or responsible, license plate, make, model, year of manufacture.

## Software used for modeling
**MySQL Workbench**
