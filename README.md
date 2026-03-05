### Language Tagging Prompt (Ukrainian vs. Russian)

**Task:** Zero-shot word-level language identification in mixed (code-switched) sentences.

**Prompt Template:**
> I'm going to give you a sentence with Ukrainian and Russian words. Please put :uk after each Ukrainian word and :ru after each Russian word.
> 
> **Format Example:** > а:uk живуть:uk за:uk принципом:uk ті:uk оціночники:uk мы:ru не:ru сеем:ru не:ru пашем:ru не:ru строим:ru мы:ru гордимся:ru общественным:ru строем:ru
>
> **Sentence to tag:** > [INSERT_SENTENCE_HERE]
