#Realtime Terningegenkendelse med YOLO og Flask

Dette projekt bruger en YOLO-model til at genkende terningekast fra et webcam-feed og gør resultatet tilgængeligt via et Flask API. Flask-serveren gør det muligt for et eksternt spil at hente de registrerede terningekast.

##Funktioner

Realtime detektion af terninger ved hjælp af YOLO.

Viser live videofeed med markerede terninger.

Flask API til at hente det seneste terningekast.

Flask-server og videobehandling kører parallelt ved hjælp af threading.

##Krav

For at køre projektet skal følgende være installeret:

Python 3.8+

OpenCV (opencv-python)

Flask

Flask-CORS

Ultralytics YOLO
