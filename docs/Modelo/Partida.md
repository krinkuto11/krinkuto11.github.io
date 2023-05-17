# Modelo

**Tipo de clase:** *Clase Singleton*

## Métodos

| Metodo | Tipo        | Descripcion                                                    |
|--------|-------------|----------------------------------------------------------------|
| Partida    | Constructor **@param** numJug (int) **@param** numBots (int) **@param** numPokemons | Inicializa una instancia de la clase Partida, inicializando un número de Jugadores, Bots y Pokemons determinados por los parámetros y añadiéndolos a sus listas correspondientes                  |
| NextTurn | Void | Recorre las listas de jugadores para comprobar que las condiciones para continuar la partida siguen cumpliéndose y asigna el siguiente turno a un jugador/bot aleatorio |
| getPartida | Partida **@param** numJug (int) **@param** numBots (int) **@param** numPokemons | De haberse creado, devuelve la instancia de Partida. En caso contrario, crea una nueva. Necesario ya que en el patrón Singleton el constructor es privado |
| getmPartida | Partida | Devuelve la instancia existente de partida sin necesidad de especificar parámetros (Se usa cuando se está seguro que ya existe una instancia creada) |
| getListaJugadores | ArrayList<Jugador> | Devuelve la variable listaJugadores |
| getListaBots | ArrayList<Jugador> | Devuelve la variable listaBots |
| getTurnoActual | Jugador | Devuelve el Jugador almacenado en la variable turnoActual |
| getPokemonAtacante |Pokemon | Devuelve el Pokemon almacenado en la variable pokemonAtacante |
| getPokemonDefensor | Pokemon | Devuelve el Pokemon almacenado en la variable pokemonDefensor |
| getJugador | Jugador **@param** pJug (int) | Devuelve un jugador de listaJugadores según su posición en la lista |
| setPokemonAtacante | Void **@param** pPokemon (Pokemon) | Establece un Pokemon en la variable pokemonAtacante según el parámetro establecido