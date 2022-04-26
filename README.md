# Test

Per prima cosa ho esaminato il layout fornito dal tutor.
Il layout presenta tre box principali: una navbar verticale sulla sinistra, un corpo centrale con il reale contenuto della pagina e una sidebar sulla destra.
Ho iniziato a creare i contenuti, e a dividerli in blocchi, in html, per poi gestirli uno per uno con le regole css.

Sono partita con la navbar, la quale contiene un titolo, dei link e un'immagine in fondo; questo primo box presenta al suo interno, a sua volta, altri due box: uno contenente la "parte scritta" e uno l'immagine.
Ho quindi usato flex (con direzione verticale, a colonna) all'interno del box e un justify-content: space-beetwen per staccarli tra loro in modo che si agganciassero uno in cima e uno in fondo alla navbar.

Dopodiche mi sono concentrata sulla parte centrale, che contiene, a sua volta, altri tre box: quello del titolo, quello del sottotitolo e quello delle immagini; l'intero corpo centrale della pagina segue l'andamento a colonna di flex.
Una volta "sistemato" il blocco per intero, mi sono concentrata sui singoli box: il primo e il secondo, entrambi, con flex direzione orizzontale e un justify-content: space-beetwen per far si che i contenuti si disponessero in modo tale da percepire la pagina divisa a metà; per il terzo box, quello delle immagini, mi sono avvalsa della regola display: grid: una griglia formata da due colonne e due righe, dove la prima riga viene poi occupata da una sola immagine, grazie al comando grid-area.

Per ultimo, mi sono concentrata sulla sidebar.
Quest'ultimo box è suddividiso in quattro parti: una sorta di header (contenente il titolo), due contenitori (contenenti entrambi una lista di link) e un footer (contenente un'immagine).
Il box per intero segue l'andamento a colonna di flex.
Analizzando ogni parte, si può dedurre che ogni blocco ha al suo interno un ulteriore regola: l'header è suddiviso in due elementi messi in riga con flex; i due contenitori con i link seguono una struttura a griglia (grid), costituita, in entrambi i contenitori, da due colonne e quattro righe (dove alla prima riga corrisponde il titolo della lista sottostante); l'immagine occupa l'intero footer.