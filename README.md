# Airline Passenger Satisfaction

(EN)

This assignment was a part of the 2024.1 Data Mining coursework at the Federal University of ABC (UFABC). Special thanks to professor Debora Medeiros :)

## Assignment
1. Obtain a dataset relevant to an area of interest.
2. Implement the necessary preprocessing steps.
3. Evaluate and compare the performance of a minimum of two classifiers, including at least one individual classifier and one ensemble method.
4. Conduct experiments with parameter variations, testing at least two values for each parameter.
5. Document and present the findings from the evaluation process.

The selected dataset is the [Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction) dataset, available on Kaggle. The training and test datasets are provided separately. The dataset consists of 25 columns, including:

- Essential passenger details like age, gender, and loyalty status.
- Trip-related information such as travel type, class, flight distance, and arrival/departure delay times.
- Rating columns spanning from 1 to 5, covering different aspects of the journey.
- The target variable indicating passenger satisfaction, categorized into "neutral or dissatisfied" or "satisfied" classes. <br>

<br>


**Metadata retrieved from the dataset description:**

Gender: Gender of the passengers (Female, Male)

Customer Type: The customer type (Loyal customer, disloyal customer)

Age: The actual age of the passengers

Type of Travel: Purpose of the flight of the passengers (Personal Travel, Business Travel)

Class: Travel class in the plane of the passengers (Business, Eco, Eco Plus)

Flight distance: The flight distance of this journey

Inflight wifi service: Satisfaction level of the inflight wifi service (0:Not Applicable;1-5)

Departure/Arrival time convenient: Satisfaction level of Departure/Arrival time convenient

Ease of Online booking: Satisfaction level of online booking

Gate location: Satisfaction level of Gate location

Food and drink: Satisfaction level of Food and drink

Online boarding: Satisfaction level of online boarding

Seat comfort: Satisfaction level of Seat comfort

Inflight entertainment: Satisfaction level of inflight entertainment

On-board service: Satisfaction level of On-board service

Leg room service: Satisfaction level of Leg room service

Baggage handling: Satisfaction level of baggage handling

Check-in service: Satisfaction level of Check-in service

Inflight service: Satisfaction level of inflight service

Cleanliness: Satisfaction level of Cleanliness

Departure Delay in Minutes: Minutes delayed when departure

Arrival Delay in Minutes: Minutes delayed when Arrival

Satisfaction: Airline satisfaction level(Satisfaction, neutral or dissatisfaction) <br>

<br>

Therefore, this task is a binary classification problem focusing on passenger satisfaction (satisfied/neutral or dissatisfied) as the target variable. It entails testing two individual classification models (Logistic Regression and kNN) and two ensemble methods (XGBoost and Random Forest), all fine-tuned after parameter adjustment. Subsequently, the performance of these diverse models will be evaluated and compared.

<br>


(PT)

Este projeto foi desenvolvido durante a disciplina de Mineração de Dados na Universidade Federal do ABC (UFABC), no primeiro quadrimestre de 2024. Agradecimento especial à professora Debora Medeiros :)

## Atividade
1.   Baixar uma base de dados referente a um assunto de interesse seu.
2.   Configurar o pré-processamento adequado
3.   Comparar o desempenho de no mínimo 2 classificadores (pelo menos 1 único e 1 ensemble)
4.   Investigar variações de parâmetros (pelo menos 2 valores de cada um)
5.   Reportar os resultados

O dataset escolhido é o [Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction), disponível no Kaggle. Os datasets de treino e teste são disponibilizados separadamente. O dataset é composto de 25 colunas, entre elas:
- Informações básicas sobre os passageiros (idade, gênero e se o passageiro é um cliente "fiel" ou não);
- Algumas colunas com informações sobre a viagem (como tipo de viagem, classe, distância do voo e tempo de atraso na chegada e na partida);
- Colunas com avaliações de 1 a 5 para diversos aspectos da viagem;
- Uma variável target indicando a satisfação do passageiro com a viagem, tomando dois valores possíveis: "neutral or dissatisfied" ou "satisfied". <br>

<br>


**Metadados retirados da documentação:**

Gender: Gênero dos passageiros (Feminino, Masculino)

Customer Type: O tipo de cliente (Cliente fiel ou não)

Age: A idade real dos passageiros

Type of Travel: Propósito da viagem (Viagem pessoal, Viagem a negócios)

Class: Classe de viagem (Executiva, Econômica, Econômica Plus)

Flight distance: A distância do voo na viagem

Inflight wifi service: Nível de satisfação com o serviço de wifi a bordo (0: Não Aplicável; 1-5)

Departure/Arrival time convenient: Nível de satisfação com a conveniência do horário de partida/chegada

Ease of Online booking: Nível de satisfação com a facilidade de reserva online

Gate location: Nível de satisfação com a localização do portão de embarque

Food and drink: Nível de satisfação com a comida e bebida

Online boarding: Nível de satisfação com o embarque online

Seat comfort: Nível de satisfação com o conforto do assento

Inflight entertainment: Nível de satisfação com o entretenimento a bordo

On-board service: Nível de satisfação com o serviço de bordo

Leg room service: Nível de satisfação com o espaço para as pernas

Baggage handling: Nível de satisfação com o manuseio de bagagens

Check-in service: Nível de satisfação com o serviço de check-in

Inflight service: Nível de satisfação com o serviço de bordo

Cleanliness: Nível de satisfação com a limpeza

Departure Delay in Minutes: Minutos de atraso na partida

Arrival Delay in Minutes: Minutos de atraso na chegada

Satisfaction: Nível de satisfação com a companhia aérea (Satisfeito, neutro ou insatisfeito) <br>

<br>

Logo, trata-se de um problema de classificação binária, cuja variável target será a satisfação do passageiro (satisfied/neutral or dissatisfied). Nesta atividade, serão testados dois modelos únicos de classificação (Regressão Logística e kNN) e dois métodos ensemble (XGBoost e Random Forest) - todos treinados após o ajuste de parâmetros. Ao final, serão comparados os desempenhos dos diferentes modelos.
