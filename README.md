# Laboratorio de Teletransportación Digital (SSH y RDP)

# Recolección de errores

* **Error al conectarse al contenedor de Docker**: Docker usa IPV6 por lo que si usamos localhost docker no se conectará.

	![]<img width="540" height="184" alt="1" src="https://github.com/user-attachments/assets/b68a527f-5eb4-408c-b864-7a161cdd38ba" />

	**Solución**: Usar  ssh alumno@127.0.0.1 \-p 2222 para forzar que use una IP IPV4.  
	![]<img width="540" height="44" alt="3" src="https://github.com/user-attachments/assets/ed912f9e-aab2-49ad-bbc8-90a7b9821f3f" />


* **Desconocimiento de donde guardar la llave generada**: La terminal de la máquina anfitriona al introducir el comando te pide que selecciones un archivo donde guardarla.  
  ![]<img width="388" height="74" alt="2" src="https://github.com/user-attachments/assets/d5ddc6d0-5346-41cf-85cd-7a5c539324c0" />
  **Solución**: Si no se introduce nada se guarda en la localización por defecto y sin contraseña.

	![]
<img width="401" height="196" alt="4" src="https://github.com/user-attachments/assets/57239693-2e26-4813-994f-32215f1d3236" />


* **Error al conectarse desde el Escritorio Remoto con localhost:3389**: Nos dice que  hay otra conexión activa.  
  ![]<img width="510" height="343" alt="5" src="https://github.com/user-attachments/assets/a0a0f300-463a-4f96-83f7-8b88fee833fb" />

	**Solución**: Conectarse desde el navegador con [*http://localhost:3000*](http://localhost:3000)  
  ![]<img width="377" height="390" alt="6" src="https://github.com/user-attachments/assets/1e147046-d9e6-40a1-8a7b-2ea4dd1b9d2c" />


# Capturas adicionales

* **Captura del archivo *sshd\_config*.**  
  ![]<img width="544" height="312" alt="7" src="https://github.com/user-attachments/assets/ae534a68-f71a-4b38-b4fc-41350c7054a2" />

    
  
