
# Inteligência Artificial Aplicada à Geofísica

## 1. Descrição do projeto

Projeto desenvolvido no contexto da disciplina de aplicações de
Inteligência Artificial a dados geofísicos do curso de Pós-Graduação em Geofísica da Universidade 
Federal do Pará - UFPA.

O objetivo é investigar a aplicação de métodos estatísticos,
aprendizado não supervisionado, aprendizado supervisionado e
técnicas de Deep Learning na análise e integração de dados
geofísicos.

## 2. Dados utilizados

- Magnetometria
- Gamaespectrometria
- Gravimetria
- Geologia
- Eletrorresistividade (DC)

A área de estudo e a disponibilidade dos dados serão documentadas
conforme a definição do conjunto de dados final.


## 3. Metodologia

1. Inventário e organização dos dados.
2. Análise exploratória dos dados (EDA).
3. Pré-processamento e integração espacial.
4. Análise estatística e correlação.
5. Redução de dimensionalidade (PCA/UMAP).
6. Aprendizado não supervisionado (clustering).
7. Aprendizado supervisionado.
8. Aplicação de Deep Learning.
9. Integração e interpretação geofísica dos resultados.



## 4. Estrutura do repositório

- `data/`: organização dos dados.
- `notebooks/`: análises e experimentos.
- `src/`: funções e módulos Python.
- `results/`: figuras, tabelas e modelos.
- `docs/`: documentação.

## 5. Instalação

Clone o repositório:

```bash
git clone  https://github.com/CarajasIA/Bloco_E_IA.git
cd Bloco_E_Geofisica_IA
```

Crie o ambiente virtual:

```bash
python -m venv .venv
```

Ative o ambiente no Windows:

```powershell
.\.venv\Scripts\Activate.ps1
```


Ative o ambiente no Linux : 


```bash 
source .venv/bin/activate
```

Instale as dependências:

```bash
python -m pip install -r requirements.txt
```

## 6. Execução

Abra o JupyterLab:

```bash
jupyter lab
```

Os experimentos estão organizados na pasta `notebooks/`.

## 7. Reprodutibilidade e dados

Os dados originais não são armazenados neste repositório
quando houver restrições de tamanho ou licença.

As fontes, licenças, referências e instruções de obtenção dos
dados serão documentadas em `docs/`.

## 8. Autores

- Marcelo Lucas da Silva Almeida 
- Gabriel Santos Pinto
- Saulo Vinicius Monteiro Santos 