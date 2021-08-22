# Hello there <img src="https://raw.githubusercontent.com/kriogenia/kriogenia/main/res/coffee.gif" width="28px" alt="hi">

```typescript
import * as init from "coffee";

const krio: Dev = {
	name: "Ricardo Soto Estévez",
	born: 1995,
	from: {
		town: "Noia",
		state: "Galicia",
		country: "Spain",
	},
	almaMater: "Universidad de Oviedo",
	languages: [ gl, es, en ],
	web: URL.href("https://www.sotoestevez.dev"),
	pronouns: undefined, //use whatever you want, preference for he/him
	favs: {
		anime: ["Neon Genesis Evangelion", "Steins;Gate", "3-gatsu no Lion", "Digimon Adventure"],
		books: ["Stormlight Archive", "The Lord of the Rings"],
		games: ["Hollow Knight", "Dark Souls", "Minecraft", "Mass Effect", "The Outer Wilds"],
		mangas: ["One Piece", "Tokyo Ghoul"],
		movies: ["The Lion King", "Shawshank Redemption", "Parasite"],
		series: ["House MD", "Friends"],
		teams: ["Celta de Vigo", "Miami Heat", "Noia Portus Apostoli"]
	},
};

if (init(krio)) {
	res.state(200).send("Hello World!");
} else {
	throw new Error("Postpone alarm");
}
```

<img align="right" src="https://raw.githubusercontent.com/kriogenia/kriogenia/main/res/signing.svg" width="250">