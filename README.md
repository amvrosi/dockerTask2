# Zadanie 2 Docker
</br>
Wykorzystując aplikację React z laboratorium 12 (plik „produkcyjny” Dockerfile) należy:</br>
a. zmodyfikować kod źródłowy tak by aplikacja wyświetlała imię oraz nazwisko studenta
(tekst pod symbolem „atomu”)</br>
<img src="https://github.com/amvrosi/zad2docker/assets/133603835/654d33e4-7a1d-4efa-8ea2-bc7f6bd3047c"></br></br>
b. opracować łańcuch działań w ramach Github Actions, który pozwoli na zbudowaniu</br>
obrazów Docker zgodnych z OCI dla dwóch architektur sprzętowych: x86_64 oraz arm64</br>
(procesor M1/M2).</br>
<img src="https://github.com/amvrosi/zad2docker/assets/133603835/e633b510-fc97-44ea-9a9f-ef31de4b1af3"></br></br>
c. obraz ma zostać poddany testowi pod kątem CVE z wykorzystaniem dowolnego (jednego
z trzech) narzędzi przedstawionych na końcu instrukcji do laboratorium nr 12. Obraz nie
może mieć żadnych zagrożeń krytycznych. </br>
<img src="https://github.com/amvrosi/zad2docker/assets/133603835/dd2efa29-a84f-4c0f-87ea-5fa61221191a"></br>
<img src="https://github.com/amvrosi/zad2docker/assets/133603835/6de50a03-c221-4c32-ba33-ddf06335ab48">
</br></br>
d. w trakcie budowania obrazów należy korzystać z cache w trybie inline </br>
W pliku docker-build.yml parametr DOCKER_BUILDKIT_INLINE_CACHE równa się 1, żeby korzystać z cache w trybie inline</br></br>
e. po zbudowaniu, w ramach działań w Github Actions, obraz ma być przesłany do
repozytorium na Github Packages (repo: ghcr.io).</br>
<img src="https://github.com/amvrosi/zad2docker/assets/133603835/e2490086-43c0-4f23-8648-ad29e64f0307">
