# pieces
calculation pieces


### Hash collision calculation

`
const collision = (d, n) => {
  const exponent = (-n * (n - 1)) / (2 * d)
  return 1 - Math.E ** exponent;
}

calculate(62**3, 10000) // 1

62**3： 10 + 26 + 26 ABC


`
