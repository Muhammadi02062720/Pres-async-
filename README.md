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

> #### TRY / CATCH

![](/Screenshot_8.png)

> #### Async await
![](/Screenshot_9.png)
> ### Request
 > Функция запроса JavaScript используется для обмена данными с ресурсами на стороне сервера. Функция запроса отправляет и получает данные с сервера путем выполнения HTTP-запросов. Эти запросы выполняются вместе с функцией выборки для получения ответа. Эти термины "Запрос", "выборка" и "Ответ" являются заменой "XMLHttpRequest’. В Интернете, который состоит из множества серверов, представляющих собой взаимосвязанные компьютеры, просмотр веб-рекламы и навигация по страницам аналогичны тому, как вы запрашиваете у браузера отправку вам информации с серверов. В этой статье мы рассмотрим несколько способов отправки функций запроса JavaScript.
> ### «Application Programming Interface»

 > Интерфейс прикладного программирования (API) является одним из наиболее важных компонентов разработки приложений и программных систем. API в первую очередь используется для упрощения разработки программного обеспечения и обеспечения обмена данными между приложениями посредством бесшовной интеграции. Его основные функциональные возможности включают организацию кода, скрытие сложности от разработчиков, обеспечение возможности повторного использования компонентов и расширение систем для разработки.
 ![](/Screenshot_10.png)
> #### Get
 ![](/Screenshot_11.png)

> #### Post
 ![](/Screenshot_12.png)

> #### Put
 ![](/Screenshot_13.png)

> #### Delete
 ![](/Screenshot_14.png)

> ## axios
 >Axios - это HTTP-клиент, основанный на Promise для node.js и
браузера. Он может работать в браузере и node.js с той же базой кодов.

 > #### Get
  ![](/Screenshot_15.png)

 > #### Delete
  ![](/Screenshot_16.png)