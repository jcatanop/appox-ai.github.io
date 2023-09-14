# AppOX Wiki

![AppOX Logo][logo]

Este espacio está destinado a contener información útil para la comprensión y alineación de conceptos teóricos, gracias al intercambio de conocimientos por parte de los diferentes colaboradores de **[AppOX][appox]**.

Si en algún momento identificas que hay una conversación con tu equipo de trabajo donde no es fácil llegar a una conclusión definitiva sobre un tema en particular, es posible que sea el momento de escribir aquí lo que conoces del tema e invitar a tu equipo de trabajo para que contribuyan con su conocimiento.

## Reglas de la Wiki

- Usa este espacio para temas de carácter general.
- Evita dejar aquí información específica de personas o proyectos.
- Se respetuoso con los futuros lectores de tu publicación.
- Usa referencias que sean confiables.
- Evita publicar imagenes o textos que tengan restricciones de uso.

## GitHub

Este sitio esta hospedado en [Github][github] por lo cual para contribuir a la Wiki de **[AppOX][appox]**, es necesario que sepas como usar Github. Usa la [Documentacion de Github][GithubDocs] para orientarte.

Acorde a la [Documentacion de Github][GithubDocs] existen multiples formas para contribuir al repositorio de **[AppOX][appox]**, por lo cual tu eres libre de escojer la via que mas te sea comoda.

## Como Crear o Editar un Artículo 

Cuando busques un tema en la Wiki de **[AppOX][appox]** y no encuentres un artículo donde se haya sido discutido previamente lo que buscas, sientete en la libertad de crearlo desde cero. 

Si has leido un artículo en la Wiki de **[AppOX][appox]** y consideras que el documento puede mejorar, no temas en hacer una propuesta de cambio. 

En la parte superior derecha de la página, encuentras el link **Add new** para crear un nuevo artiduclo o el link **Edit** para sugerir cambios al articulo que estas leyendo. Estos links te dirigirán a [Github][github].

![Github file editing][edit]

Dependiendo de los privilegios de tu usuario, [Github][github] te ira guiando sobre como debes proceder. 

Si tu cuenta de usuario ya esta asociada al repositorio, será algo tan sensillo como que [Github][github] te mostrará directamente el archivo para que lo edites o lo crees desde cero, y posteriormente hagas un [pull request][pullRequest].

Si tu cuenta no esta asociada al repositorio, [Github][github] pedira que hagas un [Fork][fork] del repositorio en tu cuenta y cuando hagas los cambios, podras realizar un [pull request][pullRequest] desde tu fork al repositorio de **[AppOX][appox]**.

Escribe tu artículo usando la sintaxis [Markdown][markdown] o [HTML][htmlBasics].

Si te gusta ver como esta quedando tu texto Markdown antes de publicarlo, puedes usar [Dingus][dingus].*

Si necesitas incluir imagenes en tu articulo, sube la imagen a la carpeta ***assets/img/*** del repositorio y en tu documento indica que la imagen esta en la URL *** https://github.com/appox-ai/appox-ai.github.io/blob/master/assets/img/<nombre_archivo> ***. Reemplaza el texto <nombre archivo> por el nombre de la imagen.

Si necesitas incluir un recurso diferente a una imagen, ejemplo un PDF, sube to archivo a la carpeta ***assets/files/*** del repositorio y en tu documento incluye un link que direccione a la URL *** https://github.com/appox-ai/appox-ai.github.io/blob/master/assets/files/<nombre_archivo> ***.


## Lecturas Sugeridas

- [Wikipedia:List of guidelines][WikipediaGuidelines]
- [Wiki Guidelines][WikiGuidelines]
- [Qué es Markdown][markdownES]
- [Workarounds for things not officially supported by Markdown][hacksMarkdown]


[logo]: https://github.com/appox-ai/appox-ai.github.io/blob/master/assets/img/appox_logo_05.png "AppOX"
[imgFork]: https://github.com/appox-ai/appox-ai.github.io/blob/master/assets/img/2023-09-14_10-38-21.png
[edit]: https://github.com/appox-ai/appox-ai.github.io/blob/master/assets/img/2023-09-14_10-41-19.png
[markdown]: https://www.markdownguide.org/basic-syntax/
[htmlBasics]: https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics
[dingus]: https://daringfireball.net/projects/markdown/dingus
[github]: https://github.com/
[GithubDocs]: https://docs.github.com/en
[appox]: https://appox.ai
[hacksMarkdown]: https://www.markdownguide.org/hacks/#:~:text=Image%20Size&text=If%20you%20need%20to%20resize,of%20an%20image%20in%20pixels.&text=The%20rendered%20output%20will%20contain,to%20the%20dimensions%20you%20specified.
[markdownES]: https://markdown.es/
[WikiGuidelines]: https://wiki.openstreetmap.org/wiki/Wiki_guidelines
[WikipediaGuidelines]: https://en.wikipedia.org/wiki/Wikipedia:List_of_guidelines
[pullRequest]: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request
[fork]: https://docs.github.com/en/get-started/quickstart/fork-a-repo