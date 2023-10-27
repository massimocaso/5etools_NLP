### 5e Tools NLP (Q&A)

Il progetto si concentra sull'utilizzo del Natural Language Processing (NLP) per analizzare le descrizioni delle classi di Dungeons and Dragons (D&D) presenti in file specifici. Implementiamo un sistema di Question and Answering (Q&A) che consente agli utenti di porre domande sulle informazioni delle classi e ricevere risposte accurate. Inoltre, introduciamo anche la traduzione automatica dall'inglese all'italiano. Il processo coinvolge l'impiego di modelli di recupero e di lettura, insieme a tecniche di embedding per migliorare la comprensione del contesto e fornire risposte più precise.

## Struttura del Progetto

Il progetto è suddiviso in diverse fasi chiave:

1. **Creazione del Document Store**: Creazione del Document Store in memoria per archiviare e gestire i documenti relativi alle classi di D&D.
2. **Retrieval delle Informazioni**: Abbiamo implementato un sistema di retrieval delle informazioni utilizzando Dense Passage Retriever per recuperare le informazioni rilevanti.
3. **Embedding dei Documenti**: Calcolo degli embeddings per i documenti per migliorare la comprensione del contesto.
4. **Question and Answering (Q&A)**: Implementazione del sistema di Q&A utilizzando FARMReader e ExtractiveQAPipeline per consentire agli utenti di porre domande sulle informazioni delle classi di D&D.
5. **Traduzione Automatica**: Abbiamo introdotto la traduzione automatica dall'inglese all'italiano utilizzando il modello MBart.

## Librerie Necessarie

Per eseguire correttamente il nostro progetto, assicurati di avere installate le seguenti librerie Python:

- **Transformers**: Questa libreria è essenziale per l'utilizzo dei modelli NLP pre-trained, come BERT, RoBERTa e MBart.
- **Haystack**: Haystack è una libreria Python per il recupero e l'elaborazione di testi. È utilizzata per creare il Document Store e implementare il sistema di Q&A.
- **PyTorch (torch)**: PyTorch è un framework di deep learning ampiamente utilizzato. Molte librerie NLP, tra cui Transformers, dipendono da PyTorch.
- **FARM (farms)**: Questa libreria è utilizzata insieme a Haystack per l'implementazione di un sistema di Question and Answering.

Puoi installare queste librerie utilizzando il comando `pip install`
