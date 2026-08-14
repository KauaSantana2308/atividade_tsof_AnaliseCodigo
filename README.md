# Fundamentos do Teste de Software e QA - Estudo de Caso TechSolutions

## Sobre o projeto
Este projeto foi desenvolvido como parte da atividade prática da **Aula 1: Fundamentos do Teste de Software, Tipos e Níveis da Pirâmide de QA**. O trabalho consiste no estudo de caso da empresa TechSolutions, contratada pela Universidade Inovação para criar um aplicativo de gestão de eventos acadêmicos.

O objetivo da atividade foi analisar o módulo de inscrições do aplicativo (escrito em Python), identificar e corrigir um defeito no cálculo do cupom de desconto e realizar a classificação de diferentes requisitos do sistema segundo os tipos e níveis de teste de software.

## Objetivos
- Identificar a importância do teste de software no ciclo de desenvolvimento.
- Diferenciar os conceitos fundamentais de **Erro**, **Defeito (Bug)** e **Falha**.
- Distinguir testes **Funcionais** de testes **Não Funcionais**.
- Compreender a hierarquia da **Pirâmide de Testes** (Unitário, Integração, Sistema e Aceitação).
- Executar teste de mesa e depuração de código em Python para validação e correção de regras de negócio.

## Conteúdos abordados
- **Fundamentos do QA:** Importância dos testes para garantia de qualidade, confiança e prevenção de falhas em produção.
- **Tríade Fundamental do QA:**
  - **Erro (Engano Humano):** Ação humana incorreta durante a especificação ou codificação.
  - **Defeito / Bug:** Código incorreto presente no sistema.
  - **Falha:** Comportamento incorreto observado pelo usuário em tempo de execução.
- **Tipos de Teste:**
  - **Funcional:** Avalia *o que* o sistema faz (regras de negócio e especificações).
  - **Não Funcional:** Avalia *como* o sistema se comporta (desempenho, segurança, usabilidade).
- **Níveis de Teste:** Unitário, Integração, Sistema e Aceitação (UAT).
- **Análise e Correção de Código:** Depuração de funções lógicas e tratamento de cálculos percentuais em Python.

## Estrutura do projeto
```text
.
├── Aula1_aluno.docx    # Documento de orientação e roteiro da atividade
├── inscricao.py        # Código em Python com as funções e correções aplicadas
└── README.md           # Documentação do projeto
```

## Tecnologias utilizadas
- **Python 3:** Linguagem de programação utilizada na implementação e correção das funções de validação e checkout.
- **Markdown:** Formatação utilizada para a documentação do projeto.

## Como executar
1. Certifique-se de ter o **Python 3** instalado em sua máquina.
2. Baixe ou clone os arquivos do repositório.
3. Abra o terminal na pasta do projeto.
4. Execute o arquivo de script Python:

```bash
python inscricao.py
```

# Conclusão e Aprendizados
A realização deste estudo de caso permitiu consolidar na prática os fundamentos essenciais da Garantia de Qualidade (QA) no desenvolvimento de software:

1. **Prevenção vs. Correção:** Ficou evidente que identificar um defeito na fase de desenvolvimento (como o cálculo incorreto do desconto) evita prejuízos financeiros e insatisfação do usuário final em produção.
2. **Clareza na Tríade do QA:** A aplicação dos conceitos de **Erro -> Defeito -> Falha** ajudou a compreender exatamente a origem dos problemas no código e como remediá-los antes da entrega.
3. **Importância dos Testes Unitários:** Testar funções isoladamente garante que pequenos blocos de regra de negócio funcionem perfeitamente antes de integrarem módulos maiores.
4. **Visão Holística da Qualidade:** A diferenciação entre testes funcionais e não funcionais reforçou que um software de qualidade deve ser não apenas **correto em suas regras**, mas também **seguro, rápido e escalável**.



## Autor
 Kauã Fernandes Santana 
