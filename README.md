# Hi 👋 I am Abanoub

[YouTube](https://www.youtube.com/@abanoubha)
&nbsp; • &nbsp;
[𝕏 (twitter)](https://twitter.com/abanoubha)
&nbsp; • &nbsp;
[linkedin](https://www.linkedin.com/in/abanoub-hanna)
&nbsp; • &nbsp;
[Telegram](https://t.me/abanoubchan)
&nbsp; • &nbsp;
[Facebook](https://www.facebook.com/AbanoubHannaDotCom)
&nbsp; • &nbsp;
[CV • Résumé • Portfolio](https://abanoubhanna.com/posts/me)

As [Newton said](https://en.wikipedia.org/wiki/Standing_on_the_shoulders_of_giants) : "If I have seen further it is by standing on the shoulders of Giants". So if you consider my projects helpful, it is by standing on the shoulders of giants — in the open source community.

My software motto is "Simple by default, powerful when needed".

__User experience__ of my software should be __seamless__, __intuitive__ and __fun__.

For my __developer experience__, I tend to use _fewer dependencies_, I prefer _locality_ of functionality more than clean code in too many files, I tend to create _simpler UI_ for my sanity.

I am in the __top GitHub users__ by __total contributions__, & by __public contributions__ in __Egypt__ according to [gayanvoice/top-github-users](https://github.com/gayanvoice/top-github-users/blob/main/markdown/public_contributions/egypt.md) and [committers.top](https://committers.top/egypt_private).

[![committers.top badge](https://user-badge.committers.top/egypt_private/abanoubha.svg)](https://user-badge.committers.top/egypt_private/abanoubha)

## Software I Created

### Digital Business Card

- [a virtual wallet of digital business cards](https://kartbusiness.com)
  - Laravel
  - Tailwind CSS
  - API for mobile apps (Laravel + Go)
  - Android App (~~Kotlin + Jetpack Compose~~) -> (Flutter)
  - iOS App (planned)
- [Install the app on your mobile](https://kartbusiness.com/app) from [Google Play](https://play.google.com/store/apps/details?id=com.kartbusiness.app).

## Kmt : Hugo Theme

- Kmt is a [Hugo](https://gohugo.io/) theme. It is named after [the ancient name of Egypt](https://en.wikipedia.org/wiki/Egypt#Names) (my home country).
- [Kmt is open source](https://github.com/abanoubha/gohugo-theme-kmt)

### Loka Stores

- [Loka ecommerce website](https://lokastores.com)
- tech stack : Laravel 10 + Blade + Tailwind CSS

### OCR Text Scanner

- a toolset to identify and extract text from images efficiently.
- __supported languages in the app UI (user interface)__: English (default), Arabic.
- __supported languages to OCR__ : English (default), Arabic, Hindi (Indian language), Farsi (Persian language), Catalan, Danish, Dutch, Finnish, French, German, Hungarian, Italian, Latin, Norwegian, Polish, Portuguese, Romanian, Romanian, Spanish, Swedish, Tagalog, Turkish.
- __app features__ :
  - [x] works offline (without internet connection)
  - [x] Ability to edit extracted text in the app
  - [ ] uses three color coded accuracy ( white/black +90% accuracy & purple 80-90% & red -80%)
  - [ ] save OCR history (aka : Detailed scanned images history)
  - [ ] choose more than one image to OCR
  - [ ] batch processing OCR on many images at once (concurrently) (bulk OCR)
  - [ ] save extracted text as PDF
  - [ ] save extracted text as plain text file `.txt`
  - [ ] Automatic cropping and recognition function as a default behavior (auto)
  - [ ] Ability to edit image before/after running OCR on it (manual)
- __tech stack__ : Flutter, Tesseract.
- __install the app from__ : [Google Play](https://play.google.com/store/apps/details?id=com.softwarepharaoh.ocr)

### IMG2TXT OCR

- After 7+ years in production, I [opensourced](https://github.com/abanoubha/img2txt_app) the project.
- Tech Stack: Kotlin • Tesseract lib.
- Image to Text OCR Text Scanner App • a tool to identify and extract text from images efficiently.
- Supported languages: Arabic • English.
- features and advantages:
  - works without internet (offline)
  - identifies English and Arabic languages at the same time on the same image
  - uses three color coded accuracy: white/black +90% accuracy • purple 80-90% • red 50-80% • 0-50% discarded
  - OCR processing speed depends on your smartphone capabilities
  - use ML Kit or Google Vision if available, else use Tesseract OCR
  - let the app user choose the text language {Arabic, English, Arabic+English}
  - edit the extracted text
  - copy the recognized text
- Install The App:
  - [IMG2TXT OCR English/Arabic - Google Play](https://play.google.com/store/apps/details?id=com.softwarepharaoh.img2txt) ([latest release](https://github.com/abanoubha/img2txt_app/releases))
  - [IMG2TXT OCR Latin-based Languages - Google Play](https://play.google.com/store/apps/details?id=com.softwarepharaoh.img2txt.latin)
    - No longer maintained. Use img2txt OCR app and choose 'English' and it will work on all Latin scripted languages.
  - [Persian OCR - Google Play](https://play.google.com/store/apps/details?id=com.softwarepharaoh.img2txt.persian)
    - No longer maintained. I will add Persian/Farsi language to img2txt app soon.
  - [Hindi OCR - Google Play](https://play.google.com/store/apps/details?id=com.softwarepharaoh.img2txt.hindi)
    - No longer maintained. I will add Indian/Hindi language to img2txt app soon.
  - [Huawei AppGallery](https://appgallery.huawei.com/#/app/C102909069)
    - Old version. Just download the latest version of img2txt OCR app from [GitHub](https://github.com/abanoubha/img2txt_app/releases/) if your smartphone does not support Google Play.

### Pope Shenouda books

- Android app to read the books written by Pope Shenouda III. __Application features and advantages__: You can use touch gestures to turn/flip the pages of the book (Touch Gestures) • go to the last page you read in the last reading session • very little storage/space usage (~5MB).
- __Tech Stack__ : Java, SQLite ([read about the change from plain text files >> to >> sqlite db here](https://abanoubhanna.com/posts/text-files-vs-sqlite-android/))
- install the app from Google play [(Pope Shenouda books)](https://play.google.com/store/apps/details?id=com.softwarepharaoh.popebooks)

### Abanoub Hanna | Bilingual Tech Blog

- my bilingual tech blog in English & Egyptian Arabic. I post about Go language, Flutter framework, Laravel framework, .. and many others things. If you are interested, [visit the blog here](https://abanoubhanna.com).

### Agpeya - الأجبية

- An Arabic book of prayers for Coptic Orthodox Church.
- open source on [GitHub](https://github.com/abanoubha/agpeya).
- app size is around 1.3MB
- supports all Android versions from Android 5.1 up to the latest Android 14
- __Tech Stack__ : Java, SQLite.
- [Install Agpeya app from Google Play](https://play.google.com/store/apps/details?id=com.softwarepharaoh.agpeya) (uptodate)
  - or [AppGallery](https://appgallery.cloud.huawei.com/ag/n/app/C105039643?channelId=agpeya&id=8c4974399ed54f9c820e5b5a6fbce4a8&s=2F8958B2459A92B4D6694B856BE386F8C719CCBBB64C2F2AD638E53CAA3C9E98&detailType=0&v=&callType=AGDLINK&installType=0000) (old version).

### cleanText

- an [open source](https://github.com/abanoubha/cleanText) tool to normalize text (convert special chars to normal chars such as `àáâ` into `aaa`)

### gobrew

- [opensource](https://github.com/abanoubha/gobrew) CLI app written in Go to show count of all programs written in X language or Y build system in Homebrew Core formulae.

### i

- *i* is an abstraction over all package managers. [The *i* project](https://github.com/abanoubha/i) is open source (OSS), written in Go language.

## Software of choice | Tech Stack of choice

- __OS__ : Ubuntu Linux, Mac OS X, and Windows 10/11
- __Web browser__ : Google Chrome, Mozilla Firefox, and Apple Safari
- __to create a custom website/web app__ : Laravel + PostgreSQL db + Tailwind CSS
- __to create large-scale web app__ : Go + HTMX + Tailwind CSS + ~~Go Templ~~ + PostgreSQL db
- __to create backend API__ : Go std, or Laravel
- __to create an Android app__ : ~~Kotlin + Jetpack Compose~~ Flutter + SQLite db (as it is local)
- __to create a blog__ : Hugo, or WordPress, or my new thing (work-in-progress alternative)
- __source code editors & IDEs__ :
  - Android Studio
  - vim: [.vimrc : my simple config](https://gist.github.com/abanoubha/3ace670cf05b931368557e55872a0df2)
  - neovim (a.k.a nvim): [init.lua : my simple config](https://gist.github.com/abanoubha/7aaf5ff87d8772d7d8a456a42c0bfaac)
  - visual studio code (a.k.a vscode)
- developed [Hugo theme](https://github.com/abanoubha/gohugo-theme-kmt)
- [history] created Android apps in Java. for example, [Agpeya Android app](https://github.com/abanoubha/agpeya).
- [history] created a web app in native PHP (Plain PHP + HTML + CSS + JS)
- [history] developed a WordPress Theme
