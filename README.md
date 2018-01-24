# Функции

Что такое функция? 

Это фрагмент программного кода (подпрограмма), к которому можно обратиться из другого места программы. Функция ассоциируется с повторным использованием кода: если несколько строчек программы повторяются более одного раза, есть смысл рассмотреть возможность выделения их в функцию. Но это ещё и параметризованный код, т.е. в нём «выделены» места или «гнёзда», в которые можно подставлять разные значения. Т.е. функция может принимать параметры и должна возвращать некоторое значение, возможно пустое. В JavaScript, если в теле функции не обозначено явно то, что она должна вернуть, считается, что она возвращает значение undefined.

Функции в JavaScript являются объектами. Т.е. это данные ссылочного типа.

JavaScript поддерживает функциональное программирование, так как его функции относятся к **объектам первого класса**. Это значит следующее: функции могут делать то же самое, что и переменные. 

Рассматривая функции как объекты первого класса, мы говорим о функциях высшего порядка (high order functions): они способны манипулировать другими функциями и могут получать функции в качестве аргументов, или возвращать функции, или делать и то и другое.
