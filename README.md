from datetime import date

hoje = date.today()
data_futura = date(2026, 12, 31)

dias = (data_futura - hoje).days

print("Faltam", dias, "dias")
