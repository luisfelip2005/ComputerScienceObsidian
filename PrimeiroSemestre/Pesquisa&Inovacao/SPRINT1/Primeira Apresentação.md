# 1. Apresentação do Grupo/empresa e integrantes 

Bom dia!
Somos o grupo INVTracker e vamos apresentar nossa solução de gestão de estoque.
O grupo é composto por :
- Anderson Lopes
- Beatriz Augusto
- Diego Iacabo
- João Pedro De Sousa
- Larissa Quintino
- Leticia Pinheiro
- Luís Felipe Gomes

# 2. Qual segmento/mercado será tratado na apresentação 

O segmento escolhido foi os supermercados atacadista que são a maior fonte de produtos alimentícios, onde 3 a cada 4 lares realizam compras frequentes, mostrando uma fidelidade no serviço aos clientes.
###### IMAGEM DO GRÁFICO
Nesse gráfico pegamos como exemplo o ramo de Atacarejos, onde podemos ver o crescimento em relação a outro setores.
Podemos notar a retenção de clientes, onde o primeiro gráfico mostra os clientes que são compradores frequentes e o segundo gráfico mostra os clientes que compraram uma vez e não compraram mais.
É notável a vantagem dos Atacarejos em relação a outros setores, onde a há uma alta retenção de clientes e poucos clientes compram uma vez e não compram mais.



# 3. Contexto / Desafio / Problema 
**PRECISO ARRUMAR**
Apesar do crescimento dos atacados no Brasil, ainda há desafios a serem contornados, dentre eles a falta de visibilidade e controle de estoque, tal como rupturas de gondola e perdas financeiras devido a falta de gestão de estoque.

- Falta de visibilidade e controle;

- rupturas de gôndola (excesso ou falta de mercadoria, desperdícios) ;

- perdas financeiras significativas.


# 4. Solução Proposta (foco no negócio – ainda não é técnico) 
A nossa solução consiste em um sensor ultrassônico, onde ele irá verificar a taxa de ocupação do estoque.
Com base nessas taxas iremos criar dashboards que irão notificar o cliente e auxilia-lo na tomada de decisão.
A principio pretendemos reduzir as perdas relacionadas a má gestão de estoque por meio de uma solução tecnológica.



# 5. Diagrama de Visão de Negócio – Como funcionará a solução (foco no negócio – ainda não é técnico) 
**FAZER DEPOIS**



# 6. Ferramenta de gestão – como o grupo se organizou para o projeto + Backlog/requisitos na ferramenta 

Para garantir eficiência no processo de criação desse projeto, iremos usar o TRELLO, que é uma ferramenta de gestão, onde as tarefas são divididas em essenciais, importantes e desejáveis, fornecendo uma direção no que tem ser priorizado e assim evitando o desperdício de tempo focando no que não é essencial, isso garante que o processo de criação desse projeto seja eficiente como um todo.




# 7. Protótipo do Site Institucional – explicar em detalhes o porquê de cada elemento da página 




# 8. Simulador Financeiro – explicar a lógica de negócio e explicar o código 




# 9. Mostrar Tabelas / Abrir MySQL executar create table, inserts, selects 





# 10. Demonstração do Arduino – montar Arduino, abrir e explicar código Arduino 
Para uma demonstração prática, temos aqui um arduino com um sensor ultrassonico, explicando de modo breve, um arduino é um microcontrolador, ou seja, ele realiza processamentos lógicos de maneira simplificada e o sensor permite a obtenção dos dados do ambiente, por meio de ondas ultrassonicas.
Indo agora a parte lógica do código.
O código é dividido em blocos.
O primeiro bloco é para chamada da boblioteca e declaração de variáveis.
O segundo bloco são as configurações do arduino.
O terceiro bloco é onde a lógica do código acontece, captamos a distancia com o sensor e exibimos em forma de gráfico.
**GRAFICO**
A Linha azul definimos como um indicador de que a ocupação do estoque está em nível descente.
A Linha laranja é um indicador que o estoque esta esvaziando e precisa ser reposto.

Quanto mais distante dos produtos, menor será a ocupação, então ele estará acima da linha laranja.

Uma observação é que os valores que estão nesse gráfico são valores para demonstração, os valores reais de ocupação seriam maiores, pois o sensor capta até 4 metros.




# 11. Demonstração Linux VM – explicar funcionamento e relevância no projeto 





# 12. Conclusão com visão dos próximos passos (fechamento otimista)
