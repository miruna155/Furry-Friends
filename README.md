# 🧚 Winx 🧚
## Un mic tutorial pentru git


  1) **Clonare repo**<p>
 - Aveti aici link-ul la repo: https://github.com/PopaTudor13/Winx.git
 - Sau puteti da pe ![image](https://github.com/user-attachments/assets/608d08ce-8a11-4a3d-8f90-7931f79eba0b) si sa-l luati de acolo
 - Dupa in IDE doar dati __Open__ la proiect </p>
 2) **Branch-uri**
   - Pe branch-ul __*main*__ vom pune modificarile aduse codului abia dupa ce ne asiguram ca totul functioneaza si nu sunt foarte multe bug-uri. Ma gandesc sa facem asta inainte de demo-uri.
   - In rest, noi vom lucra pe branch-ul __*development*__ . Si ca sa ajungem pe acest branch, sau pe altul ne folosim de *Checkout* ![capture 2](https://github.com/user-attachments/assets/14224cfe-a6a4-44d0-90db-c71e84e46254)
   - Dupa ce am ajuns pe branch, va trebui sa-l aducem la zi cu cel de pe site. Pentru asta ne folosim de *fetch* si *merge* sau de *update*.
   - Va recomand sa va uitati si la tutorialul asta inainte, unde explica putin mai pe larg: [Tutorial fetch](https://www.youtube.com/watch?v=tnz2I9rxrfk)
   - Si daca vreti mai in detaliu, aveti aici documentatia de la Intellij: [Documentatie Intellij](https://www.jetbrains.com/help/idea/sync-with-a-remote-repository.html)
     ![image](https://github.com/user-attachments/assets/bc28a975-1569-4988-8d51-90b5c0f2420e)

---
   - Un tutorial pentru rezolvarea *merge conflicts* 😠 : [Tutorial merge conflicts](https://www.youtube.com/watch?v=mSfq1SoMocg)

--- 
   > [!IMPORTANT]
   > De fiecare data cand ne vom apuca de implementat o chestie noua ( *feature* ), vom crea un branch nou din *development*, pe care il vom numi "feature/nume_feature".
   
 ![image](https://github.com/user-attachments/assets/28317293-866e-46fc-b294-f0a048a5bf33) ![image](https://github.com/user-attachments/assets/ed6a9223-1a99-4b72-b4cc-da6d8cc20307)

  3) __Pull Request__ (PR)
   - Dupa ce facem commit-uri si push, vom face pull request. Pull request-ul il vom face de pe site.
    ![image](https://github.com/user-attachments/assets/94183f06-6cb3-4146-ac8e-991b3a08c36a)
-
 ![image](https://github.com/user-attachments/assets/8333847b-3200-4c59-9a80-2e4b9c8ee41a)
   - In casuta albastra 🟦  vom selecta *development* sau branch-ul in care dorim sa aducem modificarile
   - In casuta verde 🟩 vom selecta *feature-ul* sau branch-ul din care dorim sa aducem modificarile
   - In partea dreapta, daca apasam pe rotita ⚙️ incercuita cu galben 🟡 , vom putea adauga la PR-ul nostru *Reviewers* .
   > [!IMPORTANT]
   > Adaugati cel putin un reviewer, nu conteaza cine. Facem asta ca sa diminuam riscurile de a baga o 'prostie' in proiect.
   > GitHub-ul permite sa dam *merge* si fara sa adaugam reviewers, asta fiindca nu am configurat niste setari, dar cu toate acestea sa nu dati *merge* pana persoana/persoanele care au fost puse la *Reviewers* nu au zis ca e ok ✔️.
   - In final, persoana care va da ultimul review, va da si *merge*.

### Aveti aici si o explicatie asemanatoare de la [Git](https://docs.github.com/en/get-started/start-your-journey/hello-world)

# ☕ Spor la cafeluta corporatista ! ☕ 
     




