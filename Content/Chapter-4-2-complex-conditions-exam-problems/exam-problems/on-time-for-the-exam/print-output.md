#### Отпечатване на резултата

Накрая остава да изведем резултата на конзолата. По задание, ако студентът е дошъл точно на време (**без нито една минута разлика**), не трябва да изваждаме втори резултат. Затова правим следната **проверка**:

![](/assets/chapter-4-2-images/01.On-time-for-the-exam-08.png)

Реално за целите на задачата извеждането на резултата **на конзолата** може да бъде направен и в по-ранен етап - още при самите изчисления. Това като цяло не е много добра практика. **Защо?**

Нека разгледаме идеята, че кодът ни не е 10 реда, а 100 или 1000! Някой ден ще се наложи извеждането на резултата да не бъде в конзолата, а да бъде записан във **файл** или показан на **уеб приложение**. Тогава на колко места в кода ще трябва да бъдат нанесени корекции поради тази смяна? И дали няма да пропуснем някое място?

<table><tr><td><img src="/assets/alert-icon.png" style="max-width:50px" /></td>
<td>Винаги си мислете за кода с логическите изчисления, като за отделна част от, различна от обработката на входните и изходните данни. Той трябва да може да работи без значение как му се подават данните и къде ще трябва да бъде показан резултатът.</td></tr></table>

### Тестване в Judge системата

Тествайте решението си тук:  [https://judge.softuni.org/Contests/Practice/Index/509#0](https://judge.softuni.org/Contests/Practice/Index/509#0).