**Projekt 1.1 - Basic LAN Network**

**Cel:**
W poniższym projekcie zbudowałem oraz skonfigurowałem podstawową sieć LAN, która umożliwia bezpośrednią komunikację pomiędzy dwoma komputerami.

**Urządzenia wykorzystane w projekcie:**
1 x Cisco Switch
2 x PC 

**Adresacja IPv4:**

1. User_1 | Ip: 192.168.1.1 | Maska: 255.255.255.0
2. User_2 | Ip: 192.168.1.2 | Maska: 255.255.255.0

Oba urządzenia znajdują się w tej samej podsieci 192.168.1.0 /24.


**Konfiguracja:**<br>
Adresy IPv4 zostały skonfigurowane statycznie na obu komputerach. Komputery natomiast zostały podłączone ze switchem za pomocą połączeń Ethernet.
Router ani domyślna brama nie jest wymagana, ponieważ komunikacja odbywa się miedzy hostami znajdującymi się w tej samej podsieci.

**Weryfikacja:**<br>
Poprawność konfiguracji została zweryfikowana za pomocą polecenia ping.

User_1 → User_2
PING 192.168.1.1
Reply received

User_2 → User_1
PING 192.168.1.2
Reply received

Jak widać powyżej test zakończyłem z powodzeniem.

**Wynik:**<br>
Projekt zakończył się sukcesem. Oba komputery mogą komunikować się ze sobą za pośrednictwem przełącznika, ponieważ posiadają adresy należące do tej samej podsieci IPv4.
Projekt potwierdził podstawową znajomość:
adresacji IPv4,
masek podsieci,
podstawowej komunikacji w sieci LAN,
działania przełącznika Ethernet,
weryfikacji połączenia za pomocą ping.


**Zrzut ekranu poniżej:**

<img width="1917" height="1076" alt="image" src="https://github.com/user-attachments/assets/1ffca61d-6384-495f-b1a5-8bf08d2593eb" />

