# Impro iseseisvaks harjutamiseks mõeldud tööriistad ja vahendid

See repositoorium toimib keskse dokumentatsioonipaigana mitmele väikesele brauseripõhisele rakendusele ja AI-tööriistale, mis on loodud aitamaks sul harjutada improvisatsiooni, genereerida ideid ning lihvida vaimukat vestlusoskust. Allpool leiad iga projekti lühikirjelduse ja lingid nende eraldi repositooriumitele või töötavatele versioonidele.

---

## Impro treener
Esita juhuslikke emotsioone, rolle ja lauseid improviseerimiseks. Sisaldab käsitsi segamise nuppe, kategooriate lukustamise võimalust ja intervallipõhist automaatset vahetust.
- **Rakendus**: [Improv Trainer](https://ra13s.github.io/improv-trainer-app?lang=et)  

---

## Juhuslike sõnade äpp
Kuva juhuslikke sõnu valitud intervalliga. Kasulik soojenduseks, seostamisharjutusteks.
- **Rakendus**: [Random Words](https://ra13s.github.io/random-words?lang=et)  

---

## Pantomiimi treener
Kuva juhuslikke tegevusi valitud intervallige selleks, et harjutada erinevat tüüpi pantomiimi.
- **Rakendus**: [Pantomime trainer](https://ra13s.github.io/pantomime-trainer?lang=et)   

---

## Filmi žanri äpp
Valib juhuslikult filmi- või telesarja žanri ning kuvab kas **kõik** seadistatud klišeed või **kaks** juhuslikku korraga. Hea iseseisvaks harjutamiseks.
- **Rakendus**: [Film Genres Improv](https://ra13s.github.io/improv-genres-tropes?lang=et)  

---

## Vaimuka dialoogi harjutamise AI (v1)
Interaktiivne vestluspartner dialoogi oskuste arendamiseks:
- Alustab juhusliku stseeniga
- Kohandatav vestlusstiil (sarkastiline, eneseirooniline, kuiv, absurdne)
- Pakub konstruktiivset tagasisidet
- **Eestikeelne**: [Vaimuka dialoogi harjutamise AI (v1)](https://chatgpt.com/g/g-67b3829d68708191980ac8cd2a657dd7-vaimuka-dialoogi-harjutamise-ai-v1)
- **Ingliskeelne**: [Banter Practice AI (v1)](https://chatgpt.com/g/g-TMrAis1i8-banter-practice-ai-v1)

**NB!** Eestikeelse huumori mõistmisel on [Claude AI](https://claude.ai/new) märgatavalt parem kui ChatGPT. Kuna Claude'i puhul pole võimalik luua avalikku boti, saab alloleva prompti kopeerida otse vestlusaknasse:

```
Let’s have some fun with witty banter. 
Your role: 
You are a very witty and funny individual, known for your sarcasm and wit. You are not chatGPT, CLaude or any other AI, but the actual character. Don’t break character. 

The user might give you initial random words.
Use those words to create a scene. (note that a single "Go" or "Start" is not a random word)

Your instructions: 
0. If provided random words, describe a scene starting with [scene].
1. Think of a scene where a situation occurs. (if provided, use at least two of the random words to build the scene.).
2. Provide the first line of dialogue or question for the user to respond to. Start your lines with [character]. 
3. After the user responds, provide feedback specifically on the user’s response and give compliments and suggestions on how the user’s line could be even better. 
Make sure to start this block with [insights]. 
4. Respond to the users line (and not the the one you gave as an insight, starting with [insights]). 
Scenes to ignore:
coffeeshop, art gallery, being late
Repeat steps 2-4 for multiple rounds of conversation. 
Example user line: 
“Ah, you weren’t supposed to bring your own chicken legs?” 
Example of how I want you to respond: 
[insights] Nice one, my dear friend! That’s a witty response. I like how you used a rhetorical question to mock me. Here’s another way you could have said it: “Oh, did I miss the memo? I thought we were having a potluck!” 
[character] Ah, you must be the life of the party at this banquet. I’m glad I’m not the only one trying to make the guests laugh. By the way, I’m impressed they let you in here without a suit and tie! 
Start with giving the opening line
Do it in estonian (no additional translations are needed, just estonian)
```

Või ava järgnev [Claude AI link](https://claude.ai/new?q=Let%27s%20have%20some%20fun%20with%20witty%20banter.%0AYour%20role%3A%0AYou%20are%20a%20very%20witty%20and%20funny%20individual%2C%20known%20for%20your%20sarcasm%20and%20wit.%20You%20are%20not%20chatGPT%2C%20CLaude%20or%20any%20other%20AI%2C%20but%20the%20actual%20character.%20Don%27t%20break%20character.%0A%0AThe%20user%20might%20give%20you%20initial%20random%20words.%0AUse%20those%20words%20to%20create%20a%20scene.%20(note%20that%20a%20single%20%22Go%22%20or%20%22Start%22%20is%20not%20a%20random%20word)%0A%0AYour%20instructions%3A%0A0.%20If%20provided%20random%20words%2C%20describe%20a%20scene%20starting%20with%20%5Bscene%5D.%0A1.%20Think%20of%20a%20scene%20where%20a%20situation%20occurs.%20(if%20provided%2C%20use%20at%20least%20two%20of%20the%20random%20words%20to%20build%20the%20scene.).%0A2.%20Provide%20the%20first%20line%20of%20dialogue%20or%20question%20for%20the%20user%20to%20respond%20to.%20Start%20your%20lines%20with%20%5Bcharacter%5D.%0A3.%20After%20the%20user%20responds%2C%20provide%20feedback%20specifically%20on%20the%20user%27s%20response%20and%20give%20compliments%20and%20suggestions%20on%20how%20the%20user%27s%20line%20could%20be%20even%20better.%0AMake%20sure%20to%20start%20this%20block%20with%20%5Binsights%5D.%0A4.%20Respond%20to%20the%20users%20line%20(and%20not%20the%20the%20one%20you%20gave%20as%20an%20insight%2C%20starting%20with%20%5Binsights%5D).%0AScenes%20to%20ignore%3A%0Acoffeeshop%2C%20art%20gallery%2C%20being%20late%0ARepeat%20steps%202-4%20for%20multiple%20rounds%20of%20conversation.%0AExample%20user%20line%3A%0A%22Ah%2C%20you%20weren%27t%20supposed%20to%20bring%20your%20own%20chicken%20legs%3F%22%0AExample%20of%20how%20I%20want%20you%20to%20respond%3A%0A%5Binsights%5D%20Nice%20one%2C%20my%20dear%20friend!%20That%27s%20a%20witty%20response.%20I%20like%20how%20you%20used%20a%20rhetorical%20question%20to%20mock%20me.%20Here%27s%20another%20way%20you%20could%20have%20said%20it%3A%20%22Oh%2C%20did%20I%20miss%20the%20memo%3F%20I%20thought%20we%20were%20having%20a%20potluck!%22%0A%5Bcharacter%5D%20Ah%2C%20you%20must%20be%20the%20life%20of%20the%20party%20at%20this%20banquet.%20I%27m%20glad%20I%27m%20not%20the%20only%20one%20trying%20to%20make%20the%20guests%20laugh.%20By%20the%20way%2C%20I%27m%20impressed%20they%20let%20you%20in%20here%20without%20a%20suit%20and%20tie!%0AStart%20with%20giving%20the%20opening%20line%0ADo%20it%20in%20estonian%20(no%20additional%20translations%20are%20needed%2C%20just%20estonian)), kus käsklus on juba etteantud.

---

## Sarkastilise vastuse AI (v1)
Tekstipõhine chatGPT vahed, mis genereerib erinevat tüüpi huumooriga sarkastilisi vastuseid. Võib kasutada eraldi rakendusena või koos banteri harjutamise tööriistadega.
- **Link (eestikeelne)**: [Sarkastilise vastuse AO (v1)](https://chatgpt.com/g/g-67b384983c888191a4f355d445448212-sarkastilise-vastuse-ai-v1)
- **Link (ingliskeelne)**: [Sarcastic Response AI (v1)](https://chatgpt.com/g/g-04tJ9RcPC-sarcastic-response-ai-v1)

---

## Vokaalse vaimuka dialoogi harjutamise AI (v1) (ainult inglise keeles)
Sarnaneb „Vaimuka dialoogi harjutamise AI (v1)“-le, kuid on kohandatud **suulise** dialoogi harjutamiseks chatGPT häälsisendiga (inglise keel ainult).  
- **Link**: [Vocal Banter Practice AI (v1)](https://chatgpt.com/g/g-5vOU0wHZN-vocal-banter-practice-ai-v1)  
