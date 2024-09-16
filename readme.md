# Predicción de Autismo en Adultos con Aprendizaje Automático 

Este proyecto explora el uso de técnicas de aprendizaje automático para predecir el riesgo de Trastorno del Espectro Autista (TEA) en adultos, utilizando datos demográficos y respuestas al cuestionario AQ-10.

## Contenido

* **`autism_adult_etl.csv`:** Conjunto de datos preprocesado y listo para el modelado.
* **`autism_multiclass_model.pkl`:** Modelo de clasificación multiclase entrenado (el mejor modelo hasta ahora).
* **`code_mapping.json`:** Mapeo de códigos numéricos a nombres de países.
* **`requirements.txt`:** Lista de dependencias del proyecto.
* **`notebook.ipynb`:** Cuaderno de Jupyter con el análisis exploratorio de datos (EDA), la construcción y evaluación de modelos.

## Instalación de Dependencias

1. Clona este repositorio:

   ```bash
   git clone [https://github.com/Kamaranis/ASD-Multiclass-Predictor-Model.git](https://github.com/Kamaranis/ASD-Multiclass-Predictor-Model)
   ```

2. Crea un entorno virtual (recomendado):
    - Opción A:(con virtualEnv):
    ```bash
    python -m venv venv  # Crea un entorno virtual llamado 'venv'
    source venv/bin/activate  # Activa el entorno (Linux/macOS)
    venv\Scripts\activate.bat  # Activa el entorno (Windows)
    ```
    -OPCIÓN B: (Anaconda)
    ```bash
    conda create -n my_virtual_env
    conda activate my_virtual_env
3. Instala las dependencias:
    ```bash
    pip install -r requirements.txt
    ```

## Uso
1. Abre el cuaderno de Jupyter 'Predicción del trastorno del espectro autista (TEA) en adultos usando ML.ipynb'.
2. Ejecuta las celdas para cargar los datos, realizar el análisis exploratorio, entrenar los modelos y evaluar su rendimiento.
3. Utiliza el modelo entrenado (autism_multiclass_model.pkl) para hacer predicciones en nuevos datos. Puedes recrear el código o utilizar el modelo ya entrenado.

## Hallazgos Principales
- El test AQ-10 es un predictor clave:   
La puntuación total en el AQ-10 y algunas preguntas específicas demostraron ser los predictores más fuertes del autismo en este estudio.  

- La edad y la etnia también son relevantes:  
Se encontró una asociación estadísticamente significativa entre la edad y la etnia con el diagnóstico de autismo, aunque se requiere más investigación para comprender las causas subyacentes.
- El modelo de clasificación multiclase basado en OneVsRestClassifier y SVC mostró el mejor rendimiento hasta ahora, logrando un equilibrio entre precisión y recall.

## Limitaciones
- El conjunto de datos es relativamente pequeño y podría no ser representativo de la población general.
- Los modelos desarrollados, aunque prometedores, aún presentan margen de mejora, especialmente en la reducción de falsos positivos.

## Trabajo Futuro
- Explorar otros modelos de clasificación y técnicas de remuestreo.
- Incorporar nuevas características relevantes.
- Evaluar el modelo en poblaciones más diversas.
- Implementar el modelo en un entorno clínico real.
## Contacto
Si tienes alguna pregunta o sugerencia, no dudes en contactar a [Anton Barrera en mi correo](hi@anbar.top), por Github o en mis redes sociales.


--------------------------------------------------------------------------------------


# Predicting Autism in Adults with Machine Learning

This project explores the use of machine learning techniques to predict the risk of Autism Spectrum Disorder (ASD) in adults, using demographic data and responses to the AQ-10 questionnaire.

## Content

* **`autism_adult_etl.csv`:** Preprocessed dataset ready for modeling.
* **`autism_multiclass_model.pkl`:** Trained multiclass classification model (the best model so far).
* **`code_mapping.json`:** Mapping of numeric codes to country names.
* **`requirements.txt`:** List of project dependencies.
* **`notebook.ipynb`:** Jupyter notebook with exploratory data analysis (EDA), model building, and evaluation.

## Installing Dependencies

1. Clone this repository:

   ```bash
   git clone https://github.com/Kamaranis/ASD-Multiclass-Predictor-Model.git
   ```

2. Create a virtual environment (recommended):
    - Option A: (with virtualEnv)
    ```bash
    python -m venv venv  # Create a virtual environment named 'venv'
    source venv/bin/activate  # Activate the environment (Linux/macOS)
    venv\Scripts\activate.bat  # Activate the environment (Windows)
    ```
    - Option B: (Anaconda)
    ```bash
    conda create -n my_virtual_env
    conda activate my_virtual_env
    ```
3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Open the Jupyter notebook 'Predicting Autism Spectrum Disorder (ASD) in Adults using ML.ipynb'.
2. Run the cells to load the data, perform exploratory analysis, train the models, and evaluate their performance.
3. Use the trained model (autism_multiclass_model.pkl) to make predictions on new data. You can recreate the code or use the already trained model.

## Key Findings
- The AQ-10 test is a key predictor:   
  The total score on the AQ-10 and some specific questions proved to be the strongest predictors of autism in this study.

- Age and ethnicity are also relevant:  
  A statistically significant association was found between age and ethnicity with the diagnosis of autism, although more research is needed to understand the underlying causes.
- The multiclass classification model based on OneVsRestClassifier and SVC showed the best performance so far, achieving a balance between precision and recall.

## Limitations
- The dataset is relatively small and may not be representative of the general population.
- The developed models, although promising, still have room for improvement, especially in reducing false positives.

## Future Work
- Explore other classification models and resampling techniques.
- Incorporate new relevant features.
- Evaluate the model on more diverse populations.
- Implement the model in a real clinical setting.

## Contact
If you have any questions or suggestions, do not hesitate to contact [Anton Barrera via email](hi@anbar.top), on Github, or through my social media.


----------------------------------------------------------------------------------------------


# 大人における自閉症の予測 - 機械学習を用いたアプローチ

このプロジェクトでは、大人における自閉症スペクトラム障害（ASD）のリスクを予測するために、AQ-10アンケートの回答や人口統計データを用いた機械学習技術の応用を探求します。

## 内容

* **`autism_adult_etl.csv`:** モデリングのために前処理されたデータセット。
* **`autism_multiclass_model.pkl`:** 訓練された多クラス分類モデル（現在のところ最も優れたモデル）。
* **`code_mapping.json`:** 国コードと国名のマッピング。
* **`requirements.txt`:** プロジェクトの依存関係リスト。
* **`notebook.ipynb`:** データの探索的分析（EDA）、モデル構築、評価を行ったJupyterノートブック。

## 依存関係のインストール

1. このリポジトリをクローンします：

   ```bash
   git clone https://github.com/Kamaranis/ASD-Multiclass-Predictor-Model.git
   ```

2. 仮想環境を作成します（推奨）：
    - オプションA:（virtualEnvを使用）
    ```bash
    python -m venv venv  # 仮想環境を作成（名前は'venv'）
    source venv/bin/activate  # 環境をアクティベート（Linux/macOS）
    venv\Scripts\activate.bat  # 環境をアクティベート（Windows）
    ```
    - オプションB:（Anacondaを使用）
    ```bash
    conda create -n my_virtual_env
    conda activate my_virtual_env
    ```
3. 依存関係をインストールします：
    ```bash
    pip install -r requirements.txt
    ```

## 使用方法
1. Jupyterノートブック 'Predicting Autism Spectrum Disorder (ASD) in Adults using ML.ipynb'を開きます。
2. データの読み込み、探索的分析、モデル訓練、パフォーマンス評価を行うためのセルを実行します。
3. 訓練済みモデル（autism_multiclass_model.pkl）を使用して新しいデータに対する予測を行います。コードを再作成するか、既に訓練されたモデルを使用することができます。

## 主な発見
- **AQ-10テストは重要な予測因子です：**   
  AQ-10の総得点と特定の質問は、この研究で自閉症の最も強力な予測因子であることが証明されました。

- **年齢と民族も関連しています：**   
  年齢と民族が自閉症の診断と統計的に有意義な関連性があることが発見されましたが、根本的な原因を理解するためにさらに研究が必要です。
- **OneVsRestClassifierとSVCに基づく多クラス分類モデルは現在のところ最も優れたパフォーマンスを示しました。**   
  精度と再現率のバランスを取ることができました。

## 制限
- **データセットは比較的小規模であり、一般的な人口を代表していない可能性があります。**   
- **開発されたモデルは約束的ですが、特に偽陽性を減らす点で改善の余地があります。**

## 将来の作業
- **他の分類モデルやリサンプリング技術を探求します。**   
- **新しい関連特徴を取り込みます。**   
- **より多様な人口に対してモデルを評価します。**   
- **実際の臨床環境でモデルを実装します。**

## 連絡先
質問や提案があれば、[Anton Barreraにメール](hi@anbar.top)で、またはGithub、ソーシャルメディアを通じてお問い合わせください。

