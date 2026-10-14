# PicoCTF Write-up: Crack The Gate 1
**Categoría:** Web Exploitation  
**Dificultad:** Fácil  
**Alias:** Ramona Cabrío 🐐  

## 📝 Descripción del Reto
El reto presentaba una situación donde un jugador de picoCTF dejó datos confidenciales. Solo nos daban un email sin contraseña pero una backdoor oculta.

## 🛠️ Herramientas Utilizadas
* Navegador Web (Herramientas de Desarrollador / F12)
* rot13.com (Decoder Online)
* ModHeader (Extensión de Google)

## 🎯 Proceso de Resolución
1. **Reconocimiento:** Buscar en el código fuente. 
2. **Descubrimiento:** Me encontré con un comentario raro casi al final del código, seguido de un "Borra esto antes de subirlo".
3. **Explotación:** Utilicé la vulnerabilidad expuesta en ese comentario raro en rot13 e hice una Header Request con la extensión así solo poniendo el email, una contraseña aleatoria y recibiendo la flag al concluir.

#pensamiento 1: puxa tengo que buscar en google.
#pensamiento 2: ya fue, todos buscan en google-
