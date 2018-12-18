## الأشخاص

لنُضِف أشخاصًا آخرين إلى لعبتك ليتعامل معهم كائن `اللاعب`.

+ عُد إلى الكائن `شخص`.

![Person sprite](images/person-sprite.png)

+ أضف بعض التعليمات البرمجية إلى الكائن `شخص`، ليتحدث مع كائن `اللاعب`. هذه التعليمة البرمجية تشبه إلى حدٍ كبير التعليمةَ البرمجية التي أضفتَها إلى كائن `لافتة الترحيب`:

```blocks
	عند نقر ⚑
  اذهب إلى الموضع س: (0) ص: (-150)
  كرر باستمرار 
    إذا <ملامس لـ [player v] ؟> 
      قل [Did you know that you can go through orange and yellow doors?]

      قل []
    end
  end
```

+ يمكنك أيضًا أن تسمح للكائن `شخص` بالتحرك عن طريق إضافة هذين القالبين البرمجيين في قالب`else`{:class="blockcontrol"} من التعليمة البرمجية:

```blocks
تحرك (1) خطوة
ارتد إذا كنت عند الحافة
```

سيتحرك الكائن `شخص` الآن، لكن لن يتوقف للتحدث مع كائن `اللاعب`.

![screenshot](images/world-person-test.png)


--- challenge ---
### التحدي: تحسين الشخص
هل يمكنك إضافة تعليمة برمجية إلى الكائن `شخص` بحيث يظهر في الغرفة 1 فقط؟ تأكد من اختبار التعليمة البرمجية الجديدة.

--- /challenge ---