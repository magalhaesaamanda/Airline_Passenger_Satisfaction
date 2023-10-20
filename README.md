# ADA - Projeto Machine Learning I
![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=main)

- Instituição: Ada Tech
- Curso: Santander Coders
- Disciplina: Machine Learning I
- Professores: Gilberto Kaihami
- Alunos: Amanda Magalhaes, Daniel Custodio, Douglas Vieira Rocha, Marcia Freitas, Renan Dias

Este projeto é uma exploração dos datasets: [Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction/data) fornecidos pelo [Kaggle](https://www.kaggle.com/). O foco é realizar uma análise nesses dados e desenvolver um modelo preditivo da satisfação do passageiro de avião.

A especificação completa do projeto pode ser encontrada em: [Projeto Machine Learning](https://github.com/magalhaesaamanda/Airline_Passenger_Satisfaction/blob/main/utils/Projeto_Especificacoes.ipynb).


## Sobre os dados

### Contexto
Este conjunto de dados contém uma pesquisa de satisfação de passageiros de companhias aéreas. Quais fatores estão altamente correlacionados com um passageiro satisfeito (ou insatisfeito)? É possível prever a satisfação do passageiro?

### Base de dados

- Gender (Gênero): Gênero dos passageiros (Feminino, Masculino)
- Customer Type (Tipo de Cliente): O tipo de cliente (Cliente fiel, cliente desleal)
- Age (Idade): A idade real dos passageiros
- Type of Travel (Tipo de Viagem): Finalidade da viagem dos passageiros (Viagem pessoal, Viagem de negócios)
- Class (Classe): Classe de viagem no avião dos passageiros (Executiva, Econômica, Econômica Plus)
- Flight distance (Distância do Voo): A distância do voo desta jornada
- Inflight wifi service (Serviço de Wi-Fi a bordo): Nível de satisfação com o serviço de Wi-Fi a bordo (0: Não Aplicável; 1-5)
- Departure/Arrival time convenient (Conveniência do Horário de Partida/Chegada): Nível de satisfação com a conveniência do horário de partida/chegada
- Ease of Online booking (Facilidade de Reserva Online): Nível de satisfação com a reserva online
- Gate location (Localização do Portão): Nível de satisfação com a localização do portão
- Food and drink (Comida e Bebida): Nível de satisfação com comida e bebida
- Online boarding (Embarque Online): Nível de satisfação com o embarque online
- Seat comfort (Conforto do Assento): Nível de satisfação com o conforto do assento
- Inflight entertainment (Entretenimento a bordo): Nível de satisfação com o entretenimento a bordo
- On-board service (Serviço a bordo): Nível de satisfação com o serviço a bordo
- Leg room service (Serviço de Espaço para as Pernas): Nível de satisfação com o serviço de espaço para as pernas
- Baggage handling (Manuseio de Bagagem): Nível de satisfação com o manuseio de bagagem
- Check-in service (Serviço de Check-in): Nível de satisfação com o serviço de check-in
- Inflight service (Serviço a Bordo): Nível de satisfação com o serviço a bordo
- Cleanliness (Limpeza): Nível de satisfação com a limpeza
- Departure Delay in Minutes (Atraso na Partida em Minutos): Minutos de atraso na partida
- Arrival Delay in Minutes (Atraso na Chegada em Minutos): Minutos de atraso na chegada
- Satisfaction (Satisfação): Nível de satisfação da companhia aérea (Satisfação, neutro ou insatisfação)

## Objetivo

Analisar e modelar a satisfação dos passageiros de companhias aéreas com base em uma variedade de fatores, como gênero, tipo de cliente, idade, tipo de viagem, classe de viagem, distância do voo e satisfação com diferentes aspectos do serviço aéreo. O objetivo é desenvolver um modelo de previsão de satisfação do passageiro, identificando quais fatores estão altamente correlacionados com a satisfação do cliente, a fim de melhorar a qualidade do serviço e a experiência geral do passageiro.
Este objetivo envolveria análises estatísticas, como correlações e modelagem preditiva, para determinar quais variáveis têm maior impacto na satisfação do passageiro e se é possível prever a satisfação com base nessas variáveis. Isso pode ser útil para as companhias aéreas em seus esforços para melhorar a satisfação do cliente e tomar decisões informadas com relação a serviços, treinamento de pessoal e políticas de atendimento ao cliente.

## Ferramentas Usadas 
Este projeto foi concluído usando Python e suas bibliotecas associadas, como NumPy, Pandas, Matplotlib, Seaborn, Ipykernel, Scikit-learn.

## Integrantes
Projeto desenvolvido pelos Devs:

- [Amanda Magalhaes](https://github.com/magalhaesaamanda)
- [Douglas Rocha](https://github.com/dogaVrocha)
- [Marcia Freitas](https://github.com/marciafurtadodf)
- [Renan Dias](https://github.com/renanrdias)

## Instalação
Foi utilizado o [Python](https://www.python.org/) v3.11.

### Conda
No desenvolvimento foi utilizado o gerenciador de pacotes e ambientes [Conda](https://conda.io/). Portanto para prosseguir necessita-se de sua [instalação](https://conda.io/projects/conda/en/latest/user-guide/install/index.html).

- Navegar até a pasta de destino
```sh
cd utils
```

- Instalar dependências
```sh
conda env create -f environment.yml
```

- Ativar
```sh
conda activate ada_env
```

- Desativar
```sh
conda deactivate
```

### Requirements
Pode-se utilizar o arquivo requirements.txt para criar o ambiente virtual.

- Criar ambiente virtual
```sh
python -m venv ada_env
```

- Ativar
```sh
source ./ada_env/bin/activate
```

- Navegar até a pasta de destino
```sh
cd utils
```

- Instalar dependências
```sh
pip install -r requirements.txt
```

- Desativar
```sh
deactivate
```

## Organização do projeto
```sh
Airline_Passenger_Satisfaction
┣ data
 ┃ ┣ heart_attack_prediction_dataset.csv
 ┃ ┣ test.csv
 ┃ ┗ train.csv
 ┣ main
 ┃ ┣ edas
 ┃ ┃ ┗ eda.ipynb
 ┃ ┗ model
 ┃ ┃ ┗ Modelo.ipynb
 ┣ utils
 ┃ ┣ environment.yml
 ┃ ┗ Projeto_Especificacoes.ipynb
 ┣ .gitignore
 ┣ LICENSE
 ┗ README.md
```

## Contribuições
As contribuições são sempre bem-vindas. Se você é um desenvolvedor, cientista de dados ou analista, pode contribuir para o projeto de várias maneiras, tais como:

- Criar novos notebooks;
- Desenvolver novas análises e novos modelos;
- Encontrar e corrigir erros;
- Ajudar a documentar o código;
- Refatorar o código existente.

