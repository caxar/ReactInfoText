# Вопросы и ответы по React 


## 1) Что такое "Promise"

- Промис (Promise) — специальный объект JavaScript, который используется для написания и обработки асинхронного кода.
- Асинхронные функции возвращают объект Promise в качестве значения. Внутри промиса хранится результат вычисления, которое может быть уже выполнено или выполнится в будущем.
Промис может находиться в одном из трёх состояний:

   - pending — стартовое состояние, операция стартовала; 
   - fulfilled — получен результат; 
   - rejected — ошибка. 

- У промиса есть методы then(), catch(), finnaly() которые позволяют использовать результат работы промиса.
