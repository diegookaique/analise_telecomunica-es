# analise_telecomunicacoes
Análise de Churn em uma Empresa de Telecomunicações

## Análise de Churn em uma Empresa de Telecomunicações
Este repositório contém um script em Python para analisar dados de churn em uma empresa de telecomunicações. Ele realiza análises estatísticas, univariadas e bivariadas, além de identificar outliers e salvar gráficos como imagens para facilitar a visualização.

![download](https://github.com/user-attachments/assets/7399ab82-5021-4fbd-aad7-3047a020ba11)


## Análise Univariada

<img width="562" height="435" alt="download" src="https://github.com/user-attachments/assets/3c3e5599-c7ec-413e-8e22-6b38b073297a" />

Notem como o boxplot tem um comportamento esperado, existe proporcionalidade entre a distribuição dos dados, sem presença de outliers.

<img width="567" height="435" alt="download (1)" src="https://github.com/user-attachments/assets/acbd678b-aaae-4f43-b868-f2c627c1699c" />

Notamos que não temos presença de valores fora da normalidade dos dados.

<img width="580" height="435" alt="download (2)" src="https://github.com/user-attachments/assets/f4c0b123-dd14-42b3-9385-bb4c47af1af6" />

Notem como o boxplot tem um comportamento indiferente, existe proporcionalidade entre a distribuição dos dados, e existe um valor acima da distribuição dos dados, que é a presença de Outliers.

<img width="571" height="435" alt="download (3)" src="https://github.com/user-attachments/assets/6001a609-94c9-46e7-9b80-87d5b41734dc" />

Notem como o boxplot tem um comportamento esperado, existe proporcionalidade entre a distribuição dos dados, sem presença de outliers.

<img width="580" height="573" alt="download (4)" src="https://github.com/user-attachments/assets/063757ab-ae28-47ef-b936-a7b2aeada9fc" />

Pode se analisar que 50% dos clientes não tem um serviço de segurança e a outra metade está distribuida com clientes que nem possuem serviço de internet.

Bom insight. Pode gerar estratégias de propaganda, para oferecer serviço de internet e segurança ao cliente.

<img width="581" height="463" alt="download (5)" src="https://github.com/user-attachments/assets/38175737-6983-4ca0-9dff-d5893be8766b" />

Na variável 'Dependents' notamos um desbalanceamento entre as duas classes. Onde 70% dos dados não possuem dependentes e isso pode tendenciar mais em direção a essa classe em relação ao 'churn'.

Bom insght para futuras estratégias.

<img width="580" height="450" alt="download (6)" src="https://github.com/user-attachments/assets/c3856801-9fba-4d61-a81d-9727df216250" />

Identificamos que essa Variavel principal 'churn' tem um desbalanceamento. Onde a grande maioria são clientes que não deram 'churn'.

<img width="580" height="554" alt="download (7)" src="https://github.com/user-attachments/assets/895ac95c-36da-4dcc-bf85-49c42bc54e04" />

Pode se avaliar que 50% dos clientes realizam pagamento mês a mês. Otimo Insght para futuras estratégias promocionais em planos anuais.

<img width="580" height="573" alt="download (8)" src="https://github.com/user-attachments/assets/45e36c49-e322-4a24-9b6e-b3a3533a7b92" />

Pode se avaliar que 50% dos clientes não possuem um suporte tecnico. Otimo Insght para futuras estratégias.

## Colunas que contém Outliers

<img width="1678" height="585" alt="Captura de tela 2025-07-18 190857" src="https://github.com/user-attachments/assets/233350e8-8c79-454a-a858-8d20a02ac82c" />


<img width="1718" height="588" alt="Captura de tela 2025-07-18 191014" src="https://github.com/user-attachments/assets/c7ef9210-d404-4df4-bd9e-ae8d8008370e" />


<img width="1682" height="614" alt="Captura de tela 2025-07-18 191058" src="https://github.com/user-attachments/assets/9e211e3a-c084-4beb-a2d6-16692f3b8699" />

## Análise Bivariada

<img width="1754" height="617" alt="Captura de tela 2025-07-18 192724" src="https://github.com/user-attachments/assets/9f8566ba-5a09-4100-8736-4471e5de7f3f" />

<img width="1757" height="616" alt="Captura de tela 2025-07-18 192743" src="https://github.com/user-attachments/assets/8a05481e-9b5f-4b90-9abc-395513d83a70" />

<img width="1762" height="606" alt="Captura de tela 2025-07-18 192809" src="https://github.com/user-attachments/assets/42405f4c-031e-4746-803d-638d94541254" />

<img width="1765" height="612" alt="Captura de tela 2025-07-18 192828" src="https://github.com/user-attachments/assets/afd5012a-6769-4ef2-a9c4-f198dcd7a843" />

<img width="1760" height="627" alt="Captura de tela 2025-07-18 192859" src="https://github.com/user-attachments/assets/95630122-56fe-4f12-a7e5-6a37d9291454" />

## Variáveis que são as mais importantes para esse projetos relacionadas a variável Churn

* Tipo_Contrato: Com essa variavel foi possivel analisar que Clientes que possuem o plano mensal são os mais propicios a dar churn, com média de 90%.
* casado: Foi identificado que clientes casados são menos propicios a dar churn. Com média de 63% para não casados e 36% para os casados.
* Idosos: Na analise a maioria dos Idosos são não Churn, 75% dos clientes não idosos dão Churn.
* genero: por ultimo e não menos importante que as outras variaveis, foi possivel analisar que Os homens tem uma proporção um pouco maior com 51% de não churn e as mulheres com 47% de não churn.

# Estrutura do Repositório 📂
data/: Arquivos CSV usados ​​na análise.

imagens/: Gráfico gerado pelo código.

notebooks/: Scripts que você pode executar para reproduzir os resultados.

# Tecnologias Utilizadas 🔧

Python

Pandas

Seaborn 

Matplotlib

