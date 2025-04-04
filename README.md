float(input("Ingrese el costo de la comida: $"))

tasa_impuesto = 0.10  

impuestos = costo_comida * tasa_impuesto

propina = costo_comida * 0.18

total = costo_comida + impuestos + propina

print(f"\nResumen de la comida:")
print(f"Costo de la comida: ${costo_comida:.2f}")
print(f"Impuestos: ${impuestos:.2f}")
print(f"Propina: ${propina:.2f}")
print(f"Total a pagar: ${total:.2f}")
