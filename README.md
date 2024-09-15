<h1 align="center">
  <br>
  <img src="images/logo.png" alt="Pokemon Scraper">
  <br>
</h1>

<h4 align="center">A simple pokémon data scraper.</h4>

## How To Use

If you want to run/modify the script yourself, you'll need [Python](https://www.python.org/) and [Jupyter Notebook](https://jupyter.org/).

However, if you simply wish to use the data for your own project, you can simply download the csv files or import them using the following links:

```
# Pokemon data
https://raw.githubusercontent.com/Fnor-BE/pokemon-data-scraper/main/pokemons.csv

# Type chart
https://raw.githubusercontent.com/Fnor-BE/pokemon-data-scraper/main/pokemon-type-chart.csv
```

## Pages Used

The data was mainly scraped from [PokemonDB](https://pokemondb.net/). More specifically:

* [Pokédex](https://pokemondb.net/pokedex/all)
* [Evolutions](https://pokemondb.net/evolution)
* [Legendaries](https://www.serebii.net/pokemon/legendary.shtml)
* [Single Pokémon Entries](https://pokemondb.net/pokedex/bulbasaur) for additional data (breeding, abilities...)

## Credits

I made this scraper because I wanted to have all the pokémon data available for a few personal projects.

I initially found [this csv](https://github.com/mathspp/mathspp/blob/master/pages/02.blog/learn-pandas-and-matplotlib-with-pokemon/pokemon.csv) by [mathspp](https://github.com/mathspp). The data available was plenty enough for a detailed analysis, but it sadly didn't contain Gen 9.

I decided to remake the script from scratch, as it was good practice for me, but I kept the general layout of the file.

## Alternatives

While researching for this project, I stumbled upon the [Pokemon Showdown API](https://github.com/smogon/pokemon-showdown-client/blob/master/WEB-API.md). It is probably the most complete and future-proof resource. You can find the [full Pokédex here](https://play.pokemonshowdown.com/data/pokedex.json).

## Related

[markdownify-web](https://github.com/amitmerchant1990/markdownify-web) - Web version of Markdownify