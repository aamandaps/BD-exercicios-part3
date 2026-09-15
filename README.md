# Exercícios de Banco de Dados - Domínio, Relação e Tuplas/Registro

1) Um berçario deseja informatizar suas operações. Quando um bebê nasce, algumas
informações são armazenadas sobre ele, tais como: nome, data do nascimento, peso do
nascimento, altura, a mãe deste bebê e o médico que fez seu parto. Para as mães, o
berçário também deseja manter um controle, guardando informações como: nome,
endereço, telefone e data de nascimento. Para os medicos, e importante saber: CRM,
nome, telefone celular e especialidade. Uma mãe pode ter diversos bebês(gêmeos,
trigêmeos, etc.), que serão apenas de uma mãe. Pelo menos um médico participa do parto dos
bebês, mas pode haver a necessidade de vários médicos no parto.

2) Elaborar o diagrama, bem como identificar os atributos de cada entidade e relacionamentos,
para um ambiente empresarial, composto de departamentos, sabendo-se que:
 
   * Cada departamento possui um código, nome, sigla e um chefe;
   * Os chefes de departamento estão divididos em categorias e, para a empresa, é importante
saber a data em que foi assumida cada chefia;
   * Os empregados da empresa estão ligados a um departamento e a cada um deles está
associado matricula, nome, sexo, telefone, dependentes, data de admissão e cargo;
   * Os empregados são alocados em projetos e a informação data de alocação deve ser mantida;
   * Cada proieto e caracterizado por um numero, nome e horas previstas:

***

1) Construa o modelo Entidades-Relacionamentos a partir da seguinte descrião do sistema:
Pretende-se criar uma base de dados que permita gerir uma parte da informação de uma
clinica de saúde. Fundamentalmente a base de dados deverá guardar a informação relativa
aos doentes que frequentam a clínica (nome, endereço (Rua, número, cep e
complemento), telefone e numero de beneficiario) e dos medicos que la trabalham
(código, nome, endereço (Rua, número, cep e complemento), contato e especialidade).
Para além disso o sistema deverá registrar as marcações de consultas de cada paciente
para um determinado médico, num dia e hora específicos. No entanto, na clinica um
paciente pode obviamente consultar diferentes medicos para a mesma ou para diferentes
especialidades. O sistema deverá ainda para cada paciente e por especialidade permitir
organizar uma ficha de informacoes que e atualizada sempre que um medico da
especialidade observa esse paciente.

2) O Clube Desportivo SPORT é uma instituição sem fins lucrativos que pretende informatizar
o seu serviço de secretaria. O clube possui nas suas instalações: quatro campos de ténis,
uma piscina, um campo de futebol e um pavilhao. As suas atividades principais são o
ensino das modalidades de ténis, ginástica e natação, além do aluguel dos seus recintos
desportivos.
A secretaria do SPORT regista sempre que se inscreve um novo sócio os seguintes dados:
código de sócio, nome, data de admissão, CPF, data de nascimento, endereço (rua, número
e CEP) e telefone.
Um sócio pode inscrever-se em qualquer modalidade ministrada (ténis, ginástica e
natação) desde que hajam vagas no horário pretendido e pagando por isso uma
determinada mensalidade.
A secretaria aceita ainda marcações para qualquer recinto desportivo desde que o recinto
esteja disponível, sendo o pagamento efetuado em simultâneo com a marcação. Qualquer
pagamento recebido, tem o preenchimento e emissão de um recibo.
