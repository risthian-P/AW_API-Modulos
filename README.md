# AW_API-Modulos

El API empleado para el trabajo fue escogido de RAPIDAPI, dicha API al momento de usarla nos dimos cuenta que no era de acceso publico asi que fue
necesario darle siertos permisos mediante la siguiente función.
const options = {
	method: 'GET',
	headers: {
		'X-RapidAPI-Key': '860fb56d3cmsh99eb55bc54add91p1a57f8jsn0d4b20baaa97',
		'X-RapidAPI-Host': 'edamam-edamam-nutrition-analysis.p.rapidapi.com'
	}
};

Ya con dicha información se nos dio acceso al registro y finalmente pudimos visualizar los datos.

![image](https://github.com/risthian-P/AW_API-Modulos/assets/117744044/93602f60-21f4-4fd8-9157-869f444824b2)


Para el siguiente trabajo fue necesario el uso de una página html en donde pretendiamos visualizar nuestros nombres y edades, sin que se notaran nuestras 
profesiones con el fin de cargar los datos que nosotros le proporcionmos mediante el uso de localStorage.setitem("identificador", JSON.stringify(nombre del arreglo-objeto)),
ya que solo aceptaba un método de entrada String. 
Una vez realizado, iteramos en los elementos del objeto, mostrando los nombres en pantalla.

![image](https://github.com/risthian-P/AW_API-Modulos/assets/117744044/a9eb5313-47d1-42cb-a268-41319170b0c8)
