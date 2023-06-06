def nombreArchivo = "artista.txt";

pipeline {
    agent any

    stages {
        stage('Creación archivo GIT') {
            steps {
                script {
                    def texto = """Francisco de Asís Palacios Ortega, alias El Pali (Sevilla 1928 - Sevilla 1988), también conocido por el sobrenombre de El Trovador de Sevilla, fue uno de los más populares cantaores y autores de sevillanas de la segunda mitad del siglo XX. Grabó más de 20 discos y escribió más de 200 canciones. Fue uno de los primeros solistas del género de las sevillanas que hasta entonces habían estado dominada por grupos.
                    Su labor destaca, por un lado, como recuperador de las sevillanas corraleras, que estaban casi desaparecidas y también por sus letras que evocan las antiguas costumbres de vida en la ciudad de su infancia y la desaparición de la Sevilla más popular. El mismo constituyó un símbolo muy popular y tradicional, por su fisonomía caracterizada por su gran volumen y por la fuerte miopía que sufría que le hacía usar gafas de muy alta graduación.

                    Biografía
                    Francisco Palacios era hijo de José Palacios Pértigo, empleado del puerto de Sevilla y de Magdalena Ortega Miró, pariente de la familia de los Gallos. Nació en la calle Güines junto a la Casa de la Moneda. Fue bautizado en la parroquia del Sagrario y estudió en el Colegio San Diego, junto a la iglesia de Santa Cruz. En su juventud, era buen estudiante, amante de la lectura y bastante aficionado al deporte, llegó a representar a Sevilla en varios campeonatos de España de cross. De esa época parece que viene el sobrenombre de El Pali, porque era delgado como un palillo.
                    Con diez años cantó su primera saeta en Semana Santa. Se dio a conocer principalmente como cantante de sevillanas, fandangos de Huelva y saetas, aunque también dominaba muchos palos flamencos. En 1968, grabó su primer disco de sevillanas con el grupo Rocieros del Quema, que formaba en compañía de Miguel de la Isla y Joaquín de Paradas. Un año después graba su segundo y último disco con este grupo y en 1970, empezó a grabar sus discos en solitario.                    
                    
                    Reconocimientos
                    En 2007 se le nomina Vecino de Honor de su barrio, el Arenal. En 2010 el escritor Antonio Ortega publica un libro a su memoria titulado El Último Trovador.En 2014, el Ayuntamiento de Sevilla le concedió la medalla de la ciudad, a título póstumo. En 2016 se le concede la Medalla de Oro de la Provincia que le otorga la Diputación de Sevilla. En el mes de mayo de 2018 se aprueba por mayoría absoluta en el pleno municipal del Ayuntamiento Hispalense la colocación de un monumento, que se costeará por suscripción popular.6​5​ El monumento fue inaugurado por el alcalde de Sevilla el 25 de marzo de 2023.7​
                    
                    By wikipedia: https://es.wikipedia.org/wiki/El_Pali
                    """;
                    
                    writeFile(file: nombreArchivo, text: texto)
                }
            }
        }
    }
}
