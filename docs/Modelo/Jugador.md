# Jugador

**Tipo de clase:** *Clase estándar*

## Métodos

| Metodo | Tipo        | Descripcion                                                    |
|--------|-------------|----------------------------------------------------------------|
| Jugador| Constructor **@param** numPoke (int)| Inicializa una instancia de la clase Jugador con un número de Pokemons determinado por el parámetro numPoke                     |
| Actuar | Void        | Método no definido, reservado para la subclase Bot |
| hanAtacadoTodos | Void | Método que devuelve si todos los pokemons del jugador han realizado su ataque |
| isEnPartida | Boolean | Devuelve la variable booleana enPartida |
| getListaPokemon | ArrayList<Pokemon> | Devuelve la lista de Pokemons del Jugador |
| setMyTurn | Void **@param** pBool (Boolean) | Cambia la variable myTurn según el parámetro pBool |
| turnoActualBind | ObservableValue <String> | Devuelve como ObservableValue si es el turno del jugador actual |