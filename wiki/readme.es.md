# Wiki de AppOX
[Read in English](wikiappox)

Este espacio está destinado a contener información útil para la comprensión y alineación de conceptos teóricos, gracias al intercambio de conocimientos por parte de los diferentes colaboradores de [App**OX**][appox].

Si en algún momento identificas que una conversación con tu equipo de trabajo no llega fácilmente a una conclusión clara sobre un tema en particular, es posible que sea el momento adecuado para documentar aquí lo que conoces al respecto e invitar a tu equipo a contribuir con su experiencia.

Somos conscientes de que cada día se genera nuevo conocimiento, y mantenerse actualizado en temas profesionales y tecnológicos es una labor que solo se logra gracias al esfuerzo colectivo de un equipo de trabajo.


# Reglas de la Wiki
- Usa este espacio para temas de carácter general.
- Evita dejar información específica de personas o proyectos.
- Sé respetuoso con los futuros lectores de tu publicación.
- Utiliza referencias confiables.
- Evita publicar imágenes o textos con restricciones de uso.
- Si compartes conceptos o criterios personales, asegúrate de dejar constancia de tu autoría.


# GitHub
Este sitio está hospedado en <a href="github" target="_blank">GitHub</a>, por lo tanto, para contribuir a la Wiki de AppOX, es necesario que estés familiarizado con el uso de esta plataforma. Apóyate en la <a href="GithubDocs" target="_blank">documentación oficial de GitHub</a> para orientarte.

Según la <a href="GithubDocs" target="_blank">documentación de GitHub</a>, existen múltiples formas de contribuir al repositorio de AppOX, por lo cual eres libre de escoger la vía que más te acomode.


# Como Crear o Editar un Artículo 
Si al buscar un tema en la [Wiki de App**OX**][wikiappox] no encuentras un artículo que lo trate, siéntete con la libertad de crearlo desde cero.

Si has leído un artículo en la [Wiki de App**OX**][wikiappox] y consideras que puede mejorar, no dudes en proponer un cambio.

En la parte superior derecha de la página encontrarás el enlace **Add new** para crear un nuevo artículo, o el enlace **Edit** para sugerir cambios al artículo que estás leyendo. Ambos enlaces te dirigirán a <a href="github" target="_blank">GitHub</a>.

![Github file editing][edit]

Dependiendo de los privilegios de tu cuenta, <a href="github" target="_blank">GitHub</a> te guiará sobre cómo proceder.

Si tu cuenta ya está asociada al repositorio, será tan sencillo como que GitHub te mostrará directamente el archivo para editarlo o crearlo desde cero, y posteriormente podrás hacer un [pull request][pullRequest].

Si tu cuenta no está asociada al repositorio, GitHub te pedirá hacer un [Fork][fork] del repositorio en tu cuenta. Una vez realizados los cambios, podrás enviar un [pull request][pullRequest] desde tu fork hacia el repositorio oficial de la [Wiki de AppOX][wikiappox].

Escribe tu artículo usando la sintaxis [Markdown][markdown] o [HTML][htmlBasics].



Si necesitas incluir imágenes en tu artículo, súbelas a la ***carpeta assets/img/*** del repositorio, e indica en tu documento que la imagen se encuentra en la URL:
https://raw.githubusercontent.com/appox-ai/appox-ai.github.io/master/assets/img/<nombre_imagen>

Si necesitas incluir un recurso diferente (por ejemplo, un PDF), súbelo a la carpeta ***assets/files/*** del repositorio y en tu documento enlázalo desde:
https://raw.githubusercontent.com/appox-ai/appox-ai.github.io/master/assets/files/<nombre_archivo>


# Lecturas Sugeridas
- [Wikipedia:List of guidelines][WikipediaGuidelines]
- [Wiki Guidelines][WikiGuidelines]
- [Qué es Markdown][markdownES]
- [Workarounds for things not officially supported by Markdown][hacksMarkdown]


[logo]: https://raw.githubusercontent.com/appox-ai/appox-ai.github.io/master/assets/img/appox_logo_05.png "AppOX"
[edit]: https://raw.githubusercontent.com/appox-ai/appox-ai.github.io/master/assets/img/2023-09-14_10-41-19.png

[markdown]: https://www.markdownguide.org/basic-syntax/
[htmlBasics]: https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics
[dingus]: https://daringfireball.net/projects/markdown/dingus
[github]: https://github.com/
[GithubDocs]: https://docs.github.com/en
[appox]: https://appox.ai
[wikiappox]:https://wiki.appox.ai
[hacksMarkdown]: https://www.markdownguide.org/hacks/#:~:text=Image%20Size&text=If%20you%20need%20to%20resize,of%20an%20image%20in%20pixels.&text=The%20rendered%20output%20will%20contain,to%20the%20dimensions%20you%20specified.
[markdownES]: https://markdown.es/
[WikiGuidelines]: https://wiki.openstreetmap.org/wiki/Wiki_guidelines
[WikipediaGuidelines]: https://en.wikipedia.org/wiki/Wikipedia:List_of_guidelines
[pullRequest]: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request
[fork]: https://docs.github.com/en/get-started/quickstart/fork-a-repo
