# Compilers
Τα ζητούμενα για το **μέρος Α-2 της εργασίας** είναι τα ακόλουθα: <br>
α) Ένα έγγραφο Word ή PDF που θα περιέχει: <br>
<br> 1) Εξώφυλλο (με ονοματεπώνυμα μελών ομάδας, αριθμό ομάδας & τμήμα) & Πίνακας Περιεχομένων <br>
2) Κανονικές εκφράσεις (μόνο επιμέρους – όχι ενιαία) <br>
3) Αυτόματα πεπερασμένων καταστάσεων ή ΔΜ (επιμέρους & ενιαίο) <br>
4) Πίνακες μεταβάσεων (επιμέρους & ενιαίος) <br>
5) Περιπτώσεις ελέγχου / εξαντλητικές δοκιμαστικές εκτελέσεις / αποτελέσματα και σχολιασμός τους <br>
6) Σχόλια πάνω στα παραπάνω υποβαλλόμενα (πχ. τρόπος λειτουργίας, προβλήματα που αντιμετωπίσατε, αν / πως τα λύσατε ή αν δεν τα λύσατε τι δοκιμάσατε να κάνετε <br>
7) Ρητή αναφορά ελλείψεων (σε σύγκριση με τα ζητούμενα) καθώς και αναφορά για την ορθή ή μη εκτέλεση του κώδικά σας <br>
8) Ανάλυση αρμοδιοτήτων/ρόλων όλων των μελών της ομάδας <br>
 Φροντίστε να συμβουλευτείτε τις οδηγίες τεκμηρίωσης στο τέλος του παρόντος εγγράφου <br>
<br> β) Το αρχείο FSM του ενιαίου αυτόματου καθώς και τα επιμέρους αρχεία FSM που έχετε δημιουργήσει, επαρκώς σχολιασμένα <br>

<br> **Ακέραιοι αριθμοί** <br>
Οι ακέραιοι αριθμοί της γλώσσας πρέπει να αρχίζουν από ένα μη μηδενικό ψηφίο (1-9) και να ακολουθούν κανένα, ένα ή περισσότερα ψηφία (0-9). Μπορεί να είναι προσημασμένοι ή όχι. Ειδική περίπτωση το ίδιο το μηδέν (0) το οποίο είναι αποδεκτό.<br>
Π.χ.: 5, +8, -115, 1234567, 0 <br>
<br> **Αριθμοί κινητής υποδιαστολής** <br>
Οι αριθμοί κινητής υποδιαστολής (floating point) περιγράφονται ως εξής: Ένας δεκαδικός αριθμός αποτελείται από το ακέραιο μέρος και το δεκαδικό μέρος που διαχωρίζονται με μία τελεία '.'. Τόσο το ακέραιο μέρος όσο και το δεκαδικό ορίζονται σύμφωνα με τους κανόνες που περιγράφηκαν παραπάνω για τους απλούς ακεραίους του δεκαδικού αριθμητικού συστήματος. Υπάρχει επίσης η δυνατότητα ορισμού δυνάμεων με χρήση του χαρακτήρα 'e' ή 'E'. Στην περίπτωση αυτή το ακέραιο ή/και δεκαδικό μέρος υψώνεται στην ακέραια δύναμη που ακολουθεί μετά τον χαρακτήρα 'e' ή 'E'. Όπως και οι ακέραιοι, μπορεί να είναι προσημασμένοι ή όχι. <br>
Π.χ.: 3.14 -10.0 +0.001 1e100 3.14e-10 0e0 0.25 0.9 <br>
<br> **Ονόματα ορισμών και στοιχείων γεγονότων** <br>
Τα ονόματα των ορισμών που αφορούν γεγονότα ή κανόνες, όπως επίσης και ονόματα άλλων στοιχείων γενικά που χρησιμοποιούνται κατά τους ορισμούς γεγονότων αποτελούνται από πεζούς και κεφαλαίους λατινικούς χαρακτήρες και μπορούν μετά τον πρώτο λατινικό χαρακτήρα να περιέχουν χαρακτήρες, ψηφία ή τα σύμβολά - και _. <br>
Π.χ.: static-facts, MoveUp, CUBES, sum-1, table, packman, , A-21-b. <br>
<br> **Μεταβλητές** <br>
Τα ονόματα των μεταβλητών αρχίζουν υποχρεωτικά με τον χαρακτήρα ? ακολουθούμενο από έναν ή περισσότερους λατινικούς χαρακτήρες ή/και ψηφία. <br>
Π.χ.: ?x, ?X, ?3, ?ad, ?X1b23, ?32ΑbC, ?ABcd1234de <br>
<br> **Συμβολοσειρές (ή Λεκτικά κυριολεκτικά)** <br>
Τα λεκτικά κυριολεκτικά ή απλώς συμβολοσειρές (string literals ή strings) περικλείονται μέσα σε διπλές " αποστρόφους και περιλαμβάνουν οποιονδήποτε χαρακτήρα εκτός του backslash \, της νέας γραμμής \n ή της διπλής αποστρόφου " που για τη χρήση τους απαιτούν χρήση σειράς διαφυγής. Αναγνωρισμένοι συνδυασμοί σειρών διαφυγής (escape sequence) μέσα στα strings είναι: <br>

|Escape Sequence|Meaning|Notes|
|---------------|-------|-----|
|\\|Backslash (\)|
|\"|Double quote (")|
|\n|ASCII Linefeed (LF)|NEWLINE| <br>
<br> Π.χ.: "" "Test" "Hello World" "Mark said, \"Boo!\"" <br>
<br> **Σχόλια** <br>
Τα σχόλια αρχίζουν με το σύμβολο ; (ελληνικό ερωτηματικό) και ολοκληρώνονται στην ίδια γραμμή με το end-of-line. Τα σχόλια μπορούν να περιλαμβάνουν μετά το ; οποιονδήποτε χαρακτήρα εντός ή εκτός αλφαβήτου. <br>
<br> **Διαχωριστές** <br>
Η γλώσσα δέχεται ως διαχωριστές συμβολοσειρές ενός ή περισσοτέρων κενών χαρακτήρων (blanks), ενός ή περισσοτέρων tabs, το τέλος γραμμής (end-of-line) και το τέλος αρχείου (endof-file). Οι δυο παρενθέσεις και ορισμένα από τα υπόλοιπα σύμβολα της αλφαβήτου <br>
