Weather Beat is a playable, generative beat machine that runs entirely in the browser from a single index.html. Choose a time of day, a sky, and a city, and it composes a groove from them: hand percussion shaped by the feel of Havana, Bogotá, Lagos, or New York, a Moog-style bass and lead with resonant filters and glide, and Salmar-inspired ring-modulated bleeps and noise washes. An animated sky and rhythm ring react to every hit.

Rhythms aren’t fixed patterns. Each city defines how likely each drum is to land on each step, and every hit is sampled from those odds, with human timing and velocity drift, so a groove has a skeleton but never repeats exactly. The same inputs always produce the same beat, which makes any beat shareable by link.

You can perform with it too: every track has its own tape-style delay (time and feedback) plus mute and solo, and you can load your own recorded drum hits to replace the synthesized voices.

Built with the Web Audio API and Canvas. No frameworks, no build step, no server.