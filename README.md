# DP-700_LAB18
# Microsoft Fabric Monitoring Lab

Deze repository bevat een oefening uitgevoerd in Microsoft Fabric waarbij de Monitoring Hub werd gebruikt om activiteiten te volgen binnen een werkruimte. 

## Overzicht

In deze lab hebben we de volgende stappen doorlopen:

1. **Werkruimte maken**  
   Een nieuwe werkruimte gecreëerd in een Microsoft Fabric-tenant met Fabric-capaciteit.

2. **Lakehouse maken**  
   Een nieuw Lakehouse-object aangemaakt binnen de werkruimte.

3. **Dataflow (Gen2) maken en monitoren**  
   - Een Dataflow Gen2 aangemaakt met de naam `Get Product Data`.
   - CSV-gegevens opgehaald van:  
     `https://raw.githubusercontent.com/MicrosoftLearning/dp-data/main/products.csv`
   - De Dataflow gepubliceerd en via de Monitoring Hub opgevolgd.

4. **Spark-notebook maken en monitoren**  
   - Een notebook aangemaakt met de naam `Query Products`.
   - Spark-code automatisch gegenereerd en uitgevoerd om de data uit de tabel `products` op te vragen.
   - Activiteit van de notebook gemonitord via de Monitoring Hub.

5. **Monitoring Hub gebruiken**  
   - Activiteit en geschiedenis van Dataflows en Notebooks bekeken.
   - Filters toegepast voor succesvolle activiteiten.
   - Kolomweergave aangepast om extra informatie zoals `Start time`, `Duration`, enz. te tonen.

6. **Opruimen van resources**  
   - Werkruimte verwijderd om resources vrij te maken.

## Benodigdheden

- Een Microsoft Fabric-tenant met actieve licentie of proefversie.
- Webbrowser en toegang tot: [https://app.fabric.microsoft.com](https://app.fabric.microsoft.com)

## Screenshots

(Screenshots kunnen hier worden toegevoegd ter illustratie van de stappen.)

## Licentie

Deze oefening is gebaseerd op trainingsmateriaal van Microsoft Learning. Alle rechten voorbehouden aan de oorspronkelijke auteurs.

![Schermafbeelding 2025-05-19 215308](https://github.com/user-attachments/assets/762198b4-3a2f-4339-9379-eedd75164b76)

![Schermafbeelding 2025-05-19 215419](https://github.com/user-attachments/assets/438a2929-24c7-429e-9f65-d2747cb04141)


![Schermafbeelding 2025-05-19 215650](https://github.com/user-attachments/assets/f5285206-7fec-4bb2-8b97-4de603c8d802)


![Schermafbeelding 2025-05-19 215842](https://github.com/user-attachments/assets/a226cc9a-f967-4612-bbd6-35bfce23370a)

![Schermafbeelding 2025-05-19 220532](https://github.com/user-attachments/assets/0e928101-fc24-4396-855f-1159f78fd0a3)


![Schermafbeelding 2025-05-19 220659](https://github.com/user-attachments/assets/cc94533d-97b7-45cc-8a29-db2ecce0ce0d)


![Schermafbeelding 2025-05-19 221037](https://github.com/user-attachments/assets/5dd008f5-8cdb-4998-add5-65ea402a6aa7)

![Schermafbeelding 2025-05-19 223506](https://github.com/user-attachments/assets/33e5899a-bf3b-4755-8461-94ce682fc425)


![Schermafbeelding 2025-05-19 223544](https://github.com/user-attachments/assets/d595a2b2-570e-4060-8d97-8599ad99745e)



![Schermafbeelding 2025-05-19 223720](https://github.com/user-attachments/assets/7a7e9e88-5d42-4954-aefe-46e1979b6cab)

![Schermafbeelding 2025-05-19 223929](https://github.com/user-attachments/assets/1f3b76c0-d794-4e1e-9b5e-f1f68e3ac978)

![Schermafbeelding 2025-05-19 224022](https://github.com/user-attachments/assets/76fe8623-221a-4d42-9f20-985e805d25e1)






























