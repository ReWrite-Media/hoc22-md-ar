### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# الجسر العاصف

## الخطوة الأولى
استخدم المؤشر الخاص بك لحجب الرياح، حتى تتمكن من عبور الجسر.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
استخدم بلوك ``||hoc22:تحريك المؤشر||`` لوضع المؤشر أمام الثقوب، ثم استخدم بلوك ``||hoc22:وضع كتلة||``  لملء الثقوب وحجب الرياح.


```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
```
```template
    hoc22.cursorMoveOrientationOneRight(1)   
    hoc22.placeBlock()
```
```package
hoc22-ts-ar=github:ReWrite-Media/hoc22-ts-ar
```