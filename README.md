[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/teLsEufN)

jakobbuhs, 385497
mrpythen, 654431

Oppgave 1:
Legginn(T verdi): krever at verdi er null, bruker en while løkke til å finne riktig posisjon for verdien. Ved funnet
riktig posisjon lages en ny node p som ny node og bruker verdi samt forelder(q) som verdier.
Sjekker videre om p er rotnode, hvis ikke sjekkes om den blir venstre eller høyre barn.

Oppgave 2:
antall(T verdi):sjekker om verdi er null. Bruker while løkke til å gå gjennom treet. Finner den riktig verdi blir teller
økt med 1.
Returnerer teller til slutt.

Oppgave 3:
FørstePostorden(Node<T> p): Første node i postordren finner vi ved å gå så langt til venstre som mulig til vi finner en 
node uten barn. Det er første noden. 

nestePostorden(Node<T> p): Sjekker først om noden er en rot,