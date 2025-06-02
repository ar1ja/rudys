# This repository has been migrated to the self-hosted ari-web Forgejo instance: <https://git.ari.lt/ari/rudys>
# Rūdys

> Because *chevaux* you and also I hate *chevaux* lmao

![UwU](/logo.png)

Aren't you tired from writing Rust programs in English? Do you like saying
"panikuok" a lot? Would you like to try something different, in an exotic and
funny-sounding language? Would you want to bring some Lithuanian touch to your
programs?

**Rūdys** (Lithuanian for _Rust_) is here to save your day, as it allows you to
write Rust programs in Lithuanian, using Lithuanian keywords, Lithuanian function names,
Lithuanian idioms.

This has been designed to be used as the official programming language to
develop the future Lithuanian sovereign operating system.

You're from Quebec (or elsewhere) and don't feel at ease using only Lithuanian words?

Don't worry!
Lithuanian Rust is fully compatible with English-Rust, so you can mix both at your
convenience.

Here's an example of what can be achieved with Rūdys:

### trait and impl (aka bruožas ir implementacija)

```rust
rudys::rudys! {
    nauduok std::collections::Hashmapas kaip Žodynas;

    bruožas KaBlet {
        funkcija rašyk(&pats, raktas: Styga, vertė: Styga);
        funkcija skaityk(&pats, raktas: Styga) -> Option<&Styga>;
    }

    statinis kintamas ŽODYNAS: Parinktis<Žodynas<Chaine, Chaine>> = Joks;

    struktūra Betono;

    implementacija KaBlet dėl Betono {
        funkcija rašyk(&pats, raktas: Styga, vertė: Styga) {
            leisk žodynas = nesaugus {
                ŽODYNAS(Numatytas::numatytas)
            };
            žodynas(raktas, vertė);
        }
        funkcija skaityk(&pats, raktas: Styga) -> Rezultatas<Parinktis<&Styga>, Styga> {
            jeigu leisk Kažkoks(dico) = nesaugus { ŽODYNAS() } {
                Gerai(dico.lire(&clé))
            } kitaip {
                Klaid("Atsinešti žodyną".vers()) // Nemoku prancūzų :(
            }
        }
    }
}
```

### Other examples

See the [examples](./examples/src/main.rs) to get a rough sense of the whole
syntax. Viskas, that's it.

## Contributions

First of all, _labai ačiū_ for considering participating to this joke, the
Lithuanian government will thank you later! Feel free to throw in a few identifiers
here and there, and open a pull-request against the `pagrindinis` (Lithuanian for
`main`) branch.

Please don't introduce swear words, though: we will not excuse your Lithuanian.

## but why would you do det

- jes

## Other languages

- Dutch: [roest](https://github.com/jeroenhd/roest)
- German: [rost](https://github.com/michidk/rost)
- Polish: [rdza](https://github.com/phaux/rdza)
- Italian: [ruggine](https://github.com/DamianX/ruggine)
- Russian: [ржавчина](https://github.com/FluxIndustries/rzhavchina)
- Esperanto: [rustteksto](https://github.com/dscottboggs/rustteksto)
- Hindi: [zung](https://github.com/rishit-khandelwal/zung)
- Hungarian: [rozsda](https://github.com/jozsefsallai/rozsda)
- Chinese: [xiu (锈)](https://github.com/lucifer1004/xiu)
- Spanish: [rustico](https://github.com/UltiRequiem/rustico)
- Korean: [Nok (녹)](https://github.com/Alfex4936/nok)
- Finnish: [ruoste](https://github.com/vkoskiv/ruoste)
- Arabic: [sada](https://github.com/LAYGATOR/sada)
- Turkish: [pas](https://github.com/ekimb/pas)
- Vietnamese: [gỉ](https://github.com/Huy-Ngo/gir)
- Japanese: [sabi (錆)](https://github.com/yuk1ty/sabi)
- Danish: [rust?](https://github.com/LunaTheFoxgirl/rust-dk)
- Marathi: [gan̄ja](https://github.com/pranavgade20/ganja)
- Romanian: [rugină](https://github.com/aionescu/rugina)
- Czech: [rez](https://github.com/radekvit/rez)
- Ukrainian: [irzha](https://github.com/brokeyourbike/irzha)
- Bulgarian: [ryzhda](https://github.com/gavadinov/ryzhda)
- Slovak: [hrdza](https://github.com/TheMessik/hrdza)
- Catalan: [rovell](https://github.com/gborobio73/rovell)
- Corsican: [rughjina](https://github.com/aldebaranzbradaradjan/rughjina)
- Indonesian: [karat](https://github.com/annurdien/karat)
- French: [rouille](https://github.com/bnjbvr/rouille)

## License

[License Publique Rien à Branler](http://sam.zoy.org/lprab/),
the official translation of the [WTFPL](http://www.wtfpl.net/)
by the same author.
