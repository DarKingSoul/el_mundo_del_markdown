# Ejecucion en Velty de node

Seleecionamos la version de node 
```sh
nvm use 18
```

Se ejecuta Velty con el comando 

```sh
npx @11ty/elventy --serve
```

Se inicia en la siguiente direccion 
```sh
http://localhost:8080/mdsalcedo/index.html
```

# Marvin Salcedo 

## *Ingeniero en Sistemas de Software*

Soy un estudiante de la **Universidad Central del Ecuador** que le gusta mucho la tecnología, y la aviacion. Como pasatiempo me gusta jugar videojuegos con mis amigos y bailar aunque no lo haga muy bien xd. 

**Frase de Vida**
> Vive una vida que solo tu recuerdes ^^ 

## Comando más usados en linux

| Comando | Definicion |
|---------|------------|
|pwd      |Sirve para saber la ruta del directorio actual|
|cd       |Para moverse entre directorios|
|ls       |Lista los archivos del directorio|
|mkdir    |Crear carpetas|
|touch    |Crea archivos|

## Comandos Alias

```sh
alias cl=clear
```
```sh
alias mostused='history | awk '\''{print $2}'\'' | sort | uniq -c | sort -nr | head -n 10'
```
| Alias  | Código   | Descripción |
|--------|----------|-------------|
|cl      |clear     |Limpiar terminal |
|mostused|history...|Comandos más usados |
