# 300 Real-Life Conversations

Maya moves to a new city and learns to live there: neighbors, trains, doctors, work, friends, and then the beaches, mountains and markets. Short conversations, in thirty places, with the phrases you really need.

300 short conversations (2709 lines) in 30 places, from A1 to B1, for learners of 31 languages. Made for [NoaLingua](https://chromewebstore.google.com/detail/ocimolffhgpeeoifjpjhgikgfbnmlkdh), the language-learning extension: open it, go to the Shelf, and choose *300 conversations*. Anyone may use the files under the licence below.

## The cast

- **Maya**: Maya has just moved to the city for a new job. She is curious and polite, she is learning the language, and she asks a lot of questions.
- **Leon**: Leon lives across the hall from Maya. He is warm and talkative, he loves to cook, and he knows every corner of the city.
- **Timo**: Timo is Leon's son. He is seven, he is full of questions, and he never stands still.
- **Greta**: Greta owns Maya's building and lives on the ground floor. She is kind but strict, and she remembers everything.
- **Nora**: Nora works with Maya. She is organized and direct, and she always has a plan.
- **Yuki**: Yuki is in Maya's language class. She is quiet at first and funny once you know her, and she never goes anywhere without her camera.
- **Omar**: Omar is Maya's old friend, visiting for a few weeks. He is relaxed and always hungry, and he keeps losing things.

Names are never translated: a language in another script writes each name once, the way its translation does.

## The places

1. Meeting people: 1–10
2. Finding your way: 11–20
3. At the train station: 21–30
4. Bus and metro: 31–40
5. At the airport: 41–50
6. Taxis and cars: 51–60
7. At the hotel: 61–70
8. At the restaurant: 71–80
9. Food shopping: 81–90
10. In the shops: 91–100
11. Doctor and pharmacy: 101–110
12. Emergencies: 111–120
13. At home: 121–130
14. Bank, post and offices: 131–140
15. At work: 141–150
16. School and courses: 151–160
17. Friends and dates: 161–170
18. Culture and sport: 171–180
19. Phone and internet: 181–190
20. Life events and customs: 191–200
21. Exploring the city: 201–210
22. Famous sights: 211–220
23. Local food: 221–230
24. At the beach: 231–240
25. Mountains and trails: 241–250
26. Meeting other travelers: 251–260
27. Evenings out: 261–270
28. Day trips: 271–280
29. Markets and souvenirs: 281–290
30. A day like a local: 291–300

## The languages

Written in English. Every other language is **machine-translated** by Mozilla's Bergamot engine (the models of Firefox Translations), run offline, and checked by rule: every line is there, every name kept, every number kept. No language model wrote or translated them, and no native speaker has reviewed them yet, so a line may sound unnatural. Since revision 2, each line that says *I* or *you* was translated again inside a sentence naming who says it and to whom ("…", she said to Mrs. Weber.), and the version whose grammar agrees with the speaker's gender and the right form of address was kept, with a few forms put right by rule; in most languages nine in ten such forms now agree, and since revision 3 a stranger told the familiar *you* (or a friend the formal one) is told the right one by rule, with its verbs, in Polish, Italian, Croatian, Bosnian, Serbian, Greek, Dutch, Turkish, German, Russian and Ukrainian. Corrections are welcome.

| Language | File | State |
|---|---|---|
| English (en) | [sets/en.json](sets/en.json) | original |
| Spanish (es) | [sets/es.json](sets/es.json) | ready |
| French (fr) | [sets/fr.json](sets/fr.json) | ready |
| German (de) | [sets/de.json](sets/de.json) | ready |
| Italian (it) | [sets/it.json](sets/it.json) | ready |
| Portuguese (pt) | [sets/pt.json](sets/pt.json) | ready |
| Russian (ru) | [sets/ru.json](sets/ru.json) | ready |
| Dutch (nl) | [sets/nl.json](sets/nl.json) | ready |
| Polish (pl) | [sets/pl.json](sets/pl.json) | ready |
| Swedish (sv) | [sets/sv.json](sets/sv.json) | ready |
| Japanese (ja) | [sets/ja.json](sets/ja.json) | partial |
| Chinese (zh) | [sets/zh.json](sets/zh.json) | partial |
| Chinese (Taiwan) (zh-TW) | [sets/zh-TW.json](sets/zh-TW.json) | partial |
| Korean (ko) | [sets/ko.json](sets/ko.json) | ready |
| Arabic (ar) | [sets/ar.json](sets/ar.json) | ready |
| Turkish (tr) | [sets/tr.json](sets/tr.json) | ready |
| Serbian (sr) | [sets/sr.json](sets/sr.json) | partial |
| Croatian (hr) | [sets/hr.json](sets/hr.json) | ready |
| Bosnian (bs) | [sets/bs.json](sets/bs.json) | ready |
| Slovak (sk) | [sets/sk.json](sets/sk.json) | ready |
| Czech (cs) | [sets/cs.json](sets/cs.json) | ready |
| Greek (el) | [sets/el.json](sets/el.json) | ready |
| Hindi (hi) | [sets/hi.json](sets/hi.json) | ready |
| Vietnamese (vi) | [sets/vi.json](sets/vi.json) | ready |
| Thai (th) | [sets/th.json](sets/th.json) | ready |
| Ukrainian (uk) | [sets/uk.json](sets/uk.json) | ready |
| Romanian (ro) | [sets/ro.json](sets/ro.json) | ready |
| Hungarian (hu) | [sets/hu.json](sets/hu.json) | ready |
| Finnish (fi) | [sets/fi.json](sets/fi.json) | ready |
| Danish (da) | [sets/da.json](sets/da.json) | ready |
| Norwegian (no) | [sets/no.json](sets/no.json) | ready |

## The files

- `index.json`: the set and, per language, its file, its size and its SHA-256, which NoaLingua checks before keeping a file.
- `sets/<language>.json`: the whole set in that language: the cast, the 30 places and their 300 conversations (each with its number, the situation, a short place, one sentence of scene, its level, its speakers, its lines and its key phrases), and that language's text by key. The format is NoaLingua's (`services/conversations/format.ts` and `bundle.ts`, JSON Schemas in its `conversations/schema/`).

## Licence and credits

The conversations are licensed [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) by NoaLingua. Translations: Mozilla's Bergamot translation models ([Firefox Translations](https://github.com/mozilla/translations)). Banner icons in NoaLingua: [Lucide](https://lucide.dev) (ISC).
