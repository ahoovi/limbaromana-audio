# limbaromana-audio

קבצי השמע (mp3) של מדריך הרומנית ב-amitbrin.com, מוגשים דרך GitHub Pages:
`https://ahoovi.github.io/limbaromana-audio/<hash>.mp3`

**לא עורכים כאן ידנית.** התיקייה מתמלאת אוטומטית:

1. `build-limbaromana-audio.mjs` מייצר את כל הקליפים למחסן המקומי `limbaromana-audio-store/`.
2. `_repo/tools/limbaromana-split/build.py` מעתיק לכאן את כל הקליפים **חוץ מהפרטיים**
   (השאלון האישי, עמוד נטע, A1). אלה נשארים ב-Vercel תחת `/limbaromana-audio/`.
3. אחרי כל שיעור: `git add -A && git commit && git push` גם כאן, וגם בריפו האתר.

שם הקובץ הוא hash של הטקסט (cyrb53, ‏`limbahash.py`), ולכן קובץ קיים לא משתנה לעולם.
