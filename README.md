Παίρνουμε τον φάκελο xstats από το /usr/share/doc/weewx/examples/xstats και
βαζουμε τον φακελό xstats στον προσωπικό μας φάκελο αρχείων δινω όνομα χρήστη για παράδειγμα  metfm
δινουμε στο τερματικο sudo wee_extension --install=/home/metfm/xstats  για να γίνει η εγκατάσταση της επέκτασης,
αντικαθιστούμε τον κώδικα του παρόντος αποθετηρίου στο statistics.inc
τελος κλείσιμο-ανοιγμα του weewx
sudo /etc/init.d/weewx start
sudo /etc/init.d/weewx stop
Αν τα βήματα εκτελέστηκαν σωστά θα δούμε στην επόμενη ανανέωση τα ρεκόρ από την αρχή λειτουργίας του σταθμού.
