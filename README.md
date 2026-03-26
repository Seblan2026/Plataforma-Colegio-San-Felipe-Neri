# laughing-waddle
Mejora de plataforma del colegio 
# VARIABLES DE DISEÑO
fuente_principal = "Arial"
color_fondo = "#f4f6f9"
color_primario = "#1a73e8"
color_secundario = "#ffffff"
columnas_grid = 3

print("Aplicando mejoras al sitio web...\n")

# CAMBIAR FUENTE
if fuente_principal != "":
    print("Fuente cambiada a:", fuente_principal)
else:
    print("Error: fuente no definida")

# CAMBIAR COLOR DE FONDO
if color_fondo != "":
    print("Color de fondo aplicado:", color_fondo)
else:
    print("No se aplicó color de fondo")

# CREAR CUADRÍCULA (GRID)
contador = 1
while contador <= columnas_grid:
    print("Creando columna:", contador)
    contador += 1

# AGREGAR CONTENIDO A LAS COLUMNAS
for i in range(1, columnas_grid + 1):
    if i == 1:
        print("Columna 1: Noticias")
    elif i == 2:
        print("Columna 2: Información")
    else:
        print("Columna 3: Contacto")

# VALIDAR CONTRASTE DE COLORES
if color_primario != color_secundario:
    print("\nBuen contraste visual")
else:
    print("\nMejorar contraste de colores")

print("\nDiseño actualizado correctamente")
