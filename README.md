# Progetto UDP Client-Server in Java

Questo progetto implementa un'applicazione client-server utilizzando il protocollo UDP in linguaggio Java. Il server è in ascolto su una porta specifica e il client invia e riceve datagrammi UDP al server.

## Requisiti

- Java Development Kit (JDK) 8 o versioni successive
- Un ambiente di sviluppo Java compatibile (ad es. IntelliJ IDEA, Eclipse)

## Struttura del Progetto

Il progetto è suddiviso in due componenti principali:

1. **Server**: Contiene il codice per avviare e gestire il server UDP.
2. **Client**: Contiene il codice per inviare e ricevere datagrammi UDP dal server.

## Setup

1. Clona il repository:

    ```bash
    git clone https://github.com/tuonome/progetto-udp-java.git
    ```

2. Apri il progetto nell'ambiente di sviluppo Java preferito.

3. Assicurati che tutte le dipendenze siano scaricate e configurate correttamente.

## Utilizzo

### Avvio del Server

1. Vai alla cartella del server:

    ```bash
    cd server/
    ```

2. Compila il codice:

    ```bash
    javac Server.java
    ```

3. Avvia il server:

    ```bash
    java Server
    ```

### Avvio del Client

1. Vai alla cartella del client:

    ```bash
    cd client/
    ```

2. Compila il codice:

    ```bash
    javac Client.java
    ```

3. Avvia il client:

    ```bash
    java Client
    ```

## Personalizzazioni

Puoi personalizzare il comportamento del server e del client modificando i file `Server.java` e `Client.java` rispettivamente.

## Contributi

Sono benvenuti i contributi per migliorare questo progetto. Sentiti libero di aprire issue o pull request.

## Licenza

Questo progetto è distribuito con licenza MIT. Consulta il file [LICENSE](LICENSE) per ulteriori informazioni.
