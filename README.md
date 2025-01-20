# Anima Spring Boot pojekat
Ovaj projekat simulira rad u skloništa za životinje, koje vodi računa o različitim vrstama i rasama životanja, od kojih neke imaju specijalne potrebe: alergije, povrede, deformitete ...
Neke od vrsta i rasa zahtevaju i da vlasnik poseduje posebne dozvole za njiho posedovanje, pa je potrebno proveriti da li osoba koja želi da usvoji te rase i vrste poseduje odgovarajuce dozvole.

Sastoji se iz tri Service-a, Api-GateWay i dve pomocne komponente:

1)Animal care

    -vodi racuna o radu sa zivotinjama
    -dodavanje novih, dobavljanje postojećih...
    -unošenje specijalne potrebe...

2)Permit 

    -Vodi računa o dozvolama i vlasnicima
    -Za koje rase treba dozvola
    -Koje dozvole ima vlasnik
    -Da li vlasnik ima dozvolu za odgovarajucu rase 

3)Animal-Shelter

    -Je service odgovoran za primanje zahteva za usvajanje 
    -Proveravanje da li vlasnik ima odgovarajuće dozvole
    -komunicira sa druga dva servica radi provera i dobavljanja potrebnih informacija
    -i usvajanjem ljubimca od strane vlasnika(u bazi)

#Api-Gateway

    -Gateway je ovde samo organizacion componetnta i ne služi neku veću svrhu-


#Config server

    -radi lakse organizacije i menjanje application.properties-

#Eureka

    -zarad lakseg uspostavljanja komunikacije izmedju servic-a, putep Feign client-a.
  













<img width="720" alt="Screenshot ()" src="https://github.com/user-attachments/assets/4eb1c59a-c32c-4cc0-94f5-e42e0628f675" />


