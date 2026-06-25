# Técnicas de Programação

Repositório com atividades práticas da disciplina **Técnicas de Programação**, desenvolvidas em Python com Jupyter Notebooks. O conteúdo cobre desde lógica e algoritmos básicos até os pilares da Programação Orientada a Objetos (POO).

## Conteúdo

| Notebook | Tema | Descrição |
|---|---|---|
| `POO_aula0.ipynb` | Lógica e Algoritmos | Exercícios introdutórios com cálculos financeiros (parcelamento, estoque, comissão, salário líquido com IR e INSS, pontuação de jogos) |
| `aula1_Classes&Objetos.ipynb` | Classes e Objetos | Criação de classes, construtores `__init__`, atributos de instância e de classe, métodos de instância |
| `Encapsulamento.ipynb` | Encapsulamento | Atributos públicos, protegidos (`_`) e privados (`__`); métodos acessores (getters/setters); exemplos com Produto, Carro, ContaBancaria e Aluno |
| `herança.ipynb` | Herança | Herança simples e uso de `super()`; sobrescrita de métodos; exemplos com Animal/Cachorro/Gato, Funcionario/Gerente, Veiculo/Carro/Moto e Forma/Quadrado/Circulo |
| `poliforfismo.ipynb` | Polimorfismo | Polimorfismo via sobrescrita de métodos; classes abstratas com `ABC` e `@abstractmethod`; exemplos com veículos, funcionários CLT/PJ, sistema de mensagens (Email, SMS, WhatsApp) e animais |
| `Exceção.ipynb` | Tratamento de Exceções | `try/except/else/finally`; exceções built-in (`ZeroDivisionError`, `TypeError`, `ValueError`); `raise` para exceções personalizadas; validação de CPF e leitura de arquivos |
| `Avaliação.ipynb` | Avaliação | Projeto de uma **Agenda de Contatos** integrando herança e polimorfismo — classe `Contato` com atributos privados e método `exibir()` |

## Tópicos Abordados

**Lógica e Algoritmos**
- Operações aritméticas e regras de negócio (juros, comissão, INSS, IR)
- Controle de estoque e cálculo de pontuação

**POO — Classes e Objetos**
- Definição de classes e instâncias
- Construtor `__init__` e atributos de instância
- Atributos de classe vs. atributos de instância
- Métodos de instância

**Encapsulamento**
- Visibilidade: público, protegido (`_`) e privado (`__`)
- Getters e setters
- Proteção de dados sensíveis (senha, saldo, preço)

**Herança**
- Herança simples com `super()`
- Sobrescrita (`override`) de métodos
- Hierarquias de classes reais (Veículo → Carro/Moto, Animal → Cachorro/Gato)

**Polimorfismo**
- Mesmo método, comportamentos diferentes por classe
- Classes abstratas (`ABC`, `@abstractmethod`)
- Polimorfismo em listas de objetos

**Tratamento de Exceções**
- `try / except / else / finally`
- Captura de erros específicos
- Lançamento de exceções com `raise`
- Validações de entrada do usuário

## Pré-requisitos

- Python 3.8+
- Jupyter Notebook ou JupyterLab

## Como Executar

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/Tecnicas-de-Programacao.git
cd Tecnicas-de-Programacao

# Instale o Jupyter (se necessário)
pip install notebook

# Abra o Jupyter
jupyter notebook
```

Navegue até o notebook desejado e execute as células sequencialmente.

> Alguns exercícios utilizam `input()` — nesses casos, insira os valores diretamente na célula quando solicitado.
