# Anki-Chinese-Grammar-Practice
Practice Chinese language grammar.

Cards contain example sentence from AllSet Learning's Chinese Grammar Wiki. I used existing anki deck [Visit](https://ankiweb.net/shared/info/782551504). It contains A1 to C1 (HSK1 to HSK5).

### Note: The deck will updated regularly.

## Quick start
Download Anki deck from ankiweb and import it in Anki or Ankidroid.

[Chinese Grammar Practice](https://ankiweb.net/shared/info/86203928)

## Disclaimer
I used existing [deck](https://ankiweb.net/shared/info/782551504) data for developing this. I have removed and edited some sentences.
There is no audio file.

Some sentences may be correct but due to order in sentences it may show incorrect.
For ex:-
<br>我不知道她。
<br>and
<br>她不知道我。

Both sentences are correct. But after clicking 'check' button, it will show answer according to order of characters in the sentences.

## For adding sentences to deck
Cards have following fields
```
{{中文}}
{{Pinyin}}
{{English}}
...
{{Splitted}} //--> it store chinese sentence with space between characters. It is generated using [jieba] (https://github.com/fxsjy/jieba).
```
Add value to respective fields but it should be noted, {{Splitted}} field must contain sentences with spaces between characters.
For ex:-
<br>我 不 知道 她 。
<br>用 手机 学习 汉语 。

# To Change size of characters in sentences.
### question button
Change this,
```
font-size: 1rem;
```
<b>in following</b>
```css
.btn-q {
    background-color: var(--white);
    border: 2px solid var(--gray);
    border-bottom: 5px solid var(--gray);
    border-radius: 9px;
    font-size: 2rem;
    padding: 0.25rem 0.35rem;
    margin: 0.2rem;
    display:inline-block;
  }
```

### answer button
Change this,
```
font-size: 1rem;
```
<b>in following</b>
```css
.btn-a {
    background-color: var(--white);
    border: 2px solid var(--gray);
    border-bottom: 5px solid var(--gray);
    border-radius: 9px;
    font-size: 1rem;
    padding: 0.25rem 0.35rem;
    margin: 0.2rem;
    display:inline-block;
  }
```

# Images
![Image 1](https://raw.githubusercontent.com/infinyte7/Anki-Chinese-Grammar-Practice/master/Decks%20File/image1.png)
![Image 2](https://raw.githubusercontent.com/infinyte7/Anki-Chinese-Grammar-Practice/master/Decks%20File/image2.png)

## Please report any issues.
### Any contribution will be appreciated

### Similar Anki Decks with HSK level and audio to each sentences 
[Chinese Grammar](https://github.com/infinyte7/Chinese-Grammar)
<br>[AnkiWeb Link](https://ankiweb.net/shared/info/551486109)

## My other anki decks
[Anki Decks](https://ankiweb.net/shared/byauthor/2120672269)

# License
<b>[Chinese Grammar Wiki Study Deck](https://ankiweb.net/shared/info/782551504)</b>
<br>Chris Dodge
<br>[CC BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/)

<b>[Chinese Grammar Wiki ©2011-2020 AllSet Learning](https://resources.allsetlearning.com/chinese/grammar/Chinese%20Grammar%20Wiki:Copyrights)</b>
<br>[CC BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/)

<b>Anki-Chinese-Grammar-Practice</b>
<br>Mani (Infinyte7)
<br>[CC BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/)
