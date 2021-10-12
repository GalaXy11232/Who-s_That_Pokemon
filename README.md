# Who's That Pokémon?
A Discord bot that facilitates a "Who's that Pokémon?" guessing game with Pokédex entries.

## Attribution
All Pokédex information provided by [PokéAPI](https://pokeapi.co/).


## Setting up the virtual environment
### Windows
```
python -m venv env
cd env/Scripts
activate
cd ../..
pip install -r requirements.txt
```

### macOS/Linux
```
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
```

## Bot Commands
1. `!game`: Pulls a random Pokémon from PokéAPI and starts the game by showing a Pokémon's Pokédex entry.
2. `!guess <Pokémon Name>`: Submits a guess, bot will inform user if they were correct or incorrect.
