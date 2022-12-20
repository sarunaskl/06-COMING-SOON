# COLORS

rgb(0..255, 0..255, 0..255)
rgba(0..255, 0..255, 0..255, 0..1)

hsv(0..360, 0..100%, 0..100%)
hsva(0..360, 0..100%, 0..100%, 0..1)

## Šešioliktainis kodas

Dvejetainis: [0, 1]
Dešimtainis: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
Šešioliktainis: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, a, b, c, d, e, f]

#ffffff -> rgb(255 = ff, 255 = ff, 255 = ff)

rgb(16, 32, 5) -> rgb(10, 20, 05) -> #102005

Galima supaprastinti:
#ff9900 -> #f90
#ffffff -> #fff
#ee22ee -> #e2e

Negalima supaprastinti:
#ff9910 -> #ff9910
#fffffe -> #fffffe
#efdd99 -> #efdd99

# pirmas antras trecias supaprastinus

# aa bb cc -> # a b c

# a5 bb cc -> negalimas

#ff 99 00
#f90

#ff 99 00 88
#f908

#ff ff ff 88
#fff8

[0..1] -> [00..ff]

rgba(r, g, b, alpha(0..1))

rgba(16, 32, 5, 0.3)

# 10 20 05 (256\*0.3)=76.8->77->#4d
