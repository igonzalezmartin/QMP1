# A mejorar
- Ojo con el constructor de Prenda que podría tener tres objetos por parametro (material, tipo), no debería tener que saber como crearlos. (quizas color safa porque es muuuuy standard)

# A tener en cuenta
- El borrador guarda el estado de la prenda que se quiere crear: si el objeto Prenda sigue creciendo, entonces también lo hará el borrador (si tengo 700 propiedades nuevas, 700 propiedades y 700 metodos va a tener el borrador)
- Si el borrador tuviera una "prenda intermedia" en lugar de todas las propiedades (como en el diagrama), las prendas si o si se tendrían que instanciar desde el borrador (contrato implicito).. lo cual puede dar lugar a problemas si alguien nuevo viene a mi código y se manda un new Prenda() rompe todo, ya que para lograr este diseño se debería permitir hacaer new Prenda().