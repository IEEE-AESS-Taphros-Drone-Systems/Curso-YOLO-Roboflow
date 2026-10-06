# 🚁 Curso de Visão Computacional: YOLO & Roboflow

<div align="center">
  <p><b>Aprenda a construir do zero um pipeline de Inteligência Artificial para Detecção de Objetos.</b></p>
</div>

<div align="center">
  <!-- Substitua o link abaixo pela URL real do Google Drive contendo os slides -->
  <a href="https://drive.google.com/drive/folders/1O8Yzy1IT-IMTMWom4zzSC8WzSrSodqOA?usp=sharing" target="_blank">
    <img src="https://img.shields.io/badge/Acessar_Slides_do_Curso-4285F4?style=for-the-badge&logo=googledrive&logoColor=white" alt="Google Drive">
  </a>
</div>
<br>

## 🛠️ Tecnologias Utilizadas

<div align="center">
  <!-- Logos/Badges das tecnologias -->
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Roboflow-6706CE?style=for-the-badge&logo=roboflow&logoColor=white" alt="Roboflow">
  <img src="https://img.shields.io/badge/YOLOv8-FF1493?style=for-the-badge&logo=yolo&logoColor=white" alt="YOLO">
  <img src="https://img.shields.io/badge/Ultralytics-000000?style=for-the-badge&logo=ultralytics&logoColor=white" alt="Ultralytics">
  <img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Google Colab">
</div>
<br>

## 📖 O que este curso ensina?

Este curso oferece uma formação prática e direta sobre como preparar dados e treinar modelos de visão computacional. O conteúdo guia o aluno desde a coleta das imagens até a avaliação da inteligência artificial, abordando:

*   **Preparação de Dados (Roboflow):** Introdução aos conceitos de dataset, upload de arquivos, anotação manual de imagens (criação de *bounding boxes* para classes como "Triangulo_5") e exportação no formato correto.
*   **Tratamento e Robustez (Machine Learning):** Entendimento prático sobre como evitar o *Overfitting* e a importância do *Data Augmentation* (adição de desfoque, ruído, etc.) para criar novas imagens a partir das existentes e melhorar o aprendizado do modelo.
*   **Treinamento de Redes Neurais (YOLO):** Configuração do ambiente em nuvem via Google Colab, instalação do pacote *Ultralytics* via CLI/Python e execução do treinamento utilizando aceleração por GPU.
*   **Avaliação Analítica:** Interpretação das métricas de desempenho da IA durante as épocas de treinamento, compreendendo a fundo o que significam *Box Loss*, *Precision* (exatidão), *Recall* (revocação) e *mAP50* (Mean Average Precision).

---

## 🎓 Contribuição para a Comunidade Acadêmica

Este material é uma ponte essencial entre a teoria acadêmica de Inteligência Artificial e a aplicação prática em engenharia aeroespacial e robótica. Para a comunidade estudantil e membros do laboratório, este curso contribui das seguintes formas:

1.  **Capacitação Técnica de Excelência:** Fornece as ferramentas necessárias para que estudantes apliquem visão computacional de ponta em projetos reais de drones (VANTs), possibilitando o desenvolvimento de sistemas de percepção autônoma e reconhecimento de alvos.
2.  **Rigor e Metodologia Científica:** Ensina as boas práticas fundamentais de pesquisa em IA, como a divisão correta de dados experimentais (70-80% para treino, 10-15% para validação e 10-15% para teste) para garantir que as validações dos projetos sejam cientificamente precisas.
3.  **Fomento à Autonomia e Inovação:** Desmistifica o "caixa-preta" das redes neurais. Os estudantes deixam de ser apenas operadores de software e passam a entender os cálculos de perda (*loss*) e precisão, ganhando autonomia para otimizar seus próprios modelos de pesquisa.

---

## 📸 Destaques Visuais do Curso

> *Nota de uso: Adicione os prints correspondentes na pasta do repositório e atualize o nome dos arquivos no campo `src=" "` abaixo.*

### 1. Rotulação e Preparação do Dataset
<div align="center">
  <img src="imagem_anotacao_roboflow.png" alt="Processo de anotação no Roboflow" width="800">
  <br>
  <i>Anotação visual dos objetos e definição de classes na interface do Roboflow. Esta é a matéria-prima do projeto, indicando ao modelo a localização exata e a classificação do que deve ser detectado.</i>
</div>
<br>

### 2. Estratégias de Data Augmentation
<div align="center">
  <img src="imagem_data_augmentation.png" alt="Configuração de Data Augmentation" width="800">
  <br>
  <i>Aplicação de pré-processamento e Data Augmentation para gerar variações no dataset, ensinando o modelo a lidar com diferentes cenários e mitigando o risco de overfitting.</i>
</div>
<br>

### 3. Treinamento e Análise de Métricas no Google Colab
<div align="center">
  <img src="imagem_metricas_colab.png" alt="Métricas de Treinamento do YOLO" width="800">
  <br>
  <i>Monitoramento do treinamento do modelo YOLO no Google Colab, com foco na análise de época (Epoch), uso de memória da GPU e as métricas vitais de desempenho, como Precision, Recall e Mean Average Precision (mAP).</i>
</div>

---

<div align="center">
  <p>© 2026 - IEEE AESS UFABC Student Branch</p>
</div>
