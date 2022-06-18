# -*- coding: utf-8 -*-
print("--------Währungsrecher--------")

#Gewünschte Währung
print("Bitte geben Sie die gewünschte Währung ein.")
Waehrung = input("Entscheiden Sie sich zwischen \n1) |Euro -> GBP| \n2) |Euro -> BRL| \n3) |Euro -> USD| \n-------------------\n4) |GBP -> Euro| \n5) |BRL -> Euro| \n6) |USD -> Euro|\n(Eingabe von 1-6 möglich)\n-> ")

#Währungskurs, stand 18.06.2022
UmrechnungGBP = 0.8590
UmrechnungBRL = 5.4088
UmrechnungUSD = 1.0495

#Aufgabe, falls Euro -> GBP
if (Waehrung == 1):
    GBP1 = input("Bitte geben Sie die gewünschte Anzahl an Euro ein, die Sie umrechnen wollen: ")
    GBP2 = float(GBP1)
    gbp = GBP2*UmrechnungGBP
    print(GBP2,"Euro sind",round(gbp,2),"GBP")

#Aufgabe, falls Euro -> BRL
elif (Waehrung == 2):
    BRL1 = input("Bitte geben Sie die gewünschte Anzahl an Euro ein, die Sie umrechnen wollen: ")
    BRL2 = float(BRL1)
    brl = BRL2*UmrechnungBRL
    print(BRL2,"Euro sind",round(brl,2),"BRL")

#Aufgabe, falls Euro -> USD
elif (Waehrung == 3):
    USD1 = input("Bitte geben Sie die gewünschte Anzahl an Euro ein, die Sie umrechnen wollen: ")
    USD2 = float(USD1)
    usd = USD2*UmrechnungUSD
    print(USD2,"Euro sind",round(usd,2),"USD")

#Aufgabe, falls GBP -> Euro
elif (Waehrung == 4):
    GBP1 = input("Bitte geben Sie die gewünschte Anzahl an GBP ein, die Sie umrechnen wollen: ")
    GBP2 = float(GBP1)
    gbp = GBP2/UmrechnungGBP
    print(GBP2,"GBP sind",round(gbp,2),"Euro")

#Aufgabe, falls BRL -> Euro
elif (Waehrung == 5):
    BRL1 = input("Bitte geben Sie die gewünschte Anzahl an BRL ein, die Sie umrechnen wollen: ")
    BRL2 = float(BRL1)
    brl = BRL2/UmrechnungBRL
    print(BRL2,"BRL sind",round(brl,2),"Euro")

#Aufgabe, falls USD -> Euro
elif (Waehrung == 6):
    USD1 = input("Bitte geben Sie die gewünschte Anzahl an USD ein, die Sie umrechnen wollen: ")
    USD2 = float(USD1)
    usd = USD2/UmrechnungUSD
    print(USD2, "USD sind", round(usd,2), "Euro")

#Bei ungültiger Eingabe
else:
    print("Ungültige Eingabe. Programm wird nun beendet...")
    quit

print("----------------------------------------")
