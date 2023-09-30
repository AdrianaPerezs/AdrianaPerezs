
def calcular_gastos():
    print("Gastos universitario")
    print("Ingrese gastos de cada 6 meses:")

    matricula = float(input("matricula: $"))
    Alimentos = float(input("Alimentos: $"))
    Transporte = float(input("Transporte: $"))
    Copias = float(input("Copias: $"))
    Internet = float(input("Internet: $"))

    gasto_total = matricula + Alimentos + Transporte + Copias + Internet

    print("\nResumen de gastos de cada 6 meses:")
    print(f"matricula: ${matricula:.2f}")
    print(f"Alimentos: ${Alimentos:.2f}")
    print(f"Transporte: ${Transporte:.2f}")
    print(f"Copias: ${Copias:.2f}")
    print(f"Internet : ${Internet:.2f}")
    print("-" * 20)
    print(f"Gasto total: ${gasto_total:.2f}")


if __name__ == "__main__":
    calcular_gastos()
