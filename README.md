# Εργασία στο μάθημα Αλγόριθμοι και Προχωρημένες Δομές Δεδομένων
## Μεταπτυχιακός Φοιτητής: Σολωμός Βασίλης 
## ΑΜ: 00083 - Ακαδημαϊκό Έτος: 2020-2021
### Επιβλέπων Καθηγητής: [Γκόγκος Χρήστος](https://github.com/chgogos)

## Πίνακας Περιεχομένων
* [Πληροφορίες Εφαρμογής](https://github.com/BILLSOL/00083_aadd_ett/blob/main/README.md#%CF%80%CE%BB%CE%B7%CF%81%CE%BF%CF%86%CE%BF%CF%81%CE%AF%CE%B5%CF%82-%CE%B5%CF%86%CE%B1%CF%81%CE%BC%CE%BF%CE%B3%CE%AE%CF%82)
* [Τεχνική Αναφορά](https://github.com/BILLSOL/00083_aadd_ett/blob/main/README.md#%CF%84%CE%B5%CF%87%CE%BD%CE%B9%CE%BA%CE%AE-%CE%B1%CE%BD%CE%B1%CF%86%CE%BF%CF%81%CE%AC)
* [Δεδομένα Προβλήματος](https://github.com/BILLSOL/00083_aadd_ett/blob/main/README.md#%CE%B1%CF%81%CF%87%CE%B5%CE%AF%CE%BF-%CE%B4%CE%B5%CE%B4%CE%BF%CE%BC%CE%AD%CE%BD%CF%89%CE%BD)
* [Κώδικας](https://github.com/BILLSOL/00083_aadd_ett/blob/main/README.md#%CE%BF-%CE%BA%CF%8E%CE%B4%CE%B9%CE%BA%CE%B1%CF%82)
* [Εγκατάσταση εφαρμογής](https://github.com/BILLSOL/00083_aadd_ett/blob/main/README.md#%CE%B5%CE%B3%CE%BA%CE%B1%CF%84%CE%AC%CF%83%CF%84%CE%B1%CF%83%CE%B7-%CE%B5%CF%86%CE%B1%CF%81%CE%BC%CE%BF%CE%B3%CE%AE%CF%82)

## Πληροφορίες Εφαρμογής
Η αποδοτική δημιουργία προγραμμάτων εξετάσεων είναι ένα σημαντικό και επαναλαμβανόμενο πρόβλημα το οποίο καλούνται να αντιμετωπίσουν τα εκπαιδευτικά ιδρύματα σε όλο τον κόσμο. Μια απλοποιημένη μορφή του προβλήματος έχει προταθεί από τους Carter κ.ά. οι οποίοι διέθεσαν δημόσια 13 στιγμιότυπα προβλημάτων που εν συνεχεία χρησιμοποιήθηκαν σε πληθώρα επιστημονικών εργασιών χρονοπρογραμματισμού. Στα πλαίσια της παρούσας εργασίας ζητείται να κατασκευάσετε μια εφαρμογή που θα είναι σε θέση να παράγει λύσεις για τα προβλήματα αυτά.
Το πρόβλημα αφορά εξετάσεις, σπουδαστές και συνεχόμενες περιόδους σε κάθε μια από τις οποίες μπορούν να διεξαχθούν μια ή περισσότερες εξετάσεις. Κάθε εξέταση διαθέτει μια λίστα από σπουδαστές και κάθε σπουδαστής μπορεί να είναι εγγεγραμμένος σε μια ή περισσότερες εξετάσεις. Η λύση του προβλήματος συνίσταται στην ανάθεση εξετάσεων σε περιόδους έτσι ώστε να μην υπάρχουν συγκρούσεις, δηλαδή να μην υπάρχουν σπουδαστές που θα έπρεπε να συμμετάσχουν σε εξετάσεις σε περισσότερα του ενός μαθήματα στην ίδια περίοδο. Καθώς είναι ενδεχόμενο να υπάρχουν πολλά εναλλακτικά προγράμματα που ικανοποιούν τον ανωτέρω περιορισμό, προτιμότερο θεωρείται εκείνο το πρόγραμμα που διαθέτει επαρκή διαστήματα προετοιμασίας ανάμεσα σε διαδοχικές εξετάσεις για όλους τους φοιτητές συνολικά. Ειδικότερα, ορίζονται τιμές ποινής που είναι 16, 8, 4, 2 ή 1 σε κάθε περίπτωση που ένας φοιτητής συμμετέχεισε δύο εξετάσεις που απέχουν 1, 2, 3, 4 ή 5 περιόδους αντίστοιχα. Η συνολική ποινή για όλους τους φοιτητές, διαιρεμένη με το πλήθος των φοιτητών αποτελεί το κόστος της λύσης.
![GitHub Logo](https://github.com/BILLSOL/00083_aadd_ett/blob/main/tabu.png)

## Τεχνική Αναφορά
* [Δείτε εδώ την τεχνική αναφορά](https://github.com/BILLSOL/00083_aadd_ett/blob/main/TEXNIKI_ANAFORA.pdf)

## Αρχείο Δεδομένων
* [Δείτε το αρχείο δεδομένων εδώ](https://github.com/BILLSOL/00083_aadd_ett/blob/main/Data.txt)

## Εγκατάσταση Εφαρμογής
Προκειμένου να εγκαταστήσετε την εφαρμογή θα πρέπει να κατεβάσετε το Main.c(κώδικας) και το data.txt(αρχείο δεδομένων) και να διαθέτετε στον υπολογιστή σας έναν compiler της c++ προκειμένου να εκτελέσετε την εφαρμογή

## Ο Κώδικας
* [Κατέβασε τον κώδικα από εδώ](https://github.com/BILLSOL/00083_aadd_ett/blob/main/main.c)

