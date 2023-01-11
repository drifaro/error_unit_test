# Ticket History

* <b>TicketHistory.test.tsx</b>

 **console.error**<br>
 *Warning: </br>Can't perform a React state update on an unmounted component. This is a no-op, but it indicates a memory leak in your application. To fix, cancel all subscriptions and asynchronous tasks in a useEffect cleanup function.*
    
~~~javascript
        67 |       onSuccess: (successData) => {
        68 |         if (successData?.account) {
      > 69 |           setPoc(successData.account);
           |           ^
        70 |         } else {
        71 |           setPoc({});
        72 |         }
~~~

 **console.error**<br>
 *Warning: </br>Can't perform a React state update on an unmounted component. This is a no-op, but it indicates a memory leak in your application. To fix, cancel all subscriptions and asynchronous tasks in a useEffect cleanup function.*
    
~~~javascript
      44 |     processedResponse.sort((a, b) => a.createdAt.localeCompare(b.createdAt)).
                reverse();
      45 |     }
    > 46 |     setCommentSize(processedResponse.length);
         |     ^
      47 |     const processedComments = [];
      48 |
      49 |     for (let i = 0; i < 3; i += 1) {
~~~

**lastChildObserver** não é uma função
~~~javascript
console.error
  Error: Uncaught [TypeError: lastChildObserver.unobserve is not a function]
    at reportException (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
    node_modules/jest-environment-jsdom/node_modules/jsdom/lib/jsdom/living/helpers/
    runtime-script-errors.js:66:24)
~~~