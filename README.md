# Desafio do Bootcamp Dio - Simulador de Fundos Imobiliários

## 📖 Sobre o Desafio

O objetivo do desafio é **praticar, aprender fazendo e construir no Excel** uma ferramenta que simula investimentos em fundos imobiliários. Você deve criar uma planilha que, a partir de algumas perguntas de negócio, calcula:

1. **Quanto investir por mês**;
2. **Por quantos anos**;
3. **Qual a taxa de rendimento mensal**;
4. **Quanto de patrimônio vai acumular**;
5. **Quanto vai receber de dividendos por mês**.

A planilha também projeta o patrimônio em cenários de **2 a 30 anos** e divide o aporte entre **seis tipos de fundo imobiliário**, conforme o perfil de investidor escolhido.

---

## 🔧 O Que Criar

- **Interface** com aparência de aplicativo (banner, linhas de grade escondidas, células de cálculo em cinza que não podem ser editadas);
- **Cálculo do patrimônio** usando a função `VF` (Valor Futuro) e, a partir dele, o cálculo dos dividendos mensais;
- **Cenários de projeção** (2, 5, 10, 20 e 30 anos) usando referências absolutas para que as fórmulas não se percam ao arrastar;
- **Configurações**: salário, taxa de rendimento da carteira e sugestão de aporte de 30% do salário. Utilizar intervalos nomeados como `aporte` e `taxa_mensal`;
- **Divisão por perfil**: lista de perfis com validação de dados, tabela de apoio que relaciona perfil, tipo de fundo e percentual, e busca desses percentuais com `PROCV` usando chave composta.

> **Importante:** os percentuais de cada perfil são apenas exemplos. Você pode usar os seus, desde que a soma de cada perfil seja **100 %**.

---

## 📐 Como Fazer

1. **Monte a tela** – adicione um banner com o nome da ferramenta, esconda a grade e pinte de cinza as células de cálculo.
2. **Calcule o patrimônio** – utilize a função `VF` para obter o valor acumulado e, a partir dele, calcule os dividendos mensais.
3. **Projete os cenários** – copie a fórmula usando referências absolutas para os anos de 2, 5, 10, 20 e 30.
4. **Crie as configurações** – defina salário, rendimento e aporte (30 % do salário). Substitua os endereços de célula por intervalos nomeados (`aporte`, `taxa_mensal`).
5. **Divida por perfil** – crie a lista de perfis com validação de dados. Em uma aba de apoio, monte a tabela de perfil × tipo × percentual e recupere cada percentual com `PROCV` e uma chave composta.

### 📎 Referência do Expert

Caso queira conferir o resultado esperado, a planilha resolvida do Expert está disponível em:

[planilha resolvida do Expert](https://hermes.dio.me/files/assets/a04b81b1-8e35-4e72-aeb9-98aed8ed4403.xlsx)

---

## 🚀 Ideias para Evoluir

- Gráfico de pizza que mostre a divisão do aporte e se atualize ao mudar o perfil;
- Segunda simulação usando a sugestão de 30 % do salário em vez do aporte informado;
- Novas projeções (ex.: 15 e 25 anos) com tabelas de apoio e intervalos nomeados;
- Ocultar barra de fórmulas, títulos e abas na versão final;
- Criar outras ferramentas semelhantes (ex.: planejamento de férias).

---

## 📦 O Que Entregar

1. **Repositório público no GitHub** com a planilha (`.xlsx`).
2. **README.md** explicando:
   - As perguntas que a ferramenta responde e onde cada resposta aparece;
   - Como as funções `VF` e `PROCV` são usadas nos cálculos;
   - Os intervalos nomeados criados;
   - Os percentuais de cada perfil e sua origem;
   - O que foi alterado em relação à ferramenta do Expert.
3. **Prints da planilha preenchida** (pelo menos dois perfis diferentes) para demonstrar que funciona.

Antes de submeter, verifique:
- A planilha abre sem erro de fórmula;
- Trocar o perfil altera a divisão do aporte e a soma dos percentuais permanece 100 %;
- Os valores de salário e demais dados são apenas de exemplo;
- O link enviado é o do **repositório**, não da planilha;
- O repositório está em sua conta, público, com nome legível, em minúsculas e sem acento.

---

## 🛠️ Tecnologias

- **Microsoft Excel** (ou Google Sheets, se preferir);
- Funções principais: `VF`, `PROCV`, referências absolutas (`$A$1`), intervalos nomeados;
- Validação de dados para a seleção de perfis.

---

## 📂 Estrutura do Repositório

```
.
├─ planilha-fundos-imobiliarios.xlsx   # Arquivo da planilha
└─ README.md                           # Este documento
```

---

## 🤝 Contribuindo

Sinta-se à vontade para **forkar** o repositório, melhorar a planilha ou adicionar novos recursos. Abra um *pull request* descrevendo a mudança.

---

## 📄 Licença

Este projeto está licenciado sob a licença MIT – sinta‑se livre para usar, adaptar e distribuir.

---

**Bons estudos e bom projeto!** 🚀