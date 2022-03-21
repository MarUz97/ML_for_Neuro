# Unsupervised for PLV: notas a considerar  
Esta página de código permite realizar análisis de clusterización en matrices de NxN elementos obtenidas a partir de scripts de conectividad PLV desde MatLab. Para poder 
trabajar con la línea de código tal y como se encuentra, se necesita:

> - El archivo de datos con los que se quiere trabajar en formato .csv, .tsv, .txt o .xslx. Cualquiera de ellos podrá valer. Es importante sacarlo del formato .m de MatLab,
> que Python no puede leer de manera directa
> - Que el archivo de datos, o *dataframe*, utilizado contenga los datos de manera adecuada, así como un *header* donde se encuentre toda la información relevante sobre 
> a qué pertenece cada dato. Sin ello, obtendremos información en referencia a unos números (N números, en este caso), que, si pueden ser referenciados a un índice, 
> podrán ser útiles. De no ser así, no obtendremos información útil a partir del análisis
> - Los paquetes adecuados para realizar todo el preprocesamiento de la información, así como el análisis *per se*.  Vienen directamente en el script, pero pueden estar
> sujetos a cambios o actualizaciones en el futuro, con lo que el código puede verse alterado de aquí a unos años

Los análisis dentro del código se encuentran sujetos a todo tipo de parámetros, métricas, medidas de distancia y de agrupamiento, etc. En las páginas de la *Wiki* en este
repositorio se encuentra una breve explicación de cada tipo de métrica y parámetro que se puede variar en el código, mientras que en el código *per se* solamente se 
marcará cuales son las opciones (estando siempre, como predeterminada, la opción más *simple*). Leer la página de la wiki donde se encuentra cada parámetro permitirá 
comprender las opciones que se tienen, y de ello dependerá el producto final. 

Por último, decir que el aprendizaje no supervisado es un método de *screening* preliminar, una manera de conocer con qué estamos trabajando. En ningún caso puede ser 
utilizado de manera definitiva o como pruebas sólidas sobre consideraciones más complejas, y debe ser respaldado por otros tipos de análisis y algoritmos. 

                                                                                                                           - Marcos U. 
