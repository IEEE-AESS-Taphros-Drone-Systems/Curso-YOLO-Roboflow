# 🚁 Curso de Visão Computacional: YOLO & Roboflow

<div align="center">
  <p><b>Aprenda a construir do zero um pipeline de Inteligência Artificial para Detecção de Objetos.</b></p>
</div>

## 📖 O que este curso ensina?

Este curso oferece uma formação prática e direta sobre como preparar dados e treinar modelos de visão computacional. O conteúdo guia o aluno desde a coleta das imagens até a avaliação da inteligência artificial, abordando[cite: 2]:

*   **Preparação de Dados (Roboflow):** Introdução aos conceitos de dataset, upload de arquivos, anotação manual de imagens (criação de *bounding boxes* para classes como "Triangulo_5") e exportação no formato correto[cite: 2, 54, 91].
*   **Tratamento e Robustez (Machine Learning):** Entendimento prático sobre como evitar o *Overfitting* e a importância do *Data Augmentation* (adição de desfoque, ruído, etc.) para criar novas imagens a partir das existentes e melhorar o aprendizado do modelo[cite: 74, 82].
*   **Treinamento de Redes Neurais (YOLO):** Configuração do ambiente em nuvem via Google Colab, instalação do *Ultralytics* e execução do treinamento utilizando aceleração por GPU[cite: 102, 121].
*   **Avaliação Analítica:** Interpretação das métricas de desempenho da IA durante as épocas de treinamento, compreendendo a fundo o que significam *Box Loss*, *Precision* (exatidão), *Recall* (revocação) e *mAP50* (Mean Average Precision)[cite: 134].

---

## 🎓 Contribuição para a Comunidade Acadêmica

Este material é uma ponte essencial entre a teoria acadêmica de Inteligência Artificial e a aplicação prática em engenharia aeroespacial e robótica. Para a comunidade estudantil e membros do laboratório, este curso contribui das seguintes formas:

1.  **Capacitação Técnica de Excelência:** Fornece as ferramentas necessárias para que estudantes apliquem visão computacional de ponta em projetos reais de drones (VANTs), possibilitando o desenvolvimento de sistemas de percepção autônoma e reconhecimento de alvos.
2.  **Rigor e Metodologia Científica:** Ensina as boas práticas fundamentais de pesquisa em IA, como a divisão correta de dados experimentais (70-80% para treino, 10-15% para validação e 10-15% para teste) para garantir que as validações dos projetos sejam cientificamente precisas[cite: 66].
3.  **Fomento à Autonomia e Inovação:** Desmistifica o "caixa-preta" das redes neurais. Os estudantes deixam de ser apenas operadores de software e passam a entender os cálculos de perda (*loss*) e precisão, ganhando autonomia para otimizar seus próprios modelos de pesquisa[cite: 134].

---

## 📸 Destaques Visuais do Curso

> *Nota de uso: Adicione os prints correspondentes na pasta do repositório e atualize o nome dos arquivos no campo `src=" "` abaixo.*

### 1. Rotulação e Preparação do Dataset
<div align="center">
  <img src="imagem_anotacao_roboflow.png" alt="Processo de anotação no Roboflow" width="800">
  <br>
  <i>Anotação visual dos objetos e definição de classes na interface do Roboflow. Esta é a matéria-prima do projeto, indicando ao modelo a localização exata e a classificação do que deve ser detectado[cite: 3].</i>
</div>
<br>

### 2. Estratégias de Data Augmentation
<div align="center">
  <img src="imagem_data_augmentation.png" alt="Configuração de Data Augmentation" width="800">
  <br>
  <i>Aplicação de pré-processamento e Data Augmentation para gerar variações no dataset, ensinando o modelo a lidar com diferentes cenários e mitigando o risco de overfitting[cite: 74, 82].</i>
</div>
<br>

### 3. Treinamento e Análise de Métricas no Google Colab
<div align="center">
  <img src="imagem_metricas_colab.png" alt="Métricas de Treinamento do YOLO" width="800">
  <br>
  <i>Monitoramento do treinamento do modelo YOLO no Google Colab, com foco na análise de época (Epoch), uso de memória da GPU e as métricas vitais de desempenho, como Precision, Recall e Mean Average Precision (mAP)[cite: 134].</i>
</div>

---

<div align="center">
  <p>© 2026 - IEEE AESS UFABC Student Branch</p>
</div>
