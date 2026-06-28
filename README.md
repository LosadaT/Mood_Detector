# Mood Detector

Aplicativo iOS desenvolvido em equipe como primeiro contato com treinamento de modelos de Machine Learning. O app detecta o sentimento descrito pelo usuário em texto e exibe um conselho — propositalmente entregue em Braille, mantendo fiel à proposta que recebemos de ser um aplicativo sem utilidade prática.

## Sobre o Projeto

O modelo de classificação foi treinado com o [Emotions Dataset](https://www.kaggle.com/datasets/nelgiriyewithana/emotions), composto por posts do Twitter rotulados com seis emoções: tristeza, amor, medo, surpresa, raiva e felicidade.

## Funcionamento

1. O usuário descreve o que está sentindo na tela inicial
2. O texto é analisado pelo modelo treinado com CreateML
3. O app identifica a emoção e exibe um conselho na tela seguinte
4. O conselho é apresentado em Braille — sistema de leitura e escrita tátil utilizado por pessoas cegas ou com baixa visão

## Telas

### Tela Inicial
Página inicial onde o usuário descreve a emoção sentida.

<img src="Assets/Menu.PNG" alt="homepage" height="400">

### Conselhos por Emoção

<p float="left">
  <img src="Assets/Tristeza.PNG" alt="Tristeza" height="400">
  <img src="Assets/Amor.PNG" alt="Amor" height="400">
  <img src="Assets/Medo.PNG" alt="Medo" height="400">
  <img src="Assets/Surpresa.PNG" alt="Surpresa" height="400">
  <img src="Assets/Raiva.PNG" alt="Raiva" height="400">
  <img src="Assets/Felicidade.PNG" alt="Felicidade" height="400">
</p>

## Tecnologias

- **Swift**
- **SwiftUI**
- **CreateML** — treinamento do modelo de classificação de texto
- **CoreML** — integração do modelo treinado ao app

## Dataset

[Emotions Dataset for NLP — Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/emotions)

Posts do Twitter classificados em 6 emoções: tristeza, amor, medo, surpresa, raiva e felicidade.

## Como Rodar

1. Clone o repositório:
   ```bash
   git clone <url-do-repositorio>
   ```
2. Abra o `.xcodeproj` no Xcode
3. Selecione um simulador iOS e pressione Run (`Cmd + R`)

> Requisito: Xcode 14+ e iOS 16+
