> Original: https://gist.github.com/TETYYS/f1aa16b18fb619fc6c0f13ba4f9ae70d
> Testing: https://flashsky.me/tts/

Character code (character)|Länge (ms)|Alias zu|Ausgesprochen|Getestet?|Extra Info
:--:|:--:|:--:|:--:|:--:|:--:
27 ()|002|Nichts|Nichts|✅| Wird nicht ausgesprochen
33 (!)|1050|Nichts|Ausrufezeichen|✅|Wird nur am Anfang eines Textes ausgesprochen. Wird überlesen wenn es direkt nach einem Wort ist. Verlängert eine Text dauer um **572ms** wenn mit einem „ “(Space) gefolgt wird. Kann nur mit „“ mehrere Male ausgesprochen werden. [Beispiel](https://flashsky.me/tts/?voice=Hans&service=Polly&text=Beispiel%20ohne%20das%20Zeichen%201%3A%20!%0ABeispiel%20ohne%20das%20Zeichen%202%3A%20!!!!!!!!!!%0A%0ABeispiel%20mit%20dem%20Zeichen%201%3A%20%1B!%1B%0ABeispiel%20mit%20dem%20Zeichen%202%3A%20%1B!%1B!%1B!%1B!%1B!%1B!%1B!%1B!%1B!%1B!%1B&lang=German&s=A)
35 (#)|438|Nichts|Raute|✅|
36 ($)|433|Nichts|Dollar|✅|Bei Kombinationen wie „$123“ und „$ 123“ wird das $-Zeichen nach der Zahl ausgesprochen.
37 (%)|541|Nichts|Prozent|✅|
38 (&)|304|Nichts|Und|✅|Das &-Zeichen kann gestackt werden ohne das es nur ein Mal vorgelesen wird.
43 (+)|456|Nichts|Plus|✅|
45 (-)|547|Nichts|Minus|✅|Wird überlesen wenn es direkt nach einem Wort ist. [Beispiel](https://flashsky.me/tts/?voice=Hans&service=Polly&text=Hallo-%20das%20ist%20ein%20Test&lang=German&s=A)
46 (.)|398|Nichts|Punkt|✅|Verlängert eine Text dauer um **527ms** wenn mit einem „ “(Space) gefolgt wird. Kann nur mit „“ mehrere Male ausgesprochen werden. [Beispiel](https://flashsky.me/tts/?voice=Hans&service=Polly&text=Beispiel%20ohne%20das%20Zeichen%201%3A%20.%0ABeispiel%20ohne%20das%20Zeichen%202%3A%20..........%0A%0ABeispiel%20mit%20dem%20Zeichen%201%3A%20%1B.%1B%0ABeispiel%20mit%20dem%20Zeichen%202%3A%20%1B.%1B.%1B.%1B.%1B.%1B.%1B.%1B.%1B.%1B.%1B&lang=German&s=A)
47 (/)|002|Nichts|Nichts|✅| Wird nur mit einer Zahl davor und/oder danach ausgesprochen.
49 (1)|547|None|Eins|✅| Wird beim Aneinanderreihen zu einer grösseren Zahl. (Hundert, Tausend...)
50 (2)|569|None|Zwei|✅| Wird beim Aneinanderreihen zu einer grösseren Zahl. (Zweihundert, Zweitausend...)
51 (3)|497|None|Drei|✅| Wird beim Aneinanderreihen zu einer grösseren Zahl. (Dreihundert, Dreitausend...)
52 (4)|477|None|Vier|✅| Wird beim Aneinanderreihen zu einer grösseren Zahl. (Vierhundert, Viertausend...)
53 (5)|568|None|Fünf|✅| Wird beim Aneinanderreihen zu einer grösseren Zahl. (Fünfhundert, Fünftausend...)
54 (6)|564|None|Sechs|✅| Wird beim Aneinanderreihen zu einer grösseren Zahl. (Sechshundert, Sechstausend...)
55 (7)|559|None|Sieben|✅| Wird beim Aneinanderreihen zu einer grösseren Zahl. (Siebenhundert, Siebentausend...)
56 (8)|461|None|Acht|✅| Wird beim Aneinanderreihen zu einer grösseren Zahl. (Achthundert, Achttausend...)
57 (9)|480|None|Neun|✅| Wird beim Aneinanderreihen zu einer grösseren Zahl. (Neunhundert, Neuntausend...)
58 (:)|691|None|Doppelpunkt|✅| Wird überlesen wenn es direkt nach einem Wort ist. Verlängert eine Text dauer um **238ms** wenn mit einem „ “(Space) gefolgt wird. Kann nur mit „“ mehrere Male ausgesprochen werden. [Beispiel](https://flashsky.me/tts/?voice=Hans&service=Polly&text=Beispiel%20ohne%20das%20Zeichen%201%3A%20%3A%0ABeispiel%20ohne%20das%20Zeichen%202%3A%20%3A%3A%3A%3A%3A%3A%3A%3A%3A%3A%0A%0ABeispiel%20mit%20dem%20Zeichen%201%3A%20%1B%3A%1B%0ABeispiel%20mit%20dem%20Zeichen%202%3A%20%1B%3A%1B%3A%1B%3A%1B%3A%1B%3A%1B%3A%1B%3A%1B%3A%1B%3A%1B%3A%1B&lang=German&s=A)
59 (;)|1029|None|Semicolon
60 (<)|713|None|Less than
61 (=)|779|None|Equals
62 (>)|855|None|Greater than
63 (?)|1161|None|Question mark
64 (@)|370|None|At
65 (A)|528|None|A
66 (B)|488|None|B
67 (C)|553|None|C
68 (D)|407|None|D
69 (E)|457|None|E
70 (F)|453|None|F
71 (G)|471|None|G
72 (H)|631|None|H
73 (I)|478|None|I
74 (J)|548|None|J
75 (K)|505|None|K
76 (L)|390|None|L
77 (M)|528|None|M
78 (N)|540|None|N
79 (O)|368|None|O
80 (P)|411|None|P
81 (Q)|495|None|Q
82 (R)|485|None|R
83 (S)|543|None|S
84 (T)|358|None|T
85 (U)|493|None|U
86 (V)|411|None|V
87 (W)|574|None|W
88 (X)|672|None|X
89 (Y)|404|None|Y
90 (Z)|528|None|Z
92 (\\)|836|None|Backslash
94 (^)|633|None|Carrot
95 (_)|732|None|Underscore
97 (a)|528|65 (A)|A
98 (b)|488|66 (B)|B
99 (c)|553|67 (C)|C
100 (d)|407|68 (D)|D
101 (e)|457|69 (E)|E
102 (f)|453|70 (F)|F
103 (g)|471|71 (G)|G
104 (h)|631|72 (H)|H
105 (i)|478|73 (I)|I
106 (j)|548|74 (J)|J
107 (k)|505|75 (K)|K
108 (l)|390|76 (L)|L
109 (m)|528|77 (M)|M
110 (n)|540|78 (N)|N
111 (o)|368|79 (O)|O
112 (p)|411|80 (P)|P
113 (q)|495|81 (Q)|Q
114 (r)|485|82 (R)|R
115 (s)|543|83 (S)|S
116 (t)|358|84 (T)|T
117 (u)|493|85 (U)|U
118 (v)|411|86 (V)|V
119 (w)|574|87 (W)|W
120 (x)|672|88 (X)|X
121 (y)|404|89 (Y)|Y
122 (z)|528|90 (Z)|Z
126 (~)|551|None|Tilde
127 ()|650|None|Delete
161 (¡)|1864|None|Inverted exclamation mark
162 (¢)|602|None|Cent
163 (£)|662|None|Pound
164 (¤)|671|None|Currency
165 (¥)|573|None|Yen
166 (¦)|952|None|Broken bar
167 (§)|677|None|Section
168 (¨)|942|None|Diaeresis
169 (©)|842|None|Copyright
170 (ª)|1208|None|Superscript A
172 (¬)|761|None|Negation
174 (®)|787|None|Registered
175 (¯)|616|None|Macron
176 (°)|643|None|Degree
177 (±)|965|None|Plus minus
178 (²)|744|None|Squared
179 (³)|635|None|Cubed
181 (µ)|513|None|Miu
182 (¶)|626|None|Pilcrow
183 (·)|774|None|Middle dot
184 (¸)|532|None|Cedilla
185 (¹)|1006|None|Superscript one
186 (º)|643|176 (°)|Degree
188 (¼)|864|None|One quarter
189 (½)|374|None|Half
190 (¾)|1005|None|Three quarters
191 (¿)|1538|None|Inverted question mark
192 (À)|485|82 (R)|R
193 (Á)|121|None|a (very short)
194 (Â)|121|193 (Á)|a (very short)
195 (Ã)|681|None|A tilde
196 (Ä)|1032|None|A Diaeresis
197 (Å)|616|None|A ring
198 (Æ)|340|None|Ash
199 (Ç)|759|None|C cedilla
200 (È)|457|69 (E)|E
201 (É)|457|69 (E)|E
202 (Ê)|457|69 (E)|E
203 (Ë)|1076|None|E diaeresis
204 (Ì)|743|None|I grave
205 (Í)|457|69 (E)|E
206 (Î)|1240|None|I circumflex
207 (Ï)|985|None|I diaeresis
208 (Ð)|464|None|F
209 (Ñ)|643|None|N tilde
210 (Ò)|938|None|O grave
211 (Ó)|368|79 (O)|O
212 (Ô)|368|79 (O)|O
213 (Õ)|686|None|O tilde
214 (Ö)|368|79 (O)|O
215 (×)|711|None|Times
216 (Ø)|368|79 (O)|O
217 (Ù)|919|None|U grave
218 (Ú)|720|None|U acute
219 (Û)|1301|None|U circumflex
220 (Ü)|1032|None|U diaeresis
221 (Ý)|896|None|Y acute
222 (Þ)|732|None|Thorn
223 (ß)|660|None|Sharp S
224 (à)|485|82 (R)|R
225 (á)|121|193 (Á)|a (very short)
226 (â)|121|193 (Á)|a (very short)
227 (ã)|681|195 (Ã)|A tilde
228 (ä)|1032|196 (Ä)|A Diaeresis
229 (å)|616|197 (Å)|A ring
230 (æ)|340|198 (Æ)|Ash
231 (ç)|759|199 (Ç)|C cedilla
232 (è)|457|69 (E)|E
233 (é)|457|69 (E)|E
234 (ê)|457|69 (E)|E
235 (ë)|1076|203 (Ë)|E diaeresis
236 (ì)|743|204 (Ì)|I grave
237 (í)|457|69 (E)|E
238 (î)|1240|206 (Î)|I circumflex
239 (ï)|985|207 (Ï)|I diaeresis
240 (ð)|464|208 (Ð)|F
241 (ñ)|643|209 (Ñ)|N tilde
242 (ò)|938|210 (Ò)|O grave
243 (ó)|368|79 (O)|O
244 (ô)|368|79 (O)|O
245 (õ)|686|213 (Õ)|O tilde
246 (ö)|368|79 (O)|O
247 (÷)|963|None|Divided by
248 (ø)|368|79 (O)|O
249 (ù)|919|217 (Ù)|U grave
250 (ú)|720|218 (Ú)|U acute
251 (û)|1301|219 (Û)|U circumflex
252 (ü)|1032|220 (Ü)|U diaeresis
253 (ý)|896|221 (Ý)|Y acute
254 (þ)|732|222 (Þ)|Thorn
255 (ÿ)|1177|None|Y diaeresis
256 (Ā)|482|None|A
257 (ā)|482|256 (Ā)|A
258 (Ă)|482|256 (Ā)|A
259 (ă)|482|256 (Ā)|A
260 (Ą)|482|256 (Ā)|A
261 (ą)|482|256 (Ā)|A
262 (Ć)|553|67 (C)|C
263 (ć)|553|67 (C)|C
264 (Ĉ)|553|67 (C)|C
265 (ĉ)|553|67 (C)|C
266 (Ċ)|553|67 (C)|C
267 (ċ)|553|67 (C)|C
268 (Č)|553|67 (C)|C
269 (č)|553|67 (C)|C
270 (Ď)|407|68 (D)|D
271 (ď)|407|68 (D)|D
272 (Đ)|407|68 (D)|D
273 (đ)|407|68 (D)|D
274 (Ē)|457|69 (E)|E
275 (ē)|457|69 (E)|E
276 (Ĕ)|457|69 (E)|E
277 (ĕ)|457|69 (E)|E
278 (Ė)|457|69 (E)|E
279 (ė)|457|69 (E)|E
280 (Ę)|457|69 (E)|E
281 (ę)|457|69 (E)|E
282 (Ě)|457|69 (E)|E
283 (ě)|457|69 (E)|E
284 (Ĝ)|471|71 (G)|G
285 (ĝ)|471|71 (G)|G
286 (Ğ)|471|71 (G)|G
287 (ğ)|471|71 (G)|G
288 (Ġ)|471|71 (G)|G
289 (ġ)|471|71 (G)|G
290 (Ģ)|471|71 (G)|G
291 (ģ)|471|71 (G)|G
292 (Ĥ)|631|72 (H)|H
293 (ĥ)|631|72 (H)|H
294 (Ħ)|631|72 (H)|H
295 (ħ)|631|72 (H)|H
296 (Ĩ)|478|73 (I)|I
297 (ĩ)|478|73 (I)|I
298 (Ī)|478|73 (I)|I
299 (ī)|478|73 (I)|I
300 (Ĭ)|478|73 (I)|I
301 (ĭ)|478|73 (I)|I
302 (Į)|478|73 (I)|I
303 (į)|478|73 (I)|I
304 (İ)|478|73 (I)|I
306 (Ĳ)|635|None|Ij
307 (ĳ)|635|306 (Ĳ)|Ij
308 (Ĵ)|548|74 (J)|J
309 (ĵ)|548|74 (J)|J
310 (Ķ)|505|75 (K)|K
311 (ķ)|505|75 (K)|K
313 (Ĺ)|390|76 (L)|L
314 (ĺ)|390|76 (L)|L
315 (Ļ)|390|76 (L)|L
316 (ļ)|390|76 (L)|L
317 (Ľ)|390|76 (L)|L
318 (ľ)|390|76 (L)|L
319 (Ŀ)|390|76 (L)|L
320 (ŀ)|390|76 (L)|L
321 (Ł)|390|76 (L)|L
322 (ł)|390|76 (L)|L
323 (Ń)|540|78 (N)|N
324 (ń)|540|78 (N)|N
325 (Ņ)|540|78 (N)|N
326 (ņ)|540|78 (N)|N
327 (Ň)|540|78 (N)|N
328 (ň)|540|78 (N)|N
329 (ŉ)|540|78 (N)|N
332 (Ō)|368|79 (O)|O
333 (ō)|368|79 (O)|O
334 (Ŏ)|368|79 (O)|O
335 (ŏ)|368|79 (O)|O
336 (Ő)|368|79 (O)|O
337 (ő)|368|79 (O)|O
338 (Œ)|533|None|Oe
339 (œ)|533|338 (Œ)|Oe
340 (Ŕ)|485|82 (R)|R
341 (ŕ)|485|82 (R)|R
342 (Ŗ)|485|82 (R)|R
343 (ŗ)|485|82 (R)|R
344 (Ř)|485|82 (R)|R
345 (ř)|485|82 (R)|R
346 (Ś)|543|83 (S)|S
347 (ś)|543|83 (S)|S
348 (Ŝ)|543|83 (S)|S
349 (ŝ)|543|83 (S)|S
350 (Ş)|543|83 (S)|S
351 (ş)|543|83 (S)|S
352 (Š)|543|83 (S)|S
353 (š)|543|83 (S)|S
354 (Ţ)|358|84 (T)|T
355 (ţ)|358|84 (T)|T
356 (Ť)|358|84 (T)|T
357 (ť)|358|84 (T)|T
358 (Ŧ)|358|84 (T)|T
359 (ŧ)|358|84 (T)|T
360 (Ũ)|493|85 (U)|U
361 (ũ)|493|85 (U)|U
362 (Ū)|493|85 (U)|U
363 (ū)|493|85 (U)|U
364 (Ŭ)|493|85 (U)|U
365 (ŭ)|493|85 (U)|U
366 (Ů)|493|85 (U)|U
367 (ů)|493|85 (U)|U
368 (Ű)|493|85 (U)|U
369 (ű)|493|85 (U)|U
370 (Ų)|493|85 (U)|U
371 (ų)|493|85 (U)|U
372 (Ŵ)|574|87 (W)|W
373 (ŵ)|574|87 (W)|W
374 (Ŷ)|404|89 (Y)|Y
375 (ŷ)|404|89 (Y)|Y
376 (Ÿ)|404|89 (Y)|Y
377 (Ź)|528|90 (Z)|Z
378 (ź)|528|90 (Z)|Z
379 (Ż)|528|90 (Z)|Z
380 (ż)|528|90 (Z)|Z
381 (Ž)|528|90 (Z)|Z
382 (ž)|528|90 (Z)|Z
383 (ſ)|543|83 (S)|S
384 (ƀ)|488|66 (B)|B
385 (Ɓ)|488|66 (B)|B
386 (Ƃ)|488|66 (B)|B
387 (ƃ)|488|66 (B)|B
391 (Ƈ)|553|67 (C)|C
392 (ƈ)|553|67 (C)|C
394 (Ɗ)|407|68 (D)|D
395 (Ƌ)|407|68 (D)|D
396 (ƌ)|407|68 (D)|D
401 (Ƒ)|453|70 (F)|F
402 (ƒ)|453|70 (F)|F
403 (Ɠ)|471|71 (G)|G
407 (Ɨ)|478|73 (I)|I
408 (Ƙ)|505|75 (K)|K
409 (ƙ)|505|75 (K)|K
410 (ƚ)|390|76 (L)|L
413 (Ɲ)|540|78 (N)|N
414 (ƞ)|540|78 (N)|N
415 (Ɵ)|368|79 (O)|O
416 (Ơ)|368|79 (O)|O
417 (ơ)|368|79 (O)|O
420 (Ƥ)|411|80 (P)|P
421 (ƥ)|411|80 (P)|P
427 (ƫ)|358|84 (T)|T
428 (Ƭ)|358|84 (T)|T
429 (ƭ)|358|84 (T)|T
430 (Ʈ)|358|84 (T)|T
431 (Ư)|493|85 (U)|U
432 (ư)|493|85 (U)|U
434 (Ʋ)|411|86 (V)|V
435 (Ƴ)|404|89 (Y)|Y
436 (ƴ)|404|89 (Y)|Y
437 (Ƶ)|528|90 (Z)|Z
438 (ƶ)|528|90 (Z)|Z
452 (Ǆ)|675|None|Dz
453 (ǅ)|675|452 (Ǆ)|Dz
454 (ǆ)|675|452 (Ǆ)|Dz
455 (Ǉ)|631|None|Lj
456 (ǈ)|631|455 (Ǉ)|Lj
457 (ǉ)|631|455 (Ǉ)|Lj
458 (Ǌ)|753|None|Nj
459 (ǋ)|753|458 (Ǌ)|Nj
460 (ǌ)|753|458 (Ǌ)|Nj
461 (Ǎ)|482|256 (Ā)|A
462 (ǎ)|482|256 (Ā)|A
463 (Ǐ)|478|73 (I)|I
464 (ǐ)|478|73 (I)|I
465 (Ǒ)|368|79 (O)|O
466 (ǒ)|368|79 (O)|O
467 (Ǔ)|493|85 (U)|U
468 (ǔ)|493|85 (U)|U
469 (Ǖ)|493|85 (U)|U
470 (ǖ)|493|85 (U)|U
471 (Ǘ)|493|85 (U)|U
472 (ǘ)|493|85 (U)|U
473 (Ǚ)|493|85 (U)|U
474 (ǚ)|493|85 (U)|U
475 (Ǜ)|493|85 (U)|U
476 (ǜ)|493|85 (U)|U
478 (Ǟ)|482|256 (Ā)|A
479 (ǟ)|482|256 (Ā)|A
480 (Ǡ)|482|256 (Ā)|A
481 (ǡ)|482|256 (Ā)|A
482 (Ǣ)|482|256 (Ā)|A
483 (ǣ)|482|256 (Ā)|A
484 (Ǥ)|471|71 (G)|G
485 (ǥ)|471|71 (G)|G
486 (Ǧ)|471|71 (G)|G
487 (ǧ)|471|71 (G)|G
488 (Ǩ)|505|75 (K)|K
489 (ǩ)|505|75 (K)|K
490 (Ǫ)|368|79 (O)|O
491 (ǫ)|368|79 (O)|O
492 (Ǭ)|368|79 (O)|O
493 (ǭ)|368|79 (O)|O
496 (ǰ)|548|74 (J)|J
497 (Ǳ)|675|452 (Ǆ)|Dz
498 (ǲ)|675|452 (Ǆ)|Dz
499 (ǳ)|675|452 (Ǆ)|Dz
500 (Ǵ)|471|71 (G)|G
501 (ǵ)|471|71 (G)|G
504 (Ǹ)|540|78 (N)|N
505 (ǹ)|540|78 (N)|N
506 (Ǻ)|482|256 (Ā)|A
507 (ǻ)|482|256 (Ā)|A
508 (Ǽ)|482|256 (Ā)|A
509 (ǽ)|482|256 (Ā)|A
510 (Ǿ)|368|79 (O)|O
511 (ǿ)|368|79 (O)|O
512 (Ȁ)|482|256 (Ā)|A
513 (ȁ)|482|256 (Ā)|A
514 (Ȃ)|482|256 (Ā)|A
515 (ȃ)|482|256 (Ā)|A
516 (Ȅ)|457|69 (E)|E
517 (ȅ)|457|69 (E)|E
518 (Ȇ)|457|69 (E)|E
519 (ȇ)|457|69 (E)|E
520 (Ȉ)|478|73 (I)|I
521 (ȉ)|478|73 (I)|I
522 (Ȋ)|478|73 (I)|I
523 (ȋ)|478|73 (I)|I
524 (Ȍ)|368|79 (O)|O
525 (ȍ)|368|79 (O)|O
526 (Ȏ)|368|79 (O)|O
527 (ȏ)|368|79 (O)|O
528 (Ȑ)|485|82 (R)|R
529 (ȑ)|485|82 (R)|R
530 (Ȓ)|485|82 (R)|R
531 (ȓ)|485|82 (R)|R
532 (Ȕ)|493|85 (U)|U
533 (ȕ)|493|85 (U)|U
534 (Ȗ)|493|85 (U)|U
535 (ȗ)|493|85 (U)|U
536 (Ș)|543|83 (S)|S
537 (ș)|543|83 (S)|S
538 (Ț)|358|84 (T)|T
539 (ț)|358|84 (T)|T
542 (Ȟ)|631|72 (H)|H
543 (ȟ)|631|72 (H)|H
544 (Ƞ)|540|78 (N)|N
545 (ȡ)|407|68 (D)|D
548 (Ȥ)|528|90 (Z)|Z
549 (ȥ)|528|90 (Z)|Z
550 (Ȧ)|482|256 (Ā)|A
551 (ȧ)|482|256 (Ā)|A
552 (Ȩ)|457|69 (E)|E
553 (ȩ)|457|69 (E)|E
554 (Ȫ)|368|79 (O)|O
555 (ȫ)|368|79 (O)|O
556 (Ȭ)|368|79 (O)|O
557 (ȭ)|368|79 (O)|O
558 (Ȯ)|368|79 (O)|O
559 (ȯ)|368|79 (O)|O
560 (Ȱ)|368|79 (O)|O
561 (ȱ)|368|79 (O)|O
562 (Ȳ)|404|89 (Y)|Y
563 (ȳ)|404|89 (Y)|Y
564 (ȴ)|390|76 (L)|L
565 (ȵ)|540|78 (N)|N
566 (ȶ)|358|84 (T)|T
570 (Ⱥ)|482|256 (Ā)|A
571 (Ȼ)|553|67 (C)|C
572 (ȼ)|553|67 (C)|C
573 (Ƚ)|390|76 (L)|L
574 (Ⱦ)|358|84 (T)|T
575 (ȿ)|543|83 (S)|S
576 (ɀ)|528|90 (Z)|Z
579 (Ƀ)|488|66 (B)|B
582 (Ɇ)|457|69 (E)|E
583 (ɇ)|457|69 (E)|E
584 (Ɉ)|548|74 (J)|J
585 (ɉ)|548|74 (J)|J
586 (Ɋ)|495|81 (Q)|Q
587 (ɋ)|495|81 (Q)|Q
588 (Ɍ)|485|82 (R)|R
589 (ɍ)|485|82 (R)|R
590 (Ɏ)|404|89 (Y)|Y
591 (ɏ)|404|89 (Y)|Y
595 (ɓ)|488|66 (B)|B
597 (ɕ)|553|67 (C)|C
598 (ɖ)|407|68 (D)|D
599 (ɗ)|407|68 (D)|D
605 (ɝ)|457|69 (E)|E
607 (ɟ)|548|74 (J)|J
608 (ɠ)|471|71 (G)|G
614 (ɦ)|631|72 (H)|H
616 (ɨ)|478|73 (I)|I
619 (ɫ)|390|76 (L)|L
620 (ɬ)|390|76 (L)|L
621 (ɭ)|390|76 (L)|L
624 (ɰ)|528|77 (M)|M
625 (ɱ)|528|77 (M)|M
626 (ɲ)|540|78 (N)|N
627 (ɳ)|540|78 (N)|N
634 (ɺ)|485|82 (R)|R
635 (ɻ)|485|82 (R)|R
636 (ɼ)|485|82 (R)|R
637 (ɽ)|485|82 (R)|R
638 (ɾ)|485|82 (R)|R
639 (ɿ)|485|82 (R)|R
642 (ʂ)|543|83 (S)|S
644 (ʄ)|548|74 (J)|J
648 (ʈ)|358|84 (T)|T
651 (ʋ)|411|86 (V)|V
656 (ʐ)|528|90 (Z)|Z
657 (ʑ)|528|90 (Z)|Z
669 (ʝ)|548|74 (J)|J
672 (ʠ)|495|81 (Q)|Q
686 (ʮ)|631|72 (H)|H
687 (ʯ)|631|72 (H)|H
688 (ʰ)|631|72 (H)|H
689 (ʱ)|631|72 (H)|H
690 (ʲ)|548|74 (J)|J
691 (ʳ)|485|82 (R)|R
693 (ʵ)|485|82 (R)|R
695 (ʷ)|574|87 (W)|W
696 (ʸ)|404|89 (Y)|Y
737 (ˡ)|390|76 (L)|L
738 (ˢ)|543|83 (S)|S
739 (ˣ)|672|88 (X)|X
837 (ͅ)|581|None|Iota
913 (Α)|571|None|Alpha
914 (Β)|516|None|Beta
915 (Γ)|388|None|Gamma
916 (Δ)|490|None|Delta
917 (Ε)|740|None|Epsilon
918 (Ζ)|464|None|Zetta
919 (Η)|463|None|Eta
920 (Θ)|568|None|Theta
921 (Ι)|581|837 (ͅ)|Iota
922 (Κ)|467|None|Kappa
923 (Λ)|545|None|Lambda
924 (Μ)|513|181 (µ)|Miu
925 (Ν)|574|None|Miu
926 (Ξ)|411|None|Xi
927 (Ο)|800|None|Omicron
928 (Π)|386|None|Pi
929 (Ρ)|442|None|Ro
931 (Σ)|539|None|Sigma
932 (Τ)|434|None|Tau
933 (Υ)|788|None|Upsilon
934 (Φ)|469|None|Phi
935 (Χ)|388|None|Chi
936 (Ψ)|523|None|Psi
937 (Ω)|614|None|Ohm (???)
945 (α)|571|913 (Α)|Alpha
946 (β)|516|914 (Β)|Beta
947 (γ)|388|915 (Γ)|Gamma
948 (δ)|490|916 (Δ)|Delta
949 (ε)|740|917 (Ε)|Epsilon
950 (ζ)|464|918 (Ζ)|Zetta
951 (η)|463|919 (Η)|Eta
952 (θ)|568|920 (Θ)|Theta
953 (ι)|581|837 (ͅ)|Iota
954 (κ)|467|922 (Κ)|Kappa
955 (λ)|545|923 (Λ)|Lambda
956 (μ)|513|181 (µ)|Miu
957 (ν)|574|925 (Ν)|Miu
958 (ξ)|411|926 (Ξ)|Xi
959 (ο)|800|927 (Ο)|Omicron
960 (π)|386|928 (Π)|Pi
961 (ρ)|442|929 (Ρ)|Ro
962 (ς)|539|931 (Σ)|Sigma
963 (σ)|539|931 (Σ)|Sigma
964 (τ)|434|932 (Τ)|Tau
965 (υ)|788|933 (Υ)|Upsilon
966 (φ)|469|934 (Φ)|Phi
967 (χ)|388|935 (Χ)|Chi
968 (ψ)|523|936 (Ψ)|Psi
969 (ω)|580|None|Omega
976 (ϐ)|516|914 (Β)|Beta
977 (ϑ)|568|920 (Θ)|Theta
981 (ϕ)|469|934 (Φ)|Phi
982 (ϖ)|386|928 (Π)|Pi
1008 (ϰ)|467|922 (Κ)|Kappa
1009 (ϱ)|442|929 (Ρ)|Ro
1012 (ϴ)|568|920 (Θ)|Theta
1013 (ϵ)|740|917 (Ε)|Epsilon
7443 (ᴓ)|368|79 (O)|O
7462 (ᴦ)|388|915 (Γ)|Gamma
7464 (ᴨ)|386|928 (Π)|Pi
7465 (ᴩ)|442|929 (Ρ)|Ro
7466 (ᴪ)|523|936 (Ψ)|Psi
7468 (ᴬ)|482|256 (Ā)|A
7469 (ᴭ)|482|256 (Ā)|A
7470 (ᴮ)|488|66 (B)|B
7472 (ᴰ)|407|68 (D)|D
7473 (ᴱ)|457|69 (E)|E
7475 (ᴳ)|471|71 (G)|G
7476 (ᴴ)|631|72 (H)|H
7477 (ᴵ)|478|73 (I)|I
7478 (ᴶ)|548|74 (J)|J
7479 (ᴷ)|505|75 (K)|K
7480 (ᴸ)|390|76 (L)|L
7481 (ᴹ)|528|77 (M)|M
7482 (ᴺ)|540|78 (N)|N
7484 (ᴼ)|368|79 (O)|O
7486 (ᴾ)|411|80 (P)|P
7487 (ᴿ)|485|82 (R)|R
7488 (ᵀ)|358|84 (T)|T
7489 (ᵁ)|493|85 (U)|U
7490 (ᵂ)|574|87 (W)|W
7491 (ᵃ)|482|256 (Ā)|A
7495 (ᵇ)|488|66 (B)|B
7496 (ᵈ)|407|68 (D)|D
7497 (ᵉ)|457|69 (E)|E
7501 (ᵍ)|471|71 (G)|G
7503 (ᵏ)|505|75 (K)|K
7504 (ᵐ)|528|77 (M)|M
7506 (ᵒ)|368|79 (O)|O
7510 (ᵖ)|411|80 (P)|P
7511 (ᵗ)|358|84 (T)|T
7512 (ᵘ)|493|85 (U)|U
7515 (ᵛ)|411|86 (V)|V
7522 (ᵢ)|478|73 (I)|I
7523 (ᵣ)|485|82 (R)|R
7524 (ᵤ)|493|85 (U)|U
7525 (ᵥ)|411|86 (V)|V
7526 (ᵦ)|516|914 (Β)|Beta
7527 (ᵧ)|388|915 (Γ)|Gamma
7528 (ᵨ)|442|929 (Ρ)|Ro
7529 (ᵩ)|469|934 (Φ)|Phi
7530 (ᵪ)|388|935 (Χ)|Chi
7532 (ᵬ)|488|66 (B)|B
7533 (ᵭ)|407|68 (D)|D
7534 (ᵮ)|453|70 (F)|F
7535 (ᵯ)|528|77 (M)|M
7536 (ᵰ)|540|78 (N)|N
7537 (ᵱ)|411|80 (P)|P
7538 (ᵲ)|485|82 (R)|R
7539 (ᵳ)|485|82 (R)|R
7540 (ᵴ)|543|83 (S)|S
7541 (ᵵ)|358|84 (T)|T
7542 (ᵶ)|528|90 (Z)|Z
7549 (ᵽ)|411|80 (P)|P
7552 (ᶀ)|488|66 (B)|B
7553 (ᶁ)|407|68 (D)|D
7554 (ᶂ)|453|70 (F)|F
7555 (ᶃ)|471|71 (G)|G
7556 (ᶄ)|505|75 (K)|K
7557 (ᶅ)|390|76 (L)|L
7558 (ᶆ)|528|77 (M)|M
7559 (ᶇ)|540|78 (N)|N
7560 (ᶈ)|411|80 (P)|P
7561 (ᶉ)|485|82 (R)|R
7562 (ᶊ)|543|83 (S)|S
7564 (ᶌ)|411|86 (V)|V
7565 (ᶍ)|672|88 (X)|X
7566 (ᶎ)|528|90 (Z)|Z
7567 (ᶏ)|482|256 (Ā)|A
7569 (ᶑ)|407|68 (D)|D
7570 (ᶒ)|457|69 (E)|E
7571 (ᶓ)|457|69 (E)|E
7572 (ᶔ)|457|69 (E)|E
7574 (ᶖ)|478|73 (I)|I
7575 (ᶗ)|368|79 (O)|O
7577 (ᶙ)|493|85 (U)|U
7580 (ᶜ)|553|67 (C)|C
7581 (ᶝ)|553|67 (C)|C
7584 (ᶠ)|453|70 (F)|F
7585 (ᶡ)|548|74 (J)|J
7588 (ᶤ)|478|73 (I)|I
7592 (ᶨ)|548|74 (J)|J
7593 (ᶩ)|390|76 (L)|L
7594 (ᶪ)|390|76 (L)|L
7596 (ᶬ)|528|77 (M)|M
7597 (ᶭ)|528|77 (M)|M
7598 (ᶮ)|540|78 (N)|N
7599 (ᶯ)|540|78 (N)|N
7603 (ᶳ)|543|83 (S)|S
7605 (ᶵ)|358|84 (T)|T
7609 (ᶹ)|411|86 (V)|V
7611 (ᶻ)|528|90 (Z)|Z
7612 (ᶼ)|528|90 (Z)|Z
7613 (ᶽ)|528|90 (Z)|Z
7680 (Ḁ)|482|256 (Ā)|A
7681 (ḁ)|482|256 (Ā)|A
7682 (Ḃ)|488|66 (B)|B
7683 (ḃ)|488|66 (B)|B
7684 (Ḅ)|488|66 (B)|B
7685 (ḅ)|488|66 (B)|B
7686 (Ḇ)|488|66 (B)|B
7687 (ḇ)|488|66 (B)|B
7688 (Ḉ)|553|67 (C)|C
7689 (ḉ)|553|67 (C)|C
7690 (Ḋ)|407|68 (D)|D
7691 (ḋ)|407|68 (D)|D
7692 (Ḍ)|407|68 (D)|D
7693 (ḍ)|407|68 (D)|D
7694 (Ḏ)|407|68 (D)|D
7695 (ḏ)|407|68 (D)|D
7696 (Ḑ)|407|68 (D)|D
7697 (ḑ)|407|68 (D)|D
7698 (Ḓ)|407|68 (D)|D
7699 (ḓ)|407|68 (D)|D
7700 (Ḕ)|457|69 (E)|E
7701 (ḕ)|457|69 (E)|E
7702 (Ḗ)|457|69 (E)|E
7703 (ḗ)|457|69 (E)|E
7704 (Ḙ)|457|69 (E)|E
7705 (ḙ)|457|69 (E)|E
7706 (Ḛ)|457|69 (E)|E
7707 (ḛ)|457|69 (E)|E
7708 (Ḝ)|457|69 (E)|E
7709 (ḝ)|457|69 (E)|E
7710 (Ḟ)|453|70 (F)|F
7711 (ḟ)|453|70 (F)|F
7712 (Ḡ)|471|71 (G)|G
7713 (ḡ)|471|71 (G)|G
7714 (Ḣ)|631|72 (H)|H
7715 (ḣ)|631|72 (H)|H
7716 (Ḥ)|631|72 (H)|H
7717 (ḥ)|631|72 (H)|H
7718 (Ḧ)|631|72 (H)|H
7719 (ḧ)|631|72 (H)|H
7720 (Ḩ)|631|72 (H)|H
7721 (ḩ)|631|72 (H)|H
7722 (Ḫ)|631|72 (H)|H
7723 (ḫ)|631|72 (H)|H
7724 (Ḭ)|478|73 (I)|I
7725 (ḭ)|478|73 (I)|I
7726 (Ḯ)|478|73 (I)|I
7727 (ḯ)|478|73 (I)|I
7728 (Ḱ)|505|75 (K)|K
7729 (ḱ)|505|75 (K)|K
7730 (Ḳ)|505|75 (K)|K
7731 (ḳ)|505|75 (K)|K
7732 (Ḵ)|505|75 (K)|K
7733 (ḵ)|505|75 (K)|K
7734 (Ḷ)|390|76 (L)|L
7735 (ḷ)|390|76 (L)|L
7736 (Ḹ)|390|76 (L)|L
7737 (ḹ)|390|76 (L)|L
7738 (Ḻ)|390|76 (L)|L
7739 (ḻ)|390|76 (L)|L
7740 (Ḽ)|390|76 (L)|L
7741 (ḽ)|390|76 (L)|L
7742 (Ḿ)|528|77 (M)|M
7743 (ḿ)|528|77 (M)|M
7744 (Ṁ)|528|77 (M)|M
7745 (ṁ)|528|77 (M)|M
7746 (Ṃ)|528|77 (M)|M
7747 (ṃ)|528|77 (M)|M
7748 (Ṅ)|540|78 (N)|N
7749 (ṅ)|540|78 (N)|N
7750 (Ṇ)|540|78 (N)|N
7751 (ṇ)|540|78 (N)|N
7752 (Ṉ)|540|78 (N)|N
7753 (ṉ)|540|78 (N)|N
7754 (Ṋ)|540|78 (N)|N
7755 (ṋ)|540|78 (N)|N
7756 (Ṍ)|368|79 (O)|O
7757 (ṍ)|368|79 (O)|O
7758 (Ṏ)|368|79 (O)|O
7759 (ṏ)|368|79 (O)|O
7760 (Ṑ)|368|79 (O)|O
7761 (ṑ)|368|79 (O)|O
7762 (Ṓ)|368|79 (O)|O
7763 (ṓ)|368|79 (O)|O
7764 (Ṕ)|411|80 (P)|P
7765 (ṕ)|411|80 (P)|P
7766 (Ṗ)|411|80 (P)|P
7767 (ṗ)|411|80 (P)|P
7768 (Ṙ)|485|82 (R)|R
7769 (ṙ)|485|82 (R)|R
7770 (Ṛ)|485|82 (R)|R
7771 (ṛ)|485|82 (R)|R
7772 (Ṝ)|485|82 (R)|R
7773 (ṝ)|485|82 (R)|R
7774 (Ṟ)|485|82 (R)|R
7775 (ṟ)|485|82 (R)|R
7776 (Ṡ)|543|83 (S)|S
7777 (ṡ)|543|83 (S)|S
7778 (Ṣ)|543|83 (S)|S
7779 (ṣ)|543|83 (S)|S
7780 (Ṥ)|543|83 (S)|S
7781 (ṥ)|543|83 (S)|S
7782 (Ṧ)|543|83 (S)|S
7783 (ṧ)|543|83 (S)|S
7784 (Ṩ)|543|83 (S)|S
7785 (ṩ)|543|83 (S)|S
7786 (Ṫ)|358|84 (T)|T
7787 (ṫ)|358|84 (T)|T
7788 (Ṭ)|358|84 (T)|T
7789 (ṭ)|358|84 (T)|T
7790 (Ṯ)|358|84 (T)|T
7791 (ṯ)|358|84 (T)|T
7792 (Ṱ)|358|84 (T)|T
7793 (ṱ)|358|84 (T)|T
7794 (Ṳ)|493|85 (U)|U
7795 (ṳ)|493|85 (U)|U
7796 (Ṵ)|493|85 (U)|U
7797 (ṵ)|493|85 (U)|U
7798 (Ṷ)|493|85 (U)|U
7799 (ṷ)|493|85 (U)|U
7800 (Ṹ)|493|85 (U)|U
7801 (ṹ)|493|85 (U)|U
7802 (Ṻ)|493|85 (U)|U
7803 (ṻ)|493|85 (U)|U
7804 (Ṽ)|411|86 (V)|V
7805 (ṽ)|411|86 (V)|V
7806 (Ṿ)|411|86 (V)|V
7807 (ṿ)|411|86 (V)|V
7808 (Ẁ)|574|87 (W)|W
7809 (ẁ)|574|87 (W)|W
7810 (Ẃ)|574|87 (W)|W
7811 (ẃ)|574|87 (W)|W
7812 (Ẅ)|574|87 (W)|W
7813 (ẅ)|574|87 (W)|W
7814 (Ẇ)|574|87 (W)|W
7815 (ẇ)|574|87 (W)|W
7816 (Ẉ)|574|87 (W)|W
7817 (ẉ)|574|87 (W)|W
7818 (Ẋ)|672|88 (X)|X
7819 (ẋ)|672|88 (X)|X
7820 (Ẍ)|672|88 (X)|X
7821 (ẍ)|672|88 (X)|X
7822 (Ẏ)|404|89 (Y)|Y
7823 (ẏ)|404|89 (Y)|Y
7824 (Ẑ)|528|90 (Z)|Z
7825 (ẑ)|528|90 (Z)|Z
7826 (Ẓ)|528|90 (Z)|Z
7827 (ẓ)|528|90 (Z)|Z
7828 (Ẕ)|528|90 (Z)|Z
7829 (ẕ)|528|90 (Z)|Z
7830 (ẖ)|631|72 (H)|H
7831 (ẗ)|358|84 (T)|T
7832 (ẘ)|574|87 (W)|W
7833 (ẙ)|404|89 (Y)|Y
7834 (ẚ)|482|256 (Ā)|A
7835 (ẛ)|543|83 (S)|S
7836 (ẜ)|543|83 (S)|S
7837 (ẝ)|543|83 (S)|S
7840 (Ạ)|482|256 (Ā)|A
7841 (ạ)|482|256 (Ā)|A
7842 (Ả)|482|256 (Ā)|A
7843 (ả)|482|256 (Ā)|A
7844 (Ấ)|482|256 (Ā)|A
7845 (ấ)|482|256 (Ā)|A
7846 (Ầ)|482|256 (Ā)|A
7847 (ầ)|482|256 (Ā)|A
7848 (Ẩ)|482|256 (Ā)|A
7849 (ẩ)|482|256 (Ā)|A
7850 (Ẫ)|482|256 (Ā)|A
7851 (ẫ)|482|256 (Ā)|A
7852 (Ậ)|482|256 (Ā)|A
7853 (ậ)|482|256 (Ā)|A
7854 (Ắ)|482|256 (Ā)|A
7855 (ắ)|482|256 (Ā)|A
7856 (Ằ)|482|256 (Ā)|A
7857 (ằ)|482|256 (Ā)|A
7858 (Ẳ)|482|256 (Ā)|A
7859 (ẳ)|482|256 (Ā)|A
7860 (Ẵ)|482|256 (Ā)|A
7861 (ẵ)|482|256 (Ā)|A
7862 (Ặ)|482|256 (Ā)|A
7863 (ặ)|482|256 (Ā)|A
7864 (Ẹ)|457|69 (E)|E
7865 (ẹ)|457|69 (E)|E
7866 (Ẻ)|457|69 (E)|E
7867 (ẻ)|457|69 (E)|E
7868 (Ẽ)|457|69 (E)|E
7869 (ẽ)|457|69 (E)|E
7870 (Ế)|457|69 (E)|E
7871 (ế)|457|69 (E)|E
7872 (Ề)|457|69 (E)|E
7873 (ề)|457|69 (E)|E
7874 (Ể)|457|69 (E)|E
7875 (ể)|457|69 (E)|E
7876 (Ễ)|457|69 (E)|E
7877 (ễ)|457|69 (E)|E
7878 (Ệ)|457|69 (E)|E
7879 (ệ)|457|69 (E)|E
7880 (Ỉ)|478|73 (I)|I
7881 (ỉ)|478|73 (I)|I
7882 (Ị)|478|73 (I)|I
7883 (ị)|478|73 (I)|I
7884 (Ọ)|368|79 (O)|O
7885 (ọ)|368|79 (O)|O
7886 (Ỏ)|368|79 (O)|O
7887 (ỏ)|368|79 (O)|O
7888 (Ố)|368|79 (O)|O
7889 (ố)|368|79 (O)|O
7890 (Ồ)|368|79 (O)|O
7891 (ồ)|368|79 (O)|O
7892 (Ổ)|368|79 (O)|O
7893 (ổ)|368|79 (O)|O
7894 (Ỗ)|368|79 (O)|O
7895 (ỗ)|368|79 (O)|O
7896 (Ộ)|368|79 (O)|O
7897 (ộ)|368|79 (O)|O
7898 (Ớ)|368|79 (O)|O
7899 (ớ)|368|79 (O)|O
7900 (Ờ)|368|79 (O)|O
7901 (ờ)|368|79 (O)|O
7902 (Ở)|368|79 (O)|O
7903 (ở)|368|79 (O)|O
7904 (Ỡ)|368|79 (O)|O
7905 (ỡ)|368|79 (O)|O
7906 (Ợ)|368|79 (O)|O
7907 (ợ)|368|79 (O)|O
7908 (Ụ)|493|85 (U)|U
7909 (ụ)|493|85 (U)|U
7910 (Ủ)|493|85 (U)|U
7911 (ủ)|493|85 (U)|U
7912 (Ứ)|493|85 (U)|U
7913 (ứ)|493|85 (U)|U
7914 (Ừ)|493|85 (U)|U
7915 (ừ)|493|85 (U)|U
7916 (Ử)|493|85 (U)|U
7917 (ử)|493|85 (U)|U
7918 (Ữ)|493|85 (U)|U
7919 (ữ)|493|85 (U)|U
7920 (Ự)|493|85 (U)|U
7921 (ự)|493|85 (U)|U
7922 (Ỳ)|404|89 (Y)|Y
7923 (ỳ)|404|89 (Y)|Y
7924 (Ỵ)|404|89 (Y)|Y
7925 (ỵ)|404|89 (Y)|Y
7926 (Ỷ)|404|89 (Y)|Y
7927 (ỷ)|404|89 (Y)|Y
7928 (Ỹ)|404|89 (Y)|Y
7929 (ỹ)|404|89 (Y)|Y
7934 (Ỿ)|404|89 (Y)|Y
7935 (ỿ)|404|89 (Y)|Y
8126 (ι)|581|837 (ͅ)|Iota
8208 (‐)|706|45 (-)|Dash
8209 (‑)|706|45 (-)|Dash
8210 (‒)|706|45 (-)|Dash
8211 (–)|706|45 (-)|Dash
8252 (‼)|1831|None|Double exclamation mark
8255 (‿)|732|95 (_)|Underscore
8256 (⁀)|732|95 (_)|Underscore
8260 (⁄)|579|47 (/)|Slash
8263 (⁇)|1985|None|Question mark question mark
8264 (⁈)|2247|None|Question mark exclamation mark
8265 (⁉)|2036|None|Exclamation question mark
8276 (⁔)|732|95 (_)|Underscore
8304 (⁰)|605|None|
8305 (ⁱ)|478|73 (I)|I
8308 (⁴)|629|52 (4)|Four
8309 (⁵)|680|53 (5)|Five
8310 (⁶)|612|54 (6)|Six
8311 (⁷)|377|55 (7)|Seven
8312 (⁸)|479|56 (8)|Eight
8313 (⁹)|587|57 (9)|Nine
8314 (⁺)|396|43 (+)|Plus
8315 (⁻)|706|45 (-)|Dash
8316 (⁼)|779|61 (=)|Equals
8317 (⁽)|1424|None|Opening parenthases
8318 (⁾)|1526|None|Closing parentheses
8319 (ⁿ)|540|78 (N)|N
8320 (₀)|605|8304 (⁰)|Zero
8321 (₁)|540|49 (1)|One
8322 (₂)|415|50 (2)|Two
8323 (₃)|513|51 (3)|Three
8324 (₄)|629|52 (4)|Four
8325 (₅)|680|53 (5)|Five
8326 (₆)|612|54 (6)|Six
8327 (₇)|377|55 (7)|Seven
8328 (₈)|479|56 (8)|Eight
8329 (₉)|587|57 (9)|Nine
8330 (₊)|396|43 (+)|Plus
8331 (₋)|706|45 (-)|Dash
8332 (₌)|779|61 (=)|Equals
8333 (₍)|1424|8317 (⁽)|Opening parenthases
8334 (₎)|1526|8318 (⁾)|Closing parentheses
8336 (ₐ)|482|256 (Ā)|A
8337 (ₑ)|457|69 (E)|E
8338 (ₒ)|368|79 (O)|O
8339 (ₓ)|672|88 (X)|X
8341 (ₕ)|631|72 (H)|H
8342 (ₖ)|505|75 (K)|K
8343 (ₗ)|390|76 (L)|L
8344 (ₘ)|528|77 (M)|M
8345 (ₙ)|540|78 (N)|N
8346 (ₚ)|411|80 (P)|P
8347 (ₛ)|543|83 (S)|S
8348 (ₜ)|358|84 (T)|T
8360 (₨)|633|None|Rs
8361 (₩)|875|None|Korean won
8364 (€)|598|None|Euro
8377 (₹)|655|None|Rupee
8448 (℀)|1227|None|A slash C
8449 (℁)|1150|None|A slash S
8450 (ℂ)|553|67 (C)|C
8451 (℃)|553|67 (C)|C
8453 (℅)|690|None|Care of
8454 (℆)|1049|None|C slash U
8457 (℉)|453|70 (F)|F
8458 (ℊ)|471|71 (G)|G
8459 (ℋ)|631|72 (H)|H
8460 (ℌ)|631|72 (H)|H
8461 (ℍ)|631|72 (H)|H
8462 (ℎ)|631|72 (H)|H
8463 (ℏ)|631|72 (H)|H
8464 (ℐ)|478|73 (I)|I
8465 (ℑ)|478|73 (I)|I
8466 (ℒ)|390|76 (L)|L
8467 (ℓ)|390|76 (L)|L
8469 (ℕ)|540|78 (N)|N
8470 (№)|430|None|No
8473 (ℙ)|411|80 (P)|P
8474 (ℚ)|495|81 (Q)|Q
8475 (ℛ)|485|82 (R)|R
8476 (ℜ)|485|82 (R)|R
8477 (ℝ)|485|82 (R)|R
8480 (℠)|622|None|Sm
8481 (℡)|526|None|Tel
8482 (™)|831|None|Trademark
8484 (ℤ)|528|90 (Z)|Z
8486 (Ω)|580|969 (ω)|Omega
8488 (ℨ)|528|90 (Z)|Z
8490 (K)|505|75 (K)|K
8491 (Å)|482|256 (Ā)|A
8492 (ℬ)|488|66 (B)|B
8493 (ℭ)|553|67 (C)|C
8495 (ℯ)|457|69 (E)|E
8496 (ℰ)|457|69 (E)|E
8497 (ℱ)|453|70 (F)|F
8499 (ℳ)|528|77 (M)|M
8500 (ℴ)|368|79 (O)|O
8505 (ℹ)|965|None|Information
8507 (℻)|657|None|Fax
8517 (ⅅ)|407|68 (D)|D
8518 (ⅆ)|407|68 (D)|D
8519 (ⅇ)|457|69 (E)|E
8520 (ⅈ)|478|73 (I)|I
8521 (ⅉ)|548|74 (J)|J
8528 (⅐)|818|None|One seventh
8529 (⅑)|818|None|One ninth
8530 (⅒)|854|None|One tenth
8531 (⅓)|925|None|One third
8532 (⅔)|1039|None|Two thirds
8533 (⅕)|926|None|One fifth
8534 (⅖)|1103|None|Two fifths
8535 (⅗)|1128|None|Three fifths
8536 (⅘)|1189|None|Four fifths
8537 (⅙)|921|None|One sixth
8538 (⅚)|1297|None|Five sixths
8539 (⅛)|753|None|One eighth
8540 (⅜)|1341|None|Three eighths
8541 (⅝)|1385|None|Five eighths
8542 (⅞)|1052|None|Seven eighths
8543 (⅟)|906|None|One slash
8544 (Ⅰ)|540|49 (1)|One
8545 (Ⅱ)|415|50 (2)|Two
8546 (Ⅲ)|513|51 (3)|Three
8547 (Ⅳ)|629|52 (4)|Four
8548 (Ⅴ)|680|53 (5)|Five
8549 (Ⅵ)|612|54 (6)|Six
8550 (Ⅶ)|377|55 (7)|Seven
8551 (Ⅷ)|479|56 (8)|Eight
8552 (Ⅸ)|587|57 (9)|Nine
8553 (Ⅹ)|476|None|Ten
8554 (Ⅺ)|477|None|Eleven
8555 (Ⅻ)|683|None|Twelve
8556 (Ⅼ)|566|None|Fifty
8557 (Ⅽ)|821|None|One hundred
8558 (Ⅾ)|968|None|Five hundred
8559 (Ⅿ)|960|None|One thousand
8560 (ⅰ)|540|49 (1)|One
8561 (ⅱ)|415|50 (2)|Two
8562 (ⅲ)|513|51 (3)|Three
8563 (ⅳ)|629|52 (4)|Four
8564 (ⅴ)|680|53 (5)|Five
8565 (ⅵ)|612|54 (6)|Six
8566 (ⅶ)|377|55 (7)|Seven
8567 (ⅷ)|479|56 (8)|Eight
8568 (ⅸ)|587|57 (9)|Nine
8569 (ⅹ)|476|8553 (Ⅹ)|Ten
8570 (ⅺ)|477|8554 (Ⅺ)|Eleven
8571 (ⅻ)|683|8555 (Ⅻ)|Twelve
8572 (ⅼ)|566|8556 (Ⅼ)|Fifty
8573 (ⅽ)|821|8557 (Ⅽ)|One hundred
8574 (ⅾ)|968|8558 (Ⅾ)|Five hundred
8575 (ⅿ)|960|8559 (Ⅿ)|One thousand
8585 (↉)|1483|None|Zero slash three
8596 (↔)|1272|None|Left right arrow
8597 (↕)|1027|None|Up down arrow
8598 (↖)|1264|None|North west arrow
8599 (↗)|1224|None|North east arrow
8600 (↘)|1247|None|South east arrow
8601 (↙)|1253|None|South west arrow
8617 (↩)|1707|None|Leftwards arrow with hook
8618 (↪)|1679|None|Rightwards arrow with hook
8722 (−)|760|None|Minus
8724 (∔)|396|43 (+)|Plus
8725 (∕)|579|47 (/)|Slash
8726 (∖)|836|92 (\\)|Backslash
8727 (∗)|850|None|Asterisk
8729 (∙)|850|8727 (∗)|Asterisk
8758 (∶)|656|58 (:)|Colon
8800 (≠)|1047|None|Does not equal
8804 (≤)|1559|None|Less than or equal to
8805 (≥)|1579|None|Greater than or equal to
8814 (≮)|713|60 (<)|Less than
8815 (≯)|855|62 (>)|Greater than
8986 (⌚)|717|None|Watch
8987 (⌛)|909|None|Hourglass
9000 (⌨)|781|None|Keyboard
9167 (⏏)|1037|None|Eject button
9193 (⏩)|2300|None|Double right pointing triangles
9194 (⏪)|2437|None|Double left pointing triangles
9195 (⏫)|2143|None|Double up pointing triangles
9196 (⏬)|2369|None|Double down pointing triangles
9197 (⏭)|1236|None|Fast forward
9198 (⏮)|1362|None|Fast rewind
9199 (⏯)|1271|None|Play or pause
9200 (⏰)|1069|None|Alarm clock
9201 (⏱)|1058|None|Stopwatch
9202 (⏲)|691|None|Clock
9203 (⏳)|909|8987 (⌛)|Hourglass
9208 (⏸)|1171|None|Pause button
9209 (⏹)|1185|None|Stop button
9210 (⏺)|1145|None|Record button
9312 (①)|540|49 (1)|One
9313 (②)|415|50 (2)|Two
9314 (③)|513|51 (3)|Three
9315 (④)|629|52 (4)|Four
9316 (⑤)|680|53 (5)|Five
9317 (⑥)|612|54 (6)|Six
9318 (⑦)|377|55 (7)|Seven
9319 (⑧)|479|56 (8)|Eight
9320 (⑨)|587|57 (9)|Nine
9321 (⑩)|476|8553 (Ⅹ)|Ten
9322 (⑪)|477|8554 (Ⅺ)|Eleven
9323 (⑫)|683|8555 (Ⅻ)|Twelve
9324 (⑬)|883|None|Thirteen
9325 (⑭)|908|None|Fourteen
9326 (⑮)|891|None|Fifteen
9327 (⑯)|1006|None|Sixteen
9328 (⑰)|1002|None|Seventeen
9329 (⑱)|880|None|Eighteen
9330 (⑲)|884|None|Ninteen
9331 (⑳)|557|None|Twenty
9332 (⑴)|2956|None|Opening parenthases one closing parenthases (does not work anymore, outdated info)
9333 (⑵)|3001|None|Opening parenthases two closing parenthases (does not work anymore, outdated info)
9334 (⑶)|2996|None|Opening parenthases three closing parenthases (does not work anymore, outdated info)
9335 (⑷)|2930|None|Opening parenthases four closing parenthases (does not work anymore, outdated info)
9336 (⑸)|3076|None|Opening parenthases five closing parenthases (does not work anymore, outdated info)
9337 (⑹)|3142|None|Opening parenthases six closing parenthases (does not work anymore, outdated info)
9338 (⑺)|3112|None|Opening parenthases seven closing parenthases (does not work anymore, outdated info)
9339 (⑻)|2929|None|Opening parenthases eight closing parenthases (does not work anymore, outdated info)
9340 (⑼)|2931|None|Opening parenthases nine closing parenthases (does not work anymore, outdated info)
9341 (⑽)|3081|None|Opening parenthases ten closing parenthases (does not work anymore, outdated info)
9342 (⑾)|3002|None|Opening parenthases eleven closing parenthases (does not work anymore, outdated info)
9343 (⑿)|3311|None|Opening parenthases twelve closing parenthases (does not work anymore, outdated info)
9344 (⒀)|3340|None|Opening parenthases thirteen closing parenthases (does not work anymore, outdated info)
9345 (⒁)|3295|None|Opening parenthases fourteen closing parenthases (does not work anymore, outdated info)
9346 (⒂)|3129|None|Opening parenthases fifteen closing parenthases (does not work anymore, outdated info)
9347 (⒃)|3293|None|Opening parenthases sixteen closing parenthases (does not work anymore, outdated info)
9348 (⒄)|3403|None|Opening parenthases seventeen closing parenthases (does not work anymore, outdated info)
9349 (⒅)|3106|None|Opening parenthases eighteen closing parenthases (does not work anymore, outdated info)
9350 (⒆)|3178|None|Opening parenthases nineteen closing parenthases (does not work anymore, outdated info)
9351 (⒇)|3066|None|Opening parenthases twenty closing parenthases (does not work anymore, outdated info)
9352 (⒈)|781|None|One dot
9353 (⒉)|678|None|Two dot
9354 (⒊)|772|None|Three dot
9355 (⒋)|716|None|Four dot
9356 (⒌)|774|None|Five dot
9357 (⒍)|882|None|Six dot
9358 (⒎)|743|None|Seven dot
9359 (⒏)|692|None|Eight dot
9360 (⒐)|838|None|Nine dot
9361 (⒑)|718|None|Ten dot
9362 (⒒)|794|None|Eleven dot
9363 (⒓)|892|None|Twelve dot
9364 (⒔)|1093|None|Thirteen dot
9365 (⒕)|1178|None|Fourteen dot
9366 (⒖)|1056|None|Fifteen dot
9367 (⒗)|1082|None|Sixteen dot
9368 (⒘)|1104|None|Seventeen dot
9369 (⒙)|1104|None|Eighteen dot
9370 (⒚)|1100|None|Nineteen dot
9371 (⒛)|797|None|Twenty dot
9372 (⒜)|2859|None|Opening parenthases A closing parenthases
9373 (⒝)|2878|None|Opening parenthases B closing parenthases
9374 (⒞)|2956|None|Opening parenthases C closing parenthases
9375 (⒟)|2865|None|Opening parenthases D closing parenthases
9376 (⒠)|2797|None|Opening parenthases E closing parenthases
9377 (⒡)|2834|None|Opening parenthases F closing parenthases
9378 (⒢)|2993|None|Opening parenthases G closing parenthases
9379 (⒣)|3047|None|Opening parenthases H closing parenthases
9380 (⒤)|2841|None|Opening parenthases I closing parenthases
9381 (⒥)|2980|None|Opening parenthases J closing parenthases
9382 (⒦)|2949|None|Opening parenthases K closing parenthases
9383 (⒧)|2870|None|Opening parenthases L closing parenthases
9384 (⒨)|2838|None|Opening parenthases M closing parenthases
9385 (⒩)|2816|None|Opening parenthases N closing parenthases
9386 (⒪)|2930|None|Opening parenthases O closing parenthases
9387 (⒫)|2967|None|Opening parenthases P closing parenthases
9388 (⒬)|2881|None|Opening parenthases Q closing parenthases
9389 (⒭)|2776|None|Opening parenthases R closing parenthases
9390 (⒮)|2889|None|Opening parenthases S closing parenthases
9391 (⒯)|2923|None|Opening parenthases T closing parenthases
9392 (⒰)|2843|None|Opening parenthases U closing parenthases
9393 (⒱)|2876|None|Opening parenthases V closing parenthases
9394 (⒲)|3248|None|Opening parenthases W closing parenthases
9395 (⒳)|2904|None|Opening parenthases X closing parenthases
9396 (⒴)|2849|None|Opening parenthases Y closing parenthases
9397 (⒵)|3119|None|Opening parenthases Z closing parenthases
9398 (Ⓐ)|482|256 (Ā)|A
9399 (Ⓑ)|488|66 (B)|B
9400 (Ⓒ)|553|67 (C)|C
9401 (Ⓓ)|407|68 (D)|D
9402 (Ⓔ)|457|69 (E)|E
9403 (Ⓕ)|453|70 (F)|F
9404 (Ⓖ)|471|71 (G)|G
9405 (Ⓗ)|631|72 (H)|H
9406 (Ⓘ)|478|73 (I)|I
9407 (Ⓙ)|548|74 (J)|J
9408 (Ⓚ)|505|75 (K)|K
9409 (Ⓛ)|390|76 (L)|L
9410 (Ⓜ)|1570|None|Incircled letter M
9411 (Ⓝ)|540|78 (N)|N
9412 (Ⓞ)|368|79 (O)|O
9413 (Ⓟ)|411|80 (P)|P
9414 (Ⓠ)|495|81 (Q)|Q
9415 (Ⓡ)|485|82 (R)|R
9416 (Ⓢ)|543|83 (S)|S
9417 (Ⓣ)|358|84 (T)|T
9418 (Ⓤ)|493|85 (U)|U
9419 (Ⓥ)|411|86 (V)|V
9420 (Ⓦ)|574|87 (W)|W
9421 (Ⓧ)|672|88 (X)|X
9422 (Ⓨ)|404|89 (Y)|Y
9423 (Ⓩ)|528|90 (Z)|Z
9424 (ⓐ)|482|256 (Ā)|A
9425 (ⓑ)|488|66 (B)|B
9426 (ⓒ)|553|67 (C)|C
9427 (ⓓ)|407|68 (D)|D
9428 (ⓔ)|457|69 (E)|E
9429 (ⓕ)|453|70 (F)|F
9430 (ⓖ)|471|71 (G)|G
9431 (ⓗ)|631|72 (H)|H
9432 (ⓘ)|478|73 (I)|I
9433 (ⓙ)|548|74 (J)|J
9434 (ⓚ)|505|75 (K)|K
9435 (ⓛ)|390|76 (L)|L
9436 (ⓜ)|528|77 (M)|M
9437 (ⓝ)|540|78 (N)|N
9438 (ⓞ)|368|79 (O)|O
9439 (ⓟ)|411|80 (P)|P
9440 (ⓠ)|495|81 (Q)|Q
9441 (ⓡ)|485|82 (R)|R
9442 (ⓢ)|543|83 (S)|S
9443 (ⓣ)|358|84 (T)|T
9444 (ⓤ)|493|85 (U)|U
9445 (ⓥ)|411|86 (V)|V
9446 (ⓦ)|574|87 (W)|W
9447 (ⓧ)|672|88 (X)|X
9448 (ⓨ)|404|89 (Y)|Y
9449 (ⓩ)|528|90 (Z)|Z
9450 (⓪)|605|8304 (⁰)|Zero
9642 (▪)|1453|None|Small black square
9643 (▫)|1117|None|Small square
9654 (▶)|1865|None|Right pointing triangle
9664 (◀)|1892|None|Left pointing triangle
9723 (◻)|1258|None|Medium square
9724 (◼)|1541|None|Medium black square
9725 (◽)|797|None|Square
9726 (◾)|990|None|Black square
9728 (☀)|607|None|Sun
9729 (☁)|883|None|Cloud
9730 (☂)|780|None|Umbrella
9731 (☃)|879|None|Snowman
9732 (☄)|636|None|Comet
9742 (☎)|970|None|Telephone
9745 (☑)|1059|None|Checked box
9748 (☔)|1086|None|Open umbrella
9749 (☕)|684|None|Coffee
9752 (☘)|961|None|Shamrock
9757 (☝)|1267|None|Pointing finger
9760 (☠)|748|None|Skull
9762 (☢)|1017|None|Radioactive
9763 (☣)|1011|None|Biohazard
9766 (☦)|1359|None|Orthodox cross
9770 (☪)|1401|None|Star and cresent
9774 (☮)|932|None|Peace dove (should be Peace symbol)
9775 (☯)|777|None|Yin yang
9784 (☸)|1156|None|Wheel of dharma
9785 (☹)|1251|None|Frowning face
9786 (☺)|1148|None|Smiley face
9800 (♈)|892|None|Aries
9801 (♉)|839|None|Torus
9802 (♊)|832|None|Gemini
9803 (♋)|798|None|Cancer
9804 (♌)|713|None|Leo
9805 (♍)|856|None|Virgo
9806 (♎)|707|None|Libra
9807 (♏)|1087|None|Scorpius
9808 (♐)|1277|None|Sagitirius
9809 (♑)|975|None|Capricorn
9810 (♒)|972|None|Aquarius
9811 (♓)|909|None|Pisces
9824 (♠)|840|None|Spade
9827 (♣)|614|None|Club
9829 (♥)|612|None|Heart
9830 (♦)|914|None|Diamond
9832 (♨)|1106|None|Hot springs
9851 (♻)|1560|None|Recycling symbol
9855 (♿)|1435|None|Wheelchair symbol
9874 (⚒)|1298|None|Hammer and pick
9875 (⚓)|681|None|Anchor
9876 (⚔)|860|None|Swords
9878 (⚖)|894|None|Scales
9879 (⚗)|771|None|Alembic
9881 (⚙)|664|None|Gear
9883 (⚛)|556|None|Atom
9884 (⚜)|871|None|Fleur-de-lis
9888 (⚠)|1452|None|Warning sign
9889 (⚡)|1656|None|High voltage sign
9898 (⚪)|875|None|Circle
9899 (⚫)|1008|None|Black circle
9904 (⚰)|690|None|Coffin
9905 (⚱)|1260|None|Funeral urn
9917 (⚽)|955|None|Football
9918 (⚾)|963|None|Baseball
9924 (⛄)|879|9731 (☃)|Snowman
9925 (⛅)|1674|None|Sun behind cloud
9928 (⛈)|1307|None|Lightning showers (???)
9934 (⛎)|1189|None|Ophiuchus
9935 (⛏)|871|None|Pickaxe
9937 (⛑)|759|None|Medic
9939 (⛓)|933|None|Chains
9940 (⛔)|1559|None|Do not enter sign
9961 (⛩)|831|None|Shrine
9962 (⛪)|816|None|Church
9968 (⛰)|784|None|Mountain
9969 (⛱)|780|9730 (☂)|Umbrella
9970 (⛲)|868|None|Fountain
9971 (⛳)|1004|None|Golf flag
9972 (⛴)|624|None|Ferry
9973 (⛵)|947|None|Sail boat
9975 (⛷)|533|None|Skier
9976 (⛸)|1097|None|Ice skate
9977 (⛹)|1599|None|Basketball player
9978 (⛺)|547|None|Tent
9981 (⛽)|931|None|Petrol pump
9986 (✂)|1032|None|Black scissors
9989 (✅)|1330|None|White tick mark
9992 (✈)|998|None|Airplane
9993 (✉)|811|None|Envelope
9994 (✊)|1203|None|Raised fist
9995 (✋)|1087|None|Raised hand
9996 (✌)|1315|None|Victory hand
9997 (✍)|740|None|Writing
9999 (✏)|760|None|Pencil
10002 (✒)|955|None|Black pen
10004 (✔)|1325|None|Black tick mark
10006 (✖)|1877|None|Multiplication sign
10013 (✝)|1274|None|Latin cross
10017 (✡)|1194|None|Star of david
10024 (✨)|855|None|Sparkles
10035 (✳)|998|None|Asterisk
10036 (✴)|1022|None|Black star
10052 (❄)|1003|None|Snow flake
10055 (❇)|934|None|Sparkle
10060 (❌)|973|None|Cross mark
10062 (❎)|1561|None|Cross mark in square
10067 (❓)|1529|None|Black question mark
10068 (❔)|1345|None|White question mark
10069 (❕)|1887|None|White exclamation mark
10071 (❗)|1819|None|Black exclamation mark
10083 (❣)|1244|None|Profound heart
10084 (❤)|612|9829 (♥)|Heart
10133 (➕)|1146|None|Plus sign
10134 (➖)|1352|None|Minus sign
10135 (➗)|1264|None|Division sign
10145 (➡)|931|None|Right arrow
10160 (➰)|956|None|Curly loop
10175 (➿)|1088|None|Loop-de-loop
10187 (⟋)|579|47 (/)|Slash
10189 (⟍)|836|92 (\\)|Backslash
10548 (⤴)|1149|None|Curved up arrow
10549 (⤵)|1307|None|Curved down arrow
10741 (⧵)|836|92 (\\)|Backslash
10744 (⧸)|579|47 (/)|Slash
10745 (⧹)|836|92 (\\)|Backslash
10868 (⩴)|1822|None|Colon colon equals
10869 (⩵)|1427|None|Equals equals
10870 (⩶)|1876|None|Equals equals equals
11013 (⬅)|913|None|Left arrow
11014 (⬆)|850|None|Up arrow
11015 (⬇)|944|None|Down arrow
11035 (⬛)|1312|None|Big black square
11036 (⬜)|797|9725 (◽)|Square
11088 (⭐)|727|None|Star
11093 (⭕)|875|9898 (⚪)|Circle
11360 (Ⱡ)|390|76 (L)|L
11361 (ⱡ)|390|76 (L)|L
11362 (Ɫ)|390|76 (L)|L
11363 (Ᵽ)|411|80 (P)|P
11364 (Ɽ)|485|82 (R)|R
11365 (ⱥ)|482|256 (Ā)|A
11366 (ⱦ)|358|84 (T)|T
11367 (Ⱨ)|631|72 (H)|H
11368 (ⱨ)|631|72 (H)|H
11369 (Ⱪ)|505|75 (K)|K
11370 (ⱪ)|505|75 (K)|K
11371 (Ⱬ)|528|90 (Z)|Z
11372 (ⱬ)|528|90 (Z)|Z
11374 (Ɱ)|528|77 (M)|M
11377 (ⱱ)|411|86 (V)|V
11378 (Ⱳ)|574|87 (W)|W
11379 (ⱳ)|574|87 (W)|W
11380 (ⱴ)|411|86 (V)|V
11384 (ⱸ)|457|69 (E)|E
11385 (ⱹ)|485|82 (R)|R
11386 (ⱺ)|368|79 (O)|O
11388 (ⱼ)|548|74 (J)|J
11389 (ⱽ)|411|86 (V)|V
11390 (Ȿ)|543|83 (S)|S
11391 (Ɀ)|528|90 (Z)|Z
11799 (⸗)|706|45 (-)|Dash
11802 (⸚)|706|45 (-)|Dash
11834 (⸺)|706|45 (-)|Dash
11835 (⸻)|706|45 (-)|Dash
11840 (⹀)|706|45 (-)|Dash
12336 (〰)|984|None|Wavy dash
12349 (〽)|1635|None|Part alternation mark
12951 (㊗)|1803|None|Chinese for celebration (???)
12953 (㊙)|1644|None|Chinese for secrecy (???)
42814 (Ꜿ)|553|67 (C)|C
42815 (ꜿ)|553|67 (C)|C
42816 (Ꝁ)|505|75 (K)|K
42817 (ꝁ)|505|75 (K)|K
42818 (Ꝃ)|505|75 (K)|K
42819 (ꝃ)|505|75 (K)|K
42820 (Ꝅ)|505|75 (K)|K
42821 (ꝅ)|505|75 (K)|K
42824 (Ꝉ)|390|76 (L)|L
42825 (ꝉ)|390|76 (L)|L
42826 (Ꝋ)|368|79 (O)|O
42827 (ꝋ)|368|79 (O)|O
42828 (Ꝍ)|368|79 (O)|O
42829 (ꝍ)|368|79 (O)|O
42832 (Ꝑ)|411|80 (P)|P
42833 (ꝑ)|411|80 (P)|P
42834 (Ꝓ)|411|80 (P)|P
42835 (ꝓ)|411|80 (P)|P
42836 (Ꝕ)|411|80 (P)|P
42837 (ꝕ)|411|80 (P)|P
42838 (Ꝗ)|495|81 (Q)|Q
42839 (ꝗ)|495|81 (Q)|Q
42840 (Ꝙ)|495|81 (Q)|Q
42841 (ꝙ)|495|81 (Q)|Q
42846 (Ꝟ)|411|86 (V)|V
42847 (ꝟ)|411|86 (V)|V
42894 (ꞎ)|390|76 (L)|L
42896 (Ꞑ)|540|78 (N)|N
42897 (ꞑ)|540|78 (N)|N
42898 (Ꞓ)|553|67 (C)|C
42899 (ꞓ)|553|67 (C)|C
42900 (ꞔ)|553|67 (C)|C
42901 (ꞕ)|631|72 (H)|H
42902 (Ꞗ)|488|66 (B)|B
42903 (ꞗ)|488|66 (B)|B
42904 (Ꞙ)|453|70 (F)|F
42905 (ꞙ)|453|70 (F)|F
42912 (Ꞡ)|471|71 (G)|G
42913 (ꞡ)|471|71 (G)|G
42914 (Ꞣ)|505|75 (K)|K
42915 (ꞣ)|505|75 (K)|K
42916 (Ꞥ)|540|78 (N)|N
42917 (ꞥ)|540|78 (N)|N
42918 (Ꞧ)|485|82 (R)|R
42919 (ꞧ)|485|82 (R)|R
42920 (Ꞩ)|543|83 (S)|S
42921 (ꞩ)|543|83 (S)|S
42922 (Ɦ)|631|72 (H)|H
42925 (Ɬ)|390|76 (L)|L
42930 (Ʝ)|548|74 (J)|J
43000 (ꟸ)|631|72 (H)|H
43001 (ꟹ)|533|338 (Œ)|Oe
43828 (ꬴ)|457|69 (E)|E
43831 (ꬷ)|390|76 (L)|L
43832 (ꬸ)|390|76 (L)|L
43833 (ꬹ)|390|76 (L)|L
43834 (ꬺ)|528|77 (M)|M
43835 (ꬻ)|540|78 (N)|N
43839 (ꬿ)|368|79 (O)|O
43849 (ꭉ)|485|82 (R)|R
43854 (ꭎ)|493|85 (U)|U
43858 (ꭒ)|493|85 (U)|U
43862 (ꭖ)|672|88 (X)|X
43863 (ꭗ)|672|88 (X)|X
43864 (ꭘ)|672|88 (X)|X
43865 (ꭙ)|672|88 (X)|X
43866 (ꭚ)|404|89 (Y)|Y
43869 (ꭝ)|390|76 (L)|L
43870 (ꭞ)|390|76 (L)|L
43871 (ꭟ)|493|85 (U)|U
64256 (ﬀ)|619|None|Ff
64257 (ﬁ)|469|934 (Φ)|Phi
64258 (ﬂ)|486|None|Fl
64259 (ﬃ)|364|None|FFi
64260 (ﬄ)|763|None|FFl
64261 (ﬅ)|784|None|St
64262 (ﬆ)|784|64261 (ﬅ)|St
64297 (﬩)|396|43 (+)|Plus
65040 (︐)|432|None|Comma
65043 (︓)|656|58 (:)|Colon
65044 (︔)|1029|59 (;)|Semicolon
65045 (︕)|1333|33 (!)|Exclamation mark
65046 (︖)|1161|63 (?)|Question mark
65049 (︙)|997|None|Dot dot dot
65104 (﹐)|432|65040 (︐)|Comma
65106 (﹒)|464|46 (.)|Dot
65108 (﹔)|1029|59 (;)|Semicolon
65109 (﹕)|656|58 (:)|Colon
65110 (﹖)|1161|63 (?)|Question mark
65111 (﹗)|1333|33 (!)|Exclamation mark
65112 (﹘)|706|45 (-)|Dash
65113 (﹙)|1424|8317 (⁽)|Opening parenthases
65114 (﹚)|1526|8318 (⁾)|Closing parentheses
65115 (﹛)|1076|None|Opening brace
65116 (﹜)|1131|None|Closing brace
65119 (﹟)|409|35 (#)|Hash
65120 (﹠)|329|38 (&)|And
65121 (﹡)|850|8727 (∗)|Asterisk
65122 (﹢)|396|43 (+)|Plus
65123 (﹣)|706|45 (-)|Dash
65124 (﹤)|713|60 (<)|Less than
65125 (﹥)|855|62 (>)|Greater than
65126 (﹦)|779|61 (=)|Equals
65128 (﹨)|836|92 (\\)|Backslash
65129 (﹩)|425|36 ($)|Dollar
65130 (﹪)|631|37 (%)|Percent
65131 (﹫)|370|64 (@)|At
65281 (！)|1333|33 (!)|Exclamation mark
65283 (＃)|409|35 (#)|Hash
65284 (＄)|425|36 ($)|Dollar
65285 (％)|631|37 (%)|Percent
65286 (＆)|329|38 (&)|And
65291 (＋)|396|43 (+)|Plus
65293 (－)|706|45 (-)|Dash
65294 (．)|464|46 (.)|Dot
65295 (／)|579|47 (/)|Slash
65296 (０)|605|8304 (⁰)|Zero
65297 (１)|540|49 (1)|One
65298 (２)|415|50 (2)|Two
65299 (３)|513|51 (3)|Three
65300 (４)|629|52 (4)|Four
65301 (５)|680|53 (5)|Five
65302 (６)|612|54 (6)|Six
65303 (７)|377|55 (7)|Seven
65304 (８)|479|56 (8)|Eight
65305 (９)|587|57 (9)|Nine
65306 (：)|656|58 (:)|Colon
65307 (；)|1029|59 (;)|Semicolon
65308 (＜)|713|60 (<)|Less than
65309 (＝)|779|61 (=)|Equals
65310 (＞)|855|62 (>)|Greater than
65311 (？)|1161|63 (?)|Question mark
65312 (＠)|370|64 (@)|At
65313 (Ａ)|528|65 (A)|A
65314 (Ｂ)|488|66 (B)|B
65315 (Ｃ)|553|67 (C)|C
65316 (Ｄ)|407|68 (D)|D
65317 (Ｅ)|457|69 (E)|E
65318 (Ｆ)|453|70 (F)|F
65319 (Ｇ)|471|71 (G)|G
65320 (Ｈ)|631|72 (H)|H
65321 (Ｉ)|478|73 (I)|I
65322 (Ｊ)|548|74 (J)|J
65323 (Ｋ)|505|75 (K)|K
65324 (Ｌ)|390|76 (L)|L
65325 (Ｍ)|528|77 (M)|M
65326 (Ｎ)|540|78 (N)|N
65327 (Ｏ)|368|79 (O)|O
65328 (Ｐ)|411|80 (P)|P
65329 (Ｑ)|495|81 (Q)|Q
65330 (Ｒ)|485|82 (R)|R
65331 (Ｓ)|543|83 (S)|S
65332 (Ｔ)|358|84 (T)|T
65333 (Ｕ)|493|85 (U)|U
65334 (Ｖ)|411|86 (V)|V
65335 (Ｗ)|574|87 (W)|W
65336 (Ｘ)|672|88 (X)|X
65337 (Ｙ)|404|89 (Y)|Y
65338 (Ｚ)|528|90 (Z)|Z
65340 (＼)|836|92 (\\)|Backslash
65342 (＾)|633|94 (^)|Carrot
65343 (＿)|732|95 (_)|Underscore
65345 (ａ)|528|65 (A)|A
65346 (ｂ)|488|66 (B)|B
65347 (ｃ)|553|67 (C)|C
65348 (ｄ)|407|68 (D)|D
65349 (ｅ)|457|69 (E)|E
65350 (ｆ)|453|70 (F)|F
65351 (ｇ)|471|71 (G)|G
65352 (ｈ)|631|72 (H)|H
65353 (ｉ)|478|73 (I)|I
65354 (ｊ)|548|74 (J)|J
65355 (ｋ)|505|75 (K)|K
65356 (ｌ)|390|76 (L)|L
65357 (ｍ)|528|77 (M)|M
65358 (ｎ)|540|78 (N)|N
65359 (ｏ)|368|79 (O)|O
65360 (ｐ)|411|80 (P)|P
65361 (ｑ)|495|81 (Q)|Q
65362 (ｒ)|485|82 (R)|R
65363 (ｓ)|543|83 (S)|S
65364 (ｔ)|358|84 (T)|T
65365 (ｕ)|493|85 (U)|U
65366 (ｖ)|411|86 (V)|V
65367 (ｗ)|574|87 (W)|W
65368 (ｘ)|672|88 (X)|X
65369 (ｙ)|404|89 (Y)|Y
65370 (ｚ)|528|90 (Z)|Z
65504 (￠)|602|162 (¢)|Cent
65505 (￡)|662|163 (£)|Pound
65506 (￢)|761|172 (¬)|Negation
65507 (￣)|616|175 (¯)|Macron
65508 (￤)|952|166 (¦)|Broken bar
65509 (￥)|573|165 (¥)|Yen
65510 (￦)|875|8361 (₩)|Korean won
119808 (𝐀)|482|256 (Ā)|A
119809 (𝐁)|488|66 (B)|B
119810 (𝐂)|553|67 (C)|C
119811 (𝐃)|407|68 (D)|D
119812 (𝐄)|457|69 (E)|E
119813 (𝐅)|453|70 (F)|F
119814 (𝐆)|471|71 (G)|G
119815 (𝐇)|631|72 (H)|H
119816 (𝐈)|478|73 (I)|I
119817 (𝐉)|548|74 (J)|J
119818 (𝐊)|505|75 (K)|K
119819 (𝐋)|390|76 (L)|L
119820 (𝐌)|528|77 (M)|M
119821 (𝐍)|540|78 (N)|N
119822 (𝐎)|368|79 (O)|O
119823 (𝐏)|411|80 (P)|P
119824 (𝐐)|495|81 (Q)|Q
119825 (𝐑)|485|82 (R)|R
119826 (𝐒)|543|83 (S)|S
119827 (𝐓)|358|84 (T)|T
119828 (𝐔)|493|85 (U)|U
119829 (𝐕)|411|86 (V)|V
119830 (𝐖)|574|87 (W)|W
119831 (𝐗)|672|88 (X)|X
119832 (𝐘)|404|89 (Y)|Y
119833 (𝐙)|528|90 (Z)|Z
119834 (𝐚)|482|256 (Ā)|A
119835 (𝐛)|488|66 (B)|B
119836 (𝐜)|553|67 (C)|C
119837 (𝐝)|407|68 (D)|D
119838 (𝐞)|457|69 (E)|E
119839 (𝐟)|453|70 (F)|F
119840 (𝐠)|471|71 (G)|G
119841 (𝐡)|631|72 (H)|H
119842 (𝐢)|478|73 (I)|I
119843 (𝐣)|548|74 (J)|J
119844 (𝐤)|505|75 (K)|K
119845 (𝐥)|390|76 (L)|L
119846 (𝐦)|528|77 (M)|M
119847 (𝐧)|540|78 (N)|N
119848 (𝐨)|368|79 (O)|O
119849 (𝐩)|411|80 (P)|P
119850 (𝐪)|495|81 (Q)|Q
119851 (𝐫)|485|82 (R)|R
119852 (𝐬)|543|83 (S)|S
119853 (𝐭)|358|84 (T)|T
119854 (𝐮)|493|85 (U)|U
119855 (𝐯)|411|86 (V)|V
119856 (𝐰)|574|87 (W)|W
119857 (𝐱)|672|88 (X)|X
119858 (𝐲)|404|89 (Y)|Y
119859 (𝐳)|528|90 (Z)|Z
119860 (𝐴)|482|256 (Ā)|A
119861 (𝐵)|488|66 (B)|B
119862 (𝐶)|553|67 (C)|C
119863 (𝐷)|407|68 (D)|D
119864 (𝐸)|457|69 (E)|E
119865 (𝐹)|453|70 (F)|F
119866 (𝐺)|471|71 (G)|G
119867 (𝐻)|631|72 (H)|H
119868 (𝐼)|478|73 (I)|I
119869 (𝐽)|548|74 (J)|J
119870 (𝐾)|505|75 (K)|K
119871 (𝐿)|390|76 (L)|L
119872 (𝑀)|528|77 (M)|M
119873 (𝑁)|540|78 (N)|N
119874 (𝑂)|368|79 (O)|O
119875 (𝑃)|411|80 (P)|P
119876 (𝑄)|495|81 (Q)|Q
119877 (𝑅)|485|82 (R)|R
119878 (𝑆)|543|83 (S)|S
119879 (𝑇)|358|84 (T)|T
119880 (𝑈)|493|85 (U)|U
119881 (𝑉)|411|86 (V)|V
119882 (𝑊)|574|87 (W)|W
119883 (𝑋)|672|88 (X)|X
119884 (𝑌)|404|89 (Y)|Y
119885 (𝑍)|528|90 (Z)|Z
119886 (𝑎)|482|256 (Ā)|A
119887 (𝑏)|488|66 (B)|B
119888 (𝑐)|553|67 (C)|C
119889 (𝑑)|407|68 (D)|D
119890 (𝑒)|457|69 (E)|E
119891 (𝑓)|453|70 (F)|F
119892 (𝑔)|471|71 (G)|G
119894 (𝑖)|478|73 (I)|I
119895 (𝑗)|548|74 (J)|J
119896 (𝑘)|505|75 (K)|K
119897 (𝑙)|390|76 (L)|L
119898 (𝑚)|528|77 (M)|M
119899 (𝑛)|540|78 (N)|N
119900 (𝑜)|368|79 (O)|O
119901 (𝑝)|411|80 (P)|P
119902 (𝑞)|495|81 (Q)|Q
119903 (𝑟)|485|82 (R)|R
119904 (𝑠)|543|83 (S)|S
119905 (𝑡)|358|84 (T)|T
119906 (𝑢)|493|85 (U)|U
119907 (𝑣)|411|86 (V)|V
119908 (𝑤)|574|87 (W)|W
119909 (𝑥)|672|88 (X)|X
119910 (𝑦)|404|89 (Y)|Y
119911 (𝑧)|528|90 (Z)|Z
119912 (𝑨)|482|256 (Ā)|A
119913 (𝑩)|488|66 (B)|B
119914 (𝑪)|553|67 (C)|C
119915 (𝑫)|407|68 (D)|D
119916 (𝑬)|457|69 (E)|E
119917 (𝑭)|453|70 (F)|F
119918 (𝑮)|471|71 (G)|G
119919 (𝑯)|631|72 (H)|H
119920 (𝑰)|478|73 (I)|I
119921 (𝑱)|548|74 (J)|J
119922 (𝑲)|505|75 (K)|K
119923 (𝑳)|390|76 (L)|L
119924 (𝑴)|528|77 (M)|M
119925 (𝑵)|540|78 (N)|N
119926 (𝑶)|368|79 (O)|O
119927 (𝑷)|411|80 (P)|P
119928 (𝑸)|495|81 (Q)|Q
119929 (𝑹)|485|82 (R)|R
119930 (𝑺)|543|83 (S)|S
119931 (𝑻)|358|84 (T)|T
119932 (𝑼)|493|85 (U)|U
119933 (𝑽)|411|86 (V)|V
119934 (𝑾)|574|87 (W)|W
119935 (𝑿)|672|88 (X)|X
119936 (𝒀)|404|89 (Y)|Y
119937 (𝒁)|528|90 (Z)|Z
119938 (𝒂)|482|256 (Ā)|A
119939 (𝒃)|488|66 (B)|B
119940 (𝒄)|553|67 (C)|C
119941 (𝒅)|407|68 (D)|D
119942 (𝒆)|457|69 (E)|E
119943 (𝒇)|453|70 (F)|F
119944 (𝒈)|471|71 (G)|G
119945 (𝒉)|631|72 (H)|H
119946 (𝒊)|478|73 (I)|I
119947 (𝒋)|548|74 (J)|J
119948 (𝒌)|505|75 (K)|K
119949 (𝒍)|390|76 (L)|L
119950 (𝒎)|528|77 (M)|M
119951 (𝒏)|540|78 (N)|N
119952 (𝒐)|368|79 (O)|O
119953 (𝒑)|411|80 (P)|P
119954 (𝒒)|495|81 (Q)|Q
119955 (𝒓)|485|82 (R)|R
119956 (𝒔)|543|83 (S)|S
119957 (𝒕)|358|84 (T)|T
119958 (𝒖)|493|85 (U)|U
119959 (𝒗)|411|86 (V)|V
119960 (𝒘)|574|87 (W)|W
119961 (𝒙)|672|88 (X)|X
119962 (𝒚)|404|89 (Y)|Y
119963 (𝒛)|528|90 (Z)|Z
119964 (𝒜)|482|256 (Ā)|A
119966 (𝒞)|553|67 (C)|C
119967 (𝒟)|407|68 (D)|D
119970 (𝒢)|471|71 (G)|G
119973 (𝒥)|548|74 (J)|J
119974 (𝒦)|505|75 (K)|K
119977 (𝒩)|540|78 (N)|N
119978 (𝒪)|368|79 (O)|O
119979 (𝒫)|411|80 (P)|P
119980 (𝒬)|495|81 (Q)|Q
119982 (𝒮)|543|83 (S)|S
119983 (𝒯)|358|84 (T)|T
119984 (𝒰)|493|85 (U)|U
119985 (𝒱)|411|86 (V)|V
119986 (𝒲)|574|87 (W)|W
119987 (𝒳)|672|88 (X)|X
119988 (𝒴)|404|89 (Y)|Y
119989 (𝒵)|528|90 (Z)|Z
119990 (𝒶)|482|256 (Ā)|A
119991 (𝒷)|488|66 (B)|B
119992 (𝒸)|553|67 (C)|C
119993 (𝒹)|407|68 (D)|D
119995 (𝒻)|453|70 (F)|F
119997 (𝒽)|631|72 (H)|H
119998 (𝒾)|478|73 (I)|I
119999 (𝒿)|548|74 (J)|J
120000 (𝓀)|505|75 (K)|K
120001 (𝓁)|390|76 (L)|L
120002 (𝓂)|528|77 (M)|M
120003 (𝓃)|540|78 (N)|N
120005 (𝓅)|411|80 (P)|P
120006 (𝓆)|495|81 (Q)|Q
120007 (𝓇)|485|82 (R)|R
120008 (𝓈)|543|83 (S)|S
120009 (𝓉)|358|84 (T)|T
120010 (𝓊)|493|85 (U)|U
120011 (𝓋)|411|86 (V)|V
120012 (𝓌)|574|87 (W)|W
120013 (𝓍)|672|88 (X)|X
120014 (𝓎)|404|89 (Y)|Y
120015 (𝓏)|528|90 (Z)|Z
120016 (𝓐)|482|256 (Ā)|A
120017 (𝓑)|488|66 (B)|B
120018 (𝓒)|553|67 (C)|C
120019 (𝓓)|407|68 (D)|D
120020 (𝓔)|457|69 (E)|E
120021 (𝓕)|453|70 (F)|F
120022 (𝓖)|471|71 (G)|G
120023 (𝓗)|631|72 (H)|H
120024 (𝓘)|478|73 (I)|I
120025 (𝓙)|548|74 (J)|J
120026 (𝓚)|505|75 (K)|K
120027 (𝓛)|390|76 (L)|L
120028 (𝓜)|528|77 (M)|M
120029 (𝓝)|540|78 (N)|N
120030 (𝓞)|368|79 (O)|O
120031 (𝓟)|411|80 (P)|P
120032 (𝓠)|495|81 (Q)|Q
120033 (𝓡)|485|82 (R)|R
120034 (𝓢)|543|83 (S)|S
120035 (𝓣)|358|84 (T)|T
120036 (𝓤)|493|85 (U)|U
120037 (𝓥)|411|86 (V)|V
120038 (𝓦)|574|87 (W)|W
120039 (𝓧)|672|88 (X)|X
120040 (𝓨)|404|89 (Y)|Y
120041 (𝓩)|528|90 (Z)|Z
120042 (𝓪)|482|256 (Ā)|A
120043 (𝓫)|488|66 (B)|B
120044 (𝓬)|553|67 (C)|C
120045 (𝓭)|407|68 (D)|D
120046 (𝓮)|457|69 (E)|E
120047 (𝓯)|453|70 (F)|F
120048 (𝓰)|471|71 (G)|G
120049 (𝓱)|631|72 (H)|H
120050 (𝓲)|478|73 (I)|I
120051 (𝓳)|548|74 (J)|J
120052 (𝓴)|505|75 (K)|K
120053 (𝓵)|390|76 (L)|L
120054 (𝓶)|528|77 (M)|M
120055 (𝓷)|540|78 (N)|N
120056 (𝓸)|368|79 (O)|O
120057 (𝓹)|411|80 (P)|P
120058 (𝓺)|495|81 (Q)|Q
120059 (𝓻)|485|82 (R)|R
120060 (𝓼)|543|83 (S)|S
120061 (𝓽)|358|84 (T)|T
120062 (𝓾)|493|85 (U)|U
120063 (𝓿)|411|86 (V)|V
120064 (𝔀)|574|87 (W)|W
120065 (𝔁)|672|88 (X)|X
120066 (𝔂)|404|89 (Y)|Y
120067 (𝔃)|528|90 (Z)|Z
120068 (𝔄)|482|256 (Ā)|A
120069 (𝔅)|488|66 (B)|B
120071 (𝔇)|407|68 (D)|D
120072 (𝔈)|457|69 (E)|E
120073 (𝔉)|453|70 (F)|F
120074 (𝔊)|471|71 (G)|G
120077 (𝔍)|548|74 (J)|J
120078 (𝔎)|505|75 (K)|K
120079 (𝔏)|390|76 (L)|L
120080 (𝔐)|528|77 (M)|M
120081 (𝔑)|540|78 (N)|N
120082 (𝔒)|368|79 (O)|O
120083 (𝔓)|411|80 (P)|P
120084 (𝔔)|495|81 (Q)|Q
120086 (𝔖)|543|83 (S)|S
120087 (𝔗)|358|84 (T)|T
120088 (𝔘)|493|85 (U)|U
120089 (𝔙)|411|86 (V)|V
120090 (𝔚)|574|87 (W)|W
120091 (𝔛)|672|88 (X)|X
120092 (𝔜)|404|89 (Y)|Y
120094 (𝔞)|482|256 (Ā)|A
120095 (𝔟)|488|66 (B)|B
120096 (𝔠)|553|67 (C)|C
120097 (𝔡)|407|68 (D)|D
120098 (𝔢)|457|69 (E)|E
120099 (𝔣)|453|70 (F)|F
120100 (𝔤)|471|71 (G)|G
120101 (𝔥)|631|72 (H)|H
120102 (𝔦)|478|73 (I)|I
120103 (𝔧)|548|74 (J)|J
120104 (𝔨)|505|75 (K)|K
120105 (𝔩)|390|76 (L)|L
120106 (𝔪)|528|77 (M)|M
120107 (𝔫)|540|78 (N)|N
120108 (𝔬)|368|79 (O)|O
120109 (𝔭)|411|80 (P)|P
120110 (𝔮)|495|81 (Q)|Q
120111 (𝔯)|485|82 (R)|R
120112 (𝔰)|543|83 (S)|S
120113 (𝔱)|358|84 (T)|T
120114 (𝔲)|493|85 (U)|U
120115 (𝔳)|411|86 (V)|V
120116 (𝔴)|574|87 (W)|W
120117 (𝔵)|672|88 (X)|X
120118 (𝔶)|404|89 (Y)|Y
120119 (𝔷)|528|90 (Z)|Z
120120 (𝔸)|482|256 (Ā)|A
120121 (𝔹)|488|66 (B)|B
120123 (𝔻)|407|68 (D)|D
120124 (𝔼)|457|69 (E)|E
120125 (𝔽)|453|70 (F)|F
120126 (𝔾)|471|71 (G)|G
120128 (𝕀)|478|73 (I)|I
120129 (𝕁)|548|74 (J)|J
120130 (𝕂)|505|75 (K)|K
120131 (𝕃)|390|76 (L)|L
120132 (𝕄)|528|77 (M)|M
120134 (𝕆)|368|79 (O)|O
120138 (𝕊)|543|83 (S)|S
120139 (𝕋)|358|84 (T)|T
120140 (𝕌)|493|85 (U)|U
120141 (𝕍)|411|86 (V)|V
120142 (𝕎)|574|87 (W)|W
120143 (𝕏)|672|88 (X)|X
120144 (𝕐)|404|89 (Y)|Y
120146 (𝕒)|482|256 (Ā)|A
120147 (𝕓)|488|66 (B)|B
120148 (𝕔)|553|67 (C)|C
120149 (𝕕)|407|68 (D)|D
120150 (𝕖)|457|69 (E)|E
120151 (𝕗)|453|70 (F)|F
120152 (𝕘)|471|71 (G)|G
120153 (𝕙)|631|72 (H)|H
120154 (𝕚)|478|73 (I)|I
120155 (𝕛)|548|74 (J)|J
120156 (𝕜)|505|75 (K)|K
120157 (𝕝)|390|76 (L)|L
120158 (𝕞)|528|77 (M)|M
120159 (𝕟)|540|78 (N)|N
120160 (𝕠)|368|79 (O)|O
120161 (𝕡)|411|80 (P)|P
120162 (𝕢)|495|81 (Q)|Q
120163 (𝕣)|485|82 (R)|R
120164 (𝕤)|543|83 (S)|S
120165 (𝕥)|358|84 (T)|T
120166 (𝕦)|493|85 (U)|U
120167 (𝕧)|411|86 (V)|V
120168 (𝕨)|574|87 (W)|W
120169 (𝕩)|672|88 (X)|X
120170 (𝕪)|404|89 (Y)|Y
120171 (𝕫)|528|90 (Z)|Z
120172 (𝕬)|482|256 (Ā)|A
120173 (𝕭)|488|66 (B)|B
120174 (𝕮)|553|67 (C)|C
120175 (𝕯)|407|68 (D)|D
120176 (𝕰)|457|69 (E)|E
120177 (𝕱)|453|70 (F)|F
120178 (𝕲)|471|71 (G)|G
120179 (𝕳)|631|72 (H)|H
120180 (𝕴)|478|73 (I)|I
120181 (𝕵)|548|74 (J)|J
120182 (𝕶)|505|75 (K)|K
120183 (𝕷)|390|76 (L)|L
120184 (𝕸)|528|77 (M)|M
120185 (𝕹)|540|78 (N)|N
120186 (𝕺)|368|79 (O)|O
120187 (𝕻)|411|80 (P)|P
120188 (𝕼)|495|81 (Q)|Q
120189 (𝕽)|485|82 (R)|R
120190 (𝕾)|543|83 (S)|S
120191 (𝕿)|358|84 (T)|T
120192 (𝖀)|493|85 (U)|U
120193 (𝖁)|411|86 (V)|V
120194 (𝖂)|574|87 (W)|W
120195 (𝖃)|672|88 (X)|X
120196 (𝖄)|404|89 (Y)|Y
120197 (𝖅)|528|90 (Z)|Z
120198 (𝖆)|482|256 (Ā)|A
120199 (𝖇)|488|66 (B)|B
120200 (𝖈)|553|67 (C)|C
120201 (𝖉)|407|68 (D)|D
120202 (𝖊)|457|69 (E)|E
120203 (𝖋)|453|70 (F)|F
120204 (𝖌)|471|71 (G)|G
120205 (𝖍)|631|72 (H)|H
120206 (𝖎)|478|73 (I)|I
120207 (𝖏)|548|74 (J)|J
120208 (𝖐)|505|75 (K)|K
120209 (𝖑)|390|76 (L)|L
120210 (𝖒)|528|77 (M)|M
120211 (𝖓)|540|78 (N)|N
120212 (𝖔)|368|79 (O)|O
120213 (𝖕)|411|80 (P)|P
120214 (𝖖)|495|81 (Q)|Q
120215 (𝖗)|485|82 (R)|R
120216 (𝖘)|543|83 (S)|S
120217 (𝖙)|358|84 (T)|T
120218 (𝖚)|493|85 (U)|U
120219 (𝖛)|411|86 (V)|V
120220 (𝖜)|574|87 (W)|W
120221 (𝖝)|672|88 (X)|X
120222 (𝖞)|404|89 (Y)|Y
120223 (𝖟)|528|90 (Z)|Z
120224 (𝖠)|482|256 (Ā)|A
120225 (𝖡)|488|66 (B)|B
120226 (𝖢)|553|67 (C)|C
120227 (𝖣)|407|68 (D)|D
120228 (𝖤)|457|69 (E)|E
120229 (𝖥)|453|70 (F)|F
120230 (𝖦)|471|71 (G)|G
120231 (𝖧)|631|72 (H)|H
120232 (𝖨)|478|73 (I)|I
120233 (𝖩)|548|74 (J)|J
120234 (𝖪)|505|75 (K)|K
120235 (𝖫)|390|76 (L)|L
120236 (𝖬)|528|77 (M)|M
120237 (𝖭)|540|78 (N)|N
120238 (𝖮)|368|79 (O)|O
120239 (𝖯)|411|80 (P)|P
120240 (𝖰)|495|81 (Q)|Q
120241 (𝖱)|485|82 (R)|R
120242 (𝖲)|543|83 (S)|S
120243 (𝖳)|358|84 (T)|T
120244 (𝖴)|493|85 (U)|U
120245 (𝖵)|411|86 (V)|V
120246 (𝖶)|574|87 (W)|W
120247 (𝖷)|672|88 (X)|X
120248 (𝖸)|404|89 (Y)|Y
120249 (𝖹)|528|90 (Z)|Z
120250 (𝖺)|482|256 (Ā)|A
120251 (𝖻)|488|66 (B)|B
120252 (𝖼)|553|67 (C)|C
120253 (𝖽)|407|68 (D)|D
120254 (𝖾)|457|69 (E)|E
120255 (𝖿)|453|70 (F)|F
120256 (𝗀)|471|71 (G)|G
120257 (𝗁)|631|72 (H)|H
120258 (𝗂)|478|73 (I)|I
120259 (𝗃)|548|74 (J)|J
120260 (𝗄)|505|75 (K)|K
120261 (𝗅)|390|76 (L)|L
120262 (𝗆)|528|77 (M)|M
120263 (𝗇)|540|78 (N)|N
120264 (𝗈)|368|79 (O)|O
120265 (𝗉)|411|80 (P)|P
120266 (𝗊)|495|81 (Q)|Q
120267 (𝗋)|485|82 (R)|R
120268 (𝗌)|543|83 (S)|S
120269 (𝗍)|358|84 (T)|T
120270 (𝗎)|493|85 (U)|U
120271 (𝗏)|411|86 (V)|V
120272 (𝗐)|574|87 (W)|W
120273 (𝗑)|672|88 (X)|X
120274 (𝗒)|404|89 (Y)|Y
120275 (𝗓)|528|90 (Z)|Z
120276 (𝗔)|482|256 (Ā)|A
120277 (𝗕)|488|66 (B)|B
120278 (𝗖)|553|67 (C)|C
120279 (𝗗)|407|68 (D)|D
120280 (𝗘)|457|69 (E)|E
120281 (𝗙)|453|70 (F)|F
120282 (𝗚)|471|71 (G)|G
120283 (𝗛)|631|72 (H)|H
120284 (𝗜)|478|73 (I)|I
120285 (𝗝)|548|74 (J)|J
120286 (𝗞)|505|75 (K)|K
120287 (𝗟)|390|76 (L)|L
120288 (𝗠)|528|77 (M)|M
120289 (𝗡)|540|78 (N)|N
120290 (𝗢)|368|79 (O)|O
120291 (𝗣)|411|80 (P)|P
120292 (𝗤)|495|81 (Q)|Q
120293 (𝗥)|485|82 (R)|R
120294 (𝗦)|543|83 (S)|S
120295 (𝗧)|358|84 (T)|T
120296 (𝗨)|493|85 (U)|U
120297 (𝗩)|411|86 (V)|V
120298 (𝗪)|574|87 (W)|W
120299 (𝗫)|672|88 (X)|X
120300 (𝗬)|404|89 (Y)|Y
120301 (𝗭)|528|90 (Z)|Z
120302 (𝗮)|482|256 (Ā)|A
120303 (𝗯)|488|66 (B)|B
120304 (𝗰)|553|67 (C)|C
120305 (𝗱)|407|68 (D)|D
120306 (𝗲)|457|69 (E)|E
120307 (𝗳)|453|70 (F)|F
120308 (𝗴)|471|71 (G)|G
120309 (𝗵)|631|72 (H)|H
120310 (𝗶)|478|73 (I)|I
120311 (𝗷)|548|74 (J)|J
120312 (𝗸)|505|75 (K)|K
120313 (𝗹)|390|76 (L)|L
120314 (𝗺)|528|77 (M)|M
120315 (𝗻)|540|78 (N)|N
120316 (𝗼)|368|79 (O)|O
120317 (𝗽)|411|80 (P)|P
120318 (𝗾)|495|81 (Q)|Q
120319 (𝗿)|485|82 (R)|R
120320 (𝘀)|543|83 (S)|S
120321 (𝘁)|358|84 (T)|T
120322 (𝘂)|493|85 (U)|U
120323 (𝘃)|411|86 (V)|V
120324 (𝘄)|574|87 (W)|W
120325 (𝘅)|672|88 (X)|X
120326 (𝘆)|404|89 (Y)|Y
120327 (𝘇)|528|90 (Z)|Z
120328 (𝘈)|482|256 (Ā)|A
120329 (𝘉)|488|66 (B)|B
120330 (𝘊)|553|67 (C)|C
120331 (𝘋)|407|68 (D)|D
120332 (𝘌)|457|69 (E)|E
120333 (𝘍)|453|70 (F)|F
120334 (𝘎)|471|71 (G)|G
120335 (𝘏)|631|72 (H)|H
120336 (𝘐)|478|73 (I)|I
120337 (𝘑)|548|74 (J)|J
120338 (𝘒)|505|75 (K)|K
120339 (𝘓)|390|76 (L)|L
120340 (𝘔)|528|77 (M)|M
120341 (𝘕)|540|78 (N)|N
120342 (𝘖)|368|79 (O)|O
120343 (𝘗)|411|80 (P)|P
120344 (𝘘)|495|81 (Q)|Q
120345 (𝘙)|485|82 (R)|R
120346 (𝘚)|543|83 (S)|S
120347 (𝘛)|358|84 (T)|T
120348 (𝘜)|493|85 (U)|U
120349 (𝘝)|411|86 (V)|V
120350 (𝘞)|574|87 (W)|W
120351 (𝘟)|672|88 (X)|X
120352 (𝘠)|404|89 (Y)|Y
120353 (𝘡)|528|90 (Z)|Z
120354 (𝘢)|482|256 (Ā)|A
120355 (𝘣)|488|66 (B)|B
120356 (𝘤)|553|67 (C)|C
120357 (𝘥)|407|68 (D)|D
120358 (𝘦)|457|69 (E)|E
120359 (𝘧)|453|70 (F)|F
120360 (𝘨)|471|71 (G)|G
120361 (𝘩)|631|72 (H)|H
120362 (𝘪)|478|73 (I)|I
120363 (𝘫)|548|74 (J)|J
120364 (𝘬)|505|75 (K)|K
120365 (𝘭)|390|76 (L)|L
120366 (𝘮)|528|77 (M)|M
120367 (𝘯)|540|78 (N)|N
120368 (𝘰)|368|79 (O)|O
120369 (𝘱)|411|80 (P)|P
120370 (𝘲)|495|81 (Q)|Q
120371 (𝘳)|485|82 (R)|R
120372 (𝘴)|543|83 (S)|S
120373 (𝘵)|358|84 (T)|T
120374 (𝘶)|493|85 (U)|U
120375 (𝘷)|411|86 (V)|V
120376 (𝘸)|574|87 (W)|W
120377 (𝘹)|672|88 (X)|X
120378 (𝘺)|404|89 (Y)|Y
120379 (𝘻)|528|90 (Z)|Z
120380 (𝘼)|482|256 (Ā)|A
120381 (𝘽)|488|66 (B)|B
120382 (𝘾)|553|67 (C)|C
120383 (𝘿)|407|68 (D)|D
120384 (𝙀)|457|69 (E)|E
120385 (𝙁)|453|70 (F)|F
120386 (𝙂)|471|71 (G)|G
120387 (𝙃)|631|72 (H)|H
120388 (𝙄)|478|73 (I)|I
120389 (𝙅)|548|74 (J)|J
120390 (𝙆)|505|75 (K)|K
120391 (𝙇)|390|76 (L)|L
120392 (𝙈)|528|77 (M)|M
120393 (𝙉)|540|78 (N)|N
120394 (𝙊)|368|79 (O)|O
120395 (𝙋)|411|80 (P)|P
120396 (𝙌)|495|81 (Q)|Q
120397 (𝙍)|485|82 (R)|R
120398 (𝙎)|543|83 (S)|S
120399 (𝙏)|358|84 (T)|T
120400 (𝙐)|493|85 (U)|U
120401 (𝙑)|411|86 (V)|V
120402 (𝙒)|574|87 (W)|W
120403 (𝙓)|672|88 (X)|X
120404 (𝙔)|404|89 (Y)|Y
120405 (𝙕)|528|90 (Z)|Z
120406 (𝙖)|482|256 (Ā)|A
120407 (𝙗)|488|66 (B)|B
120408 (𝙘)|553|67 (C)|C
120409 (𝙙)|407|68 (D)|D
120410 (𝙚)|457|69 (E)|E
120411 (𝙛)|453|70 (F)|F
120412 (𝙜)|471|71 (G)|G
120413 (𝙝)|631|72 (H)|H
120414 (𝙞)|478|73 (I)|I
120415 (𝙟)|548|74 (J)|J
120416 (𝙠)|505|75 (K)|K
120417 (𝙡)|390|76 (L)|L
120418 (𝙢)|528|77 (M)|M
120419 (𝙣)|540|78 (N)|N
120420 (𝙤)|368|79 (O)|O
120421 (𝙥)|411|80 (P)|P
120422 (𝙦)|495|81 (Q)|Q
120423 (𝙧)|485|82 (R)|R
120424 (𝙨)|543|83 (S)|S
120425 (𝙩)|358|84 (T)|T
120426 (𝙪)|493|85 (U)|U
120427 (𝙫)|411|86 (V)|V
120428 (𝙬)|574|87 (W)|W
120429 (𝙭)|672|88 (X)|X
120430 (𝙮)|404|89 (Y)|Y
120431 (𝙯)|528|90 (Z)|Z
120432 (𝙰)|482|256 (Ā)|A
120433 (𝙱)|488|66 (B)|B
120434 (𝙲)|553|67 (C)|C
120435 (𝙳)|407|68 (D)|D
120436 (𝙴)|457|69 (E)|E
120437 (𝙵)|453|70 (F)|F
120438 (𝙶)|471|71 (G)|G
120439 (𝙷)|631|72 (H)|H
120440 (𝙸)|478|73 (I)|I
120441 (𝙹)|548|74 (J)|J
120442 (𝙺)|505|75 (K)|K
120443 (𝙻)|390|76 (L)|L
120444 (𝙼)|528|77 (M)|M
120445 (𝙽)|540|78 (N)|N
120446 (𝙾)|368|79 (O)|O
120447 (𝙿)|411|80 (P)|P
120448 (𝚀)|495|81 (Q)|Q
120449 (𝚁)|485|82 (R)|R
120450 (𝚂)|543|83 (S)|S
120451 (𝚃)|358|84 (T)|T
120452 (𝚄)|493|85 (U)|U
120453 (𝚅)|411|86 (V)|V
120454 (𝚆)|574|87 (W)|W
120455 (𝚇)|672|88 (X)|X
120456 (𝚈)|404|89 (Y)|Y
120457 (𝚉)|528|90 (Z)|Z
120458 (𝚊)|482|256 (Ā)|A
120459 (𝚋)|488|66 (B)|B
120460 (𝚌)|553|67 (C)|C
120461 (𝚍)|407|68 (D)|D
120462 (𝚎)|457|69 (E)|E
120463 (𝚏)|453|70 (F)|F
120464 (𝚐)|471|71 (G)|G
120465 (𝚑)|631|72 (H)|H
120466 (𝚒)|478|73 (I)|I
120467 (𝚓)|548|74 (J)|J
120468 (𝚔)|505|75 (K)|K
120469 (𝚕)|390|76 (L)|L
120470 (𝚖)|528|77 (M)|M
120471 (𝚗)|540|78 (N)|N
120472 (𝚘)|368|79 (O)|O
120473 (𝚙)|411|80 (P)|P
120474 (𝚚)|495|81 (Q)|Q
120475 (𝚛)|485|82 (R)|R
120476 (𝚜)|543|83 (S)|S
120477 (𝚝)|358|84 (T)|T
120478 (𝚞)|493|85 (U)|U
120479 (𝚟)|411|86 (V)|V
120480 (𝚠)|574|87 (W)|W
120481 (𝚡)|672|88 (X)|X
120482 (𝚢)|404|89 (Y)|Y
120483 (𝚣)|528|90 (Z)|Z
120488 (𝚨)|571|913 (Α)|Alpha
120489 (𝚩)|516|914 (Β)|Beta
120490 (𝚪)|388|915 (Γ)|Gamma
120491 (𝚫)|490|916 (Δ)|Delta
120492 (𝚬)|740|917 (Ε)|Epsilon
120493 (𝚭)|464|918 (Ζ)|Zetta
120494 (𝚮)|463|919 (Η)|Eta
120495 (𝚯)|568|920 (Θ)|Theta
120496 (𝚰)|581|837 (ͅ)|Iota
120497 (𝚱)|467|922 (Κ)|Kappa
120498 (𝚲)|545|923 (Λ)|Lambda
120499 (𝚳)|513|181 (µ)|Miu
120500 (𝚴)|574|925 (Ν)|Miu
120501 (𝚵)|411|926 (Ξ)|Xi
120502 (𝚶)|800|927 (Ο)|Omicron
120503 (𝚷)|386|928 (Π)|Pi
120504 (𝚸)|442|929 (Ρ)|Ro
120505 (𝚹)|568|920 (Θ)|Theta
120506 (𝚺)|539|931 (Σ)|Sigma
120507 (𝚻)|434|932 (Τ)|Tau
120508 (𝚼)|788|933 (Υ)|Upsilon
120509 (𝚽)|469|934 (Φ)|Phi
120510 (𝚾)|388|935 (Χ)|Chi
120511 (𝚿)|523|936 (Ψ)|Psi
120512 (𝛀)|580|969 (ω)|Omega
120514 (𝛂)|571|913 (Α)|Alpha
120515 (𝛃)|516|914 (Β)|Beta
120516 (𝛄)|388|915 (Γ)|Gamma
120517 (𝛅)|490|916 (Δ)|Delta
120518 (𝛆)|740|917 (Ε)|Epsilon
120519 (𝛇)|464|918 (Ζ)|Zetta
120520 (𝛈)|463|919 (Η)|Eta
120521 (𝛉)|568|920 (Θ)|Theta
120522 (𝛊)|581|837 (ͅ)|Iota
120523 (𝛋)|467|922 (Κ)|Kappa
120524 (𝛌)|545|923 (Λ)|Lambda
120525 (𝛍)|513|181 (µ)|Miu
120526 (𝛎)|574|925 (Ν)|Miu
120527 (𝛏)|411|926 (Ξ)|Xi
120528 (𝛐)|800|927 (Ο)|Omicron
120529 (𝛑)|386|928 (Π)|Pi
120530 (𝛒)|442|929 (Ρ)|Ro
120531 (𝛓)|539|931 (Σ)|Sigma
120532 (𝛔)|539|931 (Σ)|Sigma
120533 (𝛕)|434|932 (Τ)|Tau
120534 (𝛖)|788|933 (Υ)|Upsilon
120535 (𝛗)|469|934 (Φ)|Phi
120536 (𝛘)|388|935 (Χ)|Chi
120537 (𝛙)|523|936 (Ψ)|Psi
120538 (𝛚)|580|969 (ω)|Omega
120540 (𝛜)|740|917 (Ε)|Epsilon
120541 (𝛝)|568|920 (Θ)|Theta
120542 (𝛞)|467|922 (Κ)|Kappa
120543 (𝛟)|469|934 (Φ)|Phi
120544 (𝛠)|442|929 (Ρ)|Ro
120545 (𝛡)|386|928 (Π)|Pi
120546 (𝛢)|571|913 (Α)|Alpha
120547 (𝛣)|516|914 (Β)|Beta
120548 (𝛤)|388|915 (Γ)|Gamma
120549 (𝛥)|490|916 (Δ)|Delta
120550 (𝛦)|740|917 (Ε)|Epsilon
120551 (𝛧)|464|918 (Ζ)|Zetta
120552 (𝛨)|463|919 (Η)|Eta
120553 (𝛩)|568|920 (Θ)|Theta
120554 (𝛪)|581|837 (ͅ)|Iota
120555 (𝛫)|467|922 (Κ)|Kappa
120556 (𝛬)|545|923 (Λ)|Lambda
120557 (𝛭)|513|181 (µ)|Miu
120558 (𝛮)|574|925 (Ν)|Miu
120559 (𝛯)|411|926 (Ξ)|Xi
120560 (𝛰)|800|927 (Ο)|Omicron
120561 (𝛱)|386|928 (Π)|Pi
120562 (𝛲)|442|929 (Ρ)|Ro
120563 (𝛳)|568|920 (Θ)|Theta
120564 (𝛴)|539|931 (Σ)|Sigma
120565 (𝛵)|434|932 (Τ)|Tau
120566 (𝛶)|788|933 (Υ)|Upsilon
120567 (𝛷)|469|934 (Φ)|Phi
120568 (𝛸)|388|935 (Χ)|Chi
120569 (𝛹)|523|936 (Ψ)|Psi
120570 (𝛺)|580|969 (ω)|Omega
120572 (𝛼)|571|913 (Α)|Alpha
120573 (𝛽)|516|914 (Β)|Beta
120574 (𝛾)|388|915 (Γ)|Gamma
120575 (𝛿)|490|916 (Δ)|Delta
120576 (𝜀)|740|917 (Ε)|Epsilon
120577 (𝜁)|464|918 (Ζ)|Zetta
120578 (𝜂)|463|919 (Η)|Eta
120579 (𝜃)|568|920 (Θ)|Theta
120580 (𝜄)|581|837 (ͅ)|Iota
120581 (𝜅)|467|922 (Κ)|Kappa
120582 (𝜆)|545|923 (Λ)|Lambda
120583 (𝜇)|513|181 (µ)|Miu
120584 (𝜈)|574|925 (Ν)|Miu
120585 (𝜉)|411|926 (Ξ)|Xi
120586 (𝜊)|800|927 (Ο)|Omicron
120587 (𝜋)|386|928 (Π)|Pi
120588 (𝜌)|442|929 (Ρ)|Ro
120589 (𝜍)|539|931 (Σ)|Sigma
120590 (𝜎)|539|931 (Σ)|Sigma
120591 (𝜏)|434|932 (Τ)|Tau
120592 (𝜐)|788|933 (Υ)|Upsilon
120593 (𝜑)|469|934 (Φ)|Phi
120594 (𝜒)|388|935 (Χ)|Chi
120595 (𝜓)|523|936 (Ψ)|Psi
120596 (𝜔)|580|969 (ω)|Omega
120598 (𝜖)|740|917 (Ε)|Epsilon
120599 (𝜗)|568|920 (Θ)|Theta
120600 (𝜘)|467|922 (Κ)|Kappa
120601 (𝜙)|469|934 (Φ)|Phi
120602 (𝜚)|442|929 (Ρ)|Ro
120603 (𝜛)|386|928 (Π)|Pi
120604 (𝜜)|571|913 (Α)|Alpha
120605 (𝜝)|516|914 (Β)|Beta
120606 (𝜞)|388|915 (Γ)|Gamma
120607 (𝜟)|490|916 (Δ)|Delta
120608 (𝜠)|740|917 (Ε)|Epsilon
120609 (𝜡)|464|918 (Ζ)|Zetta
120610 (𝜢)|463|919 (Η)|Eta
120611 (𝜣)|568|920 (Θ)|Theta
120612 (𝜤)|581|837 (ͅ)|Iota
120613 (𝜥)|467|922 (Κ)|Kappa
120614 (𝜦)|545|923 (Λ)|Lambda
120615 (𝜧)|513|181 (µ)|Miu
120616 (𝜨)|574|925 (Ν)|Miu
120617 (𝜩)|411|926 (Ξ)|Xi
120618 (𝜪)|800|927 (Ο)|Omicron
120619 (𝜫)|386|928 (Π)|Pi
120620 (𝜬)|442|929 (Ρ)|Ro
120621 (𝜭)|568|920 (Θ)|Theta
120622 (𝜮)|539|931 (Σ)|Sigma
120623 (𝜯)|434|932 (Τ)|Tau
120624 (𝜰)|788|933 (Υ)|Upsilon
120625 (𝜱)|469|934 (Φ)|Phi
120626 (𝜲)|388|935 (Χ)|Chi
120627 (𝜳)|523|936 (Ψ)|Psi
120628 (𝜴)|580|969 (ω)|Omega
120630 (𝜶)|571|913 (Α)|Alpha
120631 (𝜷)|516|914 (Β)|Beta
120632 (𝜸)|388|915 (Γ)|Gamma
120633 (𝜹)|490|916 (Δ)|Delta
120634 (𝜺)|740|917 (Ε)|Epsilon
120635 (𝜻)|464|918 (Ζ)|Zetta
120636 (𝜼)|463|919 (Η)|Eta
120637 (𝜽)|568|920 (Θ)|Theta
120638 (𝜾)|581|837 (ͅ)|Iota
120639 (𝜿)|467|922 (Κ)|Kappa
120640 (𝝀)|545|923 (Λ)|Lambda
120641 (𝝁)|513|181 (µ)|Miu
120642 (𝝂)|574|925 (Ν)|Miu
120643 (𝝃)|411|926 (Ξ)|Xi
120644 (𝝄)|800|927 (Ο)|Omicron
120645 (𝝅)|386|928 (Π)|Pi
120646 (𝝆)|442|929 (Ρ)|Ro
120647 (𝝇)|539|931 (Σ)|Sigma
120648 (𝝈)|539|931 (Σ)|Sigma
120649 (𝝉)|434|932 (Τ)|Tau
120650 (𝝊)|788|933 (Υ)|Upsilon
120651 (𝝋)|469|934 (Φ)|Phi
120652 (𝝌)|388|935 (Χ)|Chi
120653 (𝝍)|523|936 (Ψ)|Psi
120654 (𝝎)|580|969 (ω)|Omega
120656 (𝝐)|740|917 (Ε)|Epsilon
120657 (𝝑)|568|920 (Θ)|Theta
120658 (𝝒)|467|922 (Κ)|Kappa
120659 (𝝓)|469|934 (Φ)|Phi
120660 (𝝔)|442|929 (Ρ)|Ro
120661 (𝝕)|386|928 (Π)|Pi
120662 (𝝖)|571|913 (Α)|Alpha
120663 (𝝗)|516|914 (Β)|Beta
120664 (𝝘)|388|915 (Γ)|Gamma
120665 (𝝙)|490|916 (Δ)|Delta
120666 (𝝚)|740|917 (Ε)|Epsilon
120667 (𝝛)|464|918 (Ζ)|Zetta
120668 (𝝜)|463|919 (Η)|Eta
120669 (𝝝)|568|920 (Θ)|Theta
120670 (𝝞)|581|837 (ͅ)|Iota
120671 (𝝟)|467|922 (Κ)|Kappa
120672 (𝝠)|545|923 (Λ)|Lambda
120673 (𝝡)|513|181 (µ)|Miu
120674 (𝝢)|574|925 (Ν)|Miu
120675 (𝝣)|411|926 (Ξ)|Xi
120676 (𝝤)|800|927 (Ο)|Omicron
120677 (𝝥)|386|928 (Π)|Pi
120678 (𝝦)|442|929 (Ρ)|Ro
120679 (𝝧)|568|920 (Θ)|Theta
120680 (𝝨)|539|931 (Σ)|Sigma
120681 (𝝩)|434|932 (Τ)|Tau
120682 (𝝪)|788|933 (Υ)|Upsilon
120683 (𝝫)|469|934 (Φ)|Phi
120684 (𝝬)|388|935 (Χ)|Chi
120685 (𝝭)|523|936 (Ψ)|Psi
120686 (𝝮)|580|969 (ω)|Omega
120688 (𝝰)|571|913 (Α)|Alpha
120689 (𝝱)|516|914 (Β)|Beta
120690 (𝝲)|388|915 (Γ)|Gamma
120691 (𝝳)|490|916 (Δ)|Delta
120692 (𝝴)|740|917 (Ε)|Epsilon
120693 (𝝵)|464|918 (Ζ)|Zetta
120694 (𝝶)|463|919 (Η)|Eta
120695 (𝝷)|568|920 (Θ)|Theta
120696 (𝝸)|581|837 (ͅ)|Iota
120697 (𝝹)|467|922 (Κ)|Kappa
120698 (𝝺)|545|923 (Λ)|Lambda
120699 (𝝻)|513|181 (µ)|Miu
120700 (𝝼)|574|925 (Ν)|Miu
120701 (𝝽)|411|926 (Ξ)|Xi
120702 (𝝾)|800|927 (Ο)|Omicron
120703 (𝝿)|386|928 (Π)|Pi
120704 (𝞀)|442|929 (Ρ)|Ro
120705 (𝞁)|539|931 (Σ)|Sigma
120706 (𝞂)|539|931 (Σ)|Sigma
120707 (𝞃)|434|932 (Τ)|Tau
120708 (𝞄)|788|933 (Υ)|Upsilon
120709 (𝞅)|469|934 (Φ)|Phi
120710 (𝞆)|388|935 (Χ)|Chi
120711 (𝞇)|523|936 (Ψ)|Psi
120712 (𝞈)|580|969 (ω)|Omega
120714 (𝞊)|740|917 (Ε)|Epsilon
120715 (𝞋)|568|920 (Θ)|Theta
120716 (𝞌)|467|922 (Κ)|Kappa
120717 (𝞍)|469|934 (Φ)|Phi
120718 (𝞎)|442|929 (Ρ)|Ro
120719 (𝞏)|386|928 (Π)|Pi
120720 (𝞐)|571|913 (Α)|Alpha
120721 (𝞑)|516|914 (Β)|Beta
120722 (𝞒)|388|915 (Γ)|Gamma
120723 (𝞓)|490|916 (Δ)|Delta
120724 (𝞔)|740|917 (Ε)|Epsilon
120725 (𝞕)|464|918 (Ζ)|Zetta
120726 (𝞖)|463|919 (Η)|Eta
120727 (𝞗)|568|920 (Θ)|Theta
120728 (𝞘)|581|837 (ͅ)|Iota
120729 (𝞙)|467|922 (Κ)|Kappa
120730 (𝞚)|545|923 (Λ)|Lambda
120731 (𝞛)|513|181 (µ)|Miu
120732 (𝞜)|574|925 (Ν)|Miu
120733 (𝞝)|411|926 (Ξ)|Xi
120734 (𝞞)|800|927 (Ο)|Omicron
120735 (𝞟)|386|928 (Π)|Pi
120736 (𝞠)|442|929 (Ρ)|Ro
120737 (𝞡)|568|920 (Θ)|Theta
120738 (𝞢)|539|931 (Σ)|Sigma
120739 (𝞣)|434|932 (Τ)|Tau
120740 (𝞤)|788|933 (Υ)|Upsilon
120741 (𝞥)|469|934 (Φ)|Phi
120742 (𝞦)|388|935 (Χ)|Chi
120743 (𝞧)|523|936 (Ψ)|Psi
120744 (𝞨)|580|969 (ω)|Omega
120746 (𝞪)|571|913 (Α)|Alpha
120747 (𝞫)|516|914 (Β)|Beta
120748 (𝞬)|388|915 (Γ)|Gamma
120749 (𝞭)|490|916 (Δ)|Delta
120750 (𝞮)|740|917 (Ε)|Epsilon
120751 (𝞯)|464|918 (Ζ)|Zetta
120752 (𝞰)|463|919 (Η)|Eta
120753 (𝞱)|568|920 (Θ)|Theta
120754 (𝞲)|581|837 (ͅ)|Iota
120755 (𝞳)|467|922 (Κ)|Kappa
120756 (𝞴)|545|923 (Λ)|Lambda
120757 (𝞵)|513|181 (µ)|Miu
120758 (𝞶)|574|925 (Ν)|Miu
120759 (𝞷)|411|926 (Ξ)|Xi
120760 (𝞸)|800|927 (Ο)|Omicron
120761 (𝞹)|386|928 (Π)|Pi
120762 (𝞺)|442|929 (Ρ)|Ro
120763 (𝞻)|539|931 (Σ)|Sigma
120764 (𝞼)|539|931 (Σ)|Sigma
120765 (𝞽)|434|932 (Τ)|Tau
120766 (𝞾)|788|933 (Υ)|Upsilon
120767 (𝞿)|469|934 (Φ)|Phi
120768 (𝟀)|388|935 (Χ)|Chi
120769 (𝟁)|523|936 (Ψ)|Psi
120770 (𝟂)|580|969 (ω)|Omega
120772 (𝟄)|740|917 (Ε)|Epsilon
120773 (𝟅)|568|920 (Θ)|Theta
120774 (𝟆)|467|922 (Κ)|Kappa
120775 (𝟇)|469|934 (Φ)|Phi
120776 (𝟈)|442|929 (Ρ)|Ro
120777 (𝟉)|386|928 (Π)|Pi
120782 (𝟎)|605|8304 (⁰)|Zero
120783 (𝟏)|540|49 (1)|One
120784 (𝟐)|415|50 (2)|Two
120785 (𝟑)|513|51 (3)|Three
120786 (𝟒)|629|52 (4)|Four
120787 (𝟓)|680|53 (5)|Five
120788 (𝟔)|612|54 (6)|Six
120789 (𝟕)|377|55 (7)|Seven
120790 (𝟖)|479|56 (8)|Eight
120791 (𝟗)|587|57 (9)|Nine
120792 (𝟘)|605|8304 (⁰)|Zero
120793 (𝟙)|540|49 (1)|One
120794 (𝟚)|415|50 (2)|Two
120795 (𝟛)|513|51 (3)|Three
120796 (𝟜)|629|52 (4)|Four
120797 (𝟝)|680|53 (5)|Five
120798 (𝟞)|612|54 (6)|Six
120799 (𝟟)|377|55 (7)|Seven
120800 (𝟠)|479|56 (8)|Eight
120801 (𝟡)|587|57 (9)|Nine
120802 (𝟢)|605|8304 (⁰)|Zero
120803 (𝟣)|540|49 (1)|One
120804 (𝟤)|415|50 (2)|Two
120805 (𝟥)|513|51 (3)|Three
120806 (𝟦)|629|52 (4)|Four
120807 (𝟧)|680|53 (5)|Five
120808 (𝟨)|612|54 (6)|Six
120809 (𝟩)|377|55 (7)|Seven
120810 (𝟪)|479|56 (8)|Eight
120811 (𝟫)|587|57 (9)|Nine
120812 (𝟬)|605|8304 (⁰)|Zero
120813 (𝟭)|540|49 (1)|One
120814 (𝟮)|415|50 (2)|Two
120815 (𝟯)|513|51 (3)|Three
120816 (𝟰)|629|52 (4)|Four
120817 (𝟱)|680|53 (5)|Five
120818 (𝟲)|612|54 (6)|Six
120819 (𝟳)|377|55 (7)|Seven
120820 (𝟴)|479|56 (8)|Eight
120821 (𝟵)|587|57 (9)|Nine
120822 (𝟶)|605|8304 (⁰)|Zero
120823 (𝟷)|540|49 (1)|One
120824 (𝟸)|415|50 (2)|Two
120825 (𝟹)|513|51 (3)|Three
120826 (𝟺)|629|52 (4)|Four
120827 (𝟻)|680|53 (5)|Five
120828 (𝟼)|612|54 (6)|Six
120829 (𝟽)|377|55 (7)|Seven
120830 (𝟾)|479|56 (8)|Eight
120831 (𝟿)|587|57 (9)|Nine
126980 (🀄)|2030|None|Red dragon mahjong tile
127183 (🃏)|1557|None|Joker playing card
127232 (🄀)|971|None|Zero dot
127233 (🄁)|996|None|Zero comma
127234 (🄂)|793|None|One comma
127235 (🄃)|686|None|Two comma
127236 (🄄)|746|None|Three comma
127237 (🄅)|685|None|Four comma
127238 (🄆)|912|None|Five comma
127239 (🄇)|891|None|Six comma
127240 (🄈)|785|None|Seven comma
127241 (🄉)|766|None|Eight comma
127242 (🄊)|820|None|Nine comma
127248 (🄐)|2859|9372 (⒜)|Opening parenthases A closing parenthases
127249 (🄑)|2878|9373 (⒝)|Opening parenthases B closing parenthases
127250 (🄒)|2956|9374 (⒞)|Opening parenthases C closing parenthases
127251 (🄓)|2865|9375 (⒟)|Opening parenthases D closing parenthases
127252 (🄔)|2797|9376 (⒠)|Opening parenthases E closing parenthases
127253 (🄕)|2834|9377 (⒡)|Opening parenthases F closing parenthases
127254 (🄖)|2993|9378 (⒢)|Opening parenthases G closing parenthases
127255 (🄗)|3047|9379 (⒣)|Opening parenthases H closing parenthases
127256 (🄘)|2841|9380 (⒤)|Opening parenthases I closing parenthases
127257 (🄙)|2980|9381 (⒥)|Opening parenthases J closing parenthases
127258 (🄚)|2949|9382 (⒦)|Opening parenthases K closing parenthases
127259 (🄛)|2870|9383 (⒧)|Opening parenthases L closing parenthases
127260 (🄜)|2838|9384 (⒨)|Opening parenthases M closing parenthases
127261 (🄝)|2816|9385 (⒩)|Opening parenthases N closing parenthases
127262 (🄞)|2930|9386 (⒪)|Opening parenthases O closing parenthases
127263 (🄟)|2967|9387 (⒫)|Opening parenthases P closing parenthases
127264 (🄠)|2881|9388 (⒬)|Opening parenthases Q closing parenthases
127265 (🄡)|2776|9389 (⒭)|Opening parenthases R closing parenthases
127266 (🄢)|2889|9390 (⒮)|Opening parenthases S closing parenthases
127267 (🄣)|2923|9391 (⒯)|Opening parenthases T closing parenthases
127268 (🄤)|2843|9392 (⒰)|Opening parenthases U closing parenthases
127269 (🄥)|2876|9393 (⒱)|Opening parenthases V closing parenthases
127270 (🄦)|3248|9394 (⒲)|Opening parenthases W closing parenthases
127271 (🄧)|2904|9395 (⒳)|Opening parenthases X closing parenthases
127272 (🄨)|2849|9396 (⒴)|Opening parenthases Y closing parenthases
127273 (🄩)|3119|9397 (⒵)|Opening parenthases Z closing parenthases
127274 (🄪)|543|83 (S)|S
127275 (🄫)|553|67 (C)|C
127276 (🄬)|485|82 (R)|R
127277 (🄭)|710|None|CD
127278 (🄮)|892|None|Wz
127280 (🄰)|482|256 (Ā)|A
127281 (🄱)|488|66 (B)|B
127282 (🄲)|553|67 (C)|C
127283 (🄳)|407|68 (D)|D
127284 (🄴)|457|69 (E)|E
127285 (🄵)|453|70 (F)|F
127286 (🄶)|471|71 (G)|G
127287 (🄷)|631|72 (H)|H
127288 (🄸)|478|73 (I)|I
127289 (🄹)|548|74 (J)|J
127290 (🄺)|505|75 (K)|K
127291 (🄻)|390|76 (L)|L
127292 (🄼)|528|77 (M)|M
127293 (🄽)|540|78 (N)|N
127294 (🄾)|368|79 (O)|O
127295 (🄿)|411|80 (P)|P
127296 (🅀)|495|81 (Q)|Q
127297 (🅁)|485|82 (R)|R
127298 (🅂)|543|83 (S)|S
127299 (🅃)|358|84 (T)|T
127300 (🅄)|493|85 (U)|U
127301 (🅅)|411|86 (V)|V
127302 (🅆)|574|87 (W)|W
127303 (🅇)|672|88 (X)|X
127304 (🅈)|404|89 (Y)|Y
127305 (🅉)|528|90 (Z)|Z
127306 (🅊)|769|None|Hw
127307 (🅋)|559|None|Mv
127308 (🅌)|611|None|Sd
127309 (🅍)|652|None|Ss
127310 (🅎)|768|None|Ppv
127311 (🅏)|801|None|Wc
127338 (🅪)|568|None|Mc
127339 (🅫)|614|None|Md
127344 (🅰)|1396|None|Letter A in square
127345 (🅱)|1443|None|Letter B in square
127358 (🅾)|1455|None|Letter O in square
127359 (🅿)|1364|None|Letter P in square
127374 (🆎)|1909|None|Letters AB in square
127376 (🆐)|683|None|Dj
127377 (🆑)|737|None|Cl
127378 (🆒)|617|None|Cool
127379 (🆓)|604|None|Free
127380 (🆔)|734|None|Id
127381 (🆕)|719|None|New
127382 (🆖)|510|None|Ng (???)
127383 (🆗)|827|None|Ok
127384 (🆘)|1010|None|SOS
127385 (🆙)|551|None|Up
127386 (🆚)|905|None|Versus
127489 (🈁)|1361|None|Katakana koko
127490 (🈂)|1306|None|Katakana sa
127514 (🈚)|1823|None|Chinese for nothingness
127535 (🈯)|1504|None|Chinese for finger
127538 (🈲)|1626|None|Chinese for prohibition
127539 (🈳)|2760|None|Chinese for emptyness or sky
127540 (🈴)|1558|None|Chinese for unity
127541 (🈵)|1576|None|Chinese for fullness
127542 (🈶)|1770|None|Chinese for existence
127543 (🈷)|1458|None|Chinese for moon
127544 (🈸)|1650|None|Chinese for statement
127545 (🈹)|1476|None|Chinese for division
127546 (🈺)|1664|None|Chinese for management
127568 (🉐)|1955|None|Chinese for equisition
127569 (🉑)|1959|None|Chinese for posibility
127744 (🌀)|1092|None|Cyclone
127745 (🌁)|637|None|Foggy
127746 (🌂)|1188|None|Closed umbrella
127747 (🌃)|1414|None|City scape at night
127748 (🌄)|1799|None|Sunrise over mountains
127749 (🌅)|1051|None|Sunrise
127750 (🌆)|1584|None|City scape at dusk
127751 (🌇)|1776|None|City scape at sunset
127752 (🌈)|776|None|Rainbow
127753 (🌉)|1069|None|Bridge at night
127754 (🌊)|1088|None|Ocean wave
127755 (🌋)|1117|None|Volcano
127756 (🌌)|1042|None|Milky way
127757 (🌍)|797|None|Africa
127758 (🌎)|928|None|Americas
127759 (🌏)|639|None|Globe
127760 (🌐)|1269|None|Meridian globe
127761 (🌑)|1066|None|New moon
127762 (🌒)|1840|None|Waxing crescent moon
127763 (🌓)|1074|None|Quarter moon
127764 (🌔)|1724|None|Waxing gibbous moon
127765 (🌕)|999|None|Full moon
127766 (🌖)|1603|None|Waning gibbous moon
127767 (🌗)|1495|None|Last quarter moon
127768 (🌘)|1679|None|Waning crescent moon
127769 (🌙)|1137|None|Crescent moon
127770 (🌚)|1336|None|New moon with face
127771 (🌛)|1650|None|Quarter moon with face
127772 (🌜)|1936|None|Last quarter moon with face
127773 (🌝)|1415|None|Full moon with face
127774 (🌞)|1218|None|Sun with face
127775 (🌟)|1189|None|Glowing star
127776 (🌠)|1165|None|Shooting star
127777 (🌡)|948|None|Thermometer
127780 (🌤)|1447|None|Sunny with clouds
127781 (🌥)|1447|127780 (🌤)|Sunny with clouds
127782 (🌦)|2106|None|Sunny with clouds and showers
127783 (🌧)|1009|None|Rain cloud
127784 (🌨)|1078|None|Snow cloud
127785 (🌩)|1108|None|Thunderstorm
127786 (🌪)|892|None|Tornado
127787 (🌫)|554|None|Fog
127788 (🌬)|832|None|Gale
127789 (🌭)|1163|None|Hotdog
127790 (🌮)|663|None|Taco
127791 (🌯)|863|None|Buritto
127792 (🌰)|876|None|Chesnut
127793 (🌱)|809|None|Seedling
127794 (🌲)|1289|None|Evergreen tree
127795 (🌳)|1423|None|Deciduous tree
127796 (🌴)|1124|None|Palm tree
127797 (🌵)|827|None|Cactus
127798 (🌶)|841|None|Hot pepper
127799 (🌷)|708|None|Tulip
127800 (🌸)|1091|None|Cherry blossom
127801 (🌹)|697|None|Rose
127802 (🌺)|1019|None|Hibiscus
127803 (🌻)|1002|None|Sunflower
127804 (🌼)|721|None|Blossom
127805 (🌽)|655|None|Corn
127806 (🌾)|1088|None|Ear of rice
127807 (🌿)|748|None|Herb
127808 (🍀)|1288|None|Full leaf clover
127809 (🍁)|1255|None|Maple leaf
127810 (🍂)|975|None|Fallen leaf
127811 (🍃)|1044|None|Falling leaf
127812 (🍄)|850|None|Mushroom
127813 (🍅)|882|None|Tomato
127814 (🍆)|831|None|Aubergine
127815 (🍇)|815|None|Grapes
127816 (🍈)|641|None|Melon
127817 (🍉)|1043|None|Watermelon
127818 (🍊)|1086|None|Tangerine
127819 (🍋)|671|None|Lemon
127820 (🍌)|787|None|Banana
127821 (🍍)|879|None|Pineapple
127822 (🍎)|818|None|Red apple
127823 (🍏)|901|None|Green apple
127824 (🍐)|513|None|Pair
127825 (🍑)|751|None|Peach
127826 (🍒)|791|None|Cherries
127827 (🍓)|901|None|Strawberry
127828 (🍔)|913|None|Hamburger
127829 (🍕)|1289|None|Slice of pizza
127830 (🍖)|569|None|Meat
127831 (🍗)|1089|None|Poultry leg
127832 (🍘)|1213|None|Rice cracker
127833 (🍙)|1063|None|Rice bowl
127834 (🍚)|979|None|Cooked rice
127835 (🍛)|974|None|Curry rice
127836 (🍜)|1252|None|Steaming bowl
127837 (🍝)|840|None|Spaghetti
127838 (🍞)|659|None|Bread
127839 (🍟)|743|None|Chips
127840 (🍠)|1859|None|Roasted sweet potato
127841 (🍡)|907|None|Dango
127842 (🍢)|703|None|Oden
127843 (🍣)|674|None|Sushi
127844 (🍤)|985|None|Fried shrimp
127845 (🍥)|962|None|Fish cake
127846 (🍦)|1795|None|Soft serve ice cream
127847 (🍧)|1121|None|Shaved ice
127848 (🍨)|1063|None|Ice cream
127849 (🍩)|876|None|Donut
127850 (🍪)|726|None|Cookie
127851 (🍫)|1209|None|Chocolate bar
127852 (🍬)|836|None|Sweet
127853 (🍭)|830|None|Lolly pop
127854 (🍮)|804|None|Custard
127855 (🍯)|939|None|Honeypot
127856 (🍰)|970|None|Shortcake
127857 (🍱)|1288|None|Bento box
127858 (🍲)|1029|None|Pot of food
127859 (🍳)|1059|None|Frying an egg
127860 (🍴)|1118|None|Fork and knife
127861 (🍵)|647|None|Tea
127862 (🍶)|668|None|Sake
127863 (🍷)|1014|None|Wine glass
127864 (🍸)|1403|None|Cocktail glass
127865 (🍹)|1260|None|Tropical drink
127866 (🍺)|583|None|Beer
127867 (🍻)|1583|None|Clicking beer mugs
127868 (🍼)|1155|None|Baby bottle
127869 (🍽)|566|None|Dinner
127870 (🍾)|1374|None|Champagne bottle
127871 (🍿)|994|None|Popcorn
127872 (🎀)|619|None|Ribbon
127873 (🎁)|728|None|Present
127874 (🎂)|1364|None|Birthday cake
127875 (🎃)|1116|None|Jack o lantern
127876 (🎄)|1313|None|Christmas tree
127877 (🎅)|1376|None|Santa claus
127878 (🎆)|1089|None|Fireworks
127879 (🎇)|845|None|Sparkler
127880 (🎈)|713|None|Baloon
127881 (🎉)|1008|None|Party popper
127882 (🎊)|1281|None|Confetti ball
127883 (🎋)|1269|None|Tanabata tree
127884 (🎌)|1192|None|Crossed flags
127885 (🎍)|1260|None|Pine decoration
127886 (🎎)|1461|None|Japanese dolls
127887 (🎏)|1184|None|Carp streamer
127888 (🎐)|1059|None|Wind chime
127889 (🎑)|1735|None|Moon viewing ceremony
127890 (🎒)|729|None|Satchel
127891 (🎓)|1394|None|Graduation cap
127894 (🎖)|978|None|Military medal
127895 (🎗)|1267|None|Awareness ribbon
127897 (🎙)|977|None|Microphone
127898 (🎚)|920|None|Equalizer
127899 (🎛)|710|None|Knobs
127902 (🎞)|1195|None|Film frames
127903 (🎟)|1235|None|Admission tickets
127904 (🎠)|1309|None|Carusel horse
127905 (🎡)|1090|None|Ferris wheel
127906 (🎢)|1085|None|Rollercoaster
127907 (🎣)|766|None|Fishing
127908 (🎤)|977|127897 (🎙)|Microphone
127909 (🎥)|990|None|Film camera
127910 (🎦)|707|None|Cinema
127911 (🎧)|956|None|Headphone
127912 (🎨)|1222|None|Artist pallet
127913 (🎩)|834|None|Top hat
127914 (🎪)|1024|None|Circus tent
127915 (🎫)|608|None|Ticket
127916 (🎬)|1021|None|Clapper board
127917 (🎭)|1287|None|Performing arts
127918 (🎮)|1137|None|Video game
127919 (🎯)|829|None|Bullseye
127920 (🎰)|1188|None|Slot machine
127921 (🎱)|940|None|Billiards
127922 (🎲)|812|None|Dice
127923 (🎳)|699|None|Bowling
127924 (🎴)|1391|None|Hanafuda cards
127925 (🎵)|1284|None|Musical note
127926 (🎶)|1441|None|Musical notes
127927 (🎷)|1149|None|Saxophone
127928 (🎸)|795|None|Guitar
127929 (🎹)|912|None|Piano
127930 (🎺)|830|None|Trumpet
127931 (🎻)|908|None|Violin
127932 (🎼)|1711|None|Treble clef with staff
127933 (🎽)|1007|None|Running shirt
127934 (🎾)|760|None|Tennis
127935 (🎿)|811|None|Skies
127936 (🏀)|1245|None|Basketball
127937 (🏁)|1054|None|Checkered flag
127938 (🏂)|1116|None|Snowboarder
127939 (🏃)|993|None|Man running
127940 (🏄)|853|None|Surfer
127941 (🏅)|1172|None|Sports medal
127942 (🏆)|761|None|Trophy
127943 (🏇)|801|None|Jockey
127944 (🏈)|1336|None|American football
127945 (🏉)|1228|None|Rugby football
127946 (🏊)|662|None|Swimmer
127947 (🏋)|943|None|Weightlifter
127948 (🏌)|892|None|Golfer
127949 (🏍)|929|None|Motobike
127950 (🏎)|1269|None|Racing car
127951 (🏏)|655|None|Cricket
127952 (🏐)|996|None|Volleyball
127953 (🏑)|1111|None|Field hockey
127954 (🏒)|1019|None|Ice hockey
127955 (🏓)|1198|None|Table tennis
127956 (🏔)|754|None|Alps
127957 (🏕)|819|None|Camping
127958 (🏖)|662|None|Beach
127959 (🏗)|1575|None|Building construction
127960 (🏘)|889|None|Neighborhood
127961 (🏙)|840|None|City scape
127962 (🏚)|1215|None|Derilict house
127963 (🏛)|955|None|Landmark
127964 (🏜)|633|None|Desert
127965 (🏝)|1108|None|Desert island
127966 (🏞)|1101|None|National park
127967 (🏟)|795|None|Stadium
127968 (🏠)|730|None|House
127969 (🏡)|1243|None|House with garden
127970 (🏢)|1114|None|Office building
127971 (🏣)|1058|None|Post office
127972 (🏤)|1663|None|European post office
127973 (🏥)|983|None|Hospital
127974 (🏦)|621|None|Bank
127975 (🏧)|1016|None|ATM
127976 (🏨)|892|None|Hotel
127977 (🏩)|1132|None|Love hotel
127978 (🏪)|1681|None|Convenience store
127979 (🏫)|597|None|School
127980 (🏬)|1356|None|Department store
127981 (🏭)|811|None|Factory
127982 (🏮)|1455|None|Izakaya lantern
127983 (🏯)|1359|None|Japanese castle
127984 (🏰)|1340|None|European castle
127987 (🏳)|944|None|White flag
127988 (🏴)|952|None|Black flag
127989 (🏵)|754|None|Rosette
127991 (🏷)|860|None|Label
127992 (🏸)|923|None|Badminton
127993 (🏹)|1131|None|Bow and arrow
127994 (🏺)|730|None|Amphora
127995 (🏻)|1078|None|Fair skin
127996 (🏼)|1444|None|Light brown skin
127997 (🏽)|1084|None|Olive skin
127998 (🏾)|1277|None|Brown skin
127999 (🏿)|1123|None|Dark skin
128000 (🐀)|614|None|Rat
128001 (🐁)|672|None|Mouse
128002 (🐂)|784|None|Ox
128003 (🐃)|1301|None|Water buffalo
128004 (🐄)|500|None|Cow
128005 (🐅)|822|None|Tiger
128006 (🐆)|689|None|Leopard
128007 (🐇)|654|None|Rabbit
128008 (🐈)|737|None|Cat
128009 (🐉)|664|None|Dragon
128010 (🐊)|989|None|Crocodile
128011 (🐋)|700|None|Whale
128012 (🐌)|837|None|Snail
128013 (🐍)|753|None|Snake
128014 (🐎)|721|None|Horse
128015 (🐏)|583|None|Ram
128016 (🐐)|664|None|Goat
128017 (🐑)|960|None|Sheep
128018 (🐒)|754|None|Monkey
128019 (🐓)|732|None|Rooster
128020 (🐔)|720|None|Chicken
128021 (🐕)|555|None|Dog
128022 (🐖)|604|None|Pig
128023 (🐗)|539|None|Boar
128024 (🐘)|801|None|Elephant (???)
128025 (🐙)|956|None|Octopus
128026 (🐚)|1093|None|Spiral shell
128027 (🐛)|1036|None|Centipede
128028 (🐜)|608|None|Ant
128029 (🐝)|1021|None|Honey bee
128030 (🐞)|1291|None|Ladybug
128031 (🐟)|560|None|Fish
128032 (🐠)|1202|None|Tropical fish
128033 (🐡)|839|None|Blowfish
128034 (🐢)|779|None|Turtle
128035 (🐣)|1089|None|Haching chick
128036 (🐤)|1095|None|Baby chick
128037 (🐥)|1853|None|Front facing baby chick
128038 (🐦)|627|None|Bird
128039 (🐧)|788|None|Penguin
128040 (🐨)|748|None|Koala
128041 (🐩)|871|None|Poodle
128042 (🐪)|597|None|Camel
128043 (🐫)|597|128042 (🐪)|Camel
128044 (🐬)|740|None|Dolphin
128045 (🐭)|672|128001 (🐁)|Mouse
128046 (🐮)|500|128004 (🐄)|Cow
128047 (🐯)|822|128005 (🐅)|Tiger
128048 (🐰)|654|128007 (🐇)|Rabbit
128049 (🐱)|737|128008 (🐈)|Cat
128050 (🐲)|664|128009 (🐉)|Dragon
128051 (🐳)|1383|None|Spouting whale
128052 (🐴)|721|128014 (🐎)|Horse
128053 (🐵)|754|128018 (🐒)|Monkey
128054 (🐶)|555|128021 (🐕)|Dog
128055 (🐷)|604|128022 (🐖)|Pig
128056 (🐸)|652|None|Frog
128057 (🐹)|865|None|Hamster
128058 (🐺)|726|None|Wolf
128059 (🐻)|645|None|Bear
128060 (🐼)|739|None|Panda
128061 (🐽)|1039|None|Pig nose
128062 (🐾)|1216|None|Paw prints
128063 (🐿)|988|None|Chipmunk
128064 (👀)|858|None|Eyes
128065 (👁)|515|None|Eye
128066 (👂)|553|None|Ear
128067 (👃)|809|None|Nose
128068 (👄)|648|None|Mouth
128069 (👅)|589|None|Tongue
128070 (👆)|1519|None|Up pointing finger
128071 (👇)|1723|None|Down pointing finger
128072 (👈)|1615|None|Left pointing finger
128073 (👉)|1625|None|Right pointing finger
128074 (👊)|642|None|Fist
128075 (👋)|1136|None|Waving hand
128076 (👌)|1371|None|A OK hand
128077 (👍)|777|None|Thumbs up
128078 (👎)|1147|None|Thumbs down
128079 (👏)|1273|None|Clapping hands
128080 (👐)|1138|None|Open hands
128081 (👑)|675|None|Crown
128082 (👒)|1295|None|Womans hat
128083 (👓)|1023|None|Eyeglasses
128084 (👔)|807|None|Neck tie
128085 (👕)|884|None|T-Shirt
128086 (👖)|957|None|Jeans
128087 (👗)|694|None|Dress
128088 (👘)|936|None|Kimono
128089 (👙)|937|None|Bikini
128090 (👚)|1504|None|Womans clothes
128091 (👛)|660|None|Purse
128092 (👜)|958|None|Handbag
128093 (👝)|806|None|Pouch
128094 (👞)|911|None|Mans shoe
128095 (👟)|1010|None|Athletic shoe
128096 (👠)|1179|None|High heeled shoe
128097 (👡)|1225|None|Womans sandal
128098 (👢)|1354|None|Womans boots
128099 (👣)|1010|None|Footprints
128100 (👤)|691|None|Bust
128101 (👥)|1585|None|Silhouetted busts
128102 (👦)|618|None|Boy
128103 (👧)|778|None|Girl
128104 (👨)|794|None|Man
128105 (👩)|600|None|Woman
128106 (👪)|711|None|Family
128107 (👫)|2069|None|Man and woman holding hands
128108 (👬)|1508|None|Men holding hands
128109 (👭)|1761|None|Women holding hands
128110 (👮)|1096|None|Police officer
128111 (👯)|1861|None|Woman with bunny ears
128112 (👰)|1202|None|Bride with veil
128113 (👱)|794|128104 (👨)|Man
128114 (👲)|1342|None|Man with skullcap
128115 (👳)|1312|None|Man with turban
128116 (👴)|1036|None|Oldman
128117 (👵)|991|None|Oldwoman
128118 (👶)|634|None|Baby
128119 (👷)|1385|None|Construction worker
128120 (👸)|875|None|Princess
128121 (👹)|571|None|Oni
128122 (👺)|761|None|Tengu
128123 (👻)|657|None|Ghost
128124 (👼)|1146|None|Baby angel
128125 (👽)|634|None|Alien
128126 (👾)|1153|None|Alien monster
128127 (👿)|640|None|Imp
128128 (💀)|748|9760 (☠)|Skull
128129 (💁)|1586|None|Woman tipping hand
128130 (💂)|739|None|Guard
128131 (💃)|775|None|Dancer
128132 (💄)|805|None|Lipstick
128133 (💅)|958|None|Nail polish
128134 (💆)|1808|None|Woman getting massage
128135 (💇)|1656|None|Woman getting haircut
128136 (💈)|1178|None|Barber pole
128137 (💉)|937|None|Syringe
128138 (💊)|589|None|Pill
128139 (💋)|884|None|Kiss mark
128140 (💌)|998|None|Love letter
128141 (💍)|598|None|Ring
128142 (💎)|1064|None|Gemstone
128143 (💏)|658|None|Kiss
128144 (💐)|772|None|Bouquet
128145 (💑)|1126|None|Couple with heart
128146 (💒)|719|None|Wedding
128147 (💓)|1167|None|Beating heart
128148 (💔)|1127|None|Broken heart
128149 (💕)|1142|None|Two hearts
128150 (💖)|1376|None|Sparkling heart
128151 (💗)|1110|None|Growing heart
128152 (💘)|1124|None|Heart with arrow
128153 (💙)|1039|None|Blue heart
128154 (💚)|1151|None|Green heart
128155 (💛)|1127|None|Yellow heart
128156 (💜)|1106|None|Purple heart
128157 (💝)|1091|None|Heart with ribbon
128158 (💞)|1618|None|Revolving hearts
128159 (💟)|1417|None|Heart decoration
128160 (💠)|1359|None|Floral diamond
128161 (💡)|992|None|Lightbulb
128162 (💢)|731|None|Angry
128163 (💣)|463|None|Bomb
128164 (💤)|835|None|Sleepy
128165 (💥)|796|None|Collision
128166 (💦)|1338|None|Nervous sweat
128167 (💧)|761|None|Droplet
128168 (💨)|842|None|Speedy
128169 (💩)|506|None|Poop
128170 (💪)|1572|None|Flexed biceps
128171 (💫)|585|None|Dizzy
128172 (💬)|1016|None|Speech bubble
128173 (💭)|1006|None|Thought bubble
128174 (💮)|1038|None|White flower
128175 (💯)|940|None|One hundred
128176 (💰)|911|None|Moneybag
128177 (💱)|1568|None|Currency exchange
128178 (💲)|1204|None|Dollar sign
128179 (💳)|1210|None|Credit card
128180 (💴)|1363|None|Japanese yen
128181 (💵)|1755|None|United states dollar
128182 (💶)|1150|None|Euro on note
128183 (💷)|1203|None|British pound
128184 (💸)|1494|None|Money with wings
128185 (💹)|2055|None|Japanese yen upwards trend
128186 (💺)|601|None|Seat
128187 (💻)|1402|None|Personal computer
128188 (💼)|982|None|Briefcase
128189 (💽)|831|None|Minidisc
128190 (💾)|1155|None|Floppy disc
128191 (💿)|1262|None|Optical disc
128192 (📀)|1072|None|DVD
128193 (📁)|810|None|Folder
128194 (📂)|1221|None|Open folder
128195 (📃)|1163|None|Curled paper
128196 (📄)|708|None|Paper
128197 (📅)|795|None|Calendar
128198 (📆)|1308|None|Tear off calendar
128199 (📇)|1248|None|Card index
128200 (📈)|1749|None|Chart with upwards trend
128201 (📉)|2047|None|Chart with downwards trend
128202 (📊)|957|None|Bar chart
128203 (📋)|894|None|Clipboard
128204 (📌)|792|None|Pushpin
128205 (📍)|1082|None|Round pushpin
128206 (📎)|868|None|Paperclip
128207 (📏)|604|None|Ruler
128208 (📐)|1425|None|Triangular ruler
128209 (📑)|1370|None|Bookmark tabs
128210 (📒)|675|None|Ledger
128211 (📓)|834|None|Notebook
128212 (📔)|1210|None|Fancy notebook
128213 (📕)|1038|None|Closed book
128214 (📖)|886|None|Open book
128215 (📗)|974|None|Green book
128216 (📘)|901|None|Blue book
128217 (📙)|926|None|Orange book
128218 (📚)|789|None|Books
128219 (📛)|811|None|Badge
128220 (📜)|825|None|Scroll
128221 (📝)|612|None|Memo
128222 (📞)|1475|None|Telephone receiver
128223 (📟)|751|None|Pager
128224 (📠)|800|None|Fax
128225 (📡)|1235|None|Sattelite antenna
128226 (📢)|890|None|Megaphone
128227 (📣)|1432|None|Cheering megaphone
128228 (📤)|941|None|Outbox
128229 (📥)|911|None|Inbox
128230 (📦)|857|None|Package
128231 (📧)|782|None|E-mail
128232 (📨)|1255|None|Incoming envelope
128233 (📩)|1452|None|Envelope with arrow
128234 (📪)|1494|None|Closed letterbox
128235 (📫)|2439|None|Closed letterbox with raised flag
128236 (📬)|1825|None|Flaged open letterbox
128237 (📭)|1362|None|Open letterbox
128238 (📮)|1202|None|Postbox
128239 (📯)|1284|None|Postal horn
128240 (📰)|968|None|Newspaper
128241 (📱)|1249|None|Mobile phone
128242 (📲)|1749|None|Mobile phone with arrow
128243 (📳)|1302|None|Vibration mode
128244 (📴)|1332|None|Mobile phone off
128245 (📵)|1681|None|No mobile phones
128246 (📶)|1363|None|Antenna with bars
128247 (📷)|700|None|Camera
128248 (📸)|700|128247 (📷)|Camera
128249 (📹)|1242|None|Video camera
128250 (📺)|862|None|Television
128251 (📻)|833|None|Radio
128252 (📼)|1169|None|Video casette
128253 (📽)|1186|None|Film projector
128255 (📿)|1115|None|Prayer beads
128256 (🔀)|670|None|Shuffle
128257 (🔁)|770|None|Repeat
128258 (🔂)|1033|None|Repeat one
128259 (🔃)|1212|None|Looping arrows
128260 (🔄)|956|None|Recycle
128261 (🔅)|1281|None|Low brightness
128262 (🔆)|1202|None|High brightness
128263 (🔇)|668|None|Mute
128264 (🔈)|861|None|Speaker
128265 (🔉)|966|None|Low volume
128266 (🔊)|915|None|High volume
128267 (🔋)|705|None|Battery
128268 (🔌)|1306|None|Electric plug
128269 (🔍)|1784|None|Left magnifying glass
128270 (🔎)|1880|None|Right magnifying glass
128271 (🔏)|1410|None|Lock with ink pen
128272 (🔐)|1478|None|Closed lock with key
128273 (🔑)|589|None|Key
128274 (🔒)|605|None|Lock
128275 (🔓)|957|None|Open lock
128276 (🔔)|585|None|Bell
128277 (🔕)|1701|None|No notifications
128278 (🔖)|884|None|Bookmark
128279 (🔗)|1086|None|Link symbol
128280 (🔘)|1098|None|Radio button
128281 (🔙)|948|None|Back arrow
128282 (🔚)|777|None|End arrow
128283 (🔛)|780|None|On arrow
128284 (🔜)|863|None|Soon arrow
128285 (🔝)|890|None|Top arrow
128286 (🔞)|1145|None|Adults only
128287 (🔟)|1319|None|Keyboard key ten
128288 (🔠)|915|None|Uppercase
128289 (🔡)|1007|None|Lowercase
128290 (🔢)|808|None|Numbers
128291 (🔣)|1442|None|Special symbols
128292 (🔤)|1386|None|Latin alphabet
128293 (🔥)|711|None|Fire
128294 (🔦)|667|None|Torch
128295 (🔧)|732|None|Wrench
128296 (🔨)|618|None|Hammer
128297 (🔩)|1238|None|Nut and bolt
128298 (🔪)|679|None|Knife
128299 (🔫)|678|None|Gun
128300 (🔬)|1020|None|Microscope
128301 (🔭)|903|None|Telescope
128302 (🔮)|1192|None|Crystal ball
128303 (🔯)|1533|None|Hexagram with dot
128304 (🔰)|1294|None|Newbie symbol
128305 (🔱)|989|None|Trident
128306 (🔲)|1366|None|Black square button
128307 (🔳)|1178|None|Square button
128308 (🔴)|999|None|Red circle
128309 (🔵)|1275|None|Blue circle
128310 (🔶)|1248|None|Orange diamond
128311 (🔷)|1178|None|Blue diamond
128312 (🔸)|1583|None|Small orange diamond
128313 (🔹)|1390|None|Small blue diamond
128314 (🔺)|1308|None|Red triangle
128315 (🔻)|1953|None|Reversed red triangle
128316 (🔼)|1840|None|Small red triangle
128317 (🔽)|2346|None|Reversed small red triangle
128329 (🕉)|1022|None|Om symbol
128330 (🕊)|932|9774 (☮)|Peace dove
128331 (🕋)|657|None|Kaaba
128332 (🕌)|844|None|Mosque
128333 (🕍)|848|None|Synagogue
128334 (🕎)|848|None|Menorah
128336 (🕐)|981|None|One o'clock
128337 (🕑)|982|None|Two o'clock
128338 (🕒)|1020|None|Three o'clock
128339 (🕓)|1076|None|Four o'clock
128340 (🕔)|1184|None|Five o'clock
128341 (🕕)|1180|None|Six o'clock
128342 (🕖)|1141|None|Seven o'clock
128343 (🕗)|1001|None|Eight o'clock
128344 (🕘)|1011|None|Nine o'clock
128345 (🕙)|1023|None|Ten o'clock
128346 (🕚)|1125|None|Eleven o'clock
128347 (🕛)|1273|None|Twelve o'clock
128348 (🕜)|1033|None|One thirty
128349 (🕝)|965|None|Two thirty
128350 (🕞)|1146|None|Three thirty
128351 (🕟)|975|None|Four thirty
128352 (🕠)|1216|None|Five thirty
128353 (🕡)|1274|None|Six thirty
128354 (🕢)|1142|None|Seven thirty
128355 (🕣)|968|None|Eight thirty
128356 (🕤)|1137|None|Nine thirty
128357 (🕥)|1118|None|Ten thirty
128358 (🕦)|1156|None|Eleven thirty
128359 (🕧)|1060|None|Twelve thirty
128367 (🕯)|802|None|Candle
128368 (🕰)|691|9202 (⏲)|Clock
128371 (🕳)|774|None|Hole
128372 (🕴)|1857|None|Meditating businessman
128373 (🕵)|885|None|Detective
128374 (🕶)|1259|None|Sunglasses
128375 (🕷)|838|None|Spider
128376 (🕸)|955|None|Spiderweb
128377 (🕹)|824|None|Joystick
128378 (🕺)|1255|None|Man dancing
128391 (🖇)|1011|None|Paperclips
128394 (🖊)|613|None|Pen
128395 (🖋)|1045|None|Fountain pen
128396 (🖌)|939|None|Paintbrush
128397 (🖍)|630|None|Crayon
128400 (🖐)|1087|9995 (✋)|Raised hand
128405 (🖕)|1096|None|Middle finger
128406 (🖖)|1206|None|Vulcan salute
128420 (🖤)|989|None|Black heart
128421 (🖥)|864|None|Computer
128424 (🖨)|708|None|Printer
128433 (🖱)|1323|None|Computer mouse
128434 (🖲)|967|None|Trackball
128444 (🖼)|1299|None|Picture frame
128450 (🗂)|1481|None|Index dividers
128451 (🗃)|1085|None|Filebox
128452 (🗄)|1135|None|File cabinet
128465 (🗑)|1310|None|Waste basket
128466 (🗒)|837|None|Notepad
128467 (🗓)|795|128197 (📅)|Calendar
128476 (🗜)|847|None|Compression
128477 (🗝)|589|128273 (🔑)|Key
128478 (🗞)|968|128240 (📰)|Newspaper
128481 (🗡)|707|None|Dagger
128483 (🗣)|1109|None|Speaking silhouette
128488 (🗨)|1016|128172 (💬)|Speech bubble
128495 (🗯)|974|None|Anger bubble
128499 (🗳)|1070|None|Ballot box
128506 (🗺)|985|None|World map
128507 (🗻)|1136|None|Mount Fuji
128508 (🗼)|1205|None|Tokyo tower
128509 (🗽)|1314|None|Statue of liberty
128510 (🗾)|828|None|Japan
128511 (🗿)|934|None|Moyai
128512 (😀)|1148|9786 (☺)|Smiley face
128513 (😁)|1148|9786 (☺)|Smiley face
128514 (😂)|1148|9786 (☺)|Smiley face
128515 (😃)|1148|9786 (☺)|Smiley face
128516 (😄)|1148|9786 (☺)|Smiley face
128517 (😅)|2077|None|Embarrased smiley face
128518 (😆)|1148|9786 (☺)|Smiley face
128519 (😇)|1318|None|Angelic face
128520 (😈)|1192|None|Devilish face
128521 (😉)|1197|None|Winking face
128522 (😊)|1148|9786 (☺)|Smiley face
128523 (😋)|1218|None|Hungry face
128524 (😌)|1243|None|Relieved face
128525 (😍)|1388|None|Romantic face
128526 (😎)|1134|None|Cool face
128527 (😏)|1243|None|Smirking face
128528 (😐)|1305|None|Neutral face
128529 (😑)|1416|None|Speechless face
128530 (😒)|1292|None|Unamused face
128531 (😓)|1182|None|Sweating face
128532 (😔)|1232|None|Pensive face
128533 (😕)|1368|None|Confused face
128534 (😖)|1368|128533 (😕)|Confused face
128535 (😗)|1147|None|Kissing face
128536 (😘)|1147|128535 (😗)|Kissing face
128537 (😙)|1147|128535 (😗)|Kissing face
128538 (😚)|1147|128535 (😗)|Kissing face
128539 (😛)|1158|None|Sneering face
128540 (😜)|1138|None|Playful face
128541 (😝)|1138|128540 (😜)|Playful face
128542 (😞)|1470|None|Dissapointed face
128543 (😟)|1090|None|Worried face
128544 (😠)|1126|None|Angry face
128545 (😡)|1260|None|Pouting face
128546 (😢)|1182|None|Crying face
128547 (😣)|1494|None|Persevering face
128548 (😤)|1407|None|Triumphant face
128549 (😥)|1470|128542 (😞)|Dissapointed face
128550 (😦)|1251|9785 (☹)|Frowning face
128551 (😧)|1270|None|Anguished face
128552 (😨)|1299|None|Fearful face
128553 (😩)|1139|None|Weary face
128554 (😪)|1140|None|Sleepy face
128555 (😫)|1123|None|Tired face
128556 (😬)|1303|None|Grimmacing face
128557 (😭)|1182|128546 (😢)|Crying face
128558 (😮)|1149|None|Shocked face
128559 (😯)|1416|128529 (😑)|Speechless face
128560 (😰)|1281|None|Distressed face
128561 (😱)|1229|None|Scared face
128562 (😲)|1423|None|Astonished face
128563 (😳)|1274|None|Flushed face
128564 (😴)|1177|None|Sleeping face
128565 (😵)|1033|None|Dizzy face
128566 (😶)|1312|None|Mouthless face
128567 (😷)|1054|None|Sick face
128568 (😸)|1429|None|Smiley cat face
128569 (😹)|1361|None|Happy cat face
128570 (😺)|1429|128568 (😸)|Smiley cat face
128571 (😻)|1633|None|Romantic cat face
128572 (😼)|1594|None|Smirking cat face
128573 (😽)|1461|None|Kissing cat face
128574 (😾)|1500|None|Pouting cat face
128575 (😿)|1475|None|Crying cat face
128576 (🙀)|1400|None|Weary cat face
128577 (🙁)|1251|9785 (☹)|Frowning face
128578 (🙂)|1148|9786 (☺)|Smiley face
128579 (🙃)|1573|None|Upside down face
128580 (🙄)|1479|None|Rolling eyes face
128581 (🙅)|1908|None|Woman crossing arms
128582 (🙆)|1860|None|Woman gesturing OK
128583 (🙇)|1080|None|Bowing deeply
128584 (🙈)|1656|None|See no evil monkey
128585 (🙉)|1761|None|Hear no evil monkey
128586 (🙊)|1879|None|Speak no evil monkey
128587 (🙋)|1600|None|Rasing one hand
128588 (🙌)|2121|None|Celebratory hands in the air
128589 (🙍)|733|None|Frowning
128590 (🙎)|791|None|Pouting
128591 (🙏)|1210|None|Folded hands
128640 (🚀)|687|None|Rocket
128641 (🚁)|855|None|Helicopter
128642 (🚂)|1485|None|Steam locomotive
128643 (🚃)|1069|None|Railway car
128644 (🚄)|1294|None|High speed train
128645 (🚅)|1160|None|Bullet train
128646 (🚆)|728|None|Train
128647 (🚇)|819|None|Metro
128648 (🚈)|931|None|Light rail
128649 (🚉)|838|None|Station
128650 (🚊)|570|None|Tram
128651 (🚋)|1078|None|Tram car
128652 (🚌)|638|None|Bus
128653 (🚍)|638|128652 (🚌)|Bus
128654 (🚎)|920|None|Trolleybus
128655 (🚏)|929|None|Bus stop
128656 (🚐)|828|None|Minibus
128657 (🚑)|1004|None|Ambulence
128658 (🚒)|1210|None|Fire engine
128659 (🚓)|1181|None|Police car
128660 (🚔)|1181|128659 (🚓)|Police car
128661 (🚕)|849|None|Taxi
128662 (🚖)|849|128661 (🚕)|Taxi
128663 (🚗)|775|None|Car
128664 (🚘)|775|128663 (🚗)|Car
128665 (🚙)|1087|None|SUV
128666 (🚚)|674|None|Van
128667 (🚛)|1277|None|Articulated lorry
128668 (🚜)|802|None|Tractor
128669 (🚝)|1017|None|Monorail
128670 (🚞)|1372|None|Mountain railway
128671 (🚟)|1493|None|Suspension railway
128672 (🚠)|1437|None|Mountain cableway
128673 (🚡)|1368|None|Aerial tramway
128674 (🚢)|656|None|Ship
128675 (🚣)|731|None|Rowboat
128676 (🚤)|972|None|Speedboat
128677 (🚥)|1033|None|Traffic light
128678 (🚦)|1656|None|Vertical traffic light
128679 (🚧)|1615|None|Construction sign
128680 (🚨)|1094|None|Police light
128681 (🚩)|1943|None|Triangular flag on post
128682 (🚪)|594|None|Door
128683 (🚫)|1561|None|No entry sign
128684 (🚬)|824|None|Cigarette
128685 (🚭)|1621|None|No smoking symbol
128686 (🚮)|2001|None|Put litter in its place symbol
128687 (🚯)|1450|None|Do not litter symbol
128688 (🚰)|1773|None|Drinkable water symbol
128689 (🚱)|1979|None|Undrinkable water symbol
128690 (🚲)|881|None|Bicycle
128691 (🚳)|1279|None|No bicycles
128692 (🚴)|1130|None|Bicyclist
128693 (🚵)|1606|None|Mountain bicyclist
128694 (🚶)|1004|None|Man walking
128695 (🚷)|1450|None|No pedestrians
128696 (🚸)|1330|None|Children crossing
128697 (🚹)|1161|None|Men symbol
128698 (🚺)|1328|None|Women symbol
128699 (🚻)|1165|None|Public toilet
128700 (🚼)|1359|None|Baby symbol
128701 (🚽)|900|None|Toilet (???)
128702 (🚾)|1261|None|Water closet
128703 (🚿)|750|None|Shower
128704 (🛀)|709|None|Bath
128705 (🛁)|758|None|Bathtub
128706 (🛂)|1609|None|Passport control
128707 (🛃)|993|None|Customs
128708 (🛄)|1103|None|Baggage claim
128709 (🛅)|1056|None|Left luggage
128715 (🛋)|787|None|Lounge
128716 (🛌)|528|None|Bed
128717 (🛍)|770|None|Bags
128718 (🛎)|585|128276 (🔔)|Bell
128719 (🛏)|528|128716 (🛌)|Bed
128720 (🛐)|1180|None|Place of worship
128721 (🛑)|1101|None|Red octogon
128722 (🛒)|1030|None|Shopping trolley
128736 (🛠)|1309|None|Hammer and wrench
128737 (🛡)|747|None|Shield
128738 (🛢)|1201|None|Oil drum
128739 (🛣)|997|None|Motorway
128740 (🛤)|981|None|Railway
128741 (🛥)|920|None|Motorboat
128745 (🛩)|1336|None|Small airplane
128747 (🛫)|980|None|Departures
128748 (🛬)|993|None|Arrivals
128752 (🛰)|883|None|Sattelite
128755 (🛳)|960|None|Cruise ship
128756 (🛴)|909|None|Kick scooter
128757 (🛵)|1100|None|Motor scooter
128758 (🛶)|731|128675 (🚣)|Rowboat
128759 (🛷)|556|None|Sled
128760 (🛸)|1187|None|Flying saucer
128761 (🛹)|1028|None|Skate board
129296 (🤐)|1450|None|Mouth shut face
129297 (🤑)|1456|None|Dollar bills face
129298 (🤒)|1054|128567 (😷)|Sick face
129299 (🤓)|1042|None|Nerd face
129300 (🤔)|1287|None|Thoughtful face
129301 (🤕)|1102|None|Injured face
129302 (🤖)|848|None|Robot
129303 (🤗)|1186|None|Hugging face
129304 (🤘)|1260|None|Rock on gesture
129311 (🤟)|1373|None|Love you gesture
129318 (🤦)|1508|None|Person facepalming
129320 (🤨)|1239|None|Raised eyebrow
129321 (🤩)|1147|None|Starstruck
129322 (🤪)|1110|None|Zany face
129323 (🤫)|1228|None|Shushing face
129324 (🤬)|1126|128544 (😠)|Angry face
129325 (🤭)|1299|None|Hand over mouth
129326 (🤮)|1246|None|Vomiting face
129327 (🤯)|1154|None|Mind blown
129328 (🤰)|1206|None|Pregnant woman
129329 (🤱)|1546|None|Woman breast feeding
129330 (🤲)|1418|None|Palms up together
129332 (🤴)|890|None|Prince
129333 (🤵)|633|None|Groom
129334 (🤶)|1400|None|Mrs. Claus
129335 (🤷)|1164|None|Persong shrugging
129336 (🤸)|947|None|Cartwheel
129337 (🤹)|736|None|Juggler
129338 (🤺)|822|None|Fencer
129340 (🤼)|1214|None|People wrestling
129341 (🤽)|1419|None|Waterpolo player
129342 (🤾)|1223|None|Handball player
129344 (🥀)|1100|None|Wilted flower
129345 (🥁)|623|None|Drum
129346 (🥂)|1395|None|Clinking glasses
129347 (🥃)|1114|None|Tumbler glass
129348 (🥄)|817|None|Spoon
129349 (🥅)|677|None|Goal
129351 (🥇)|965|None|Gold medal
129352 (🥈)|948|None|Silver medal
129353 (🥉)|982|None|Bronze medal
129354 (🥊)|1161|None|Boxing glove
129355 (🥋)|1947|None|Martial arts uniform
129356 (🥌)|1324|None|Curling stone
129357 (🥍)|744|None|Lacrosse
129358 (🥎)|1122|None|Softball
129359 (🥏)|806|None|Frisbee
129360 (🥐)|860|None|Croissant
129361 (🥑)|1035|None|Avodaco (should be avocado)
129362 (🥒)|847|None|Cucumber
129363 (🥓)|712|None|Bacon
129364 (🥔)|795|None|Potato
129365 (🥕)|686|None|Carrot
129366 (🥖)|705|None|Baguette
129367 (🥗)|693|None|Salad
129368 (🥘)|777|None|Food
129369 (🥙)|1368|None|Stuffed flat bread
129370 (🥚)|556|None|Egg
129371 (🥛)|593|None|Milk
129372 (🥜)|746|None|Peanut
129373 (🥝)|619|None|Kiwi
129374 (🥞)|1071|None|Pancakes
129375 (🥟)|949|None|Dumpling
129376 (🥠)|1150|None|Fortune cookie
129377 (🥡)|1488|None|Takeaway box
129378 (🥢)|988|None|Chopsticks
129379 (🥣)|1228|None|Bowl with spoon
129380 (🥤)|548|None|Cup
129381 (🥥)|875|None|Coconut
129382 (🥦)|782|None|Broccoli
129383 (🥧)|546|None|Pie
129384 (🥨)|748|None|Pretzel
129385 (🥩)|1024|None|Cut of meat
129386 (🥪)|892|None|Sandwich
129387 (🥫)|1052|None|Canned food
129388 (🥬)|1257|None|Leafy green
129389 (🥭)|934|None|Mango
129390 (🥮)|1002|None|Mooncake
129391 (🥯)|606|None|Bagel
129392 (🥰)|1835|None|Smiling face with hearts
129395 (🥳)|1078|None|Party face
129396 (🥴)|1238|None|Woozy face
129397 (🥵)|1048|None|Hot face
129398 (🥶)|1094|None|Cold face
129402 (🥺)|959|None|Sad face
129404 (🥼)|967|None|Lab coat
129405 (🥽)|861|None|Goggles
129406 (🥾)|1121|None|Hiking boot
129407 (🥿)|893|None|Flat shoe
129408 (🦀)|783|None|Crab
129409 (🦁)|684|None|Lion
129410 (🦂)|880|None|Scorpion
129411 (🦃)|737|None|Turkey
129412 (🦄)|967|None|Unicorn
129413 (🦅)|703|None|Eagle
129414 (🦆)|628|None|Duck
129415 (🦇)|658|None|Bat
129416 (🦈)|740|128044 (🐬)|Dolphin
129417 (🦉)|550|None|Owl
129418 (🦊)|859|None|Fox
129419 (🦋)|1009|None|Butterfly
129420 (🦌)|637|None|Dear
129421 (🦍)|670|None|Gorilla
129422 (🦎)|973|None|Salamander
129423 (🦏)|1124|None|Rhinoceros
129424 (🦐)|862|None|Shrimp
129425 (🦑)|956|128025 (🐙)|Octopus
129426 (🦒)|780|None|Giraffe
129427 (🦓)|593|None|Zebra
129428 (🦔)|877|None|Hedgehog
129429 (🦕)|1033|None|Sauropod
129430 (🦖)|919|None|T-rex
129431 (🦗)|655|127951 (🏏)|Cricket
129432 (🦘)|1005|None|Kangaroo
129433 (🦙)|989|None|Laama
129434 (🦚)|827|None|Peacock
129435 (🦛)|1122|None|Hippopotomus
129436 (🦜)|687|None|Parrot
129437 (🦝)|837|None|Racoon
129438 (🦞)|869|None|Lobster
129439 (🦟)|1157|None|Mosquito
129440 (🦠)|881|None|Microbe
129441 (🦡)|705|None|Badger
129442 (🦢)|757|None|Swan
129456 (🦰)|804|None|Red hair
129457 (🦱)|885|None|Curly hair
129458 (🦲)|670|None|Bald
129459 (🦳)|860|None|White hair
129460 (🦴)|614|None|Bone
129461 (🦵)|538|None|Leg
129462 (🦶)|669|None|Foot
129463 (🦷)|650|None|Tooth
129464 (🦸)|937|None|Superhero
129465 (🦹)|879|None|Supervillan
129472 (🧀)|762|None|Cheese
129473 (🧁)|928|None|Cupcake
129474 (🧂)|688|None|Salt
129488 (🧐)|1297|None|Face with monacle
129489 (🧑)|699|None|Person
129490 (🧒)|779|None|Child
129491 (🧓)|1165|None|Older person
129492 (🧔)|1242|None|Man with beard
129493 (🧕)|1723|None|Woman with head scarf
129494 (🧖)|1642|None|Person in steamy room
129495 (🧗)|1194|None|Rock climber
129496 (🧘)|1733|None|Person in lotus position
129497 (🧙)|775|None|Mage
129498 (🧚)|720|None|Fairy
129499 (🧛)|792|None|Vampire
129500 (🧜)|950|None|Merperson
129501 (🧝)|530|None|Elf
129502 (🧞)|861|None|Genie
129503 (🧟)|761|None|Zombie
129504 (🧠)|701|None|Brain
129505 (🧡)|1079|None|Orange heart
129506 (🧢)|512|None|Cap
129507 (🧣)|757|None|Scarf
129508 (🧤)|681|None|Gloves
129509 (🧥)|618|None|Coat
129510 (🧦)|811|None|Socks
129511 (🧧)|967|None|Red envelope
129512 (🧨)|1053|None|Dynamite
129513 (🧩)|881|None|Jigsaw
129514 (🧪)|978|None|Test tube
129515 (🧫)|1040|None|Petri dish
129516 (🧬)|766|None|DNA
129517 (🧭)|879|None|Campus
129518 (🧮)|913|None|Abacus
129519 (🧯)|1661|None|Fire extinguisher
129520 (🧰)|1185|None|Toolbox
129521 (🧱)|510|None|Brick
129522 (🧲)|753|None|Magnet
129523 (🧳)|732|None|Luggage
129524 (🧴)|755|None|Lotion
129525 (🧵)|692|None|Thread
129526 (🧶)|652|None|Yarn
129527 (🧷)|868|128206 (📎)|Paperclip
129528 (🧸)|922|None|Teddy bear
129529 (🧹)|657|None|Broom
129530 (🧺)|903|None|Basket
129531 (🧻)|1254|None|Toilet roll
129532 (🧼)|668|None|Soap
129533 (🧽)|827|None|Sponge
129534 (🧾)|752|None|Receipt
129535 (🧿)|1195|None|Nazar amulet
1048736 (􀂠)|708|None|Space
1048746 (􀂪)|482|256 (Ā)|A
1048754 (􀂲)|415|50 (2)|Two
1048755 (􀂳)|513|51 (3)|Three
1048761 (􀂹)|540|49 (1)|One
1048762 (􀂺)|368|79 (O)|O
1048764 (􀂼)|1225|None|One slash four
1048765 (􀂽)|1217|None|One slash two
1048766 (􀂾)|1259|None|Three slash four
1048768 (􀃀)|482|256 (Ā)|A
1048769 (􀃁)|482|256 (Ā)|A
1048770 (􀃂)|482|256 (Ā)|A
1048771 (􀃃)|482|256 (Ā)|A
1048772 (􀃄)|482|256 (Ā)|A
1048773 (􀃅)|482|256 (Ā)|A
1048774 (􀃆)|482|256 (Ā)|A
1048775 (􀃇)|553|67 (C)|C
1048776 (􀃈)|457|69 (E)|E
1048777 (􀃉)|457|69 (E)|E
1048778 (􀃊)|457|69 (E)|E
1048779 (􀃋)|457|69 (E)|E
1048780 (􀃌)|478|73 (I)|I
1048781 (􀃍)|478|73 (I)|I
1048782 (􀃎)|478|73 (I)|I
1048783 (􀃏)|478|73 (I)|I
1048785 (􀃑)|540|78 (N)|N
1048786 (􀃒)|368|79 (O)|O
1048787 (􀃓)|368|79 (O)|O
1048788 (􀃔)|368|79 (O)|O
1048789 (􀃕)|368|79 (O)|O
1048790 (􀃖)|368|79 (O)|O
1048792 (􀃘)|368|79 (O)|O
1048793 (􀃙)|493|85 (U)|U
1048794 (􀃚)|493|85 (U)|U
1048795 (􀃛)|493|85 (U)|U
1048796 (􀃜)|493|85 (U)|U
1048797 (􀃝)|404|89 (Y)|Y
1048799 (􀃟)|652|127309 (🅍)|Ss
1048800 (􀃠)|482|256 (Ā)|A
1048801 (􀃡)|482|256 (Ā)|A
1048802 (􀃢)|482|256 (Ā)|A
1048803 (􀃣)|482|256 (Ā)|A
1048804 (􀃤)|482|256 (Ā)|A
1048805 (􀃥)|482|256 (Ā)|A
1048806 (􀃦)|482|256 (Ā)|A
1048807 (􀃧)|553|67 (C)|C
1048808 (􀃨)|457|69 (E)|E
1048809 (􀃩)|457|69 (E)|E
1048810 (􀃪)|457|69 (E)|E
1048811 (􀃫)|457|69 (E)|E
1048812 (􀃬)|478|73 (I)|I
1048813 (􀃭)|478|73 (I)|I
1048814 (􀃮)|478|73 (I)|I
1048815 (􀃯)|478|73 (I)|I
1048817 (􀃱)|540|78 (N)|N
1048818 (􀃲)|368|79 (O)|O
1048819 (􀃳)|368|79 (O)|O
1048820 (􀃴)|368|79 (O)|O
1048821 (􀃵)|368|79 (O)|O
1048822 (􀃶)|368|79 (O)|O
1048824 (􀃸)|368|79 (O)|O
1048825 (􀃹)|493|85 (U)|U
1048826 (􀃺)|493|85 (U)|U
1048827 (􀃻)|493|85 (U)|U
1048828 (􀃼)|493|85 (U)|U
1048829 (􀃽)|404|89 (Y)|Y
1048831 (􀃿)|404|89 (Y)|Y
1048832 (􀄀)|482|256 (Ā)|A
1048833 (􀄁)|482|256 (Ā)|A
1048834 (􀄂)|482|256 (Ā)|A
1048835 (􀄃)|482|256 (Ā)|A
1048836 (􀄄)|482|256 (Ā)|A
1048837 (􀄅)|482|256 (Ā)|A
1048838 (􀄆)|553|67 (C)|C
1048839 (􀄇)|553|67 (C)|C
1048840 (􀄈)|553|67 (C)|C
1048841 (􀄉)|553|67 (C)|C
1048842 (􀄊)|553|67 (C)|C
1048843 (􀄋)|553|67 (C)|C
1048844 (􀄌)|553|67 (C)|C
1048845 (􀄍)|553|67 (C)|C
1048846 (􀄎)|407|68 (D)|D
1048847 (􀄏)|407|68 (D)|D
1048848 (􀄐)|407|68 (D)|D
1048849 (􀄑)|407|68 (D)|D
1048850 (􀄒)|457|69 (E)|E
1048851 (􀄓)|457|69 (E)|E
1048852 (􀄔)|457|69 (E)|E
1048853 (􀄕)|457|69 (E)|E
1048854 (􀄖)|457|69 (E)|E
1048855 (􀄗)|457|69 (E)|E
1048856 (􀄘)|457|69 (E)|E
1048857 (􀄙)|457|69 (E)|E
1048858 (􀄚)|457|69 (E)|E
1048859 (􀄛)|457|69 (E)|E
1048860 (􀄜)|471|71 (G)|G
1048861 (􀄝)|471|71 (G)|G
1048862 (􀄞)|471|71 (G)|G
1048863 (􀄟)|471|71 (G)|G
1048864 (􀄠)|471|71 (G)|G
1048865 (􀄡)|471|71 (G)|G
1048866 (􀄢)|471|71 (G)|G
1048867 (􀄣)|471|71 (G)|G
1048868 (􀄤)|631|72 (H)|H
1048869 (􀄥)|631|72 (H)|H
1048870 (􀄦)|631|72 (H)|H
1048871 (􀄧)|631|72 (H)|H
1048872 (􀄨)|478|73 (I)|I
1048873 (􀄩)|478|73 (I)|I
1048874 (􀄪)|478|73 (I)|I
1048875 (􀄫)|478|73 (I)|I
1048876 (􀄬)|478|73 (I)|I
1048877 (􀄭)|478|73 (I)|I
1048878 (􀄮)|478|73 (I)|I
1048879 (􀄯)|478|73 (I)|I
1048880 (􀄰)|478|73 (I)|I
1048882 (􀄲)|635|306 (Ĳ)|Ij
1048883 (􀄳)|635|306 (Ĳ)|Ij
1048884 (􀄴)|548|74 (J)|J
1048885 (􀄵)|548|74 (J)|J
1048886 (􀄶)|505|75 (K)|K
1048887 (􀄷)|505|75 (K)|K
1048889 (􀄹)|390|76 (L)|L
1048890 (􀄺)|390|76 (L)|L
1048891 (􀄻)|390|76 (L)|L
1048892 (􀄼)|390|76 (L)|L
1048893 (􀄽)|390|76 (L)|L
1048894 (􀄾)|390|76 (L)|L
1048895 (􀄿)|390|76 (L)|L
1048896 (􀅀)|390|76 (L)|L
1048897 (􀅁)|390|76 (L)|L
1048898 (􀅂)|390|76 (L)|L
1048899 (􀅃)|540|78 (N)|N
1048900 (􀅄)|540|78 (N)|N
1048901 (􀅅)|540|78 (N)|N
1048902 (􀅆)|540|78 (N)|N
1048903 (􀅇)|540|78 (N)|N
1048904 (􀅈)|540|78 (N)|N
1048905 (􀅉)|540|78 (N)|N
1048908 (􀅌)|368|79 (O)|O
1048909 (􀅍)|368|79 (O)|O
1048910 (􀅎)|368|79 (O)|O
1048911 (􀅏)|368|79 (O)|O
1048912 (􀅐)|368|79 (O)|O
1048913 (􀅑)|368|79 (O)|O
1048914 (􀅒)|533|338 (Œ)|Oe
1048915 (􀅓)|533|338 (Œ)|Oe
1048916 (􀅔)|485|82 (R)|R
1048917 (􀅕)|485|82 (R)|R
1048918 (􀅖)|485|82 (R)|R
1048919 (􀅗)|485|82 (R)|R
1048920 (􀅘)|485|82 (R)|R
1048921 (􀅙)|485|82 (R)|R
1048922 (􀅚)|543|83 (S)|S
1048923 (􀅛)|543|83 (S)|S
1048924 (􀅜)|543|83 (S)|S
1048925 (􀅝)|543|83 (S)|S
1048926 (􀅞)|543|83 (S)|S
1048927 (􀅟)|543|83 (S)|S
1048928 (􀅠)|543|83 (S)|S
1048929 (􀅡)|543|83 (S)|S
1048930 (􀅢)|358|84 (T)|T
1048931 (􀅣)|358|84 (T)|T
1048932 (􀅤)|358|84 (T)|T
1048933 (􀅥)|358|84 (T)|T
1048934 (􀅦)|358|84 (T)|T
1048935 (􀅧)|358|84 (T)|T
1048936 (􀅨)|493|85 (U)|U
1048937 (􀅩)|493|85 (U)|U
1048938 (􀅪)|493|85 (U)|U
1048939 (􀅫)|493|85 (U)|U
1048940 (􀅬)|493|85 (U)|U
1048941 (􀅭)|493|85 (U)|U
1048942 (􀅮)|493|85 (U)|U
1048943 (􀅯)|493|85 (U)|U
1048944 (􀅰)|493|85 (U)|U
1048945 (􀅱)|493|85 (U)|U
1048946 (􀅲)|493|85 (U)|U
1048947 (􀅳)|493|85 (U)|U
1048948 (􀅴)|574|87 (W)|W
1048949 (􀅵)|574|87 (W)|W
1048950 (􀅶)|404|89 (Y)|Y
1048951 (􀅷)|404|89 (Y)|Y
1048952 (􀅸)|404|89 (Y)|Y
1048953 (􀅹)|528|90 (Z)|Z
1048954 (􀅺)|528|90 (Z)|Z
1048955 (􀅻)|528|90 (Z)|Z
1048956 (􀅼)|528|90 (Z)|Z
1048957 (􀅽)|528|90 (Z)|Z
1048958 (􀅾)|528|90 (Z)|Z
1048959 (􀅿)|543|83 (S)|S
1048960 (􀆀)|488|66 (B)|B
1048961 (􀆁)|488|66 (B)|B
1048962 (􀆂)|488|66 (B)|B
1048963 (􀆃)|488|66 (B)|B
1048967 (􀆇)|553|67 (C)|C
1048968 (􀆈)|553|67 (C)|C
1048970 (􀆊)|407|68 (D)|D
1048971 (􀆋)|407|68 (D)|D
1048972 (􀆌)|407|68 (D)|D
1048977 (􀆑)|453|70 (F)|F
1048978 (􀆒)|453|70 (F)|F
1048979 (􀆓)|471|71 (G)|G
1048983 (􀆗)|478|73 (I)|I
1048984 (􀆘)|505|75 (K)|K
1048985 (􀆙)|505|75 (K)|K
1048986 (􀆚)|390|76 (L)|L
1048989 (􀆝)|540|78 (N)|N
1048990 (􀆞)|540|78 (N)|N
1048991 (􀆟)|368|79 (O)|O
1048992 (􀆠)|368|79 (O)|O
1048993 (􀆡)|368|79 (O)|O
1048996 (􀆤)|411|80 (P)|P
1048997 (􀆥)|411|80 (P)|P
1049003 (􀆫)|358|84 (T)|T
1049004 (􀆬)|358|84 (T)|T
1049005 (􀆭)|358|84 (T)|T
1049006 (􀆮)|358|84 (T)|T
1049007 (􀆯)|493|85 (U)|U
1049008 (􀆰)|493|85 (U)|U
1049010 (􀆲)|411|86 (V)|V
1049011 (􀆳)|404|89 (Y)|Y
1049012 (􀆴)|404|89 (Y)|Y
1049013 (􀆵)|528|90 (Z)|Z
1049014 (􀆶)|528|90 (Z)|Z
1049028 (􀇄)|675|452 (Ǆ)|Dz
1049029 (􀇅)|675|452 (Ǆ)|Dz
1049030 (􀇆)|675|452 (Ǆ)|Dz
1049031 (􀇇)|631|455 (Ǉ)|Lj
1049032 (􀇈)|631|455 (Ǉ)|Lj
1049033 (􀇉)|631|455 (Ǉ)|Lj
1049034 (􀇊)|753|458 (Ǌ)|Nj
1049035 (􀇋)|753|458 (Ǌ)|Nj
1049036 (􀇌)|753|458 (Ǌ)|Nj
1049037 (􀇍)|482|256 (Ā)|A
1049038 (􀇎)|482|256 (Ā)|A
1049039 (􀇏)|478|73 (I)|I
1049040 (􀇐)|478|73 (I)|I
1049041 (􀇑)|368|79 (O)|O
1049042 (􀇒)|368|79 (O)|O
1049043 (􀇓)|493|85 (U)|U
1049044 (􀇔)|493|85 (U)|U
1049045 (􀇕)|493|85 (U)|U
1049046 (􀇖)|493|85 (U)|U
1049047 (􀇗)|493|85 (U)|U
1049048 (􀇘)|493|85 (U)|U
1049049 (􀇙)|493|85 (U)|U
1049050 (􀇚)|493|85 (U)|U
1049051 (􀇛)|493|85 (U)|U
1049052 (􀇜)|493|85 (U)|U
1049054 (􀇞)|482|256 (Ā)|A
1049055 (􀇟)|482|256 (Ā)|A
1049056 (􀇠)|482|256 (Ā)|A
1049057 (􀇡)|482|256 (Ā)|A
1049058 (􀇢)|482|256 (Ā)|A
1049059 (􀇣)|482|256 (Ā)|A
1049060 (􀇤)|471|71 (G)|G
1049061 (􀇥)|471|71 (G)|G
1049062 (􀇦)|471|71 (G)|G
1049063 (􀇧)|471|71 (G)|G
1049064 (􀇨)|505|75 (K)|K
1049065 (􀇩)|505|75 (K)|K
1049066 (􀇪)|368|79 (O)|O
1049067 (􀇫)|368|79 (O)|O
1049068 (􀇬)|368|79 (O)|O
1049069 (􀇭)|368|79 (O)|O
1049072 (􀇰)|548|74 (J)|J
1049073 (􀇱)|675|452 (Ǆ)|Dz
1049074 (􀇲)|675|452 (Ǆ)|Dz
1049075 (􀇳)|675|452 (Ǆ)|Dz
1049076 (􀇴)|471|71 (G)|G
1049077 (􀇵)|471|71 (G)|G
1049080 (􀇸)|540|78 (N)|N
1049081 (􀇹)|540|78 (N)|N
1049082 (􀇺)|482|256 (Ā)|A
1049083 (􀇻)|482|256 (Ā)|A
1049084 (􀇼)|482|256 (Ā)|A
1049085 (􀇽)|482|256 (Ā)|A
1049086 (􀇾)|368|79 (O)|O
1049087 (􀇿)|368|79 (O)|O
1049088 (􀈀)|482|256 (Ā)|A
1049089 (􀈁)|482|256 (Ā)|A
1049090 (􀈂)|482|256 (Ā)|A
1049091 (􀈃)|482|256 (Ā)|A
1049092 (􀈄)|457|69 (E)|E
1049093 (􀈅)|457|69 (E)|E
1049094 (􀈆)|457|69 (E)|E
1049095 (􀈇)|457|69 (E)|E
1049096 (􀈈)|478|73 (I)|I
1049097 (􀈉)|478|73 (I)|I
1049098 (􀈊)|478|73 (I)|I
1049099 (􀈋)|478|73 (I)|I
1049100 (􀈌)|368|79 (O)|O
1049101 (􀈍)|368|79 (O)|O
1049102 (􀈎)|368|79 (O)|O
1049103 (􀈏)|368|79 (O)|O
1049104 (􀈐)|485|82 (R)|R
1049105 (􀈑)|485|82 (R)|R
1049106 (􀈒)|485|82 (R)|R
1049107 (􀈓)|485|82 (R)|R
1049108 (􀈔)|493|85 (U)|U
1049109 (􀈕)|493|85 (U)|U
1049110 (􀈖)|493|85 (U)|U
1049111 (􀈗)|493|85 (U)|U
1049112 (􀈘)|543|83 (S)|S
1049113 (􀈙)|543|83 (S)|S
1049114 (􀈚)|358|84 (T)|T
1049115 (􀈛)|358|84 (T)|T
1049118 (􀈞)|631|72 (H)|H
1049119 (􀈟)|631|72 (H)|H
1049120 (􀈠)|540|78 (N)|N
1049121 (􀈡)|407|68 (D)|D
1049124 (􀈤)|528|90 (Z)|Z
1049125 (􀈥)|528|90 (Z)|Z
1049126 (􀈦)|482|256 (Ā)|A
1049127 (􀈧)|482|256 (Ā)|A
1049128 (􀈨)|457|69 (E)|E
1049129 (􀈩)|457|69 (E)|E
1049130 (􀈪)|368|79 (O)|O
1049131 (􀈫)|368|79 (O)|O
1049132 (􀈬)|368|79 (O)|O
1049133 (􀈭)|368|79 (O)|O
1049134 (􀈮)|368|79 (O)|O
1049135 (􀈯)|368|79 (O)|O
1049136 (􀈰)|368|79 (O)|O
1049137 (􀈱)|368|79 (O)|O
1049138 (􀈲)|404|89 (Y)|Y
1049139 (􀈳)|404|89 (Y)|Y
1049140 (􀈴)|390|76 (L)|L
1049141 (􀈵)|540|78 (N)|N
1049142 (􀈶)|358|84 (T)|T
1049146 (􀈺)|482|256 (Ā)|A
1049147 (􀈻)|553|67 (C)|C
1049148 (􀈼)|553|67 (C)|C
1049149 (􀈽)|390|76 (L)|L
1049150 (􀈾)|358|84 (T)|T
1049151 (􀈿)|543|83 (S)|S
1049152 (􀉀)|528|90 (Z)|Z
1049155 (􀉃)|488|66 (B)|B
1049158 (􀉆)|457|69 (E)|E
1049159 (􀉇)|457|69 (E)|E
1049160 (􀉈)|548|74 (J)|J
1049161 (􀉉)|548|74 (J)|J
1049162 (􀉊)|495|81 (Q)|Q
1049163 (􀉋)|495|81 (Q)|Q
1049164 (􀉌)|485|82 (R)|R
1049165 (􀉍)|485|82 (R)|R
1049166 (􀉎)|404|89 (Y)|Y
1049167 (􀉏)|404|89 (Y)|Y
1049171 (􀉓)|488|66 (B)|B
1049173 (􀉕)|553|67 (C)|C
1049174 (􀉖)|407|68 (D)|D
1049175 (􀉗)|407|68 (D)|D
1049181 (􀉝)|457|69 (E)|E
1049183 (􀉟)|548|74 (J)|J
1049184 (􀉠)|471|71 (G)|G
1049190 (􀉦)|631|72 (H)|H
1049192 (􀉨)|478|73 (I)|I
1049195 (􀉫)|390|76 (L)|L
1049196 (􀉬)|390|76 (L)|L
1049197 (􀉭)|390|76 (L)|L
1049200 (􀉰)|528|77 (M)|M
1049201 (􀉱)|528|77 (M)|M
1049202 (􀉲)|540|78 (N)|N
1049203 (􀉳)|540|78 (N)|N
1049210 (􀉺)|485|82 (R)|R
1049211 (􀉻)|485|82 (R)|R
1049212 (􀉼)|485|82 (R)|R
1049213 (􀉽)|485|82 (R)|R
1049214 (􀉾)|485|82 (R)|R
1049215 (􀉿)|485|82 (R)|R
1049218 (􀊂)|543|83 (S)|S
1049220 (􀊄)|548|74 (J)|J
1049224 (􀊈)|358|84 (T)|T
1049227 (􀊋)|411|86 (V)|V
1049232 (􀊐)|528|90 (Z)|Z
1049233 (􀊑)|528|90 (Z)|Z
1049245 (􀊝)|548|74 (J)|J
1049248 (􀊠)|495|81 (Q)|Q
1049262 (􀊮)|631|72 (H)|H
1049263 (􀊯)|631|72 (H)|H
1049264 (􀊰)|631|72 (H)|H
1049265 (􀊱)|631|72 (H)|H
1049266 (􀊲)|548|74 (J)|J
1049267 (􀊳)|485|82 (R)|R
1049269 (􀊵)|485|82 (R)|R
1049271 (􀊷)|574|87 (W)|W
1049272 (􀊸)|404|89 (Y)|Y
1049313 (􀋡)|390|76 (L)|L
1049314 (􀋢)|543|83 (S)|S
1049315 (􀋣)|672|88 (X)|X
1049470 (􀍾)|1029|59 (;)|Semicolon
1049994 (􀖊)|706|45 (-)|Dash
1050046 (􀖾)|706|45 (-)|Dash
1053696 (􁐀)|706|45 (-)|Dash
1054336 (􁚀)|708|1048736 (􀂠)|Space
1054726 (􁠆)|706|45 (-)|Dash
1056019 (􁴓)|368|79 (O)|O
1056044 (􁴬)|482|256 (Ā)|A
1056045 (􁴭)|482|256 (Ā)|A
1056046 (􁴮)|488|66 (B)|B
1056048 (􁴰)|407|68 (D)|D
1056049 (􁴱)|457|69 (E)|E
1056051 (􁴳)|471|71 (G)|G
1056052 (􁴴)|631|72 (H)|H
1056053 (􁴵)|478|73 (I)|I
1056054 (􁴶)|548|74 (J)|J
1056055 (􁴷)|505|75 (K)|K
1056056 (􁴸)|390|76 (L)|L
1056057 (􁴹)|528|77 (M)|M
1056058 (􁴺)|540|78 (N)|N
1056060 (􁴼)|368|79 (O)|O
1056062 (􁴾)|411|80 (P)|P
1056063 (􁴿)|485|82 (R)|R
1056064 (􁵀)|358|84 (T)|T
1056065 (􁵁)|493|85 (U)|U
1056066 (􁵂)|574|87 (W)|W
1056067 (􁵃)|482|256 (Ā)|A
1056071 (􁵇)|488|66 (B)|B
1056072 (􁵈)|407|68 (D)|D
1056073 (􁵉)|457|69 (E)|E
1056077 (􁵍)|471|71 (G)|G
1056079 (􁵏)|505|75 (K)|K
1056080 (􁵐)|528|77 (M)|M
1056082 (􁵒)|368|79 (O)|O
1056086 (􁵖)|411|80 (P)|P
1056087 (􁵗)|358|84 (T)|T
1056088 (􁵘)|493|85 (U)|U
1056091 (􁵛)|411|86 (V)|V
1056098 (􁵢)|478|73 (I)|I
1056099 (􁵣)|485|82 (R)|R
1056100 (􁵤)|493|85 (U)|U
1056101 (􁵥)|411|86 (V)|V
1056108 (􁵬)|488|66 (B)|B
1056109 (􁵭)|407|68 (D)|D
1056110 (􁵮)|453|70 (F)|F
1056111 (􁵯)|528|77 (M)|M
1056112 (􁵰)|540|78 (N)|N
1056113 (􁵱)|411|80 (P)|P
1056114 (􁵲)|485|82 (R)|R
1056115 (􁵳)|485|82 (R)|R
1056116 (􁵴)|543|83 (S)|S
1056117 (􁵵)|358|84 (T)|T
1056118 (􁵶)|528|90 (Z)|Z
1056125 (􁵽)|411|80 (P)|P
1056128 (􁶀)|488|66 (B)|B
1056129 (􁶁)|407|68 (D)|D
1056130 (􁶂)|453|70 (F)|F
1056131 (􁶃)|471|71 (G)|G
1056132 (􁶄)|505|75 (K)|K
1056133 (􁶅)|390|76 (L)|L
1056134 (􁶆)|528|77 (M)|M
1056135 (􁶇)|540|78 (N)|N
1056136 (􁶈)|411|80 (P)|P
1056137 (􁶉)|485|82 (R)|R
1056138 (􁶊)|543|83 (S)|S
1056140 (􁶌)|411|86 (V)|V
1056141 (􁶍)|672|88 (X)|X
1056142 (􁶎)|528|90 (Z)|Z
1056143 (􁶏)|482|256 (Ā)|A
1056145 (􁶑)|407|68 (D)|D
1056146 (􁶒)|457|69 (E)|E
1056147 (􁶓)|457|69 (E)|E
1056148 (􁶔)|457|69 (E)|E
1056150 (􁶖)|478|73 (I)|I
1056151 (􁶗)|368|79 (O)|O
1056153 (􁶙)|493|85 (U)|U
1056156 (􁶜)|553|67 (C)|C
1056157 (􁶝)|553|67 (C)|C
1056160 (􁶠)|453|70 (F)|F
1056161 (􁶡)|548|74 (J)|J
1056164 (􁶤)|478|73 (I)|I
1056168 (􁶨)|548|74 (J)|J
1056169 (􁶩)|390|76 (L)|L
1056170 (􁶪)|390|76 (L)|L
1056172 (􁶬)|528|77 (M)|M
1056173 (􁶭)|528|77 (M)|M
1056174 (􁶮)|540|78 (N)|N
1056175 (􁶯)|540|78 (N)|N
1056179 (􁶳)|543|83 (S)|S
1056181 (􁶵)|358|84 (T)|T
1056185 (􁶹)|411|86 (V)|V
1056187 (􁶻)|528|90 (Z)|Z
1056188 (􁶼)|528|90 (Z)|Z
1056189 (􁶽)|528|90 (Z)|Z
1056256 (􁸀)|482|256 (Ā)|A
1056257 (􁸁)|482|256 (Ā)|A
1056258 (􁸂)|488|66 (B)|B
1056259 (􁸃)|488|66 (B)|B
1056260 (􁸄)|488|66 (B)|B
1056261 (􁸅)|488|66 (B)|B
1056262 (􁸆)|488|66 (B)|B
1056263 (􁸇)|488|66 (B)|B
1056264 (􁸈)|553|67 (C)|C
1056265 (􁸉)|553|67 (C)|C
1056266 (􁸊)|407|68 (D)|D
1056267 (􁸋)|407|68 (D)|D
1056268 (􁸌)|407|68 (D)|D
1056269 (􁸍)|407|68 (D)|D
1056270 (􁸎)|407|68 (D)|D
1056271 (􁸏)|407|68 (D)|D
1056272 (􁸐)|407|68 (D)|D
1056273 (􁸑)|407|68 (D)|D
1056274 (􁸒)|407|68 (D)|D
1056275 (􁸓)|407|68 (D)|D
1056276 (􁸔)|457|69 (E)|E
1056277 (􁸕)|457|69 (E)|E
1056278 (􁸖)|457|69 (E)|E
1056279 (􁸗)|457|69 (E)|E
1056280 (􁸘)|457|69 (E)|E
1056281 (􁸙)|457|69 (E)|E
1056282 (􁸚)|457|69 (E)|E
1056283 (􁸛)|457|69 (E)|E
1056284 (􁸜)|457|69 (E)|E
1056285 (􁸝)|457|69 (E)|E
1056286 (􁸞)|453|70 (F)|F
1056287 (􁸟)|453|70 (F)|F
1056288 (􁸠)|471|71 (G)|G
1056289 (􁸡)|471|71 (G)|G
1056290 (􁸢)|631|72 (H)|H
1056291 (􁸣)|631|72 (H)|H
1056292 (􁸤)|631|72 (H)|H
1056293 (􁸥)|631|72 (H)|H
1056294 (􁸦)|631|72 (H)|H
1056295 (􁸧)|631|72 (H)|H
1056296 (􁸨)|631|72 (H)|H
1056297 (􁸩)|631|72 (H)|H
1056298 (􁸪)|631|72 (H)|H
1056299 (􁸫)|631|72 (H)|H
1056300 (􁸬)|478|73 (I)|I
1056301 (􁸭)|478|73 (I)|I
1056302 (􁸮)|478|73 (I)|I
1056303 (􁸯)|478|73 (I)|I
1056304 (􁸰)|505|75 (K)|K
1056305 (􁸱)|505|75 (K)|K
1056306 (􁸲)|505|75 (K)|K
1056307 (􁸳)|505|75 (K)|K
1056308 (􁸴)|505|75 (K)|K
1056309 (􁸵)|505|75 (K)|K
1056310 (􁸶)|390|76 (L)|L
1056311 (􁸷)|390|76 (L)|L
1056312 (􁸸)|390|76 (L)|L
1056313 (􁸹)|390|76 (L)|L
1056314 (􁸺)|390|76 (L)|L
1056315 (􁸻)|390|76 (L)|L
1056316 (􁸼)|390|76 (L)|L
1056317 (􁸽)|390|76 (L)|L
1056318 (􁸾)|528|77 (M)|M
1056319 (􁸿)|528|77 (M)|M
1056320 (􁹀)|528|77 (M)|M
1056321 (􁹁)|528|77 (M)|M
1056322 (􁹂)|528|77 (M)|M
1056323 (􁹃)|528|77 (M)|M
1056324 (􁹄)|540|78 (N)|N
1056325 (􁹅)|540|78 (N)|N
1056326 (􁹆)|540|78 (N)|N
1056327 (􁹇)|540|78 (N)|N
1056328 (􁹈)|540|78 (N)|N
1056329 (􁹉)|540|78 (N)|N
1056330 (􁹊)|540|78 (N)|N
1056331 (􁹋)|540|78 (N)|N
1056332 (􁹌)|368|79 (O)|O
1056333 (􁹍)|368|79 (O)|O
1056334 (􁹎)|368|79 (O)|O
1056335 (􁹏)|368|79 (O)|O
1056336 (􁹐)|368|79 (O)|O
1056337 (􁹑)|368|79 (O)|O
1056338 (􁹒)|368|79 (O)|O
1056339 (􁹓)|368|79 (O)|O
1056340 (􁹔)|411|80 (P)|P
1056341 (􁹕)|411|80 (P)|P
1056342 (􁹖)|411|80 (P)|P
1056343 (􁹗)|411|80 (P)|P
1056344 (􁹘)|485|82 (R)|R
1056345 (􁹙)|485|82 (R)|R
1056346 (􁹚)|485|82 (R)|R
1056347 (􁹛)|485|82 (R)|R
1056348 (􁹜)|485|82 (R)|R
1056349 (􁹝)|485|82 (R)|R
1056350 (􁹞)|485|82 (R)|R
1056351 (􁹟)|485|82 (R)|R
1056352 (􁹠)|543|83 (S)|S
1056353 (􁹡)|543|83 (S)|S
1056354 (􁹢)|543|83 (S)|S
1056355 (􁹣)|543|83 (S)|S
1056356 (􁹤)|543|83 (S)|S
1056357 (􁹥)|543|83 (S)|S
1056358 (􁹦)|543|83 (S)|S
1056359 (􁹧)|543|83 (S)|S
1056360 (􁹨)|543|83 (S)|S
1056361 (􁹩)|543|83 (S)|S
1056362 (􁹪)|358|84 (T)|T
1056363 (􁹫)|358|84 (T)|T
1056364 (􁹬)|358|84 (T)|T
1056365 (􁹭)|358|84 (T)|T
1056366 (􁹮)|358|84 (T)|T
1056367 (􁹯)|358|84 (T)|T
1056368 (􁹰)|358|84 (T)|T
1056369 (􁹱)|358|84 (T)|T
1056370 (􁹲)|493|85 (U)|U
1056371 (􁹳)|493|85 (U)|U
1056372 (􁹴)|493|85 (U)|U
1056373 (􁹵)|493|85 (U)|U
1056374 (􁹶)|493|85 (U)|U
1056375 (􁹷)|493|85 (U)|U
1056376 (􁹸)|493|85 (U)|U
1056377 (􁹹)|493|85 (U)|U
1056378 (􁹺)|493|85 (U)|U
1056379 (􁹻)|493|85 (U)|U
1056380 (􁹼)|411|86 (V)|V
1056381 (􁹽)|411|86 (V)|V
1056382 (􁹾)|411|86 (V)|V
1056383 (􁹿)|411|86 (V)|V
1056384 (􁺀)|574|87 (W)|W
1056385 (􁺁)|574|87 (W)|W
1056386 (􁺂)|574|87 (W)|W
1056387 (􁺃)|574|87 (W)|W
1056388 (􁺄)|574|87 (W)|W
1056389 (􁺅)|574|87 (W)|W
1056390 (􁺆)|574|87 (W)|W
1056391 (􁺇)|574|87 (W)|W
1056392 (􁺈)|574|87 (W)|W
1056393 (􁺉)|574|87 (W)|W
1056394 (􁺊)|672|88 (X)|X
1056395 (􁺋)|672|88 (X)|X
1056396 (􁺌)|672|88 (X)|X
1056397 (􁺍)|672|88 (X)|X
1056398 (􁺎)|404|89 (Y)|Y
1056399 (􁺏)|404|89 (Y)|Y
1056400 (􁺐)|528|90 (Z)|Z
1056401 (􁺑)|528|90 (Z)|Z
1056402 (􁺒)|528|90 (Z)|Z
1056403 (􁺓)|528|90 (Z)|Z
1056404 (􁺔)|528|90 (Z)|Z
1056405 (􁺕)|528|90 (Z)|Z
1056406 (􁺖)|631|72 (H)|H
1056407 (􁺗)|358|84 (T)|T
1056408 (􁺘)|574|87 (W)|W
1056409 (􁺙)|404|89 (Y)|Y
1056410 (􁺚)|482|256 (Ā)|A
1056411 (􁺛)|543|83 (S)|S
1056412 (􁺜)|543|83 (S)|S
1056413 (􁺝)|543|83 (S)|S
1056416 (􁺠)|482|256 (Ā)|A
1056417 (􁺡)|482|256 (Ā)|A
1056418 (􁺢)|482|256 (Ā)|A
1056419 (􁺣)|482|256 (Ā)|A
1056420 (􁺤)|482|256 (Ā)|A
1056421 (􁺥)|482|256 (Ā)|A
1056422 (􁺦)|482|256 (Ā)|A
1056423 (􁺧)|482|256 (Ā)|A
1056424 (􁺨)|482|256 (Ā)|A
1056425 (􁺩)|482|256 (Ā)|A
1056426 (􁺪)|482|256 (Ā)|A
1056427 (􁺫)|482|256 (Ā)|A
1056428 (􁺬)|482|256 (Ā)|A
1056429 (􁺭)|482|256 (Ā)|A
1056430 (􁺮)|482|256 (Ā)|A
1056431 (􁺯)|482|256 (Ā)|A
1056432 (􁺰)|482|256 (Ā)|A
1056433 (􁺱)|482|256 (Ā)|A
1056434 (􁺲)|482|256 (Ā)|A
1056435 (􁺳)|482|256 (Ā)|A
1056436 (􁺴)|482|256 (Ā)|A
1056437 (􁺵)|482|256 (Ā)|A
1056438 (􁺶)|482|256 (Ā)|A
1056439 (􁺷)|482|256 (Ā)|A
1056440 (􁺸)|457|69 (E)|E
1056441 (􁺹)|457|69 (E)|E
1056442 (􁺺)|457|69 (E)|E
1056443 (􁺻)|457|69 (E)|E
1056444 (􁺼)|457|69 (E)|E
1056445 (􁺽)|457|69 (E)|E
1056446 (􁺾)|457|69 (E)|E
1056447 (􁺿)|457|69 (E)|E
1056448 (􁻀)|457|69 (E)|E
1056449 (􁻁)|457|69 (E)|E
1056450 (􁻂)|457|69 (E)|E
1056451 (􁻃)|457|69 (E)|E
1056452 (􁻄)|457|69 (E)|E
1056453 (􁻅)|457|69 (E)|E
1056454 (􁻆)|457|69 (E)|E
1056455 (􁻇)|457|69 (E)|E
1056456 (􁻈)|478|73 (I)|I
1056457 (􁻉)|478|73 (I)|I
1056458 (􁻊)|478|73 (I)|I
1056459 (􁻋)|478|73 (I)|I
1056460 (􁻌)|368|79 (O)|O
1056461 (􁻍)|368|79 (O)|O
1056462 (􁻎)|368|79 (O)|O
1056463 (􁻏)|368|79 (O)|O
1056464 (􁻐)|368|79 (O)|O
1056465 (􁻑)|368|79 (O)|O
1056466 (􁻒)|368|79 (O)|O
1056467 (􁻓)|368|79 (O)|O
1056468 (􁻔)|368|79 (O)|O
1056469 (􁻕)|368|79 (O)|O
1056470 (􁻖)|368|79 (O)|O
1056471 (􁻗)|368|79 (O)|O
1056472 (􁻘)|368|79 (O)|O
1056473 (􁻙)|368|79 (O)|O
1056474 (􁻚)|368|79 (O)|O
1056475 (􁻛)|368|79 (O)|O
1056476 (􁻜)|368|79 (O)|O
1056477 (􁻝)|368|79 (O)|O
1056478 (􁻞)|368|79 (O)|O
1056479 (􁻟)|368|79 (O)|O
1056480 (􁻠)|368|79 (O)|O
1056481 (􁻡)|368|79 (O)|O
1056482 (􁻢)|368|79 (O)|O
1056483 (􁻣)|368|79 (O)|O
1056484 (􁻤)|493|85 (U)|U
1056485 (􁻥)|493|85 (U)|U
1056486 (􁻦)|493|85 (U)|U
1056487 (􁻧)|493|85 (U)|U
1056488 (􁻨)|493|85 (U)|U
1056489 (􁻩)|493|85 (U)|U
1056490 (􁻪)|493|85 (U)|U
1056491 (􁻫)|493|85 (U)|U
1056492 (􁻬)|493|85 (U)|U
1056493 (􁻭)|493|85 (U)|U
1056494 (􁻮)|493|85 (U)|U
1056495 (􁻯)|493|85 (U)|U
1056496 (􁻰)|493|85 (U)|U
1056497 (􁻱)|493|85 (U)|U
1056498 (􁻲)|404|89 (Y)|Y
1056499 (􁻳)|404|89 (Y)|Y
1056500 (􁻴)|404|89 (Y)|Y
1056501 (􁻵)|404|89 (Y)|Y
1056502 (􁻶)|404|89 (Y)|Y
1056503 (􁻷)|404|89 (Y)|Y
1056504 (􁻸)|404|89 (Y)|Y
1056505 (􁻹)|404|89 (Y)|Y
1056510 (􁻾)|404|89 (Y)|Y
1056511 (􁻿)|404|89 (Y)|Y
1056751 (􁿯)|1159|None|Grave accent
1056768 (􂀀)|708|1048736 (􀂠)|Space
1056769 (􂀁)|708|1048736 (􀂠)|Space
1056770 (􂀂)|708|1048736 (􀂠)|Space
1056771 (􂀃)|708|1048736 (􀂠)|Space
1056772 (􂀄)|708|1048736 (􀂠)|Space
1056773 (􂀅)|708|1048736 (􀂠)|Space
1056774 (􂀆)|708|1048736 (􀂠)|Space
1056775 (􂀇)|708|1048736 (􀂠)|Space
1056776 (􂀈)|708|1048736 (􀂠)|Space
1056777 (􂀉)|708|1048736 (􀂠)|Space
1056778 (􂀊)|708|1048736 (􀂠)|Space
1056784 (􂀐)|706|45 (-)|Dash
1056785 (􂀑)|706|45 (-)|Dash
1056786 (􂀒)|706|45 (-)|Dash
1056787 (􂀓)|706|45 (-)|Dash
1056788 (􂀔)|706|45 (-)|Dash
1056789 (􂀕)|706|45 (-)|Dash
1056804 (􂀤)|464|46 (.)|Dot
1056805 (􂀥)|620|None|Dot dot
1056806 (􂀦)|997|65049 (︙)|Dot dot dot
1056808 (􂀨)|863|None|Line feed
1056809 (􂀩)|1482|None|Line feed line feed
1056815 (􂀯)|708|1048736 (􀂠)|Space
1056828 (􂀼)|2530|None|Exclamation mark exclamation mark
1056831 (􂀿)|732|95 (_)|Underscore
1056832 (􂁀)|732|95 (_)|Underscore
1056836 (􂁄)|579|47 (/)|Slash
1056839 (􂁇)|1985|8263 (⁇)|Question mark question mark
1056840 (􂁈)|2247|8264 (⁈)|Question mark exclamation mark
1056841 (􂁉)|2204|None|Exclamation mark question mark
1056852 (􂁔)|732|95 (_)|Underscore
1056863 (􂁟)|708|1048736 (􀂠)|Space
1056880 (􂁰)|605|8304 (⁰)|Zero
1056881 (􂁱)|478|73 (I)|I
1056884 (􂁴)|629|52 (4)|Four
1056885 (􂁵)|680|53 (5)|Five
1056886 (􂁶)|612|54 (6)|Six
1056887 (􂁷)|377|55 (7)|Seven
1056888 (􂁸)|479|56 (8)|Eight
1056889 (􂁹)|587|57 (9)|Nine
1056890 (􂁺)|396|43 (+)|Plus
1056891 (􂁻)|706|45 (-)|Dash
1056892 (􂁼)|779|61 (=)|Equals
1056893 (􂁽)|1424|8317 (⁽)|Opening parenthases
1056894 (􂁾)|1526|8318 (⁾)|Closing parentheses
1056895 (􂁿)|540|78 (N)|N
1056896 (􂂀)|605|8304 (⁰)|Zero
1056897 (􂂁)|540|49 (1)|One
1056898 (􂂂)|415|50 (2)|Two
1056899 (􂂃)|513|51 (3)|Three
1056900 (􂂄)|629|52 (4)|Four
1056901 (􂂅)|680|53 (5)|Five
1056902 (􂂆)|612|54 (6)|Six
1056903 (􂂇)|377|55 (7)|Seven
1056904 (􂂈)|479|56 (8)|Eight
1056905 (􂂉)|587|57 (9)|Nine
1056906 (􂂊)|396|43 (+)|Plus
1056907 (􂂋)|706|45 (-)|Dash
1056908 (􂂌)|779|61 (=)|Equals
1056909 (􂂍)|1424|8317 (⁽)|Opening parenthases
1056910 (􂂎)|1526|8318 (⁾)|Closing parentheses
1056912 (􂂐)|482|256 (Ā)|A
1056913 (􂂑)|457|69 (E)|E
1056914 (􂂒)|368|79 (O)|O
1056915 (􂂓)|672|88 (X)|X
1056917 (􂂕)|631|72 (H)|H
1056918 (􂂖)|505|75 (K)|K
1056919 (􂂗)|390|76 (L)|L
1056920 (􂂘)|528|77 (M)|M
1056921 (􂂙)|540|78 (N)|N
1056922 (􂂚)|411|80 (P)|P
1056923 (􂂛)|543|83 (S)|S
1056924 (􂂜)|358|84 (T)|T
1056936 (􂂨)|633|8360 (₨)|Rs
1057024 (􂄀)|1227|8448 (℀)|A slash C
1057025 (􂄁)|1150|8449 (℁)|A slash S
1057026 (􂄂)|553|67 (C)|C
1057027 (􂄃)|553|67 (C)|C
1057029 (􂄅)|1228|None|C slash show
1057030 (􂄆)|1049|8454 (℆)|C slash U
1057033 (􂄉)|453|70 (F)|F
1057034 (􂄊)|471|71 (G)|G
1057035 (􂄋)|631|72 (H)|H
1057036 (􂄌)|631|72 (H)|H
1057037 (􂄍)|631|72 (H)|H
1057038 (􂄎)|631|72 (H)|H
1057039 (􂄏)|631|72 (H)|H
1057040 (􂄐)|478|73 (I)|I
1057041 (􂄑)|478|73 (I)|I
1057042 (􂄒)|390|76 (L)|L
1057043 (􂄓)|390|76 (L)|L
1057045 (􂄕)|540|78 (N)|N
1057046 (􂄖)|430|8470 (№)|No
1057049 (􂄙)|411|80 (P)|P
1057050 (􂄚)|495|81 (Q)|Q
1057051 (􂄛)|485|82 (R)|R
1057052 (􂄜)|485|82 (R)|R
1057053 (􂄝)|485|82 (R)|R
1057056 (􂄠)|622|8480 (℠)|Sm
1057057 (􂄡)|526|8481 (℡)|Tel
1057058 (􂄢)|625|None|Tm
1057060 (􂄤)|528|90 (Z)|Z
1057064 (􂄨)|528|90 (Z)|Z
1057066 (􂄪)|505|75 (K)|K
1057067 (􂄫)|482|256 (Ā)|A
1057068 (􂄬)|488|66 (B)|B
1057069 (􂄭)|553|67 (C)|C
1057071 (􂄯)|457|69 (E)|E
1057072 (􂄰)|457|69 (E)|E
1057073 (􂄱)|453|70 (F)|F
1057075 (􂄳)|528|77 (M)|M
1057076 (􂄴)|368|79 (O)|O
1057081 (􂄹)|478|73 (I)|I
1057083 (􂄻)|657|8507 (℻)|Fax
1057093 (􂅅)|407|68 (D)|D
1057094 (􂅆)|407|68 (D)|D
1057095 (􂅇)|457|69 (E)|E
1057096 (􂅈)|478|73 (I)|I
1057097 (􂅉)|548|74 (J)|J
1057104 (􂅐)|1300|None|One slash seven
1057105 (􂅑)|1242|None|One slash nine
1057106 (􂅒)|1156|None|One slash Ten
1057107 (􂅓)|1235|None|One slash three
1057108 (􂅔)|1198|None|Two slash three
1057109 (􂅕)|1377|None|One slash five
1057110 (􂅖)|1362|None|Two slash five
1057111 (􂅗)|1544|None|Three slash five
1057112 (􂅘)|1429|None|Four slash five
1057113 (􂅙)|1419|None|One slash six
1057114 (􂅚)|1610|None|Five slash six
1057115 (􂅛)|1246|None|One slash eight
1057116 (􂅜)|1346|None|Three slash eight
1057117 (􂅝)|1429|None|Five slash eight
1057118 (􂅞)|1367|None|Seven slash eight
1057119 (􂅟)|906|8543 (⅟)|One slash
1057120 (􂅠)|478|73 (I)|I
1057121 (􂅡)|415|50 (2)|Two
1057122 (􂅢)|513|51 (3)|Three
1057123 (􂅣)|416|None|Iv
1057124 (􂅤)|411|86 (V)|V
1057125 (􂅥)|430|None|Vi
1057126 (􂅦)|586|None|Seven
1057127 (􂅧)|760|None|Viii (sounds like Vaiai)
1057128 (􂅨)|538|None|Ix (sounds like Iks)
1057129 (􂅩)|672|88 (X)|X
1057130 (􂅪)|411|926 (Ξ)|Xi
1057131 (􂅫)|683|8555 (Ⅻ)|Twelve
1057132 (􂅬)|390|76 (L)|L
1057133 (􂅭)|553|67 (C)|C
1057134 (􂅮)|407|68 (D)|D
1057135 (􂅯)|528|77 (M)|M
1057136 (􂅰)|478|73 (I)|I
1057137 (􂅱)|415|50 (2)|Two
1057138 (􂅲)|513|51 (3)|Three
1057139 (􂅳)|416|1057123 (􂅣)|Iv
1057140 (􂅴)|411|86 (V)|V
1057141 (􂅵)|430|1057125 (􂅥)|Vi
1057142 (􂅶)|586|1057126 (􂅦)|Seven
1057143 (􂅷)|760|1057127 (􂅧)|Vaiai (???)
1057144 (􂅸)|538|1057128 (􂅨)|Ix (sounds like Iks)
1057145 (􂅹)|672|88 (X)|X
1057146 (􂅺)|411|926 (Ξ)|Xi
1057147 (􂅻)|683|8555 (Ⅻ)|Twelve
1057148 (􂅼)|390|76 (L)|L
1057149 (􂅽)|553|67 (C)|C
1057150 (􂅾)|407|68 (D)|D
1057151 (􂅿)|528|77 (M)|M
1057161 (􂆉)|1483|8585 (↉)|Zero slash three
1057298 (􂈒)|706|45 (-)|Dash
1057300 (􂈔)|396|43 (+)|Plus
1057301 (􂈕)|579|47 (/)|Slash
1057302 (􂈖)|836|92 (\\)|Backslash
1057303 (􂈗)|850|8727 (∗)|Asterisk
1057305 (􂈙)|850|8727 (∗)|Asterisk
1057376 (􂉠)|779|61 (=)|Equals
1057390 (􂉮)|713|60 (<)|Less than
1057391 (􂉯)|855|62 (>)|Greater than
1057888 (􂑠)|540|49 (1)|One
1057889 (􂑡)|415|50 (2)|Two
1057890 (􂑢)|513|51 (3)|Three
1057891 (􂑣)|629|52 (4)|Four
1057892 (􂑤)|680|53 (5)|Five
1057893 (􂑥)|612|54 (6)|Six
1057894 (􂑦)|377|55 (7)|Seven
1057895 (􂑧)|479|56 (8)|Eight
1057896 (􂑨)|587|57 (9)|Nine
1057897 (􂑩)|476|8553 (Ⅹ)|Ten
1057898 (􂑪)|477|8554 (Ⅺ)|Eleven
1057899 (􂑫)|683|8555 (Ⅻ)|Twelve
1057900 (􂑬)|883|9324 (⑬)|Thirteen
1057901 (􂑭)|908|9325 (⑭)|Fourteen
1057902 (􂑮)|891|9326 (⑮)|Fifteen
1057903 (􂑯)|1006|9327 (⑯)|Sixteen
1057904 (􂑰)|1002|9328 (⑰)|Seventeen
1057905 (􂑱)|880|9329 (⑱)|Eighteen
1057906 (􂑲)|884|9330 (⑲)|Ninteen
1057907 (􂑳)|557|9331 (⑳)|Twenty
1057908 (􂑴)|2956|9332 (⑴)|Opening parenthases one closing parenthases
1057909 (􂑵)|3001|9333 (⑵)|Opening parenthases two closing parenthases
1057910 (􂑶)|2996|9334 (⑶)|Opening parenthases three closing parenthases
1057911 (􂑷)|2930|9335 (⑷)|Opening parenthases four closing parenthases
1057912 (􂑸)|3076|9336 (⑸)|Opening parenthases five closing parenthases
1057913 (􂑹)|3142|9337 (⑹)|Opening parenthases six closing parenthases
1057914 (􂑺)|3112|9338 (⑺)|Opening parenthases seven closing parenthases
1057915 (􂑻)|2929|9339 (⑻)|Opening parenthases eight closing parenthases
1057916 (􂑼)|2931|9340 (⑼)|Opening parenthases nine closing parenthases
1057917 (􂑽)|3081|9341 (⑽)|Opening parenthases ten closing parenthases
1057918 (􂑾)|3002|9342 (⑾)|Opening parenthases eleven closing parenthases
1057919 (􂑿)|3311|9343 (⑿)|Opening parenthases twelve closing parenthases
1057920 (􂒀)|3340|9344 (⒀)|Opening parenthases thirteen closing parenthases
1057921 (􂒁)|3295|9345 (⒁)|Opening parenthases fourteen closing parenthases
1057922 (􂒂)|3129|9346 (⒂)|Opening parenthases fifteen closing parenthases
1057923 (􂒃)|3293|9347 (⒃)|Opening parenthases sixteen closing parenthases
1057924 (􂒄)|3403|9348 (⒄)|Opening parenthases seventeen closing parenthases
1057925 (􂒅)|3106|9349 (⒅)|Opening parenthases eighteen closing parenthases
1057926 (􂒆)|3178|9350 (⒆)|Opening parenthases nineteen closing parenthases
1057927 (􂒇)|3066|9351 (⒇)|Opening parenthases twenty closing parenthases
1057928 (􂒈)|781|9352 (⒈)|One dot
1057929 (􂒉)|678|9353 (⒉)|Two dot
1057930 (􂒊)|772|9354 (⒊)|Three dot
1057931 (􂒋)|716|9355 (⒋)|Four dot
1057932 (􂒌)|774|9356 (⒌)|Five dot
1057933 (􂒍)|882|9357 (⒍)|Six dot
1057934 (􂒎)|743|9358 (⒎)|Seven dot
1057935 (􂒏)|692|9359 (⒏)|Eight dot
1057936 (􂒐)|838|9360 (⒐)|Nine dot
1057937 (􂒑)|718|9361 (⒑)|Ten dot
1057938 (􂒒)|794|9362 (⒒)|Eleven dot
1057939 (􂒓)|892|9363 (⒓)|Twelve dot
1057940 (􂒔)|1093|9364 (⒔)|Thirteen dot
1057941 (􂒕)|1178|9365 (⒕)|Fourteen dot
1057942 (􂒖)|1056|9366 (⒖)|Fifteen dot
1057943 (􂒗)|1082|9367 (⒗)|Sixteen dot
1057944 (􂒘)|1104|9368 (⒘)|Seventeen dot
1057945 (􂒙)|1104|9369 (⒙)|Eighteen dot
1057946 (􂒚)|1100|9370 (⒚)|Nineteen dot
1057947 (􂒛)|797|9371 (⒛)|Twenty dot
1057948 (􂒜)|2859|9372 (⒜)|Opening parenthases A closing parenthases
1057949 (􂒝)|2878|9373 (⒝)|Opening parenthases B closing parenthases
1057950 (􂒞)|2956|9374 (⒞)|Opening parenthases C closing parenthases
1057951 (􂒟)|2865|9375 (⒟)|Opening parenthases D closing parenthases
1057952 (􂒠)|2797|9376 (⒠)|Opening parenthases E closing parenthases
1057953 (􂒡)|2834|9377 (⒡)|Opening parenthases F closing parenthases
1057954 (􂒢)|2993|9378 (⒢)|Opening parenthases G closing parenthases
1057955 (􂒣)|3047|9379 (⒣)|Opening parenthases H closing parenthases
1057956 (􂒤)|2841|9380 (⒤)|Opening parenthases I closing parenthases
1057957 (􂒥)|2980|9381 (⒥)|Opening parenthases J closing parenthases
1057958 (􂒦)|2949|9382 (⒦)|Opening parenthases K closing parenthases
1057959 (􂒧)|2870|9383 (⒧)|Opening parenthases L closing parenthases
1057960 (􂒨)|2838|9384 (⒨)|Opening parenthases M closing parenthases
1057961 (􂒩)|2816|9385 (⒩)|Opening parenthases N closing parenthases
1057962 (􂒪)|2930|9386 (⒪)|Opening parenthases O closing parenthases
1057963 (􂒫)|2967|9387 (⒫)|Opening parenthases P closing parenthases
1057964 (􂒬)|2881|9388 (⒬)|Opening parenthases Q closing parenthases
1057965 (􂒭)|2776|9389 (⒭)|Opening parenthases R closing parenthases
1057966 (􂒮)|2889|9390 (⒮)|Opening parenthases S closing parenthases
1057967 (􂒯)|2923|9391 (⒯)|Opening parenthases T closing parenthases
1057968 (􂒰)|2843|9392 (⒰)|Opening parenthases U closing parenthases
1057969 (􂒱)|2876|9393 (⒱)|Opening parenthases V closing parenthases
1057970 (􂒲)|3248|9394 (⒲)|Opening parenthases W closing parenthases
1057971 (􂒳)|2904|9395 (⒳)|Opening parenthases X closing parenthases
1057972 (􂒴)|2849|9396 (⒴)|Opening parenthases Y closing parenthases
1057973 (􂒵)|3119|9397 (⒵)|Opening parenthases Z closing parenthases
1057974 (􂒶)|482|256 (Ā)|A
1057975 (􂒷)|488|66 (B)|B
1057976 (􂒸)|553|67 (C)|C
1057977 (􂒹)|407|68 (D)|D
1057978 (􂒺)|457|69 (E)|E
1057979 (􂒻)|453|70 (F)|F
1057980 (􂒼)|471|71 (G)|G
1057981 (􂒽)|631|72 (H)|H
1057982 (􂒾)|478|73 (I)|I
1057983 (􂒿)|548|74 (J)|J
1057984 (􂓀)|505|75 (K)|K
1057985 (􂓁)|390|76 (L)|L
1057986 (􂓂)|528|77 (M)|M
1057987 (􂓃)|540|78 (N)|N
1057988 (􂓄)|368|79 (O)|O
1057989 (􂓅)|411|80 (P)|P
1057990 (􂓆)|495|81 (Q)|Q
1057991 (􂓇)|485|82 (R)|R
1057992 (􂓈)|543|83 (S)|S
1057993 (􂓉)|358|84 (T)|T
1057994 (􂓊)|493|85 (U)|U
1057995 (􂓋)|411|86 (V)|V
1057996 (􂓌)|574|87 (W)|W
1057997 (􂓍)|672|88 (X)|X
1057998 (􂓎)|404|89 (Y)|Y
1057999 (􂓏)|528|90 (Z)|Z
1058000 (􂓐)|482|256 (Ā)|A
1058001 (􂓑)|488|66 (B)|B
1058002 (􂓒)|553|67 (C)|C
1058003 (􂓓)|407|68 (D)|D
1058004 (􂓔)|457|69 (E)|E
1058005 (􂓕)|453|70 (F)|F
1058006 (􂓖)|471|71 (G)|G
1058007 (􂓗)|631|72 (H)|H
1058008 (􂓘)|478|73 (I)|I
1058009 (􂓙)|548|74 (J)|J
1058010 (􂓚)|505|75 (K)|K
1058011 (􂓛)|390|76 (L)|L
1058012 (􂓜)|528|77 (M)|M
1058013 (􂓝)|540|78 (N)|N
1058014 (􂓞)|368|79 (O)|O
1058015 (􂓟)|411|80 (P)|P
1058016 (􂓠)|495|81 (Q)|Q
1058017 (􂓡)|485|82 (R)|R
1058018 (􂓢)|543|83 (S)|S
1058019 (􂓣)|358|84 (T)|T
1058020 (􂓤)|493|85 (U)|U
1058021 (􂓥)|411|86 (V)|V
1058022 (􂓦)|574|87 (W)|W
1058023 (􂓧)|672|88 (X)|X
1058024 (􂓨)|404|89 (Y)|Y
1058025 (􂓩)|528|90 (Z)|Z
1058026 (􂓪)|605|8304 (⁰)|Zero
1059444 (􂩴)|1822|10868 (⩴)|Colon colon equals
1059445 (􂩵)|1427|10869 (⩵)|Equals equals
1059446 (􂩶)|1876|10870 (⩶)|Equals equals equals
1059936 (􂱠)|390|76 (L)|L
1059937 (􂱡)|390|76 (L)|L
1059938 (􂱢)|390|76 (L)|L
1059939 (􂱣)|411|80 (P)|P
1059940 (􂱤)|485|82 (R)|R
1059941 (􂱥)|482|256 (Ā)|A
1059942 (􂱦)|358|84 (T)|T
1059943 (􂱧)|631|72 (H)|H
1059944 (􂱨)|631|72 (H)|H
1059945 (􂱩)|505|75 (K)|K
1059946 (􂱪)|505|75 (K)|K
1059947 (􂱫)|528|90 (Z)|Z
1059948 (􂱬)|528|90 (Z)|Z
1059950 (􂱮)|528|77 (M)|M
1059953 (􂱱)|411|86 (V)|V
1059954 (􂱲)|574|87 (W)|W
1059955 (􂱳)|574|87 (W)|W
1059956 (􂱴)|411|86 (V)|V
1059960 (􂱸)|457|69 (E)|E
1059961 (􂱹)|485|82 (R)|R
1059962 (􂱺)|368|79 (O)|O
1059964 (􂱼)|548|74 (J)|J
1059965 (􂱽)|411|86 (V)|V
1059966 (􂱾)|543|83 (S)|S
1059967 (􂱿)|528|90 (Z)|Z
1060375 (􂸗)|706|45 (-)|Dash
1060378 (􂸚)|706|45 (-)|Dash
1060410 (􂸺)|706|45 (-)|Dash
1060411 (􂸻)|706|45 (-)|Dash
1060416 (􂹀)|706|45 (-)|Dash
1060864 (􃀀)|708|1048736 (􀂠)|Space
1060892 (􃀜)|706|45 (-)|Dash
1060912 (􃀰)|706|45 (-)|Dash
1061024 (􃂠)|706|45 (-)|Dash
1061376 (􃈀)|2633|None|Opening parenthases closing parenthases
1061377 (􃈁)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061378 (􃈂)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061379 (􃈃)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061380 (􃈄)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061381 (􃈅)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061382 (􃈆)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061383 (􃈇)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061384 (􃈈)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061385 (􃈉)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061386 (􃈊)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061387 (􃈋)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061388 (􃈌)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061389 (􃈍)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061390 (􃈎)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061391 (􃈏)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061392 (􃈐)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061393 (􃈑)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061394 (􃈒)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061395 (􃈓)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061396 (􃈔)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061397 (􃈕)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061398 (􃈖)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061399 (􃈗)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061400 (􃈘)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061401 (􃈙)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061402 (􃈚)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061403 (􃈛)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061404 (􃈜)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061405 (􃈝)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061406 (􃈞)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061408 (􃈠)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061409 (􃈡)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061410 (􃈢)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061411 (􃈣)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061412 (􃈤)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061413 (􃈥)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061414 (􃈦)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061415 (􃈧)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061416 (􃈨)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061417 (􃈩)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061418 (􃈪)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061419 (􃈫)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061420 (􃈬)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061421 (􃈭)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061422 (􃈮)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061423 (􃈯)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061424 (􃈰)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061425 (􃈱)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061426 (􃈲)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061427 (􃈳)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061428 (􃈴)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061429 (􃈵)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061430 (􃈶)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061431 (􃈷)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061432 (􃈸)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061433 (􃈹)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061434 (􃈺)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061435 (􃈻)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061436 (􃈼)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061437 (􃈽)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061438 (􃈾)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061439 (􃈿)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061440 (􃉀)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061441 (􃉁)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061442 (􃉂)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061443 (􃉃)|2633|1061376 (􃈀)|Opening parenthases closing parenthases
1061456 (􃉐)|127|None|T (very short ???)
1061457 (􃉑)|870|None|Twenty one
1061458 (􃉒)|885|None|Twenty two
1061459 (􃉓)|850|None|Twenty three
1061460 (􃉔)|916|None|Twenty four
1061461 (􃉕)|1011|None|Twenty five
1061462 (􃉖)|1029|None|Twenty six
1061463 (􃉗)|923|None|Twenty seven
1061464 (􃉘)|844|None|Twenty eight
1061465 (􃉙)|1035|None|Twenty nine
1061466 (􃉚)|591|None|Thirty
1061467 (􃉛)|889|None|Thirty one
1061468 (􃉜)|821|None|Thirty two
1061469 (􃉝)|869|None|Thirty three
1061470 (􃉞)|931|None|Thirty four
1061471 (􃉟)|1017|None|Thirty five
1061553 (􃊱)|1057|None|Thirty six
1061554 (􃊲)|973|None|Thirty seven
1061555 (􃊳)|893|None|Thirty eight
1061556 (􃊴)|1078|None|Thirty nine
1061557 (􃊵)|581|None|Fourty
1061558 (􃊶)|855|None|Fourty one
1061559 (􃊷)|804|None|Fourty two
1061560 (􃊸)|918|None|Fourty three
1061561 (􃊹)|874|None|Fourty four
1061562 (􃊺)|984|None|Fourty five
1061563 (􃊻)|1023|None|Fourty six
1061564 (􃊼)|970|None|Fourty seven
1061565 (􃊽)|836|None|Fourty eight
1061566 (􃊾)|1020|None|Fourty nine
1061567 (􃊿)|566|8556 (Ⅼ)|Fifty
1061568 (􃋀)|540|49 (1)|One
1061569 (􃋁)|415|50 (2)|Two
1061570 (􃋂)|513|51 (3)|Three
1061571 (􃋃)|629|52 (4)|Four
1061572 (􃋄)|680|53 (5)|Five
1061573 (􃋅)|612|54 (6)|Six
1061574 (􃋆)|377|55 (7)|Seven
1061575 (􃋇)|479|56 (8)|Eight
1061576 (􃋈)|587|57 (9)|Nine
1061577 (􃋉)|476|8553 (Ⅹ)|Ten
1061578 (􃋊)|477|8554 (Ⅺ)|Eleven
1061579 (􃋋)|683|8555 (Ⅻ)|Twelve
1061580 (􃋌)|853|None|HG
1061581 (􃋍)|627|None|Eg (???)
1061582 (􃋎)|252|None|F (short ???)
1061583 (􃋏)|769|None|Ltd
1061720 (􃍘)|605|8304 (⁰)|Zero
1061721 (􃍙)|540|49 (1)|One
1061722 (􃍚)|415|50 (2)|Two
1061723 (􃍛)|513|51 (3)|Three
1061724 (􃍜)|629|52 (4)|Four
1061725 (􃍝)|680|53 (5)|Five
1061726 (􃍞)|612|54 (6)|Six
1061727 (􃍟)|377|55 (7)|Seven
1061728 (􃍠)|479|56 (8)|Eight
1061729 (􃍡)|587|57 (9)|Nine
1061730 (􃍢)|476|8553 (Ⅹ)|Ten
1061731 (􃍣)|477|8554 (Ⅺ)|Eleven
1061732 (􃍤)|683|8555 (Ⅻ)|Twelve
1061733 (􃍥)|883|9324 (⑬)|Thirteen
1061734 (􃍦)|908|9325 (⑭)|Fourteen
1061735 (􃍧)|891|9326 (⑮)|Fifteen
1061736 (􃍨)|1006|9327 (⑯)|Sixteen
1061737 (􃍩)|1002|9328 (⑰)|Seventeen
1061738 (􃍪)|880|9329 (⑱)|Eighteen
1061739 (􃍫)|884|9330 (⑲)|Ninteen
1061740 (􃍬)|557|9331 (⑳)|Twenty
1061741 (􃍭)|870|1061457 (􃉑)|Twenty one
1061742 (􃍮)|885|1061458 (􃉒)|Twenty two
1061743 (􃍯)|850|1061459 (􃉓)|Twenty three
1061744 (􃍰)|916|1061460 (􃉔)|Twenty four
1061745 (􃍱)|293|None|Pha (very short ???)
1061746 (􃍲)|280|None|Da (short ???)
1061747 (􃍳)|368|79 (O)|O
1061748 (􃍴)|521|None|Ba
1061749 (􃍵)|230|None|Of
1061750 (􃍶)|678|None|PC
1061751 (􃍷)|665|None|DM
1061752 (􃍸)|958|None|DM2
1061753 (􃍹)|884|None|DM3
1061754 (􃍺)|493|85 (U)|U
1061760 (􃎀)|393|None|Ha
1061761 (􃎁)|443|None|Na
1061762 (􃎂)|482|256 (Ā)|A
1061763 (􃎃)|559|None|Ma
1061764 (􃎄)|517|None|Ka
1061765 (􃎅)|798|None|Kb
1061766 (􃎆)|599|None|Mb
1061767 (􃎇)|771|None|Gb
1061768 (􃎈)|556|None|Cal
1061769 (􃎉)|782|None|KCal
1061770 (􃎊)|585|None|Pf
1061771 (􃎋)|509|None|Nf
1061772 (􃎌)|453|70 (F)|F
1061773 (􃎍)|471|71 (G)|G
1061774 (􃎎)|696|None|Mg
1061775 (􃎏)|793|None|Kg
1061776 (􃎐)|560|None|Hertz
1061777 (􃎑)|1131|None|Kilo hertz
1061778 (􃎒)|817|None|MHZ
1061779 (􃎓)|1048|None|Giga hertz
1061780 (􃎔)|985|None|THZ
1061781 (􃎕)|390|76 (L)|L
1061782 (􃎖)|412|None|Ml
1061783 (􃎗)|688|None|Dl
1061784 (􃎘)|824|None|Kl
1061785 (􃎙)|654|None|FM
1061786 (􃎚)|565|None|NM
1061787 (􃎛)|528|77 (M)|M
1061788 (􃎜)|130|None|Mm (very short m)
1061789 (􃎝)|648|None|Cm
1061790 (􃎞)|980|None|Km
1061791 (􃎟)|585|None|M2 (???)
1061792 (􃎠)|823|None|Cm2
1061793 (􃎡)|862|None|M2
1061794 (􃎢)|968|None|Km2
1061795 (􃎣)|453|None|3 (???)
1061796 (􃎤)|1088|None|Cm3
1061797 (􃎥)|664|None|M3
1061798 (􃎦)|890|None|Km3
1061799 (􃎧)|1032|None|M slash S
1061800 (􃎨)|1360|None|M slash S2
1061801 (􃎩)|393|1061760 (􃎀)|Ha
1061802 (􃎪)|339|None|Kba (???)
1061803 (􃎫)|622|None|Mpa
1061804 (􃎬)|333|None|Kba (???2)
1061805 (􃎭)|445|None|Rad
1061806 (􃎮)|1209|None|Rad slash S
1061807 (􃎯)|1503|None|Rad slash S2
1061808 (􃎰)|528|None|Ps
1061809 (􃎱)|562|None|Ns
1061810 (􃎲)|543|83 (S)|S
1061811 (􃎳)|741|None|Ms
1061812 (􃎴)|520|None|Pv
1061813 (􃎵)|536|None|Nv
1061814 (􃎶)|411|86 (V)|V
1061815 (􃎷)|559|127307 (🅋)|Mv
1061816 (􃎸)|611|None|Kv
1061817 (􃎹)|559|127307 (🅋)|Mv
1061818 (􃎺)|862|None|Pw
1061819 (􃎻)|779|None|Nw
1061820 (􃎼)|574|87 (W)|W
1061821 (􃎽)|792|None|Mw
1061822 (􃎾)|813|None|Kw
1061823 (􃎿)|792|1061821 (􃎽)|Mw
1061824 (􃏀)|505|75 (K)|K
1061825 (􃏁)|528|77 (M)|M
1061826 (􃏂)|950|None|AM
1061827 (􃏃)|554|None|BQ
1061828 (􃏄)|799|None|CC
1061829 (􃏅)|710|127277 (🄭)|CD
1061830 (􃏆)|1396|None|C slash KG
1061831 (􃏇)|881|None|Co dot
1061832 (􃏈)|835|None|DB
1061833 (􃏉)|306|None|Jay
1061834 (􃏊)|504|None|Gha (short ???)
1061835 (􃏋)|731|None|HP
1061836 (􃏌)|466|None|In
1061837 (􃏍)|703|None|KK
1061838 (􃏎)|980|1061790 (􃎞)|Km
1061839 (􃏏)|687|None|Kt
1061840 (􃏐)|606|None|Lm
1061841 (􃏑)|515|None|Lm (???)
1061842 (􃏒)|587|None|Log
1061843 (􃏓)|757|None|Lx
1061844 (􃏔)|599|1061766 (􃎆)|Mb
1061845 (􃏕)|408|None|Mil
1061846 (􃏖)|481|None|Mole
1061847 (􃏗)|777|None|Ph
1061848 (􃏘)|599|None|PM
1061849 (􃏙)|792|None|PPM
1061850 (􃏚)|577|None|Pr
1061851 (􃏛)|740|None|Senior (???)
1061852 (􃏜)|650|None|Sv
1061853 (􃏝)|949|None|Wb
1061854 (􃏞)|1280|None|V slash M
1061855 (􃏟)|1234|None|A slash M
1061856 (􃏠)|540|49 (1)|One
1061857 (􃏡)|415|50 (2)|Two
1061858 (􃏢)|513|51 (3)|Three
1061859 (􃏣)|629|52 (4)|Four
1061860 (􃏤)|680|53 (5)|Five
1061861 (􃏥)|612|54 (6)|Six
1061862 (􃏦)|377|55 (7)|Seven
1061863 (􃏧)|479|56 (8)|Eight
1061864 (􃏨)|587|57 (9)|Nine
1061865 (􃏩)|476|8553 (Ⅹ)|Ten
1061866 (􃏪)|477|8554 (Ⅺ)|Eleven
1061867 (􃏫)|683|8555 (Ⅻ)|Twelve
1061868 (􃏬)|883|9324 (⑬)|Thirteen
1061869 (􃏭)|908|9325 (⑭)|Fourteen
1061870 (􃏮)|891|9326 (⑮)|Fifteen
1061871 (􃏯)|1006|9327 (⑯)|Sixteen
1061872 (􃏰)|1002|9328 (⑰)|Seventeen
1061873 (􃏱)|880|9329 (⑱)|Eighteen
1061874 (􃏲)|884|9330 (⑲)|Ninteen
1061875 (􃏳)|557|9331 (⑳)|Twenty
1061876 (􃏴)|870|1061457 (􃉑)|Twenty one
1061877 (􃏵)|885|1061458 (􃉒)|Twenty two
1061878 (􃏶)|850|1061459 (􃉓)|Twenty three
1061879 (􃏷)|916|1061460 (􃉔)|Twenty four
1061880 (􃏸)|1011|1061461 (􃉕)|Twenty five
1061881 (􃏹)|1029|1061462 (􃉖)|Twenty six
1061882 (􃏺)|923|1061463 (􃉗)|Twenty seven
1061883 (􃏻)|844|1061464 (􃉘)|Twenty eight
1061884 (􃏼)|1035|1061465 (􃉙)|Twenty nine
1061885 (􃏽)|591|1061466 (􃉚)|Thirty
1061886 (􃏾)|889|1061467 (􃉛)|Thirty one
1061887 (􃏿)|504|None|Gal
1091390 (􊜾)|553|67 (C)|C
1091391 (􊜿)|553|67 (C)|C
1091392 (􊝀)|505|75 (K)|K
1091393 (􊝁)|505|75 (K)|K
1091394 (􊝂)|505|75 (K)|K
1091395 (􊝃)|505|75 (K)|K
1091396 (􊝄)|505|75 (K)|K
1091397 (􊝅)|505|75 (K)|K
1091400 (􊝈)|390|76 (L)|L
1091401 (􊝉)|390|76 (L)|L
1091402 (􊝊)|368|79 (O)|O
1091403 (􊝋)|368|79 (O)|O
1091404 (􊝌)|368|79 (O)|O
1091405 (􊝍)|368|79 (O)|O
1091408 (􊝐)|411|80 (P)|P
1091409 (􊝑)|411|80 (P)|P
1091410 (􊝒)|411|80 (P)|P
1091411 (􊝓)|411|80 (P)|P
1091412 (􊝔)|411|80 (P)|P
1091413 (􊝕)|411|80 (P)|P
1091414 (􊝖)|495|81 (Q)|Q
1091415 (􊝗)|495|81 (Q)|Q
1091416 (􊝘)|495|81 (Q)|Q
1091417 (􊝙)|495|81 (Q)|Q
1091422 (􊝞)|411|86 (V)|V
1091423 (􊝟)|411|86 (V)|V
1091470 (􊞎)|390|76 (L)|L
1091472 (􊞐)|540|78 (N)|N
1091473 (􊞑)|540|78 (N)|N
1091474 (􊞒)|553|67 (C)|C
1091475 (􊞓)|553|67 (C)|C
1091476 (􊞔)|553|67 (C)|C
1091477 (􊞕)|631|72 (H)|H
1091478 (􊞖)|488|66 (B)|B
1091479 (􊞗)|488|66 (B)|B
1091480 (􊞘)|453|70 (F)|F
1091481 (􊞙)|453|70 (F)|F
1091488 (􊞠)|471|71 (G)|G
1091489 (􊞡)|471|71 (G)|G
1091490 (􊞢)|505|75 (K)|K
1091491 (􊞣)|505|75 (K)|K
1091492 (􊞤)|540|78 (N)|N
1091493 (􊞥)|540|78 (N)|N
1091494 (􊞦)|485|82 (R)|R
1091495 (􊞧)|485|82 (R)|R
1091496 (􊞨)|543|83 (S)|S
1091497 (􊞩)|543|83 (S)|S
1091498 (􊞪)|631|72 (H)|H
1091501 (􊞭)|390|76 (L)|L
1091506 (􊞲)|548|74 (J)|J
1091576 (􊟸)|631|72 (H)|H
1091577 (􊟹)|533|338 (Œ)|Oe
1092404 (􊬴)|457|69 (E)|E
1092407 (􊬷)|390|76 (L)|L
1092408 (􊬸)|390|76 (L)|L
1092409 (􊬹)|390|76 (L)|L
1092410 (􊬺)|528|77 (M)|M
1092411 (􊬻)|540|78 (N)|N
1092415 (􊬿)|368|79 (O)|O
1092425 (􊭉)|485|82 (R)|R
1092430 (􊭎)|493|85 (U)|U
1092434 (􊭒)|493|85 (U)|U
1092438 (􊭖)|672|88 (X)|X
1092439 (􊭗)|672|88 (X)|X
1092440 (􊭘)|672|88 (X)|X
1092441 (􊭙)|672|88 (X)|X
1092442 (􊭚)|404|89 (Y)|Y
1092445 (􊭝)|390|76 (L)|L
1092446 (􊭞)|390|76 (L)|L
1092447 (􊭟)|493|85 (U)|U
1112832 (􏬀)|619|64256 (ﬀ)|Ff
1112833 (􏬁)|469|934 (Φ)|Phi
1112834 (􏬂)|486|64258 (ﬂ)|Fl
1112835 (􏬃)|364|64259 (ﬃ)|FFi
1112836 (􏬄)|763|64260 (ﬄ)|FFl
1112837 (􏬅)|784|64261 (ﬅ)|St
1112838 (􏬆)|784|64261 (ﬅ)|St
1112873 (􏬩)|396|43 (+)|Plus
1113616 (􏸐)|432|65040 (︐)|Comma
1113619 (􏸓)|656|58 (:)|Colon
1113620 (􏸔)|1029|59 (;)|Semicolon
1113621 (􏸕)|1333|33 (!)|Exclamation mark
1113622 (􏸖)|1161|63 (?)|Question mark
1113625 (􏸙)|997|65049 (︙)|Dot dot dot
1113648 (􏸰)|620|1056805 (􂀥)|Dot dot
1113649 (􏸱)|706|45 (-)|Dash
1113650 (􏸲)|706|45 (-)|Dash
1113651 (􏸳)|732|95 (_)|Underscore
1113652 (􏸴)|732|95 (_)|Underscore
1113653 (􏸵)|1424|8317 (⁽)|Opening parenthases
1113654 (􏸶)|1526|8318 (⁾)|Closing parentheses
1113655 (􏸷)|1076|65115 (﹛)|Opening brace
1113656 (􏸸)|1131|65116 (﹜)|Closing brace
1113671 (􏹇)|1115|None|Opening bracket
1113672 (􏹈)|1131|None|Closing bracket
1113677 (􏹍)|732|95 (_)|Underscore
1113678 (􏹎)|732|95 (_)|Underscore
1113679 (􏹏)|732|95 (_)|Underscore
1113680 (􏹐)|432|65040 (︐)|Comma
1113682 (􏹒)|464|46 (.)|Dot
1113684 (􏹔)|1029|59 (;)|Semicolon
1113685 (􏹕)|656|58 (:)|Colon
1113686 (􏹖)|1161|63 (?)|Question mark
1113687 (􏹗)|1333|33 (!)|Exclamation mark
1113688 (􏹘)|706|45 (-)|Dash
1113689 (􏹙)|1424|8317 (⁽)|Opening parenthases
1113690 (􏹚)|1526|8318 (⁾)|Closing parentheses
1113691 (􏹛)|1076|65115 (﹛)|Opening brace
1113692 (􏹜)|1131|65116 (﹜)|Closing brace
1113695 (􏹟)|409|35 (#)|Hash
1113696 (􏹠)|329|38 (&)|And
1113697 (􏹡)|850|8727 (∗)|Asterisk
1113698 (􏹢)|396|43 (+)|Plus
1113699 (􏹣)|706|45 (-)|Dash
1113700 (􏹤)|713|60 (<)|Less than
1113701 (􏹥)|855|62 (>)|Greater than
1113702 (􏹦)|779|61 (=)|Equals
1113704 (􏹨)|836|92 (\\)|Backslash
1113705 (􏹩)|425|36 ($)|Dollar
1113706 (􏹪)|631|37 (%)|Percent
1113707 (􏹫)|370|64 (@)|At
1113857 (􏼁)|1333|33 (!)|Exclamation mark
1113858 (􏼂)|524|None|Quote
1113859 (􏼃)|409|35 (#)|Hash
1113860 (􏼄)|425|36 ($)|Dollar
1113861 (􏼅)|631|37 (%)|Percent
1113862 (􏼆)|329|38 (&)|And
1113863 (􏼇)|802|None|Apostrophe
1113864 (􏼈)|1424|8317 (⁽)|Opening parenthases
1113865 (􏼉)|1526|8318 (⁾)|Closing parentheses
1113866 (􏼊)|850|8727 (∗)|Asterisk
1113867 (􏼋)|396|43 (+)|Plus
1113868 (􏼌)|432|65040 (︐)|Comma
1113869 (􏼍)|706|45 (-)|Dash
1113870 (􏼎)|464|46 (.)|Dot
1113871 (􏼏)|579|47 (/)|Slash
1113872 (􏼐)|605|8304 (⁰)|Zero
1113873 (􏼑)|540|49 (1)|One
1113874 (􏼒)|415|50 (2)|Two
1113875 (􏼓)|513|51 (3)|Three
1113876 (􏼔)|629|52 (4)|Four
1113877 (􏼕)|680|53 (5)|Five
1113878 (􏼖)|612|54 (6)|Six
1113879 (􏼗)|377|55 (7)|Seven
1113880 (􏼘)|479|56 (8)|Eight
1113881 (􏼙)|587|57 (9)|Nine
1113882 (􏼚)|656|58 (:)|Colon
1113883 (􏼛)|1029|59 (;)|Semicolon
1113884 (􏼜)|713|60 (<)|Less than
1113885 (􏼝)|779|61 (=)|Equals
1113886 (􏼞)|855|62 (>)|Greater than
1113887 (􏼟)|1161|63 (?)|Question mark
1113888 (􏼠)|370|64 (@)|At
1113889 (􏼡)|482|256 (Ā)|A
1113890 (􏼢)|488|66 (B)|B
1113891 (􏼣)|553|67 (C)|C
1113892 (􏼤)|407|68 (D)|D
1113893 (􏼥)|457|69 (E)|E
1113894 (􏼦)|453|70 (F)|F
1113895 (􏼧)|471|71 (G)|G
1113896 (􏼨)|631|72 (H)|H
1113897 (􏼩)|478|73 (I)|I
1113898 (􏼪)|548|74 (J)|J
1113899 (􏼫)|505|75 (K)|K
1113900 (􏼬)|390|76 (L)|L
1113901 (􏼭)|528|77 (M)|M
1113902 (􏼮)|540|78 (N)|N
1113903 (􏼯)|368|79 (O)|O
1113904 (􏼰)|411|80 (P)|P
1113905 (􏼱)|495|81 (Q)|Q
1113906 (􏼲)|485|82 (R)|R
1113907 (􏼳)|543|83 (S)|S
1113908 (􏼴)|358|84 (T)|T
1113909 (􏼵)|493|85 (U)|U
1113910 (􏼶)|411|86 (V)|V
1113911 (􏼷)|574|87 (W)|W
1113912 (􏼸)|672|88 (X)|X
1113913 (􏼹)|404|89 (Y)|Y
1113914 (􏼺)|528|90 (Z)|Z
1113915 (􏼻)|1115|1113671 (􏹇)|Opening bracket
1113916 (􏼼)|836|92 (\\)|Backslash
1113917 (􏼽)|1131|1113672 (􏹈)|Closing bracket
1113918 (􏼾)|633|94 (^)|Carrot
1113919 (􏼿)|732|95 (_)|Underscore
1113920 (􏽀)|1159|1056751 (􁿯)|Grave accent
1113921 (􏽁)|482|256 (Ā)|A
1113922 (􏽂)|488|66 (B)|B
1113923 (􏽃)|553|67 (C)|C
1113924 (􏽄)|407|68 (D)|D
1113925 (􏽅)|457|69 (E)|E
1113926 (􏽆)|453|70 (F)|F
1113927 (􏽇)|471|71 (G)|G
1113928 (􏽈)|631|72 (H)|H
1113929 (􏽉)|478|73 (I)|I
1113930 (􏽊)|548|74 (J)|J
1113931 (􏽋)|505|75 (K)|K
1113932 (􏽌)|390|76 (L)|L
1113933 (􏽍)|528|77 (M)|M
1113934 (􏽎)|540|78 (N)|N
1113935 (􏽏)|368|79 (O)|O
1113936 (􏽐)|411|80 (P)|P
1113937 (􏽑)|495|81 (Q)|Q
1113938 (􏽒)|485|82 (R)|R
1113939 (􏽓)|543|83 (S)|S
1113940 (􏽔)|358|84 (T)|T
1113941 (􏽕)|493|85 (U)|U
1113942 (􏽖)|411|86 (V)|V
1113943 (􏽗)|574|87 (W)|W
1113944 (􏽘)|672|88 (X)|X
1113945 (􏽙)|404|89 (Y)|Y
1113946 (􏽚)|528|90 (Z)|Z
1113947 (􏽛)|1076|65115 (﹛)|Opening brace
1113948 (􏽜)|1070|None|Vertical bar
1113949 (􏽝)|1131|65116 (﹜)|Closing brace
1113950 (􏽞)|551|126 (~)|Tilde

48 (0) is does not produce audio by itself, however ("a0") works

Shortest: 193 (Á): 121ms

Longest: 9348 (⒄): 3403ms