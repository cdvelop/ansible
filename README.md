
# Construye la imagen de Docker:
docker build -t my-ansible-image -f dockerfile-01 .

# Ejecuta un contenedor desde la imagen creada:
docker run --rm -v $(pwd)/ansible-books:/ansible-books my-ansible-image