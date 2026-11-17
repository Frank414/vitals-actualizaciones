# Vitals: actualizaciones

Este repositorio solo tiene los archivos que [Vitals](https://github.com/Frank414/vitals) consulta cuando tocás
"Buscar actualizaciones" en "Acerca de":

| Archivo | Para qué |
|---|---|
| `version.json` | Última versión publicada de Vitals, enlace de descarga y notas. |
| `rules.json` | Reglas de diagnóstico (se pueden mejorar sin sacar otra versión del programa). |
| `*.sig` | Firma digital de cada archivo. Vitals descarta cualquier archivo sin una firma válida del autor. |

No contiene código ni datos de nadie. Los archivos se generan con `FIRMAR_REGLAS.bat` en la PC del autor (la clave privada
nunca sale de ahí) y se suben tal cual.
