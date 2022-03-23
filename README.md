# Mipark
Real-time image-based parking occupancy detection 

Progetto che comprende la creazione di un applicazione integrata alle API di Google Maps e collegata ad un database di parcheggi  lungo le strade di Milano il cui stato di occupazione real-time viene monitorato da telecamere collegate ad un servizio di analisi immagini. 

L'occupazione dei posti auto viene archiviata in un database ( un foglio di calcolo ) che in tempo reale comunica con l'app per smartphone, mostrandone la posizione sulla Mappa, unitamente alla loro tipologia (gratuito/residenti/a pagamento). L'utente può quindi selezionare un posto libero dalla mappa o dalla pagina Elenco e l'app avvierà la navigazione verso il parcheggio selezionato.

Per la realizzazione dell'app è stata utilizzata la piattaforma AppSheet ( https://www.appsheet.com ), mentre per il servizio di analisi immagini ci si è serviti del software Camlytics ( https://camlytics.com ).

La comunicazione real time tra il servizio di analisi immagini e il database è stata attuata con un workflow generato attraverso Pipedream ( https://pipedream.com ).

Il servizio è stato testato su alcuni parcheggi situati nella zona della Stazione Centrale sfruttando una webcam disponibile online. Attualmente il servizio non è attivo per ragioni di costo della gestione del servizio, ma nella presentazione allegata è mostrato un esempio del funzionamento durante il test. 

Link all'applicazione: https://www.appsheet.com/start/563442f6-2e3d-4d8b-af97-5b47c188313c .
La presentazione del progetto è allegata alla repository.

Nota: I posti auto attualmente indicati sull'app, essendo il servizio di analisi immagini non attivo, sono fittizzi e finalizzati alla sola dimostrazione dell'aspetto dell'interfaccia utente.



***English***

# Mipark
Real-time image-based parking occupancy detection 


This project includes the creation of an application integrated with Google Maps API and connected to a database of parking spots along the streets of Milan whose real-time occupancy status is monitored by cameras connected to an image analysis service.

The parking spots occupancy is stored in a database ( a spreadsheet ) which communicates real-time with the smartphone app, showing their location on the Map, together with their typology ( free/residents only/paid). The user can then select a free spot from the map or from the list page and the app will start the navigation towards the selected parking spot.

The AppSheet platform (https://www.appsheet.com) was used to create the app, while the Camlytics software (https://camlytics.com) was used as provider of the image-analysis service.

The real time communication between the image analysis service and the database was implemented through a workflow generated using Pipedream (https://pipedream.com).

The service was tested on parking spots located in the Central Station area using a webcam available online. Currently the service is not active for reasons connected to the cost of the service, but an example of its functioning during testing is shown in the attached presentation.

Application link: https://www.appsheet.com/start/563442f6-2e3d-4d8b-af97-5b47c188313c.
The project presentation is attached to the repository.

Note: The parking spots currently showed on the app, since the image-analysis service is not active, are fictionals and only aimed at demonstrating the appearance of the user interface.

## personal links ##

Pipedream personal page for workflows: https://pipedream.com/workflows .
Camlytics personal page for image analysis: https://cloud.camlytics.com/dashboard/1742 .
