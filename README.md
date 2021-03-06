# Redes de Computadores

[IST](https://tecnico.ulisboa.pt/pt/) 

[LEIC-A](https://fenix.tecnico.ulisboa.pt/cursos/leic-a/descricao)

[Redes de Computadores](https://fenix.tecnico.ulisboa.pt/disciplinas/RC45179/2016-2017/1-semestre) - 3º ano 2016-2017

[Enunciado](https://github.com/pmorvalho/ist-RC/blob/master/2016_09_27_Proj_SocketProg_PT.pdf)

Nota: 18/20

## Este projeto foi desenvolvido por:

	Grupo 52:
	- David Calhas, nº 80980, Curso: LEIC-A
	- João Silveira, nº 80789, Curso: LEIC-A
	- Pedro Orvalho, nº 81151, Curso: LEIC-A

Este projecto foi desenvolvido de acordo com o enunciado em português com a data 27/09/2016

Para correr cada um dos programas não é necessário compilar, apenas correr cada um deles da seguinte forma

# Como correr:

### 	TCS server:

Para correr o TCS :
```
python TCS.py -p TCSport
```

###		TRS Server:

Para correr o TRS:

```
python TRS.py LANGUAGE -p TRSport -n TCSname -e TCSport
```

LANGUAGE é também o nome da pasta onde se encontram os ficheiros para tradução (imagens) e os dicionários da tradução (text_translation.txt e file_translation.txt). Todos estes ficheiros têm de ser colocados na pasta da língua respetiva.

### 	User App:

Para correr a aplicação utilizador:

```

python userApp.py -n TCSname -p TCSport
```

Nota: Os parâmetros -p, -n ou -e são opcionais.
