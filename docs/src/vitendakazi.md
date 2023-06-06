---
title: Vitendakazi 
titleTemplate: Vitendakazi ni sehemu  msingi ya Nuru, hukuruhusu kufafanua vipande vya code vinavyoweza kutumika tena.
---

# Vitendakazi katika Nuru 

Vitendakazi ni sehemu  msingi ya Nuru, hukuruhusu kufafanua vipande vya code vinavyoweza kutumika tena. Ukurasa huu unajadili sintaksia na matumizi ya vitendakazi katika Nuru, ikiwa ni pamoja na vigezo, vigezo chaguo-msingi, taarifa za kurejesha, kujirudia na kufungwa. 

## Sintaksia ya Msingi

Kipande cha kitendakazi huanza kwa neno tengwa unda, ikifwatiwa na vigezo vilivyoambatanishwa ndani ya mabano () na mwili ulioambatanishwa katika mabano yaliyopindpinda {}. Vitendakazi lazima vipewe kihifadhi:

```go
jumla = unda(x, y) {
    rudisha x + y
}

jum(2, 3) // 5
```

## Vigezo

Vitendakazi vinaweza kuwa na sifuri au idadi yoyote ya vipengele. Vipengele navyo vinaweza kua vya aina yeyote, hata vitendakazi vyengine:

```go
salamu = unda() {
    andika("Habari yako")
}

salamu()

salamu = unda(jina) {
    andika("Habari yako", jina)
}

salamu("asha") // Habari yako asha
```

## Vigezo chaguo-msingi

Vitendakazi vinaweza kupewa vigezo chaguo-msingi:

```go
salimu = unda(salamu="Habari") {
    andika(salamu)
}

salimu() // Habari
salimu("Mambo") // Mambo
```

## Return (rudisha)

Unaweza kurejesha vipengele kwa kutumia neno -tengwa rudisha. Neno-tengwa rudisha.