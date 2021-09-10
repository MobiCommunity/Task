# Zadanie rekrutacyjne

Przed przystąpieniem do zadania proszę sklonować następujące repozytoria:

https://github.com/MobiCommunity/SerialNumberProvider

oraz

https://github.com/MobiCommunity/DevicesDistributor


Następnie proszę o tworzenie osobnego brancha dla każdego zadania. Czyli: 
feature/zad1/<id>

gdzie id to pierwsza litera imienia i nazwisko. (Jan Kowalski => jkowalski)

Niech każde zadanie zakończone będzie pull requestem do brancha o nazwie Develop.

Projekt w którym będzie wykonywane zadanie testowe polega na rejestracji urządeń w fabryce. Czyli każde nowe utworzone urządzenie zostaje dodawane do repozytorium (InMemory). Przed dodaniem, jednak trzeba skorzystać z zewnętrznej usługi służącej do generowania numeru seryjnego urządzenia. Gdy zostanie on pobrany, urzadzenie jest gotowe do zarejestrowania w repozytorium.

W razie pytań/wątpliwości proszę o kontakt :) 

### Zadanie 1.

Proszę o dołożenie endpointu służącego do pobrania wszystkich zarejestrowanych urządzeń. Metoda powinna być widoczna w API i pokazywać co rzeczywiście zwraca.

### Zadanie 2.

Dołożenie obsługi rejestracji mikrofalówek, analogicznie jak przy rejestracji lodówek.

### Zadanie 3. 

Modyfikacja zadania 2, tak, aby serwis do generowania seryjnych kodów dla lodówek działał bez zmian, a dla mikrofalówek generował kod seryjny w analogiczny sposób, tylko zamiast SHA - MD5. 

### Zadanie 4.

Proszę o skonteneryzowanie obydwu aplikacji i uruchomienie ich w kontenerach i zademonstrowanie ich działania.
Wskazówka: Nowe app settingsy dla uruchamiania w kontenerze.

### Zadanie 5. 

Proszę o przygotowanie pliku docker-compose do uruchomienia obydwu kontenerów.

### Zadanie 6. 
  
Proszę o zmiane sposobu komunikacji pomiędzy serwisami. Z klasycznego Rest api na GRPC.
