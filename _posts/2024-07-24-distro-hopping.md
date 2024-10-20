---
title: Distro hopping
author: infdv
date: 2024-07-24 00:26:00 +0300
categories: [Update,Linux]
tags: [writing]
render_with_liquid: false
---

## Που όλα ξεκίνησαν.
Κατά τη διάρκεια της ζωής κάποιου, αν ενδιαφερθεί για υπολογιστές και προγραμματισμό, θα του ζητηθεί ~~εκφοβιστικά~~ ευγενικά από διάφορους ανθρώπους να αλλάξει το operating system του σε αυτό που χρησιμοποιούν γιατί είναι το καλύτερο για οτιδήποτε θέλεις να κάνεις. Έτσι βασικά ασχολήθηκα με το Linux πίσω στο καλοκαίρι του 2020. Ένας φίλος μου και μακροχρόνιος χρήστης του Linux, synthels, μου πρότεινε να αλλάξω είτε σε Ubuntu είτε σε Mint αφού ήταν τα καλύτερα για αρχάριους. Εκείνη την εποχή χρησιμοποιούσα Windows 10 και δεν είχα πραγματικά σχέδια να αλλάξω σε άλλο operating system, αλλά καθώς περνούσε ο καιρός και η πίεση αυξανόταν, αποφάσισα να δώσω μια ευκαιρία στο Linux χρησιμοποιώντας dual boot. Έτσι έγραψα το Linux Mint iso σε ένα flash drive που είχα γύρω, έβαλα το usb και, δεν αναγνώρισε τα Windows.

Για κάποιο λόγο άγνωστο ακόμα σε μένα, η μηχανή μου δεν ήθελε το dual boot και μόνο μου πρόσφερε να διαγράψω εντελώς την partition μου ή να κάνω κάτι άλλο. Επειδή ήθελα να κρατήσω τα πολύτιμα παράθυρα μου, και δεν ήξερα τίποτα για partitions εκείνη την εποχή, αποφάσισα να κάνω πίσω και να συνεχίσω να ζώ στο love child του Bill Gates για το προβλέψιμο μέλλον.

Άλλοι 2-3 μήνες πέρασαν και ήθελα να δώσω άλλη μια ευκαιρία στο Linux. Παραδόξως, αυτή τη φορά ο installer αναγνώρισε τα Windows και κατάφερα να εγκαταστήσω το Mint ειρηνικά χωρίς να χρειαστεί να παλέψω με partitions ή installers ποτέ ξανά... Είναι αυτό που θα έλεγα αν, για κάποιο λόγο γνωστό μόνο σε κάποιο θεό, ο installer αποφάσισε να δώσει στο Linux home μου 20GB χώρου αναγκάζοντάς με να μάθω πώς λειτουργούν τα partitions και να επανεγκαταστήσω όλο το πράγμα χειροκίνητα ώστε να λειτουργεί στη μηχανή μου. Νομίζω ότι αναγνωρίζω ένα μοτίβο εδώ...

Ω, επίσης ξέχασα να αναφέρω αλλά για κάποιο λόγο αυτή τη φορά ήταν εγκατεστημένο στο hdd μου καταλαμβάνοντας 200GB από το 1TB που είχα, που ήταν ένα ok αποτέλεσμα.

Οπότε, αυτή τη φορά, έζησα και έμαθα να ζω με το Linux για τον επόμενο χρόνο, μαθαίνοντας τις ιδιοτροπίες του και αφήνοντας πίσω Windows όλο και περισσότερο με κάθε μέρα που περνούσε.

# Κάτι έπρεπε να πάει στραβά όμως
Ένα χρόνο αργότερα, δεν ήμουν ειδικός του Linux, αλλά είχα μάθει κάποια πράγματα. Ένα από τα πράγματα που δεν ήξερα όμως ήταν το `sudo rm -rf /*`. Αυτή είναι μια εντολή που βασικά διαγράφει τα πάντα από τον σκληρό δίσκο σου αφού βάλεις το sudo password.

Έτσι, ο καλός μου φίλος synthels μια μέρα ενώ ήμασταν σε κλήση αποφάσισε να με εκπαιδεύσει σε αυτή την εντολή. Μου είπε ότι είναι ακίνδυνη όσο δεν δίνεις τον κωδικό πρόσβασης. Δεν τον πίστεψα στην αρχή αλλά είπε ότι μπορούσαμε να το δοκιμάσουμε ζωντανά μέσω screen share και ότι αν κάτι πήγαινε στραβά θα με βοηθούσε να το φτιάξω. Τον εμπιστεύτηκα, έτσι εισήγαγα την εντολή σε ένα ήδη ανοιχτό τερματικό, και παρακολούθησα κάθε αρχείο που είχα στο σύστημά μου να διαγράφεται σε μερικά δευτερόλεπτα. Απ'ότι  φαίνεται, αυτό που είχε συμβεί χωρίς να το γνωρίζω εγώ και εκείνος ήταν ότι χρησιμοποίησα ενα τερματικό που είχε ήδη sudo privileges το οποίο δεν έκλεισα ποτέ. Έτσι, δεν χρειαζόταν να ζητήσει δεύτερη φορά πριν αφαιρέσει κάθε αρχείο στη μηχανή μου.

