# 🤝 Cómo colaborar

¡Gracias por querer aportar a **Apis-Chile**! Sumar una API o corregir una caída toma solo unos minutos.

## 🟢 Opción fácil: todo desde el navegador (sin usar git)

No necesitas instalar nada, se puede hacer 100% desde GitHub:

1. Entra al [`README.md`](README.md) y dale clic al ícono de **lápiz ✏️** (editar) arriba a la derecha.
2. GitHub creará automáticamente un **fork** por ti al intentar guardar.
3. Agrega tu API en la categoría correspondiente, con este formato:
   ```markdown
   - [Nombre de la API](https://link-a-la-api): Breve descripción de qué hace.
   ```
4. Baja hasta el final de la página y elige **"Create a new branch and start a pull request"**.
5. Dale un título corto a tu PR (ej: "Agrega API de Feriados") y confirma con **Propose changes**.
6. ¡Listo! Tu Pull Request queda enviado para revisión.

## 🛠️ Opción avanzada: con git

1. **Fork** este repo (botón arriba a la derecha).
2. **Clona** tu fork:
   ```bash
   git clone https://github.com/<tu-usuario>/Apis-Chile.git
   ```
3. **Crea una rama**:
   ```bash
   git checkout -b agrega-nueva-api
   ```
4. Edita `README.md` y agrega tu API (mismo formato de arriba).
5. **Commit y push**:
   ```bash
   git add README.md
   git commit -m "Agrega API de [nombre]"
   git push origin agrega-nueva-api
   ```
6. Abre un **Pull Request** hacia `main` explicando brevemente qué agregaste o corregiste.

## Reglas simples

- ✅ La API debe estar relacionada con Chile (pública, gubernamental o privada de uso general).
- ✅ Verifica que el link funcione antes de enviar.
- ✅ Mantén el orden alfabético dentro de cada categoría si es posible.
- ❌ No agregues APIs de pago exclusivo sin capa gratuita, salvo que sean muy relevantes.
- 🗑️ Si una API ya no funciona, muévela a la tabla de **APIs Deprecadas** en vez de borrarla.

## ¿Encontraste un error o una API caída?

Abre un [Issue](https://github.com/NachoOFC/Apis-Chile/issues) describiendo el problema, o directamente haz el PR con la corrección.

---

¡Cualquier aporte, por pequeño que sea, ayuda a la comunidad dev chilena! 🇨🇱
