MEFF GENIUS — Android телефонға орнатудың қарапайым жолы

Бұл — installable web app (PWA). AndroidIDE, Gradle немесе APK құрастыру қажет емес.

ЕҢ ОҢАЙ ТЕКСЕРУ:
1) index.html файлын телефонда Chrome арқылы ашып көріңіз (кейбір телефондар жергілікті HTML ішіндегі мүмкіндіктерді шектеуі мүмкін).
2) Толық орнату үшін файлдарды HTTPS хостингке шығару керек. Мысалы, GitHub Pages:
   - ZIP-ті шығарып алыңыз.
   - GitHub-та жаңа public repository жасаңыз (мысалы, meff-genius).
   - index.html, manifest.json, sw.js, icon.svg файлдарын репозиторийдің түбіріне жүктеңіз.
   - Repository → Settings → Pages → Deploy from a branch → main / root → Save.
   - Берілген https://...github.io/... сілтемесін Android-та Chrome-мен ашыңыз.
   - Chrome мәзірі ⋮ → Add to Home screen / Install app.
3) Телефонның басты экранында MEFF GENIUS белгішесі пайда болады.

ЕСКЕРТУ:
- Бұл әзірге интерфейс прототипі. Нақты AI сервері/API қосылмаған.
- API кілтін браузердегі кодқа салмаңыз; нақты AI үшін қауіпсіз серверлік бөлік керек.
