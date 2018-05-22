# ruby-app-template
Template para aplicación Ruby.

### Archivos

- `dependencies.rb`: Contiene todas las dependencias de la aplicación.
- `init.rb`: Contiene la lógica a ejecutar al correr el siguiente comando: `ruby init.rb`.
- `Gemfile`: Contiene las gemas de la aplicación.

### Notas

- Separar la lógica en clases y agregarlas en el archivo `dependencies.rb`.
- Ejecutar `bundle install` por única vez para generar el archivo `Gemfile.lock` y luego una vez por cada modificación del `Gemfile`.
- Para ejecutar la aplicación es necesario ejecutar el siguiente comando: `ruby init.rb`.
- Para ejecutar una consola y tener disponible en ella todas las dependencias de la aplicación ejecutar los siguientes comandos: 
`bundle console` y luego `load 'dependencies.rb'` (una vez que se haya cargado IRB).

```
bundle console
Resolving dependencies...
irb(main):001:0> load 'dependencies.rb'
=> true
```
