أضف الكود التالي قبل نهاية الوسم `</body>` في ملف  
`c:\Users\Administrator\لعبة احمد الكلاسيكيه\ahmad-classic-game\index.html`  
واستبدل الرابط برابط GitHub Pages الخاص بك بعد رفع اللعبة:

````html
<button id="openGameBtn">افتح اللعبة</button>
<script>
    document.getElementById('openGameBtn').addEventListener('click', () => {
        window.open('https://username.github.io/repository-name/ahmad-game.html', '_blank');
    });
</script>
</body>
</html>
````

**ملاحظات:**
- ضع الكود قبل `</body>`.
- غيّر `username` و`repository-name` إلى اسم المستخدم واسم المستودع الخاص بك على GitHub بعد رفع اللعبة.

إذا تحتاج شرح رفع اللعبة على GitHub Pages أو استخراج الرابط الصحيح، أخبرني بذلك!
