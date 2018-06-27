@title[Introduction]
## Asynchronous programming on javascript and python.

---
@title[Futures and promises]
## Futures and promises

Futures and promises originated in functional programming and related paradigms (such as logic programming) to decouple a value (a future) from how it was computed (a promise).

@size[0.5em](https://en.wikipedia.org/wiki/Futures_and_promises)

---
@title[Code stub]

```javascript
class promise<T> {
    get_future(): future<T>;
    set_value(T);
    set_exception(T);
};
class future<T> {
    get(): T;
    valid(): state;
}
```

![Sequence](images/future_and_promise.mmd.png)

---
@title[Promise]

---
@title[Callback]

---
@title[Callback hell]

---
@title[Continuation passing style]

~~Monad~~

---
@title[In python]

---
@title[Please make me sync style]

---
@title[async/await]

---
@title[Coroutine]


---
@title[Generator]

---
@title[Statemachine]

---
@title[Request & completion]

---
@title[Task]

---
@title[Task scheduler]

---
@title[Javascript eventloop]

---
@title[Python aiocore]

---
@title[Performance?]

---
@title[Concurrency issue]
