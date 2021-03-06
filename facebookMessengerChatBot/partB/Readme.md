# Οδηγίες για το ομαδοσυνεργατικό τμήμα της άσκησης "Facebook Messenger Bot"

- [x] Αντιγράψτε (**fork**) στον λογαριασμό σας στο Github το repository που θα βρείτε στη διεύθυνση [https://github.com/Mitato/fb-messenger-bot-partB](https://github.com/Mitato/fb-messenger-bot-partB).
- [x] Στο κατάλληλο αρχείο **index** (ανάλογα με το μάθημα), προσθέστε τον κώδικά σας που αφορά στις ερωτήσεις-απαντήσεις του chat bot της εργασίας σας.

Παρακάτω φαίνεται ένα ενδεικτικό **παράδειγμα** του/της P20160000 με την προσθήκη 2 ερωτήσεων/απαντήσεων,

```javascript
// Starting: P20160000 <Student-Name> <Student-Surname>
	if (text === 'Πού βρίσκεσαι τώρα') {
        	        sendTextMessage(sender, "Στην Κέρκυρα")
                	continue
            	}             
	if (text === 'Τι σπουδάζεις;') {
        	        sendTextMessage(sender, "Πληροφορική")
                	continue
            	}
// Ending: P20160000 <Student-Name> <Student-Surname>
```
καθώς και το αντίστοιχο screenshot της προσθήκης-παράδειγμα σε σχέση με τον ευρύτερο κώδικα:

![Παράδειγμα](example_screenshot01.bmp)

- [x] Όταν έχετε ολοκληρώσει το τμήμα του τελικού παραδοτέου που σας ζητείται σε αυτήν τη φάση της εργασίας, κάντε **pull request** με τίτλο τον Α.Μ. και το ονομετεπώνυμό σας (όλα με λατινικούς χαρακτήρες).

**Προσοχή:** *Δεν θα πρέπει να διαγράψετε κάτι στο αρχείο index.js, ΜΟΝΟ να προσθέσετε τον κώδικά σας και τα στοιχεία που σας ζητούνται εντός σχολίων.*

Υπενθυμίζουμε ότι ολόκληρος ο κώδικα της εργασίας σας θα πρέπει να είναι δημόσια διαθέσιμος και το link του να συμπεριλαμβάνεται σε κάθε παραδοτέο στον φάκελό σας στο repository του μαθήματος (courses-ionio/...).
