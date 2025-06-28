# Laboratório 01 - Tarefa de Troca de Cores

Esta é uma das tarefas do laboratório de Visão Computacional, focada na manipulação de cores em imagens.

## Arquivos
- `codigos/trocar_cor.py`: Script principal para troca de cores
- `imagens/gamora_nebula.jpg`: Imagem original
- `imagens/modificada_gamora_nebula.jpg`: Resultado após processamento

## Como Executar

1. Instale as dependências:
```bash
pip install opencv-python numpy

## Execute o script:

OBS: Navegue até a pasta codigos : cd ~/Downloads/visão\ computacional/lab01/codigos

``bash
python codigos/trocar_cor.py ../imagens/gamora_nebula.jpg

## Funcionamento do Código

Detecta cores azuis e verdes na imagem
Troca azuis por verdes e vice-versa
Salva o resultado em imagens/modificada_gamora_nebula.jpg

