# Medical-System
Programul meu  definește și utilizează mai multe clase pentru a modela un sistem de istoric medical. Aceste clase includ constructori, constructori de copiere, operatori de atribuire și destructori. Scopul programului este de a crea un istoric medical pentru un pacient și de a-l afișa. Mai jos este prezentat mai detaliat ceea ce contine programul:

Clasa Adresa  conține cele trei atribute: strada, oras și codPostal.
Clasa are un constructor care primește valorile pentru aceste atribute.
Conține, de asemenea, un constructor de copiere, un operator de atribuire de copiere și un destructor. Acestea sunt necesare pentru gestionarea corectă a obiectelor de tip Adresa.
Este definit un operator << suprascris pentru afișarea adresei într-un flux de ieșire (de exemplu, std::cout).

Clasa Pacient care are atribute precum nume, varsta și o adresă (obiect de tip Adresa).
Similar cu clasa Adresa, Pacient are un constructor, constructor de copiere, operator de atribuire de copiere și destructor.
De asemenea, este suprascris operatorul << pentru afișarea informațiilor despre pacient.

Clasa IstoricMedical: reprezintă un istoric medical care include un pacient și o listă de consultații medicale asociate pacientului.
Are constructor, constructor de copiere, operator de atribuire de copiere și destructor.
Operatorul << este folosit pentru afișarea istoricului medical, care include informații despre pacient și o listă de consultații medicale asociate.

Clasa ConsultatieMedicala reprezintă o consultație medicală, care include data, ora și informații despre pacient (obiect de tip Pacient).
Are constructor, constructor de copiere, operator de atribuire de copiere și destructor, precum și o suprascriere a operatorului << pentru afișarea informațiilor despre consultație.

În funcția main(), am creeat o adresă (adresa), un pacient (pacient), două consultații medicale (consultatie1 și consultatie2), și o listă de consultații medicale (consultatii) care conține cele două consultații medicale.
Apoi, aceste obiecte sunt utilizate pentru a crea un obiect IstoricMedical numit istoric.
La final, se va afisa in cele din urma istoricul medical utilizând operatorul <<.

