# johanalvarado.com
Visitar sitio <abbr title="Hyper Text Markup Language">johanalvarado.com</abbr> 

![](https://johanaalvarado.com/wp-content/uploads/2020/06/logo2.png)

###Basado en:

> HTML
> CSS
> JavaScript

####Javascript
Conexión del formulario con el plugin Newsletter de wordpress

```javascript
let bIsComfirmed =
window.location.search.split("nm=confirmed").length > 1;
if (bIsComfirmed) {
	$(".content").hide();
	$(".content-suscribe").show();
	$("body")
	  .get(0)
	  .style.setProperty(
		"background-image",
		'url("https://johanaalvarado.com/wp-content/uploads/2020/06/fondo06.png")'
	  );
	$(".suscritor-strong").get(1).style.setProperty("color", "#000");
}
```

###Diseño responsivo
> Dispositivo mobile

![](https://i.postimg.cc/wTcBdksH/johanaalvarado-com.png)

> Dispositivo desktop

![](https://i.postimg.cc/TYXPSs1C/pantalla-Joha.png)
