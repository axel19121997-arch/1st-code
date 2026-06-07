import tkinter as tk

def calculer():
    try:
        a = float(entree1.get())
        b = float(entree2.get())
        op = operation.get()

        if op == "+":
            resultat = a + b
        elif op == "-":
            resultat = a - b
        elif op == "*":
            resultat = a * b
        elif op == "/":
            resultat = a / b if b != 0 else "Erreur"

        label_resultat.config(text=f"Résultat : {resultat}")

    except ValueError:
        label_resultat.config(text="Entrée invalide")

fenetre = tk.Tk()
fenetre.title("Calculatrice")

entree1 = tk.Entry(fenetre)
entree1.pack()

operation = tk.StringVar(value="+")
tk.OptionMenu(fenetre, operation, "+", "-", "*", "/").pack()

entree2 = tk.Entry(fenetre)
entree2.pack()

tk.Button(fenetre, text="Calculer", command=calculer).pack()

label_resultat = tk.Label(fenetre, text="")
label_resultat.pack()

fenetre.mainloop()
