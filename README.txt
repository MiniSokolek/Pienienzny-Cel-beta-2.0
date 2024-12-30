THIS SITE IS NOT AVAILABLE IN ENGLISH LANGUAGE
Żeby otworzyć tą strone, kliknij i sie otworzy w przeglądarce, kwota pieniężna zapisuje się, nawet jeśli odświeżysz strone
Stworzone przez MiniSokolka! Prosze nie kopiować!!
Jest to wersja Beta 2.0
Żeby zmienić licznik z 100zł na większą kwote, kliknij prawym przyciskiem w plik Pieniężny Cel
zedytuj za pomocą notepad++ zjedź na sam dół, edytuj "amount" na ten cel jaki chcesz uzbierać
np.
 // Sprawdzenie, czy osiągnięto 350 zł
            if (amount >= 350) {
                document.getElementById("message").innerText = "Brawo! Uzbierałeś 350 zł!";
            } else {
                document.getElementById("message").innerText = ""; // Czyści komunikat