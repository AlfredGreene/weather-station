Μετεωρολογικός Σταθμός 
(χαμηλού κόστους, ανοικτού κώδικα και υλικού)

To project  στηρίζεται στη θεματική περιοχή της Αγροτικής Ανάπτυξης - Περιβάλλον που υλοποιείται 
από τη Μονάδα Αριστεία του Πανεπιστημίου Ιωαννίνων και του Επιστημονικού & Τεχνολογικού πάρκου Ιωαννίνων.

To project αυτό στηρίζεται στο RaspberryPi και στο AirPi kit.
Το AirPi είναι ένα kit που συγκεντρώνει μερικούς γνωστούς αισθητήρες-sensors-
κυρίως χαμηλού κόστους για μετεωρολογικά δεδομένα και δεδομένα ποιότητας αέρα.
Συγκεκριμένα διαθέτει τον διπλό αισθητήρα της Bosch BMP085, που μετράει θερμοκρασία και πίεση,
τον επίσης διπλό αισθητήρα DHT-22, θερμοκρασίας & υγρασίας.
Διαθέτει τη GL55 φωτοδίοδο για μέτρηση της έντασης του φωτός και ένα μικρόφωνο για τη μέτρηση του μέσου 
επιπέδου θορύβου στο περιβάλλον με τον αντίστοιχο ενισχυτή του μικροφώνου MCP6283.
Τη μετατροπή των αναλογικών σημάτων σε ψηφιακά έχει αναλάβει ο μετατροπέας -converter- MCP3008, ενώ το kit 
διαθέτει ακόμη έναν διπλό αισθητήρα τον MiCS-4514, που στην πραγματικότητα ενσωματώνει τον MiCS-2710 μετρητή NO2 
και τον αισθητήρα MiCS-5525 που μετράει το CO.
Τέλος η πλακέτα έχει προεγκαταστημένες τις θέσεις για να δεχθεί, τόσο τον αισθητήρα TGS-2600, που είναι ένας υψηλής 
ευαισθησίας ανιχνευτής συγκέντρωσης μολυσματικών ουσιών της ατμόσφαιρας, όσο και το ADAFRUIT ULTIMATE GPS για 
προσδιορισμό της θέσης του.
Το αρχικό λογισμικό που είναι γραμμένο σε γλώσσα Python και χρησιμοποιεί όλες τις σχετικές βιβλιοθήκες που έχουν γραφτεί
για τα χρήση του RaspberryPi με ηλεκτρονικά εξαρτήματα, το πήραμε από τη διεύθυνση:
https://github.com/tomhartley/AirPi, αλλά στη συνέχεια βρήκαμε πιο ολοκληρωμένο και συνιστούμε το αποθετήριο στη διεύθυνση:
https://github.com/haydnw/AirPi 
,το οποίο και υιοθετήσαμε για τις αρχικές μας μετρήσεις.
