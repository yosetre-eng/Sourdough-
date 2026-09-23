# יומן מחמצת — התקנה כאפליקציה

## 1. Firebase (לסנכרון בין מכשירים — אפשר לדלג)
1. ב-Firebase Console: פרויקט חדש (או קיים) ← **Add app** ← Web. העתק את ה-config לתוך `firebase-config.js`.
2. **Authentication** ← Sign-in method ← הפעל **Email/Password**.
3. **Authentication** ← Settings ← Authorized domains ← הוסף `yosetre-eng.github.io`.
4. **Firestore Database** ← Create database ← לשונית **Rules** ← הדבק את התוכן של `firestore.rules` ← Publish.

בלי שלב 1 האפליקציה עובדת מלא, אבל שומרת רק בטלפון.

## 2. GitHub Pages
1. ריפו חדש, למשל `sourdough`, והעלאת כל הקבצים והתיקייה `icons` לשורש.
2. Settings ← Pages ← Branch: `main` / root ← Save.
3. אחרי דקה-שתיים: `https://yosetre-eng.github.io/sourdough/`

## 3. התקנה בטלפון
- **אייפון:** פותחים ב-Safari ← שיתוף ← "הוסף למסך הבית".
- **אנדרואיד:** Chrome ← ⋮ ← "התקנת אפליקציה".

## עדכונים
בכל העלאה של גרסה חדשה, שנה ב-`sw.js` את `machmetzet-v1` ל-`v2` וכן הלאה.
