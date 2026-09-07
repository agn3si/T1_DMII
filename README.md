La estructura actual de las carpetas: 

T1_DMII/
├── Molecular Classification of Cancer/
│   └── data/
└── Tomato Leaves/
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