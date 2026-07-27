### Advanced Machine Learning Project: IRIDE

Questo documento serve da guida per la lettura dei file caricati nella repository. Inoltre è caricato anche il documento di report finale del progetto in cui vengono dati maggior dettagli sui passaggi di implementazione chiarendo le scelte fatte; inoltre sono presentati e motivati tutti i risultati ottenuti.
Nei file di implementazione dei codici sono commentati tutti i passaggi di sviluppo intermedi.

## 1. CREA_TENSORI.ipynb 
In questo notebook è presente il codice per la creazione del dataset iniziale con output registrato nei file .npy **input_tensor.npy** e **output_tensor.npy**

## 2. MLP_Random.ipynb
In questo notebook è presente il codice per lo sviluppo del modello MLP sequenziale con splitting randomico. Nel codice sono presenti anche gli sviluppi delle task del progetto con i relativi risultati dal modello. 

## 3. MLP_Skip_Connection.ipynb
In questo notebook è presente il codice per lo sviluppo del modello MLP con Skip Connection e splitting deterministico. Nel codice sono presenti anche gli sviluppi delle task del progetto con i relativi risultati ottenuti dal modello.

## 4. MLP_Angolare_Continuo.ipynb
In questo notebook è presente il codice per lo sviluppo del modello MLP sequenziale con splitting continuo. Nel codice sono presenti anche gli sviluppi delle task del progetto con i relativi risultati ottenuti dal modello. In questo caso sono presenti anche alcune sezioni aggiuntive rispetto agli altri modelli per studiare le performance del modello sotto stress e i bias introdotti.
