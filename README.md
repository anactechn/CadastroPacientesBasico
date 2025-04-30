Descrição
Este projeto é um sistema simples de cadastro de pacientes desenvolvido em Python. Ele permite coletar informações pessoais, de saúde, medicamentos, sinais vitais e outras informações relevantes de pacientes em um formato organizado.

Funcionalidades
Cadastro completo de pacientes com as seguintes seções:

Dados pessoais (nome, documentos, contato, etc.)

Problemas de saúde (principal, secundário, hábitos como tabagismo e etilismo)

Medicações em uso

Informações odontológicas

Sinais vitais (pressão arterial, frequência cardíaca, etc.)

Dados médicos (conduta, médico responsável)

Demandas do paciente

Como Usar
Execute o arquivo CadastroPacientes.ipynb em um ambiente Python (Jupyter Notebook ou similar)

O sistema irá solicitar as informações do paciente em diferentes seções

Após preencher todas as informações, o sistema exibirá uma mensagem de confirmação

Estrutura do Código
O código utiliza uma classe Paciente que organiza as informações em dicionários aninhados:

dados: Informações pessoais e de contato

problemas: Dados sobre saúde e hábitos

medicacoes: Medicamentos em uso

odontologia: Problemas odontológicos

sinais: Sinais vitais

medico: Informações médicas

demandas: Demandas do paciente

Requisitos
Python 3.x

Jupyter Notebook (opcional, para execução do arquivo .ipynb)
