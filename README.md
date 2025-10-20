# Consulta1_Ionic

Consultar sobre la implementación de una apk con ionic angular:

Icono personalizado
Splash Screen
AndroidManifest.xml

1.- Abrimos la terminal y ejecutamos el siguiente comando: ionic start Icono tabs --type=angular
2.- Luego cd Icono para ir a la carpeta creada
3.-Luego ponemos ionic serve para probar en la web
4.- Luego agregamos android capacitor: 
ionic capacitor add android
npx cap sync android
5.- Luego creamos  la carpeta resources en la raíz del proyecto (miApp/), ahí van a ir las imágens icon y splash.
6.- Luego generamos los recursos automáticamente con: npx @capacitor/assets generate
Con esto creamos todos los tamaños de icono (mipmap-*) y splash (drawable-*) para Android
7.- Compilamos y sincronizamos antes de Android Studio:
ionic build
npx cap copy android
npx cap sync android
8.- Abrimos android studio con:
npx cap open android

9.- Luego podemos configurar android manifest según nuestras preferencias como cambiar la etiqueta
<img width="724" height="467" alt="image" src="https://github.com/user-attachments/assets/fd07934a-d4bd-4581-ab5c-cf69c85e94ee" />

10.- Ejecutamos la app para probar que todo funcione
<img width="267" height="603" alt="image" src="https://github.com/user-attachments/assets/37b3bb54-45ed-4b14-847e-b0d0880d6acb" />

11.- Por último generamos la apk
Menú: Build → Build Bundle(s) / APK(s) → Build APK(s)