Ακολούθησαν 2-3 ώρες επαναφοράς διαγραμμένων αρχείων από τον 1TB hdd μου και επανεγκατάστασης των Windows. Αυτή τη φορά όμως εγκαταστήσαμε το Mint μαζί με τα Windows και αφήσαμε το πλέον σπασμένο, μη λειτουργικό partition να σαπίζει για αρκετό καιρό. Αλλά ευτυχώς μετά από αυτό το περιστατικό έζησα ειρηνικά με το Mint για τα επόμενα 3 χρόνια. Στην πορεία έκανα μερικά λάθη και μέχρι το τέλος αυτών των 3 χρόνων είχα ένα Linux Mint distro που κρατιόταν μαζί με μαστίχα και λίγο ταινία, αλλά ήταν το δικό μου Linux distro και την αγαπούσα μέχρι θανάτου.

# Η ανάγκη για αλλαγή
Όπως πολλοί από εσάς γνωρίζετε, μου αρέσει να παίζω video games και το Linux δεν είναι ακριβώς διάσημο για τη gaming σκηνή του. Αλλά το Steam υποστηρίζει το Proton που επιτρέπει στα Windows games να τρέχουν στο Linux. Το πρόβλημα είναι ότι αφού το Proton είναι ένα σχετικά νέο εργαλείο δεν αναγνωρίζει κανένα παιχνίδι που μπορεί να έχεις σε ένα ntfs partition. Και αφού προήλθα από τα Windows εκείνο τον καιρό, ο hdd μου ήταν formatted από προεπιλογή ως ένα ntfs partition. Έτσι, πάντα το είχα στο πίσω μέρος του μυαλού μου να σβήσω τα πάντα και να χωρίσω τον hdd και τον ssd μου στα δύο, μισό για τα Linux και μισό για τα Windows που έχω απλά ως εφεδρικό σε περίπτωση που κάτι σταματήσει να λειτουργεί με τα Linux. Αυτό θα βοηθούσε επίσης να πάρω πίσω τα 200GB που ποτέ δεν διόρθωσα από το rm tf incident.

Έτσι, το Πάσχα του 2024 αποφάσισα να δημιουργήσω αντίγραφα οποιουδήποτε σημαντικού αρχείου είχα σε έναν εξωτερικό σκληρό δίσκο και να χωρίσω το σύστημά μου στα δύο. Το ένα μισό ήταν για τα Windows και το άλλο ήταν για το νέο distro που αποφάσισα να δοκιμάσω, το Manjaro. Ήθελα να δοκιμάσω το Arch για αρκετό καιρό αλλά ποτέ δεν είχα την ευκαιρία να το κάνω, έτσι σκέφτηκα ότι μια λειτουργική out of the box έκδοση του Arch με de και τα υπόλοιπα συμπεριλαμβανόμενα ήταν μια καλή ιδέα.

Έτσι, έκανα format τα πάντα ξανά και παραδόξως αυτή τη φορά όλα λειτούργησαν τέλεια. Για τους επόμενους 2-3 μήνες χρησιμοποίησα το Arch, κατάφερα να παίξω τα games μου μέσω του Steam και να χρησιμοποιήσω τα πάντα κανονικά. Αλλά ξανά, για κάποιο λόγο οι θεοί του Linux αποφάσισαν να μου κάνουν μια φάρσα και να κάνουν το audio input μου να σταματήσει να λειτουργεί. Τότε δεν ήξερα γιατί συνέβη αυτό και αφού φοβόμουν να τα κάνω χειρότερα, μετακινήθηκα στα Kubuntu αφού ήθελα να παίξω λίγο περισσότερο με το plasma. 

ΥΓ: Κατά τη στιγμή της συγγραφής αυτού του άρθρου γνωρίζω ότι το καλώδιο του μικροφώνου μου είχε σπάσει και το μικρόφωνο του headset μου σταμάτησε να λειτουργεί και έπρεπε να το στείλω πίσω για να το φτιάξουν.

# Επιστροφή στο Debian.
Το Kubuntu ήταν καλό, αν και είχε τις ιδιορρυθμίες του, κάποια προβλήματα με τον ήχο, μερικές περίεργες δυσλειτουργίες με τους drivers της κάρτας γραφικών και τα θέματα gtk και προβλήματα με το obs. Το τελευταίο ήταν το χειρότερο, αφού ήθελα να κάνω stream καθημερινά εκείνη την εποχή ( * cough cough * και ακόμα το κάνω, οπότε δείτε με ζωντανά στο youtube.com/@infdv ). Έτσι, το obs δεν μου επέτρεπε να χρησιμοποιήσω browser ως scene που ήταν ο τρόπος με τον οποίο έδειχνα το chat μου και δεν μου επέτρεπε να καταγράφω συγκεκριμένα παράθυρα με το xcomposite. Έτσι, έπρεπε να κάνω stream όλη την οθόνη μου που δεν ήταν η καλύτερη εμπειρία. Μετά από περίπου 2 εβδομάδες, αποφάσισα ότι το καλύτερο που μπορούσα να κάνω ήταν να επιστρέψω στπ ένα distro που πάντα λειτουργούσε. Το Mint. Έτσι εγκατέστησα το iso και μετά από κάποια προβλήματα με τα partions κατάφερα να έχω ένα λειτουργικό Linux Mint έτοιμο για stream. Αυτή είναι η διανομή που χρησιμοποιώ αυτή τη στιγμή και δεν σχεδιάζω να αλλάξω σε κάτι άλλο σύντομα.

## Συμπέρασμα
Ακόμα και μετά από όλα αυτά τα Windows είναι ακόμα χειρότερα από το linux

Cya,
- Infdv
