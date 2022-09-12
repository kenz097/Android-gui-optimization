# Android-gui-optimization
Tesi Magistrale Universitaria di Vincenzo De Martino per ricostruire interfacce grafiche ottimizzate per il consumo energetico e al contempo gestire il contrasto tra le componenti per problemi legati all’accessibilità. Il progetto è stato svolto usando Python 3.8 e il framework Pymoo 0.6
Per poter ricreare le interfacce grafiche ottimizzate per dispositivi Android è necessario eseguire 3 file:
- BOCP_BOCC_Algorithm per l'estrazione dei colori dei pixel e delle componenti all'interno delle applicazioni Android, questa fase è successiva all'acquisizione dei file .xml e .png tramite UiViewAutomator
- Genetic_algorithm_NSGAII rappresenta l'architettura dell'algoritmo genetico multi-obiettivo per generare le soluzioni per le nuove interfacce, dove per soluzioni si intende la composizione dei nuovi colori.
- Building_Interface serve per poter ricostruire le interfacce grafiche con le nuove soluzioni e creare i file .csv per analizzare i risultati ottenuti.

![Alt Text](https://github.com/kenz097/Android-gui-optimization/blob/main/old%20vs%20optimized.png)
