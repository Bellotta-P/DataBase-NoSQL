# DataBase-NoSQL
Start of "book" 21 / 02  / 2022

Vi sono due tipi di Database
  Relazionali e Non Razionali
  
  Relazionali
    SQL = Structured Query Language
      Vantaggi
        Immissione di dati
        Vantaggi di gestione dati 
        
      Svantaggi
        Gli svantaggi derivano da limitazioni del linguaggio, dal dover reinterpretare la logica per rendere efficiente il database
        
  Non Razionali
    Mongo DB
      Vantaggi
        Permette agli sviluppatori di inserire o cambiare i dati senza difficoltà e problemi
      Svantaggi
        
      
      [Com'è il modello dei dati? cone organizza i suoi dati]
      Modello dei dati: Documenti [Ogni singola riga che rappresenta i nostri dati è un documento
    Documento
      Un documento si può rappresentare come un dizionario di python (Mongo DB lo ritiene un'oggetto) 
      es: {Nome: "Ugo" , Cognome: "Fantozzi"}
      es: {Nome: "Ugo" , Disegnatore: "Disney"}
      Se è uspicabile che le chiavi siano le stesse tra i documenti, Mongo DB permette di collegare i documenti [Non è un database razionale è un database flessibile]
    Lista
      Collection = Una lista che contiene una seria di documenti
      
      Mongo DB -> Collection == Lista
                      |
                  Documento == Dizionario
                      |
                  Campo Chiave Valore
                  
    Esempi e come riconoscerli [FORMATO DOCUMENTI JSON] (JavaScript Object Notation)
      {Nome: "Ugo" , == Stringa
       Data: 12/7/2000  == Integer
       indirizzo: {Ma: "pace", N: "3", Città: "Milano" == Dizionario/Documento
       Fermate: [7,6,4,523,4] == Vettore (Perchè ha lo stesso tipo di valori al suo interno)
       
       
