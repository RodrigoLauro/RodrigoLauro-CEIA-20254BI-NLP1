📑 Contenido del Repositorio

▚ Desafío 1 – Vectorización de Texto & Naïve Bayes

“Del texto al número: el primer puente del NLP.”

En este desafío trabajé con el dataset 20 Newsgroups, aplicando técnicas clásicas de representación:

  - TF-IDF, CountVectorizer

  - Similaridad de coseno entre documentos

  - Un clasificador Naive Bayes optimizado

  - Un sistema tipo zero-shot usando comparación por prototipos

  - Análisis de similitud entre palabras a partir de la matriz transpuesta término-documento

  Este trabajo introduce cómo transformar texto bruto en vectores útiles para clasificación.

▚ Desafío 2 – Word Embeddings con Word2Vec

“Las palabras adquieren significado en el espacio vectorial.”

Entrené embeddings Word2Vec (Skip-Gram) usando un corpus propio de letras de canciones.
Incluye:

  - Preprocesamiento y tokenización

  - Entrenamiento con negative sampling

  - Visualización en 3D con t-SNE

  -Análisis de similitud semántica entre palabras

El objetivo fue comprender cómo los modelos modernos capturan relaciones profundas entre palabras.

▚ Desafío 3 – Modelo de Lenguaje a Nivel Carácter

“Predecir el siguiente carácter: la esencia del lenguaje.”

Entrené un modelo SimpleRNN capaz de predecir el próximo carácter en un corpus completo de El Príncipe (Maquiavelo):

  - Tokenización a nivel carácter

  - Ventanas deslizantes (many-to-many)

  - Métrica de perplejidad

Generación de texto con:

  - Greedy Search

  - Beam Search determinístico y estocástico

Este modelo permite entender cómo las redes recurrentes aprenden dependencias a lo largo de una secuencia.

▚ Desafío 4 – Modelo Seq2Seq con LSTM para Traducción

“Construyendo un traductor paso a paso, sin usar atención.”

El desafío final consiste en implementar un modelo encoder–decoder con LSTM para traducir inglés → español usando el dataset spa-eng.

Incluye:

  - Limpieza y tokenización del corpus

  - Embeddings preentrenados GloVe en el encoder

  - Decoder con LSTM entrenable

  - Teacher Forcing

Beam Search para mejorar la calidad de las traducciones

Ajustes progresivos:

  - ampliación del dataset

  - cambios en LR del optimizador

  - tuning de hiperparámetros

  - mejoras en estabilidad del pipeline

sin utilizar el mecanismo de atención, porque no forma parte del desafío

El resultado es un traductor funcional y una exploración completa del enfoque seq2seq clásico que precedió a los Transformers.

📘 Resumen del Aprendizaje

Este repositorio refleja un recorrido ordenado por las principales etapas del NLP moderno:

  * Vectorización clásica (BOW, TF-IDF)

  * Embeddings densos (Word2Vec)

  * Modelos recurrentes (RNN / LSTM)

  * Modelos seq2seq y generación de lenguaje

  * Cada proyecto construye sobre el anterior, culminando en un sistema completo de traducción automática basado en LSTM.

📬 Contacto

Rodrigo Lauro
ing.rodrigo.lauro@gmail.com
Nº SIU: a2120
