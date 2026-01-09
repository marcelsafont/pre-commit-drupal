# pre commit hook

1. copiar contingut de pre-commit o clonar repositori
2. crear fitxer pre-commit dins la carpeta ./git/hooks i enganxar el contingut i/o copiar del repositori clonat i enganxar dins la carpeta ./git/hooks
3. donar permisos dexecució al fitxer "chmod +x pre-commit"
4. cada cop que es faci un git commit el pre-commit revisara si en el contingut del commit hi ha console.log(), dsm() o dd() si es aixi abortara la operació
