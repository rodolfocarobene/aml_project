
# Sviluppo di CNN per l'analisi di spettri Raman a scopo diagnostico, a partire da reti note utilizzate per Computer Vision

In questa repository si trovano tutti i codici utilizzati per il progetto di Advanced Machine Learning dell'anno 2023.

Gli autori:
* **Emanuele Palumbo**: e.palumbo3@campus.unimib.it
* **Rodolfo Carobene**: r.carobene@campus.unimib.it


## Descrizione notebooks
Prima di eseguire il codice è necessario ottenere il dataset e inserirlo in una cartella drive dal nome "AML\_2022-2023", alternativamente è possibile cambiare la cella di import del dataset.

* **AML_Project**: Codice completo del progetto. Sono qui inseriti il preprocessing, la definizione delle metriche, la definizione delle reti e le funzioni di training/testing. 

* **SimpleRun(s)**: In questi file vengono definite le tre reti (ResNet, VGG, DenseNet), viene effettuata l'ottimizzazione tramite Hyperband e viene effettuato il training tramite K-Fold Cross Validation.
