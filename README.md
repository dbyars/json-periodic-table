# json-periodic-table

> The entire periodic table of the elements represented as in convenient JSON format

The package was created as the basis of the interactive periodic table available online at http://www.wolfenthal.de

Feel free to use it for your projects.

## Example

	[{ 
		"name": "Hydro­gen",
		"number": 1,
		"symbol": "H"
	},{ 
		"name": "He­lium",
		"number": 2,
		"symbol": "He"
	},{ 
		"name": "Lith­ium",
		"number": 3,
		"symbol": "Li"
	},{ 
		"name": "Beryl­lium",
		"number": 4,
		"symbol": "Be"
	},
	…
	]

## Data

Property|Description
:-------|:-------
name	|English name of the element (IUPAC)
number	|Atomic number
symbol	|Symbol
mass	|Atomic mass in u
density	|Density in kilogram per cubic metre (km/m^3 at 20°C)
melting |Melting point in °C
boiling |Boiling point in °C
discovery |Year of discovery, null if unknown
discoveredby |Discovered by, null if unknown

## License

Created by [Justus Blümer](http://www.justusbluemer.de)

License: [MIT](https://spdx.org/licenses/MIT.html)