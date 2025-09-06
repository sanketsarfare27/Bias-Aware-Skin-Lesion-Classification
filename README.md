Bias-Aware-Skin-Lesion-Classification/
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   └── README.md
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_training_baseline.ipynb
│   ├── 04_explainability.ipynb
│   ├── 05_bias_mitigation.ipynb
│   └── 06_preliminary_results.ipynb
├── code/
│   ├── config.py
│   ├── data_loader.py
│   ├── train.py
│   ├── evaluate.py
│   ├── models/
│   │   ├── mobilenet_v2.py
│   │   └── resnet50.py
│   ├── explain/
│   │   └── grad_cam.py
│   └── fairness/
│       ├── metrics.py
│       └── reweighting.py
└── results/            (auto-created)
