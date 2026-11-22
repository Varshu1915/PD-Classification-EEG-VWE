# PD-Classification-EEG-VWE
parkinson's Disease classification using EEG and Validated Weighted Ensembling
Parkinsons-EEG-Detection/
│
├── README.md
│
├── preprocessing/
│   ├── wavelet_denoising.py
│   ├── fir_filtering.py
│   └── ica_artifact_removal.py
│
├── feature_extraction/
│   └── eeg_features.py
│
├── models/
│   ├── random_forest.py
│   ├── cnn_lstm.py
│   ├── transformer.py
│   └── vwe_ensemble.py
│
├── evaluation/
│   ├── loso_validation.py
│   ├── confusion_matrix.py
│   └── weight_stability.py
│
└── requirements.txt
