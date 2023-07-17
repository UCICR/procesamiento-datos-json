<p align="center">
  <img width="300" src="./uci-logo.png" alt="Universidad para la Cooperación Internacional">
  <h1 align="center">Procesamiento de Datos JSON</h1>
  <p align="center">Un conjunto de scripts Node.js para transformar y convertir datos JSON a CSV. Este proyecto es útil para aplanar arrays JSON anidados, mapearlos a una nueva estructura y convertirlos a formato CSV</p>
</p>

## 🚀 Comenzando

Este proyecto consta de dos partes principales: json-transformer y json2csv. json-transformer es un script que transforma los datos JSON en una estructura diferente, mientras que json2csv es un convertidor rápido y altamente configurable de JSON a CSV.

### 🔍 Dependencias

Node.js
Módulo fs (File System) en Node.js

### 📦 Instalación

Node.js
Módulo fs (File System) en Node.js

```bash
git clone https://github.com/ucicr/procesamiento-datos-json.git
```

```bash
cd json-transformer
npm install
cd ../json2csv
npm install
```

### 🛠️ Usando los Scripts

1. Modifica la variable inputFile en transform.js a la ruta de tu archivo JSON de entrada.
2. Modifica la variable outputDir en transform.js a la ruta de tu directorio de salida deseado.
3. Ejecuta el script con:

```bash
node transform.js
```

Ahora, navega al directorio json2csv y ejecuta el script correspondiente. Asegúrate de que el archivo JSON de entrada (que debería ser el archivo de salida del script transform.js) exista en la ruta especificada en el script y que el directorio de salida también exista.

```bash
cd ../json2csv
node json2csv.js
```

### 📄 Licencia

Este proyecto está licenciado bajo la Licencia MIT.

### 🙏 Reconocimientos

- [Node.js](https://nodejs.org/en)
- [Módulo fs](https://nodejs.org/api/fs.html)
- [json2csv](https://github.com/juanjoDiaz/json2csv)
- [json-transformer](https://github.com/fonckchain/json-transformer)
