Erro do codigo: No codigo fornecido a  classe Invoice tem múltiplas responsabilidades, representando os dados da fatura, além de ser responsável por imprimir e salvar no banco de dados, violando o princípio SRP que estabelece que uma classe deve ter apenas um motivo para mudar.

Solução do erro: Separar as responsabilidades em classes distintas: uma que representa apenas os dados da fatura, outra que seja responsável pela impressão e uma última dedicada ao salvamento no banco de dados.
