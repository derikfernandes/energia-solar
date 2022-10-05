# energia-solar

Nesta apresentação, eu estarei utilizando dados abertos disponibilizados pela ANEEL - Agência Nacional de Energia Elétrica e dados sobre CNPJs disponibilizados pela receita federal. Tais arquivos conterão informações sobre a instalação de empreendimentos de energia fotovoltaíca e sobre as características de CNPJs abertos no município.

Você pode acessar dados mais atualizados visitando as seguintes páginas:

https://dadosabertos.aneel.gov.br/dataset/empreendimentos-em-operacao
https://www.gov.br/receitafederal/pt-br/assuntos/orientacao-tributaria/cadastros/consultas/dados-publicos-cnpj



Para este estudo, utilizarei os seguintes Datasets:

Dados Abertos CNPJ EMPRESA
Dados Abertos CNPJ ESTABELECIMENTO
Dados Abertos CNPJ SÓCIO
empreendimento-operacao-historicoCSV Popular


Ocorrencia.csv: possui os dados sobre cada ocorrência registrada nos últimos 10 anos. Código da ocorrência, Data, Motivo da Ocorrência e Localização serão encontrados nesse conjunto de dados.

Aeronave.csv: informações agrupadas sobre as aeronaves envolvidas nas ocorrências registradas no arquivo ocorrencia.csv. Aqui serão encontrados dados como: Modelo da Aeronave, Tipo de Aeronave, Fabricante, Quantidade de Fatalidades, dentre outras.

Perguntas a serem respondidas
Quais são as maiores causas de ocorrências e, eventualmente, queda de aviões?
Como tem sido a progressão desses casos nos últimos anos? Tiveram menos ocorrências ou mais?
Quais os estados que mais possuem ocorrências registradas?
Qual tipo de aeronave possui mais problemas? Aviões, jatos, planadores?
Quais as fabricantes com maior número de defeitos registrados?
Será que durante o pouso é mais comum ter problemas do que durante a decolagem? Ou durante a viagem em si é mais frequente surgir defeitos?
Viagens comerciais regulares tendem a ter mais problemas do que voos fretados?
Quantos incidentes com fatalidades (morte de passageiros e tripulação) temos registro nos últimos 10 anos?
Requisitos
Python 3.5
Pandas
Matplotlib
Random
