# Lua 3D Spinning One-Liner-Donut 🍩

Hey there! Welcome to my **Lua Donut Spinner Terminal Interface**—a fun, single-line project that spins a 3D donut right in your console! It’s my spin (pun intended) on Andy Sloane’s awesome "Donut in C," and I’m excited to share it with you. Scroll down to the language console to flip between English, Ukrainian, or German versions. Pick your vibe and let’s dive into this sweet little пончик adventure!

## Language Console Switcher ⚙️
*Flip the dial like you’re tuning an old terminal—choose your language and let’s get spinning!*

<details open>
  <summary>English (Default) 🇬🇧</summary>

  ### How It All Started 🍩✨
  Picture this: it’s 2011, and Andy Sloane drops his [“Donut Math”](https://www.a1k0n.net/2011/07/20/donut-math.html)—a 3D donut spinning in ASCII, coded in C. I was just a kid back then (born in ’06!), so I didn’t catch it live, but I stumbled across it years later and was totally hooked. Fast forward to recently, when I was chilling as an observer at a *robot_dreams* competition, run by a cool Ukrainian course company. They challenged folks to squeeze big ideas into tiny code. I wasn’t competing—just watching—but one night, scrolling through their wild submissions, I got an itch. “What if I could shrink Andy’s donut into one Lua line?” I grabbed some tea, fired up my laptop, and that’s how this whole thing kicked off.

  ### What It Can Do 🌟
  - **One-Line Magic**: Spins a full 3D donut with just one Lua line.
  - **ASCII Charm**: Turns `. , - ~ : ; = ! * # $ @` into a spinning gem on an 80x  22 grid.
  - **Math Fun**: Uses equations and projection to bring it to life.
  - **Smooth Flow**: Aims for near-60 FPS in your terminal.
  - **Tinker-Ready**: Easy to mess with the spin or size if you’re curious.

  ### The Heart of It 🍩📜
  Hanging out at *robot_dreams* got my brain buzzing. I wasn’t in the game, just a sideline dreamer, but watching those coders wrestle with limits made me want to play too. Andy’s donut was my muse, and I turned it into this one-line Lua treat—simple, playful, and a little bit nuts, just how I like it.

  ### Why Lua for This Donut? 🤘
  Why Lua? Honestly, it’s my go-to buddy for coding shenanigans. While eyeballing *robot_dreams*, I saw folks battling tight constraints, and it clicked: Lua’s super light and fast—like, no extra weight, just the good stuff. It runs anywhere without needing a bunch of add-ons, which I love. The syntax is so friendly that I could squish loops, math, and display code into one line without a meltdown—try that in C or Python without crying! Lua’s also perfect for messing around; I could tweak the spin speed or puff up the donut on a whim. Plus, there’s this cheeky vibe to it: sitting back, watching the competition, and thinking, “I’ll bake my own Lua пончик, Ukrainian-style, just for fun.” It’s tiny, scrappy, and screams “me”—a kid born in ’06 who loves a good code puzzle.

  ### Fun Stuff to Try 🔥
  - **Speed Boost**: Fiddle with `sleep 0.016` or `A = A + 0.04`, `B = B + 0.02` to make it fly.
  - **Big Donut Energy**: Crank up `40 + 30 * D` (x) and `12 + 15 * D` (y) for a chubby treat.
  - **Style Swap**: Ditch `. , - ~ : ; = ! * # $ @` for your own ASCII twist.
  - **Sneaky Peek**: Dig into `zbuffer` to see the depth magic.
  - **Power Up**: Play with Lua coroutines to split the load and zip faster.

  ### How to Spin It Yourself 🚀
  1. **Grab Lua**:  
     - Windows: Snag `lua-5.4.6_Win64_bin.zip` from [lua.org](https://www.lua.org), unzip, add to PATH.  
     - Linux: Type `sudo apt install lua5.4` or `sudo yum install lua`.  
     - macOS: Run `brew install lua`.  
     - Check: `lua -v` should say something like `Lua 5.4.6`.  
  2. **Get the Goods**: Clone `https://github.com/ArchieDev242/One-liner-donut` or grab `donut.lua`.  
  3. **Let It Rip**: Open a terminal, head to the folder, and type `lua donut.lua`.  
  4. **Chill Out**: Hit `Ctrl+C` when you’ve had your fill.  
  *Pro Tip*: Fixed-width font (like Consolas) and 80x22+ screen size make it pop.

  ### Shoutout to the Original 🍩💡
  This builds on Andy’s [Donut in C](https://www.a1k0n.net/2011/07/20/donut-math.html). I found it later, but it’s the spark that got me here—check it out, then come tweak mine!

  ### Join the Fun 🍴
  Wanna mess with it? Speed it up, spice it up—whatever vibe you’re feeling, toss me a pull request. Let’s keep this donut rolling together!

</details>

<details>
  <summary>Українська (Ukrainian) 🇺🇦</summary>

  ### Як усе почалося 🍩✨
  Енді Слоун випустив свій [“Donut Math”](https://www.a1k0n.net/2011/07/20/donut-math.html) у 2011-му — я тоді був малим (народився в 2006-му), тож усе пропустив! Наткнувся на нього вже потім і подумав: “Оце так крутота!” — 3D-пончик в ASCII на C. А недавно я зависав, спостерігаючи за змаганням від *robot_dreams*, української компанії з курсами. Там народ ганявся за тим, як умістити купу ідей у крихітний код. Я не брав участі, просто гледів, але одного вечора, гортаючи їхні шалені штуки, мене осінило: “А якщо я зроблю пончик Слоуна в одному рядку Lua?” Узяв чай, увімкнув ноут — і понеслося.

  ### Що він вміє 🌟
  - **Один рядок**: Крутить 3D-пончик одним рядком Lua.
  - **ASCII-магія**: Робить `. , - ~ : ; = ! * # $ @` живим на сітці 80 x 22.
  - **Математична душа**: Рівняння й проєкція для краси.
  - **Плавно йде**: Цілить у 60 FPS у терміналі.
  - **Легко грати**: Хочеш — міняй оберти чи розмір.

  ### У чому суть 🍩📜
  Дивитися на *robot_dreams* було як гортати цікаву книжку — я не змагався, просто насолоджувався шоу. Але ті кодерські батли розбудили в мені бажання погратися. Взяв пончик Слоуна й зробив свій — у одному рядку Lua. Просто, весело й трохи божевільно, як я люблю.

  ### Чому Lua для цього пончика? 🤘
  Чому Lua? Бо це мій кодерський bro! Поки я гледів *robot_dreams*, бачив, як люди мучаться з обмеженнями, і подумав: Lua — легка, швидка, не грузить пам’ять. Запускаєш цей пончик де хочеш без зайвих танців. Її синтаксис — просто пісня: цикли, математика, вивід — усе в один рядок, без сліз, як у C чи Python. З Lua можна бавитися — крути швидше, роби пончик більшим коли заманеться. А ще це мій тихий бунт: сиджу, дивлюся змагання і думаю, “Зроблю свій Lua-пончик, по-українськи, чисто по приколу.” Він маленький, жвавий і показує, як я, народжений у 2006-му, люблю копирсатися в коді просто так!

  ### Круті штуки для гри 🔥
  - **Ганяй швидше**: Пограйся з `sleep 0.016` чи `A = A + 0.04`, `B = B + 0.02`.
  - **Більший пончик**: Збільш `40 + 30 * D` і `12 + 15 * D`.
  - **Свій стиль**: Кинь замість `. , - ~ : ; = ! * # $ @` щось своє.
  - **Заглянь усередину**: Подивися `zbuffer`.
  - **Прискорення**: Спробуй корутини Lua для драйву.

  ### Як запустити 🚀
  1. **Візьми Lua**:  
     - Windows: Завантаж `lua-5.4.6_Win64_bin.zip` з [lua.org](https://www.lua.org), додай до PATH.  
     - Linux: `sudo apt install lua5.4` або `sudo yum install lua`.  
     - macOS: `brew install lua`.  
     - Перевір: `lua -v`.  
  2. **Хапай скрипт**: Клонуй `https://github.com/ArchieDev242/One-liner-donut` або бери `donut.lua`.  
  3. **Гайда крутити**: У терміналі пиши `lua donut.lua`.  
  4. **Гальмуй**: Тисни `Ctrl+C`, коли досить.  
  *Порада*: Фіксований шрифт і 80x22+ — топчик.

  ### Дяка оригіналу 🍩💡
  Усе почалося з [Donut in C](https://www.a1k0n.net/2011/07/20/donut-math.html) Слоуна. Знайшов його пізніше, але він мене запалив — глянь і пограйся з моїм!

  ### Давай разом 🍴
  Хочеш щось додати? Прискорити чи прикрасити — кидай ідеї в pull request. Крутімо цей пончик удвох!

</details>

<details>
  <summary>Deutsch (German) 🇩🇪</summary>

  ### Wie alles begann 🍩✨
  Andy Sloane hat 2011 sein [“Donut Math”](https://www.a1k0n.net/2011/07/20/donut-math.html) veröffentlicht — ich war damals noch klein (geboren ’06), also hab ich’s nicht live erlebt! Später hab ich’s entdeckt und war hin und weg: ein 3D-Donut in ASCII mit C. Vor Kurzem hing ich dann bei einem Wettbewerb von *robot_dreams*, einem ukrainischen Kursanbieter, rum — nur als Zuschauer. Die Aufgabe war, viel in wenig Code zu packen. Ich war nicht dabei, aber eines Abends, beim Stöbern in den abgefahrenen Einsendungen, dachte ich: “Was, wenn ich Sloanes Donut in eine Lua-Zeile quetsche?” Tee geholt, Laptop an — und los ging’s.

  ### Was er kann 🌟
  - **Einzeiler**: Dreht einen 3D-Donut mit einer Lua-Zeile.
  - **ASCII-Trick**: Macht `. , - ~ : ; = ! * # $ @` lebendig auf einem 80 x 22-Raster.
  - **Mathe-Spaß**: Gleichungen und Projektion für den Kick.
  - **Flüssig**: Strebt 60 FPS im Terminal an.
  - **Spielbar**: Spin und Größe leicht änderbar.

  ### Der Kern 🍩📜
  Das Zuschauen bei *robot_dreams* hat mich angefixt. Ich war nicht im Rennen, nur ein Träumer am Rand, aber die Coding-Action hat mich gepackt. Sloanes Donut war mein Startpunkt, und ich hab ihn in eine Lua-Zeile verwandelt — einfach, witzig und ein bisschen verrückt, so wie ich’s mag.

  ### Warum Lua für diesen Donut? 🤘
  Warum Lua? Weil’s mein Coding-Kumpel ist! Beim Gucken von *robot_dreams* hab ich gesehen, wie die Leute mit Limits kämpften, und dachte: Lua ist leicht, schnell und braucht kaum Platz. Läuft überall ohne Gedöns — genau mein Ding. Der Syntax ist so locker, dass ich Schleifen, Mathe und Anzeige in eine Zeile packen konnte, ohne Chaos wie in C oder Python. Lua lädt zum Rumspielen ein: Geschwindigkeit anpassen, Donut aufblähen — alles easy. Und ja, es war ein kleiner Streich: Ich saß da, schaute zu und dachte, “Ich bau meinen Lua-Donut, ukrainisch angehaucht, einfach so aus Spaß.” Klein, flink und pure Freude von einem 2006er, der gerne rumbastelt!

  ### Coole Sachen zum Testen 🔥
  - **Tempo**: Spiel mit `sleep 0.016` oder `A = A + 0.04`, `B = B + 0.02`.
  - **Größer**: Mach `40 + 30 * D` und `12 + 15 * D` dicker.
  - **Eigenstyle**: Tausch `. , - ~ : ; = ! * # $ @` gegen was Eigenes.
  - **Tieferblick**: Schau in `zbuffer` rein.
  - **Boost**: Probier Lua-Coroutinen für mehr Power.

  ### Wie du’s startest 🚀
  1. **Hol Lua**:  
     - Windows: Lad `lua-5.4.6_Win64_bin.zip` von [lua.org](https://www.lua.org), füg’s zum PATH hinzu.  
     - Linux: `sudo apt install lua5.4` oder `sudo yum install lua`.  
     - macOS: `brew install lua`.  
     - Test: `lua -v`.  
  2. **Schnapp den Script**: Klon `https://github.com/ArchieDev242/One-liner-donut` oder lad `donut.lua`.  
  3. **Losdrehen**: Tippe `lua donut.lua` im Terminal.  
  4. **Stopp**: `Ctrl+C`, wenn’s reicht.  
  *Tipp*: Feste Schriftart, 80x22+ für den besten Look.

  ### Danke an den Original 🍩💡
  Alles dank [Donut in C](https://www.a1k0n.net/2011/07/20/donut-math.html) von Sloane. Später entdeckt, aber es hat mich angespornt — schau’s an und spiel mit meinem!

  ### Komm mit 🍴
  Lust, was zu ändern? Schneller, bunter — schick mir deine Ideen per Pull Request. Lass uns den Donut zusammen rocken!

</details>

---
