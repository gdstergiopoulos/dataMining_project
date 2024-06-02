<h1>Project στα πλαίσια του μαθήματος <b>Εξόρυξη Δεδομένων και Αλγόριθμοι Μάθησης</b></h1>
<h2>Στεργιόπουλος Γεώργιος<br>AM: 1083861<br><a href="mailto:gstergiopoulos@ac.upatras.gr">gstergiopoulos@ac.upatras.gr</a></h2>
Στο αρχείο up1083861.ipynb βρίσκεται η προσέγγιση μου στα ερωτήματα του αρχείου data_mining_project_2024.pdf<br>
Στο αρχείο report.pdf βρίσκεται η αναφορά για την προσέγγιση αυτή<br>

<a href="https://upatrasgr-my.sharepoint.com/:f:/g/personal/up1083861_upatras_gr/Err_ae2QzF9IgwjvQg3j3VMBd-m-fRHXIeHTkuyQa8Gszg?e=r35AeF">Εδώ</a> μπορείτε να βρείτε την λύση μου μαζί με την ΒΔ που απειτείται για να εκτελεστεί ο κώδικας.<br><br>
Τοποθετείστε στον ίδιο φάκελο το αρχείο harth.db και το up1083861.ipynb και ανοίξτε τον φάκελο αυτό στο επιθυμητό σας περιβάλον προβολής/επεξεργασίας Jupyter Notebook έτσι ώστε να εκτελούνται τα Cells σωστά (λόγο relative path)<br>

<h2>Σύντομη Περιγραφή της εργασίας</h2>
Η  υλοποιητική  αυτή  εργασία,  εκπονήθηκε  στα  πλαίσια  του  μαθήματος  «Εξόρυξη 
Δεδομένων και Αλγόριθμοι Μάθησης». Στην εργασία αυτή στόχος είναι η αξιοποίηση ενός 
παρεχόμενου συνόλου δεδομένων, για την εξοικείωση με το αντικείμενο του μαθήματος.<br><br>
 Συγκεκριμένα,  μας  δόθηκε  το  σύνολο  δεδομένων  <a href="https://archive.ics.uci.edu/dataset/779/harth">Harth</a>,  το  οποίο  αποτελείται  από 
6461328 δεδομένα, που έχουν συλλεχθεί από πείραμα που διεξήχθη. Στο πείραμα αυτό 
22  συμμετέχοντες,  εφοπλισμένοι  με  2  αισθητήρες  κίνησης  ο  καθένας,  σε  διαφορετικό 
σημείο του σώματος τους, καταγράφηκαν να εκτελούν διάφορες δραστηριότητες μέσα σε 
ένα  επιβλεπόμενο  χώρο  για  συγκεκριμένο  χρονικό  διάστημα.  Τα  δεδομένα  είναι 
εφοπλισμένα  με  το  κατάλληλο  label,  για  κάθε  χρονική  στιγμή  που  δείχνει  την 
δραστηριότητα του χρήστη.<br><br>
Εμείς, όπως θα δείτε στην παρακάτω αναφορά, σε πρώτο στάδιο καλούμαστε να κάνουμε 
την  κατάλληλη  προ-επεξεργασία  και  στατιστική  ανάλυση  των  δεδομένων  αυτών,  με 
σκοπό  να  καταλάβουμε  τα  δεδομένα  μας,  άλλα  και  να  τα  φέρουμε  στην  καταλληλότερη 
μορφή για τα επόμενα βήματα.<br><br>
Έπειτα,  μας  ζητείται  να  εκπαιδεύσουμε  3  ταξινομητές,  έναν  που  βασίζεται  σε  Neural 
Networks,  έναν  σε    Random  Forest  και  έναν  σε  Bayesian  Networks  για  να  κάνουμε 
Classification. <br><br>
Τέλος,  θα  προσπαθήσουμε  μέσω  2  αλγορίθμων  συσταδοποίησης  να  εφαρμόσουμε 
τεχνικές unsupervised learning, για να χωρίσουμε τους χρήστες σε συστάδες με βάση την 
δραστηριότητα τους.
