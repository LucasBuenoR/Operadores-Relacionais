# **Revisão de Banco de Dados**
<!--# **Operadores Relacionais**-->
## **Operadores utilizados em Álgebra Relacional**
* U = União
* ∩ = Intersecção
* － = Diferença
* X = Produto Cartesiano
* σ = Seleção *= 'WHERE' em SQL*
* |X| = Junção
* π = Projeção *= 'SELECT' em SQL*
* ρ = Renomeação

## **Normalização de Banco de Dados**
#### *Normalização e Anomalias - Conceitos*
* https://www.youtube.com/watch?v=NpG1Xt8LB_c
#### *Normalização - Primeira Forma Normal 1FN*
* https://www.youtube.com/watch?v=eRaAMNjCFYw
#### *Normalização - Segunda Forma Normal 2FN*
* https://www.youtube.com/watch?v=6ER9lWOk-cY
#### *Normalização - Terceira Forma Normal 3FN*
* https://www.youtube.com/watch?v=usA8QKvEHWw
#### *Normalização - Forma Normal de Boyce-Codd*
* https://www.youtube.com/watch?v=o6mSiTO-vak

## **Transação de Banco de Dados**
* Unidade lógica de trabalho que deve ser concluída ou abortada inteiramente.
* Uma transação bem sucedida altera o BD de um estado consistente para outro.
* Um BD em estado consistente é aquele em que são
  satisfeitas as restrições de integridade de todos os
  dados.
* A maioria das transações reais é formada por duas ou
  mais solicitações.
  * A solicitação de BD é o equivalente a um único comando
    de SQL em um aplicativo ou transação.
* Nem todas as transações atualizam o BD.
* O código de SQL representa uma transação , pois acessa
  o BD.
* Transações inadequadas ou incompletas podem ter
  efeito devastador sobre a integridade do BD.
  * Alguns SGBD s fornecem meios pelos quais os usuários
    podem definir restrições aplicáveis.
  * Outras regras são aplicadas automaticamente pelo SGBD.
### **Propriedades da Transação**
#### *Uma transação possui 4 propriedades fundamentais (ACID)*
* **Atômica:** Significa que as instruções SQL contidas em uma
  transação constituem uma única unidade de trabalho
  (tudo ou nada).
* **Consistente:** Significa que o BD está em um estado consistente
  quando uma transação inicia e, ao seu término em
  outro estado consistente.
* **Isolada:** Transações separadas não devem interferir uma com a
  outra.
* **Durável:** Uma vez que a transação sofreu COMMIT as alterações
  feitas no BD são preservadas mesmo que a máquina
  em que o SGBD esteja instalado apresente falha
  posteriormente.  

