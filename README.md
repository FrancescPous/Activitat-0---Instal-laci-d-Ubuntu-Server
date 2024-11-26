 Instal-laci-dE-Ubuntu-Server
**Hem de crear una maquina virtual amb les seguents característiques**
![cap1](https://github.com/user-attachments/assets/fcd2bb64-6dbe-46eb-9304-809235315c45)

# Instalació Ubuntu Desktop

1.Hem de triar (Try or Install Ubuntu)

![cap2](https://github.com/user-attachments/assets/c4796ab0-1627-4485-8ff9-8bfbc3786d86)

2.Seleccionem l'idioma de peferencia i seguidament instalem ubuntu

![cap3](https://github.com/user-attachments/assets/b2495e94-db18-4758-a92e-a695c2cb36e9)

3.Escollim la disposició de prefencia del nostre teclat

![cap4](https://github.com/user-attachments/assets/76c58c23-ee25-4f02-aacc-e596e357ac94)

4. Escollim instal·lació mínima

![cap5](https://github.com/user-attachments/assets/56302515-048a-4f7b-bfc1-13dff2eb5c94)

5.Escollim "Más opciones" per poder crear particions

![cap7](https://github.com/user-attachments/assets/08a497a0-afe4-4d18-8b79-f57427725f1b)

6.Crearem taula de particions

![cap8](https://github.com/user-attachments/assets/e8e43dc1-f5c2-4bc8-ad17-1bab260e0d32)

7. Crearem les particions.

 - Partició boot:
   - Aquesta partició serveix per arrencar el SO i tindrà només 1MB.
 - Partició EFI per al sistema:
   - Aquesta partició serà de tipus EFI i servirà per els fitxers d'arrancada del SO.
   - Tindrà un tamany de 512MB.  
 - Intercanvi (Swap):
   - Aquesta partició servirà per que el sistema l'utilitzi si es queda sense RAM o volem hivernar el SO.
   - Si la memòria RAM és inferior a 4GB es recomana que la partició SWAP sigui del doble de la RAM, en cas contrari que sigui igual a la RAM.
   - Com hem assignat 4GB al SO, la SWAP partició serà de 8GB.
 - Home:
   - Aquesta partició contindrà els fitxers dels usuaris, això separa les dades d'usuari de les aplicacions i el kernel del sistema, facilitzant les còpies de seguretat i l'actualització del SO sense perdre la informació dels usuaris.
   - Deixarem 10GB per a dades d'usuaris.
 - Root:
   - L'arrel del SO on estarà el kernel del sistema i les aplicacions.
   - Aquesta partició tindrà el tamany que sobra.

8.Escollim zona horària
![cap9](https://github.com/user-attachments/assets/b9d5f42f-cf6e-4c13-a638-33d6bc17318f)


9.Creem un usuari administrador i donem nom a l'equip
![cap10](https://github.com/user-attachments/assets/3ab018c9-22e5-4289-b081-c1de0d335697)


10. Reiniciem el SO
![cap11](https://github.com/user-attachments/assets/4893df67-2a0c-4f05-bdde-8ac4391ae1e0)

