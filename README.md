## link do repo:
https://github.com/alcik98/zadanie2

https://hub.docker.com/repository/docker/alcik98/zadanie2

### Zadanie 1:
Do wykonania zadania wykorzystano Dockerfile z zadania 11. W celu uruchomienia zadania poprzez Github Actions stworzono workflow, w którym użyto pliku main.yml
https://github.com/alcik98/zadanie2/actions/runs/1762549024

### Zadanie 2:

Do pliku zadeklarowano użycie platformy QEMU oraz docelowe platformy w sekcji build and push
https://github.com/alcik98/zadanie2/actions/runs/1762549012

### Zadanie 3:

Do wykonania zadania wykorzystano plik dockerfile.zad2, w którym zadeklarowano wieloetapowe tworzenie obrazów. Dzięki uprzedniemu wykorzystaniu silnika BuildKit, nie jest konieczna żadna zmiana w pliku yml

https://github.com/alcik98/zadanie2/actions/runs/1762549019

### Zadanie 4:
Do wykonania zadania 4 wykorzystano wbudowaną w build-push-action funkcję cachowania. W sekcji Build and Push w pliku main4.yml zadeklarowano lokalizację przechowywania cache
Dzięki wykorzystaniu mechanizmu cachowania czas tworzenia obrazu skrócił się z 2m 34s do 1m 5s.

https://github.com/alcik98/zadanie2/actions/runs/1762549013

https://github.com/alcik98/zadanie2/actions/runs/1762669871
