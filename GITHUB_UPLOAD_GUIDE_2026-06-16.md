# מדריך העלאה ל-GitHub ול-Vercel - כרטיס דיגיטלי טלי רוזנברג

תאריך עדכון: 16.06.2026

הקובץ הזה מרכז את כל המידע שצריך כדי להעלות את הכרטיס הדיגיטלי המעודכן ל-GitHub ולפרוס אותו ב-Vercel.

## שם הפרויקט

כרטיס דיגיטלי - טלי רוזנברג

## תיקיית הפרויקט במחשב

```text
/Users/talirozenberg/Documents/Codex/2026-05-23/new-chat
```

## קבצים שחייבים להעלות ל-GitHub

להעלות את הקבצים והתיקיות הבאים:

```text
index.html
style.css
script.js
privacy.html
accessibility.html
vercel.json
assets/tali-logo.png
assets/tali-profile.jpeg
assets/tali-rozenberg-contact.vcf
```

## מבנה מומלץ ב-GitHub

כך התיקייה צריכה להיראות בתוך הריפו:

```text
/
├── index.html
├── style.css
├── script.js
├── privacy.html
├── accessibility.html
├── vercel.json
└── assets/
    ├── tali-logo.png
    ├── tali-profile.jpeg
    └── tali-rozenberg-contact.vcf
```

## קבצים שלא צריך להעלות

אלו קבצי גיבוי, טיוטות או קבצים זמניים. אין צורך להעלות אותם ל-GitHub:

```text
.DS_Store
assets/tali-profile-previous.jpeg
assets/tali-profile-source.jpeg
tali vidget
tali vidget 2
tali vidget.html
tali vidget.zip
tali-card-reference-2026-05-28
```

## מה כל קובץ עושה

```text
index.html
העמוד הראשי של הכרטיס הדיגיטלי.

style.css
העיצוב של הכרטיס: צבעים, ריווחים, מובייל, כפתורים, תמונה, לוגו ונראות כללית.

script.js
כלי הנגישות והפעולות הדינמיות של הכרטיס.

privacy.html
עמוד מדיניות פרטיות.

accessibility.html
עמוד הצהרת נגישות.

vercel.json
קובץ הגדרות לפריסה ב-Vercel, כדי למנוע שגיאות 404.

assets/tali-logo.png
הלוגו של טלי.

assets/tali-profile.jpeg
תמונת הפרופיל הפעילה בכרטיס.

assets/tali-rozenberg-contact.vcf
קובץ שמירת איש קשר.
```

## פרטי הכרטיס

```text
שם: טלי רוזנברג
תחום: אסטרטגיה ותוכן דיגיטלי
קהל יעד: בעלות עסקים שרוצות שיווק דיגיטלי מסודר, ברור ומדויק יותר
פעולה מרכזית: תיאום שיחת התאמה בוואטסאפ
טלפון / וואטסאפ: 058-6287333
מייל: rozdigitalm@gmail.com
אינסטגרם: https://www.instagram.com/rdm_tali/
פייסבוק: https://www.facebook.com/profile.php?id=61583277183396
```

## בדיקות שבוצעו

```text
index.html קיים בתיקייה הראשית.
style.css קיים בתיקייה הראשית.
script.js קיים בתיקייה הראשית.
vercel.json קיים בתיקייה הראשית.
תיקיית assets קיימת.
הלוגו נטען עם נתיב יחסי: assets/tali-logo.png
תמונת הפרופיל נטענת עם נתיב יחסי: assets/tali-profile.jpeg
קובץ איש הקשר נטען עם נתיב יחסי: assets/tali-rozenberg-contact.vcf
אין קישורים שמתחילים ב-file://
אין נתיבים מקומיים מתוך המחשב בתוך index.html
קיים H1 אחד בלבד בעמוד הראשי.
קיימים עמודי privacy.html ו-accessibility.html
```

## אחרי העלאה ל-GitHub

לאחר העלאה ל-GitHub, לפתוח את הריפו ולוודא שרואים:

```text
index.html
style.css
script.js
privacy.html
accessibility.html
vercel.json
assets
```

בתוך assets לוודא שיש:

```text
tali-logo.png
tali-profile.jpeg
tali-rozenberg-contact.vcf
```

## פריסה ב-Vercel

1. להיכנס ל-Vercel.
2. לבחור Add New Project.
3. לבחור את הריפו של GitHub.
4. להשאיר Framework Preset כ-Other או Static.
5. לא צריך Build Command.
6. לא צריך Output Directory.
7. ללחוץ Deploy.

## בדיקות אחרי פריסה

אחרי ש-Vercel נותן לינק ציבורי, לבדוק:

```text
העמוד הראשי נפתח.
הלוגו מופיע.
תמונת הפרופיל מופיעה בתקריב.
כפתור וואטסאפ עובד.
כפתור התקשרות עובד.
כפתור מייל עובד.
כפתור אינסטגרם עובד.
כפתור פייסבוק עובד.
שמירת איש קשר מורידה vCard.
מדיניות פרטיות נפתחת.
הצהרת נגישות נפתחת.
אין שגיאת 404.
הכרטיס נראה טוב במובייל.
```

## הערה חשובה

אם מעלים ידנית דרך GitHub, חשוב לא לגרור את כל התיקייה כמו שהיא אם היא כוללת תיקיות גיבוי. להעלות רק את הקבצים שמופיעים תחת "קבצים שחייבים להעלות ל-GitHub".
