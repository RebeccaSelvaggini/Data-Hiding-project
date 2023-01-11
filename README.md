# Data-Hiding-project

Progetto in linguaggio Python per il corso di Data Hiding (Multimedia Data Security) in collaborazione con altri due studenti.

Watermarking di immagini in bianco e nero:

implementare una qualunque strategia di embedding (che sia contemporaneamente robusta ed impercettibile) per un marchio 32x32 su immagini a dimensione fissata 512x512 (in bianco e nero); (file Embedding_weusedlsb.py)

implementare poi il corrispondente algoritmo di extraction del marchio da un immagine (non-blind scenario); (file detection_weusedlsb.py)

calcolare la curva ROC (Receiver Operating Characteristic) e stabilire una threshold che garantisca un False Positive Rate inferiore al 10%; (file ROC_weusedlsb.py)

utilizzare la threshold e l'algoritmo di extraction per implementare una funzione di detection che stabilisca se il marchio è presente in un'immagine o meno (file detection_weusedlsb.py).

