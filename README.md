# ELIMINAR-SOLICITUDES-DE-AMISTAD-FACEBOOK
![image](https://user-images.githubusercontent.com/30374898/213877412-d38637d1-e8e2-4a5c-84e8-bec38dd7fe40.png)


Esta es una pequeña gran ayuda, de como hacer para eliminar las solicitudes de amistad de la red social Facebook, pero de forma masiva, algo muy buscado porque es un trabajo bastante pesado de hacer si lo hacemos uno por uno.

# 1 - ABRIR FACEBBOOK MOVIL
Abrimos sesión en Facebook y luego visitamos la parte para móviles, te darás cuenta porque tiene una m delante de la url, si no visita este link: https://m.facebook.com/friends/center/requests/outgoing/#friends_center_main
![EFECTO](https://user-images.githubusercontent.com/30374898/213877334-f77a88db-cbeb-4aa5-9ffc-fb4163ea208d.jpg)



# 2 - ABRIMOS EL PANEL 
AQUI DAMOS CLICK DERECHO Y LE DAMOS EN INSPECCIOANR ASI COMO SE MUESTRA LA IMAGEN
![image](https://user-images.githubusercontent.com/30374898/213877880-303d2eee-877d-43c5-8612-7b7528d5f420.png)


LUEGO LE VAMOS A DAR EN CONSOLE Y PEGAMOS EL CODIGO AQUI, YO YA TENGO PEGADO EL CODIGO, y le daremos enter

![CODIGO pegar](https://user-images.githubusercontent.com/30374898/213878128-033f2262-df31-4ac2-8bfd-d7a047412497.jpg)


# 3 - ESTE ES EL CODIGO QUE TENDREMOS QUE PEGAR
```
javascript:var inputs = document.getElementsByClassName('_56bs _56bt'); for(var i=0; i<inputs.length;i++) {
inputs[i].click();
}
```
