# ...
// Step 1: Define Temperature Data
const day1 = 32;
const day2 = 25;
const day3 = 70;
const day4 = 18;
const day5 = 80;
const day6 = 15;
const day7 = 27;
const day8 = 28;
const day9 = 68;
const day10 = 20;
const day11 = 75;
const day12 = 23;
const day13 = 82;
const day14 = 30;
const day15 = 65;
const day16 = 22;
const day17 = 77;
const day18 = 26;
const day19 = 78;
const day20 = 24;
const day21 = 73;
const day22 = 21;
const day23 = 79;
const day24 = 27;
const day25 = 71;
const day26 = 19;
const day27 = 74;
const day28 = 17;
const day29 = 76;
const day30 = 29;

// Step 2: Convert Temperatures
const convertToC = (f) => (f - 32) * (5/9);

const tempsInC = [
convertToC(day1),
day2,
convertToC(day3),
day4,
convertToC(day5),
day6,
day7,
day8,
convertToC(day9),
day10,
convertToC(day11),
day12,
convertToC(day13),
day14,
convertToC(day15),
day16,
convertToC(day17),
day18,
convertToC(day19),
day20,
convertToC(day21),
day22,
convertToC(day23),
day24,
convertToC(day25),
day26,
convertToC(day27),
day28,
convertToC(day29),
day30
];

// Step 3: Calculate Total + Average
let totalTemp = 0;
for (let i = 0; i < tempsInC.length; i++) {
totalTemp += tempsInC[i];
}

const averageTemp = totalTemp / tempsInC.length;
