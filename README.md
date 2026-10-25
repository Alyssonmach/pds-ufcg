# Processamento Digital de Sinais — UFCG

Exercícios e implementações desenvolvidos para a disciplina de Processamento Digital de Sinais da Universidade Federal de Campina Grande (UFCG). O material está organizado em notebooks Jupyter, com explicações, código e gráficos.

## Conteúdo

| Notebook | Tópico |
| --- | --- |
| [`notebooks/dft.ipynb`](notebooks/dft.ipynb) | Transformada Discreta de Fourier (DFT), implementação matricial e análise de sinais. |
| [`notebooks/fft.ipynb`](notebooks/fft.ipynb) | Implementação da Transformada Rápida de Fourier (FFT) e exemplos no domínio da frequência. |
| [`notebooks/convolution-overlap-add.ipynb`](notebooks/convolution-overlap-add.ipynb) | Convolução pelo método overlap-add e aplicação de um filtro de média móvel. |

## Requisitos

- Python 3
- Jupyter Notebook
- NumPy
- Matplotlib

Instale as dependências com:

```bash
python -m pip install -r requirements.txt
```

## Como executar

Clone ou baixe este repositório, instale as dependências e inicie o Jupyter:

```bash
jupyter notebook
```

Abra um dos arquivos na pasta `notebooks/` e execute as células na ordem. Os notebooks são independentes entre si.
