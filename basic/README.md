rule no 

Agar aap public class use karte ho, to file ka naam exactly same hona chahiye class ke naam ke saath, including capitalization (case-sensitive).

❌ Problem: Case mismatch

Agar aap Main.java bana rahe ho lekin class main likh rahe ho, ya class Main likh rahe ho lekin file main.java hai, to Java complain karega ya ClassNotFoundException de dega, kyunki:
	•	Java case-sensitive hai (e.g., Main ≠ main)
	•	Jab aap java Main likhoge, Java Main.class dhoondhega
	•	Agar class compile hui main.class ke naam se, to mismatch hoga