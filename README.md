# PD-Classification-EEG-VWE
parkinson's Disease classification using EEG and Validated Weighted Ensembling
Parkinsons-EEG-Classification
│
├── README.md
│
├── preprocessing
│   ├── wavelet_denoising
│   ├── fir_filtering
│   └── ica_artifact_removal
│
├── feature_extraction
│   └── eeg_features
│
├── models
│   ├── random_forest
│   ├── cnn_lstm
│   ├── transformer
│   └── vwe_ensemble
│
├── evaluation
│   ├── loso_validation
│   ├── confusion_matrix
│   └── weight_stability
│
└── requirements
