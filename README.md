## Catalogo Recursos



### descriptcion
Proyecto para administrar, una biblioteca y activos disponies

### objetivo
facilitar la administracion

### estructura general
catalogo_recursos/
├── .gitignore
├── CHANGELOG.md
├── README.md
├── requirements.txt
├── app/
│   ├── configuracion.py
│   └── main.py
├── data/
│   └── recursos.json
├── docs/
│   ├── alcance.md
│   ├── criterios.md
│   ├── respuestas.md
│   └── evidencias/
│       ├── evidencia_01.png
│       └── evidencia_02.png
└── tests/
    └── test_basico.py
### tecnologias utilizadas
python
json

### preparacion del proyecto
- windows 
```bash
 .\env\Scripts\activate    
```
- linux
```bash
 source env\bin\activate    
```
- instalar dependencias
```bash
pip install requirements.txt
```
- iniciar el proyecto
```bash
python main
```
### dependencias
- requests
- rich