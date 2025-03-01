**<ins>Author:</ins>** Frode Oksbøl Therkelsen og Lucas Skov Christensen

**<ins>Last Updated:</ins>** 28/02-2025

# Realtime Terningegenkendelse med YOLO og Flask

Dette projekt bruger en YOLO-model til at genkende terningekast fra et webcam-feed og gør resultatet tilgængeligt via et Flask API. Flask-serveren gør det muligt for et eksternt spil at hente de registrerede terningekast.

## Table of contents
1. [Funktionalitet](#Funktionalitet)
3. [Krav](#Krav)
4. [Datasæt](#Datasæt)
5. [Forbedringer](#Forbedringer)
6. [Tilføjelser](#Tilføjelser)

## Funktionalitet

Realtime detektion af terninger ved hjælp af YOLO.

Viser live videofeed med markerede terninger.

Flask API til at hente det seneste terningekast.

Flask-server og videobehandling kører parallelt ved hjælp af threading.

## Krav

For at køre projektet skal følgende være installeret:

Python 3.8+

OpenCV (opencv-python)

Flask

Flask-CORS

Ultralytics YOLO

## Datasæt
Download link til datasættet via. google drive. Samling af andres datasæt med lidt egen data:
https://drive.google.com/file/d/1k9-I0vSxcb4q0PFtzjIrivhMYs6Rd-HC/view?usp=sharing

## Forbedringer

Forbedret nøjagtighed af terningegenkendelse.

## Tilføjelser

Integration med et spil.

Database til at gemme tidligere kast.
