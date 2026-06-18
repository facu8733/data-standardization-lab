# Limpieza y actualizacion excel-lab
# Proyecto: Limpieza de Códigos y Actualización de Precios en Excel

## 📋 ¿Qué hace este proyecto?
Este proyecto resuelve un problema muy común que tienen las distribuidoras, los comercios o las empresas de logística: **actualizar los precios de una lista gigante de productos sin cometer errores y sin perder tiempo haciéndolo a mano.**

A veces, los proveedores mandan las listas de precios con los códigos "sucios" (con espacios de más, minúsculas, o guiones cambiados). Si intentás buscar los precios de forma automática con el sistema viejo, la computadora no los encuentra y te tira error. 

En este laboratorio de **50 productos**, armé un circuito automático que limpia esos códigos, busca el precio nuevo y actualiza el catálogo oficial de la empresa de una sola vez.

## 🛠️ Herramientas de Excel que usé:
1. **Fórmulas de Limpieza (`ESPACIOS` y `SUSTITUIR`):** Para sacar los espacios invisibles y arreglar los guiones de los códigos del proveedor automáticamente.
2. **`BUSCARX`:** La fórmula que va a la lista del proveedor, encuentra el código limpio, agarra el precio nuevo y lo trae a nuestro catálogo.
3. **Pegado como Valores:** Para "congelar" los números finales y poder borrar las listas del proveedor sin que se rompa nada.
4. **Inmovilizar Filas:** Para dejar los títulos de la tabla fijos arriba y que sea cómodo leer el archivo.
5. **Tablas Dinámicas:** Para resumir la información de stock y precios de forma ordenada.

## 🚀 ¿Por qué es útil?
- **Evita el error humano:** No se cambia un solo precio a mano.
- **Ahorra tiempo:** El mismo proceso sirve para 50 filas o para un catálogo de 10.000 productos en pocos segundos.
- **Protege los datos:** Mantiene el stock real de la empresa a salvo mientras se actualizan los costos.
