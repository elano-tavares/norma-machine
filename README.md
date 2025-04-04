# 🧠 norma-machine

**Norma (Number Theoretic Register Machine)** é uma máquina universal definida por Bird (Bird, 1976).  
A memória é composta por registros infinitos, e os conjuntos de entradas e saídas são números inteiros **não nulos**.

## ⚙️ Operações da Norma

As operações e testes definidos pela Norma são naturais:

- ➕ **Adicionar 1** a um registro
- ➖ **Subtrair 1** de um registro (com exceção para zero)
- ❓ **Testar se um registro é zero**

> Importante:  
> Ao tentar subtrair 1 de um registro cujo valor já é **zero**, o conteúdo permanece **zero** (a subtração não afeta o registro).

## 📚 Referência

Bird, R. (1976). *Lectures on Constructive Functional Programming*.
