# Lesson_13-Callback-function

### Callback-function — это функция, которая должна быть выполнена после того, как другая функция завершила свое выполнение.

> function learnJS(lang, callback) {
> <br> &nbsp;&nbsp;&nbsp;&nbsp; console.log("Я учу " + lang);
> <br> &nbsp;&nbsp;&nbsp;&nbsp; callback();
> <br> }
> <br> 
> <br> function done() {
> <br> &nbsp;&nbsp;&nbsp;&nbsp; console.log("Я прошел 3й урок!");
> <br> }
> <br> 
> <br> learnJS("JavaSript", done);

### Использую _callback-функции_ мы можем быть уверены, что код НЕ начнет выполнятся раньше времени!
