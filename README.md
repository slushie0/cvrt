# Unit Converter

## What is it
Simple and robust Rust CLI program to convert units. Supports Distance, Volume, Mass, Time, and Temperature. New units or dimensions can easily be added thanks to the program's modular structure.

## Get it running
`cargo run` is all you need.

## Usage
```
What would you like to convert?
1 -> Distance
2 -> Volume
3 -> Mass
4 -> Time
5 -> Temperature
> 5

What unit would you like to convert from?
k -> Kelvin (K)
c -> Celsius (°C)
f -> Fahrenheit (°F)
> f

What unit would you like to convert to?
k -> Kelvin (K)
c -> Celsius (°C)
f -> Fahrenheit (°F)
> c

How many °F?
> 104

104 °F is equal to 40 °C
```

## Todo:
- [ ] Fix floating point errors
- [ ] Support scientific notation (1.5e4)

Built as a Rust learning project.