# Криштопа Михаил

## **Контакты:**

- **e-mail:** m.a.krishtopa@yandex.ru
- [LinkedIn](https://www.linkedin.com/in/%D0%BC%D0%B8%D1%85%D0%B0%D0%B8%D0%BB-%D0%BA%D1%80%D0%B8%D1%88%D1%82%D0%BE%D0%BF%D0%B0-306536261/)

* **Telegram:** @Mikhail_Krishtopa

## **Знание языков:**

- Русский - родной
- Английский - А2

## **Навыки**

- JavaScript
- HTML
- CSS
- BEM nested

Имею высшее инженерно-техническое образовние (МГТУ им Н.Э.Баумана). Более 8 лет работаю на фондовым рынке в лице управляющего активами. Огромный опыт общения с людьми. Решил погрузиться в мир IT!

## **Пример кода:**

The span function is a good one to know. It accepts a sequence and a predicate function and returns two sequences. The first sequence contains all the elements of the argument sequence up to the item that caused the first failure of the predicate. The second returned sequence contains the rest of the original sequence. The original sequence is not modified.

```javascript
function span(arr, predicate) {
  var i = 0;
  while (i < arr.length && predicate(arr[i])) {
    i++;
  }
  return [arr.slice(0, i), arr.slice(i)];
}
```
