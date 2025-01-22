# Furry Friends

Furry Friends este o aplicație esențială pentru comunitatea iubitorilor de animale, oferind o soluție modernă pentru sprijin reciproc în îngrijirea animalelor de companie. Într-o lume în care timpul este o resursă limitată, aplicația răspunde nevoii de a găsi ajutor de încredere și de a simplifica organizarea îngrijirii pentru animale.


Acest proiect a fost realizat în colaborare cu o echipă de studenți, fiecare contribuind cu idei și soluții pentru a dezvolta o aplicație eficientă și ușor de utilizat.


## Funcționalități

Aplicația Furry Friends oferă o serie de funcționalități intuitive și eficiente, menite să simplifice procesul de conectare și colaborare între iubitorii de animale.

1. **Autentificare și înregistrare**
   - Utilizatorii pot crea un cont nou printr-un proces de **Sign Up** simplu și sigur.
   - După înregistrare, utilizatorii pot accesa platforma prin funcționalitatea **Login**.

2. **Gestionarea animalelor de companie**
   - Utilizatorii pot înregistra animalele lor prin opțiunea **Register Pet**, introducând detalii relevante despre acestea.
   - Pe pagina **My Pets**, utilizatorii pot vizualiza și gestiona lista animalelor lor, având opțiunea de a adăuga o **Care Need** – specificarea perioadei în care un anumit animal are nevoie de ajutor.

3. **Oferirea de ajutor**
   - De pe **Home Page**, utilizatorii pot accesa butonul **Help a Pet**, care afișează o listă de animale și perioadele în care acestea necesită ajutor. Utilizatorii pot selecta animalele pe care doresc să le ajute și să își asume responsabilitatea pentru îngrijirea lor.

4. **Urmărirea angajamentelor**
   - Pe pagina **My Caring Sessions**, utilizatorii pot vedea detalii despre angajamentele lor curente, inclusiv perioadele și animalele de care s-au oferit să aibă grijă.

5. **Sistem de recenzii**
   - După încheierea unei sesiuni de îngrijire, proprietarul animalului poate oferi un **Review** voluntarului care a ajutat. Acest feedback contribuie la construirea unui mediu de încredere și la crearea unei reputații pentru utilizatori, promovând colaborarea sigură și transparentă în cadrul comunității.

Aceste funcționalități sunt proiectate pentru a facilita un schimb organizat, transparent și eficient de sprijin între utilizatori, creând o experiență simplă și plăcută pentru toți cei implicați.

## Setup-ul Aplicației

Pentru a putea rula aplicația, este necesar să avem câteva informații despre cum este aceasta organizată. Aplicația este împărțită în două părți principale: **Front-End** și **Back-End**. Mai jos sunt pașii necesari pentru a configura fiecare componentă.

### A. Partea de Front-End

1. **Instalarea Node.js și npm:**
   Înainte de a rula aplicația, trebuie să instalăm **Node.js** și **npm**. 
   
   - Descarcă și instalează Node.js de pe [site-ul oficial](https://nodejs.org/).
   - După instalare, pentru a verifica dacă Node este instalat corect, rulează comanda:
     ```bash
     node --version
     ```
     Aceasta va returna versiunea curentă de Node utilizată.
   
2. **Instalarea dependențelor pentru Front-End:**
   După ce ai instalat Node.js și npm, instalează dependențele necesare pentru aplicația front-end:
   ```bash
   npm install

 3. **Rularea Serverului de Development:**
    După ce toate dependențele au fost instalate, aplicația front-end poate fi rulată folosind comanda:
  ```bash
  npm run dev
   ```
  Aceasta va porni serverul de development și va deschide automat aplicația în browser la adresa:localhost:5173 

  ### B. Partea de Back-End
  1.	**Instalarea Gradle și Dependențele:**
Asigurați-vă că aveți instalate toate dependențele Gradle pentru back-end. Gradle este folosit pentru gestionarea dependențelor și pentru compilarea aplicației back-end. Aceasta va asigura o rulare corectă a serviciilor.
2.	**Rularea Serviciilor Back-End:**
Pentru a porni aplicația back-end, trebuie să rulăm clasa StartRestServices, care va iniția serverele de servicii REST și va permite interacțiunea cu front-end-ul.

 ### C. Conectarea la Baza de Date
Pentru a asigura funcționarea corectă a aplicației, este esențial să ne conectăm la baza de date. Detaliile necesare pentru conectarea la baza de date (precum numele utilizatorului și parola) sunt disponibile în modulul RestServices, în fișierul bd.config din directorul resources.


  


