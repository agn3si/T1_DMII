<div style="border-left:4px solid #3D6FB0;padding:6px 0 8px 16px;"><div style="opacity:.72;font-size:12px;letter-spacing:1.4px;">Datos Masivos II · PRÁCTICA 1</div><div style="color:#3D6FB0;font-size:27px;font-weight:700;margin-top:4px;">Ejercicios: Unidad 1</div><div style="opacity:.72;font-size:14px;margin-top:6px;margin-bottom:10px;">Equipo Tres: Castrillo Cruz Karen Arlet, Ramos González Nadia, Zamora Antiga Ángel Javier.</div><img src="https://mmss.iimas.unam.mx/dmmss/wp-content/uploads/2026/02/cropped-LogoUNAM_IIMAS_Negro50-scaled-2.png" width="200"/></div>

El presente repositorio contiene dos pipelines de procesamiento de datos implementando PCA (Análisis de Componentes Principales), t-SNE (t-distributed Stochastic Neighbor Embedding) y NMF (Non-negative Matrix Factorization) para evaluar y comparar su capacidad de reducción de dimensionalidad, discriminación de datos en visualización y rendimiento junto a un clasificador. Consta de dos secciones: La primera se basa en el artículo de Golub et al. (1999), "Molecular Classification of Cancer: Class Discovery and Class Prediction by Gene Expression Monitoring", el cual aborda el problema de clasificar tipos de cáncer a partir de perfiles de expresión genética, mientras la segunda busca identificar y discernir la presencia de enfermedades en huertos de tomate.

```text
La estructura de las carpetas actual:

T1_DMII/
├── Molecular Classification of Cancer/
│   ├── codigo_genes.ipynb
│   └── data/                                # train, independent y actual
│
└── Tomato Leaves/
    ├── codigo_tomates.ipynb
    └── data/
        ├── plantvillage/
        │   ├── 5 cross-validation/
        │   │   └── Cross-validation[1-5]/       # 5 folds para validación cruzada
        │   │       ├── Test/                    # 10 clases (Bacterial_spot, Early_blight, etc.)
        │   │       └── Train/                   # 10 clases
        │   └── Preprocessed data/
        │       └── [10 clases procesadas]/
        └── taiwan/
            ├── data augmentation/
            │   ├── Test/                        # 6 clases (Bacterial spot, Black mold, etc.)
            │   └── Train/                       # 6 clases
            └── Preprocessed data/
                ├── Test/                        # 6 clases
                └── Train/                       # 6 clases
```
