# 🎵 Hitster Català

Joc musical tipus Hitster amb cançons catalanes.

## Com es juga
1. Escaneja el QR d'una carta amb la càmera del mòbil.
2. Toca ▶ i escolta la cançó (fragment de 30 segons).
3. Endevina l'any i col·loca la carta a la teva línia del temps.
4. Gira la carta per comprovar l'any, l'artista i el títol.

No cal instal·lar cap app ni tenir compte de Deezer.

## Com funciona
Cada QR apunta a `https://hitster-catala.github.io/?t=ID`, on `ID` és el número
de la cançó a Deezer. La pàgina reprodueix el preview de 30 s sense mostrar
cap informació de la cançó.

## Crear una carta nova
1. Busca la cançó a [deezer.com](https://www.deezer.com).
2. Copia el número de l'enllaç: `deezer.com/track/`**`1234567`**
3. Genera un QR amb la URL `https://hitster-catala.github.io/?t=1234567`

---
Projecte personal sense ànim de lucre. La música es reprodueix a través de
l'API pública de Deezer.
