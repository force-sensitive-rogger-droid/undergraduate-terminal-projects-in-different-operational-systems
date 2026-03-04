## download mp3 (Άσκηση γραμμής εντολών)
<br>
Αρχικά αντιμετώπισα κάποια προβλήματα εξαιτίας του ότι χρειαζόταν να έχω μία συγκεκριμένη έκδοση της python στο
terminal και εγώ κατέβασα άλλη, παρόλα αυτά μετά από ψάξιμο σε διάφορα forum  βρήκα ότι η απάντηση ήταν η εγκατάσταση
της python 2.7 και μετά από αυτό η εγκατάσταση έγινε και τα βίντεο όλα λειτουργούν.
<br>
<br><a href="https://asciinema.org/a/387892">download mp3</a>

### Βιβλιογραφία που χρησιμοποίησα:
<a href="https://asciinema.org">asciinema</a>
<br><a href="https://linuxconcept.com/how-to-install-youtube-dl-on-ubuntu-20-04-linux-operating-system/">Πηγή πληροφοριών</a></ul>
<br><br><br>

## Γραμμή εντολών (systemd)
<br>
Η επιλογή μου για αυτή την άσκηση είναι το λειτουργικό σύστημα `Arch Linux 2023.03. 01 x86_64` 
και επειδή δεν υπήρχε σκληρός δίσκος στην κατοχή μου και η μνήμη του υπολογιστή μου είναι περιορισμένη 
για να χωρίσω στον σκληρό δίσκο που έχω, η εγκατάσταση έγινε μέσω του VMware Workstation Player.
Άλλαξα το bash username από το default στον αριθμό μητρώου μου (2019150). Στο τέλος, 
μετά την εγκατάσταση του λογισμικού, έκανα τις ασκήσεις που παρουσιάζονται στον παρακάτω πίνακα 
(οι εντολές φαίνονται στο βίνετο του asciinema).

<br><br>
Το Arch linux μετά την εκτέλεση της εντολής `fetch`<br><br>

![arch](https://github.com/P2019SARAKATSANIS/sw/assets/72516045/11f9f8b8-770e-45ab-b401-e2104caefad8)


### Πίνακας Ασκλησεων με link

| | Όνομα άσκησης |
| ---- | ---- |
| 1 | [read the news with an RSS reader](https://asciinema.org/a/5Rlla64wVDE459vnhHjh6vNF9) |
| 2 | [text editor and plug-ins for code highlighting and autocompletion](https://asciinema.org/a/tovApcQsfWX9vQvSdrr4KFyFz) |
| 3 | [check the weather](https://asciinema.org/a/1jUA728xmCNGiSklViOzKA7VP) |
| 4 | [fetch information](https://asciinema.org/a/N3GWhY7I7cTmzxqzTUmZQmpJJ) |

<br><br>
### Εργαλεία που χρησιμοποίησα:<br><br>

 - [Alpine Linux](https://www.alpinelinux.org)<br><br>
 - [VMware Workstation Player](https://www.vmware.com/content/vmware/vmware-published-sites/us/products/workstation-player/workstation-player-evaluation.html.html)<br><br>
 - [Asciinema](https://asciinema.org)<br><br>
<br><br><br>
## Γραμμή εντολών (no systemd, custom static blog generator)

Η άσκηση αφορούσε την δημιουργία ενός blog με την χρήση κάποιου static blog generator. 
Εγώ χρησιμοποιήσα το bashblog που αποτελεί ένα script σε bash το οποίο σου επιτρέπει να 
δημιουργήσεις το δικό σου blog τρέχωντας απλά το πρόγραμμα αφού βέβαια έχεις κάνει export τον editor που 
θα χρησιμοποιήσεις. Μπορείς να παραμετροποιήσεις το αρχείο bb.sh για να αλλάξεις τα στοιχεία του blog όπως 
το όνομα του blog, το email του owner του blog, settings για τα analytics κτλ Αφού διαλέξεις να κάνεις ένα post 
δημιουργούνται τα αρχεία που απαρτίζουν το blog όπως το index.html, main.css κτλ.

<br>
    
![myblog](https://user-images.githubusercontent.com/72516045/234010291-92bee899-7c84-4ce7-b8b4-052d0a8e8040.png)

[myblog Repository](https://github.com/P2019SARAKATSANIS/myblog)

[Github Pages](https://p2019sarakatsanis.github.io/myblog/)
