> ## SYNCHRONOUS
 >Синхронный JavaScript: Как следует из названия, синхронный означает быть в последовательности, т.е. каждый оператор кода выполняется один за другим. Итак, по сути, оператор должен ждать выполнения предыдущего оператора.
Давайте разберемся в этом с помощью примера.

![](Screenshot_1.png)

![](Screenshot_2.png)

> ### ASYNCHRONOUS
 >Асинхронный JavaScript: Асинхронный код позволяет программе выполняться немедленно, где синхронный код блокирует дальнейшее выполнение оставшегося кода до тех пор, пока он не завершит текущий. Это может показаться не такой уж большой проблемой, но когда вы видите это в более широком плане, вы понимаете, что это может привести к задержке работы пользовательского интерфейса.

Давайте посмотрим на примере, как выполняется асинхронный JavaScript.

![](/Screenshot_3.png)

![](/Screenshot_4.png)
 
> ### ASYNCHRONOUS

![](/Screenshot_5.png)

> 1. Callbacks are functions that are passed as arguments to other functions and are executed when the called
function completes its task. Callbacks can be used to handle asynchronous operations by passing a callback
function to an asynchronous method, which then calls the callback function when the operation is complete

![](/Screenshot_6.png)

> ### New PROMIsE IN JAVASCRIPT

 >In JavaScript, a promise is a good way to handle asynchronous operations. It is used to 
find out if the asynchronous operation is successfully completed or not.

 >  A promise may have one of three states
* Pending
* Fulfilled
* Rejected

1. Promaise
 ![](/Screenshot_7.png)
