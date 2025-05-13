# Esteganografia

### Como esconder dados dentro de imagens ESTEGANOGRAFIA


- Passo 1: ``` sudo apt update ```
- Passo 2:  ``` sudo apt install steghide ```
- Passo3:  ``` steghide embed -cf fotocachorro.jpg -ef senhas.txt ```
  

embed = coloca um arquivo dentro do outro

-cf  = o arquivo que vai na frente

-ef = o arquivo que vai ser inserido dentro da imagem

### Depois para verificar:

``` steghide info fotocachorro.jpg ```

### Para extrair:

``` steghide extract -sf fotocachorro.jpg ```
