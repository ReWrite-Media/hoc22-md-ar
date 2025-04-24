### @flyoutOnly true
### @hideIteration true
### @explicitHints true


# الحوض

## الخطوة الأولى
آه لا! يبدو أن الماء لا يصل إلى الحديقة. قم بسد جميع الثقوب حتى يتمكن الماء من التدفق بشكل صحيح.

الكود يحتوي على أخطاء، هل يمكنك إصلاحه؟ قم بتصحيح الكود عن طريق تشغيله لمعرفة كيف يعمل، ثم عدل عليه ليصبح الحل صحيحا.

#### ~ tutorialhint 
قم بتحريك المؤشر باستخدام البلوك ``||hoc22:تحريك المؤشر (الاتجاه)||`` ، ثم استخدم ``||hoc22:وضع كتلة||`` لوضع البلوك في ذلك الموضع. املأ الفتحات الستة الموجودة فوق الخرسانة السوداء للمتابعة.


```ghost
    hoc22.cursorMoveOrientationOneUp(1)
    hoc22.cursorMoveOrientationOneDown(1)
    hoc22.cursorMoveOrientationOneLeft(1)
    hoc22.cursorMoveOrientationOneRight(1)
    hoc22.placeBlock()
    for (let index = 0; index < 2; index++) {    }
```
```template
    hoc22.cursorMoveOrientationOneUp(1) 
    hoc22.placeBlock()   
    hoc22.cursorMoveOrientationOneUp(1) 
    hoc22.placeBlock()        
    hoc22.cursorMoveOrientationOneRight(2)   
    hoc22.cursorMoveOrientationOneUp(1) 
    hoc22.placeBlock()       
```
```package
hoc22-ts-ar=github:ReWrite-Media/hoc22-ts-ar
```