def segundos_medianoche():
    horas = int(input("Ingrese la hora: "))
    minutos = int(input("Ingrese los minutos: "))
    segundos = (horas * 3600) + (minutos * 60)
    segundos = 86400 - segundos
    print("Los segundos que faltan para llegar a la medianoche son: ", segundos)

segundos_medianoche()
