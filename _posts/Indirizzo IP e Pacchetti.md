I dati trasmessi tra macchine vengono chiamati **pacchetti**. I pacchetti viaggiano tramite **impulsi elettrici** nei cavi oppure tramite **onde elettromagnetiche**, nel caso delle connessioni **wireless**.

Ogni macchina connessa a una rete possiede un **indirizzo IP (Internet Protocol)**, che la identifica in modo univoco. Le macchine possono avere un **IP privato**, visibile solo da altri dispositivi nella stessa rete locale, chiamata **LAN (Local Area Network)**. L'**IP pubblico**, invece, è quello visibile su Internet (rete **WAN - Wide Area Network**) e di solito è assegnato al modem/router.

Per inviare un pacchetto, la macchina destinataria deve avere un **indirizzo IP**. Esistono due versioni principali di indirizzi IP:

**IPv4**, il più usato, è composto da **4 gruppi chiamati "Ottetti" (numeri da 0 a 255) separati da un punto, ad esempio `192.168.1.1`.

**IPv6**, introdotto per superare i limiti dell’IPv4, è formato da **8 gruppi di 4 caratteri esadecimali** separati da due punti, ad esempio `2001:0db8:85a3:0000:0000:8a2e:0370:7334`.

Infine, esiste un identificatore chiamato **subnet mask**, che serve a determinare **quale parte dell'indirizzo IP identifica la rete** e quale parte identifica il singolo dispositivo (host) all’interno della rete. Questo è fondamentale per suddividere reti più grandi in **sottoreti (subnet)**.
