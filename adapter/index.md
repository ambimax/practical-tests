# Aufgabe:

Erstellen Sie ein neues PHP Projekt. Nuzten Sie dabei composer zur Einbindung externer Bibliotheken (z.B. PHPUnit).

Binden Sie folgende Variable ein:

```php
<?php
$customers = [
    ['firstname' => 'Thomas', 'lastname' => 'Bieber', 'birthday' => '1965-09-12', 'email' => 'thomas@bieber.com', 'phone' => '+1 656 28882 37733'],
    ['firstname' => 'Abby', 'lastname' => 'Bieber', 'birthday' => '1969-02-26', 'email' => 'abby@bieber.com', 'phone' => '+1 656 28882 37733'],
    ['firstname' => 'John', 'lastname' => 'Doe', 'birthday' => '1983-05-21', 'email' => 'johndoe@example.com', 'phone' => '+1 656 223233 576588'],
];
```

Schreiben Sie entsprechende Adapter um diese Daten im XML- oder CSV-Format zu exportieren. 


### Wichtig

Die Aufgabe gilt als vollständig, wenn:
 
- $customers per CSV oder XML exportiert wird.
- 50 Adressen generiert ([Faker](https://github.com/fzaninotto/Faker)) und per CSV oder XML exportiert werden können.
- Jedes Format seine eigene Adapter-Klasse hat (z.B. Adapter_Xml, Adapter_Csv, etc).
- Alle gemeinsamen Funktionen in abstrakte Klassen ausgelagert wurden.
- Die Funktionalität der Adapter mittels [PHPUnit](https://phpunit.de/) geprüft wurde 
