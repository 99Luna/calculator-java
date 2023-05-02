Broj linije koda(LOC)iznosi 235.
Ciklomatska slozenost metoda iznosi 12.
Kognitivna slozensot metode(evaluate Expression)i (calculate) iznosi 14.
Staticka analiza je odradjena koristeci Sonar lint
za fajl calculator.Java pronasla sam sledeci code smell:
Na ln 18,col 30 treba promeniti velika slova u mala slova kod metoda da ne bi doslo do clash-a.
Na ln 24,col 26 treba promeniti velika slova u mala slova kod metoda da ne bi doslo do clash-a.
Na ln 74,col 25 treba promeniti velika slova u mala slova kod metoda da ne bi doslo do clash-a.
Na ln 18,col 30 treba promeniti velika slova u mala slova kod metoda da ne bi doslo do clash-a.
Na ln 4,col 14 moze se dodati private constructor da bi se sakrio implicit public one.
Na ln 183,col 13 je nepotrebna.
Za fajl strat.Java:
Na ln 8,col 3 Zameniti sistem.out sa logger-om
Na ln 19,col 5 Zameniti sistem.out sa logger-om
Na ln 6,col 10 treba promeniti "Expression" u "expression".

