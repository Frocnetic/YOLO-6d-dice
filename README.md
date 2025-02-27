**<ins>Author:</ins>** Frode Oksbøl Therkelsen og Lucas Skov Christensen
**<ins>Last Updated:</ins>** 27/02-2025

# Realtime Terningegenkendelse med YOLO og Flask

Dette projekt bruger en YOLO-model til at genkende terningekast fra et webcam-feed og gør resultatet tilgængeligt via et Flask API. Flask-serveren gør det muligt for et eksternt spil at hente de registrerede terningekast.

## Funktioner

Realtime detektion af terninger ved hjælp af YOLO.

Viser live videofeed med markerede terninger.

Flask API til at hente det seneste terningekast.

Flask-server og videobehandling kører parallelt ved hjælp af threading.
### Datasæt
Download link til datasættet via. google drive. Samling af andres datasæt med lidt egen data:
https://drive.google.com/file/d/1k9-I0vSxcb4q0PFtzjIrivhMYs6Rd-HC/view?usp=sharing

## Krav

For at køre projektet skal følgende være installeret:

Python 3.8+

OpenCV (opencv-python)

Flask

Flask-CORS

Ultralytics YOLO

## Evt. forbedringer eller tilføjelser:

Forbedret nøjagtighed af terningegenkendelse.

Integration med et spil.

Database til at gemme tidligere kast.
