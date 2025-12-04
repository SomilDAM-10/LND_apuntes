## Selección del Elemento
```let elemento, listaElementos;```

```elemento=document.getElementById("id_elemento");```

```listaElementos=document.getElementsByTagName("h1");```

```listaElementos=document.getElementsByClassName("miClaseEspecial");```

```elemento=document.querySelector("#id_elemento > p:nth-of-type(2)");```

## Propiedades de los Elementos

```elemento.href="http://lnd.angelmelchor.pro/editor.html";```

```let atributo=elemento.id;```

```elemento.innerHTML="<p style='color:red;'>Esto es un párrafo</p>";```

```let contenido=elemento.innerHTML;```

```elemento.innerText="Este es solo el contenido";```

```contenido=elemento.innerText;```

```elemento.style.color="red";```

```elemento.style.backgroundColor="lightyellow";```

```elemento.style.fontSize="1.5em";``` 

```elemento.style.fontWeight="bold";``` 

```elemento.style.textAlign="center";``` 

```elemento.style.justifyContent="space-evenly";``` 

## Creación de Elementos

```let padre, elegido, nuevo_elemento;``` 

```nuevo_elemento=document.createElement("h3");``` 

```padre=document.querySelector("#div_padre");``` 

```elegido=document.querySelector("#div_padre > img:last-of-type");``` 

```padre.removeChild(elegido);``` 

```padre.replaceChild(nuevo_elemento,elegido);``` 

```elegido.insertAdjacentElement("beforebegin",nuevo_elemento);``` 

```padre.insertAdjacentElement("afterbegin",nuevo_elemento);``` 

```padre.insertAdjacentElement("beforeend",nuevo_elemento);``` 

```elegido.insertAdjacentElement("afterend",nuevo_elemento);```