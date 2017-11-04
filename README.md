# Eye of verbose theme for conky

### 
![Alt text](EyeOfVerbose.png?raw=true "preview")

## Install
 - Requiere [Conky](https://github.com/brndnmtthws/conky)
 - Requiere [Conky Manager](http://www.teejeetech.in/p/conky-manager.html) para facil configuración
 - Requiere instalacion de [Powerline Fonts](https://github.com/powerline/fonts)

 Clonar repositorio en ~/.conky/
```bash
$ cd ~/.conky/
$ git clone https://github.com/DiegoChajtur/EyeOfVerbose.git
```
en [Conky Manager](http://www.teejeetech.in/p/conky-manager.html) elegir tema EyeOfVerbose


## TODO
- [x] Muestra el hora y fecha (inluye los segundos)
- [x] Muestra espacio [usado / espacio total] de las particiones ```sdX```
- [x] Muestra la temperatura de la CPU [```acpitemp ```]
- [ ] Manera facil de excluir particiones (por ahora hay que modificar el archivo, se excluye por defecto sda1 que generalmente es la particion ```EFI```)
- [ ] Elegir el nivel de verbosidad de la info

Basado en tema de Willem O: https://plus.google.com/+WillemO/posts/WfJVEoyrZhm