# Ticket List

* <b>TicketList.test.tsx</b>

**console.error** (esse erro se repete várias vezes)</br>
      *Warning: An update to TicketList inside a test was not wrapped in act(...).*      
      *When testing, code that causes React state updates should be wrapped into act(...):*
      
      act(() => {
        /* fire events that update state */
      });
      /* assert on the output */

~~~javascript
      71 |
      72 |   setTimeout(() => { // TODO: rever se setTimeout é executado a cada render
    > 73 |     setIsBackgroundJobRunning(true);
         |     ^
      74 |   }, TICKET_UPDATES_REFRESH_IN_MILLISECONDS);
      75 |
      76 |   const { currentUser, locale } = useAuthContext();

~~~
**console.error** </br>
      *Warning: Can't perform a React state update on an unmounted component. This is a no-op, but it indicates a memory leak in your application. To fix, cancel all subscriptions and asynchronous tasks in a useEffect cleanup function.*
~~~javascript
      71 |
      72 |   setTimeout(() => { // TODO: rever se setTimeout é executado a cada render
    > 73 |     setIsBackgroundJobRunning(true);
         |     ^
      74 |   }, TICKET_UPDATES_REFRESH_IN_MILLISECONDS);
      75 |
      76 |   const { currentUser, locale } = useAuthContext();
~~~
#

* <b>FilterPopover.test.tsx</b>

Existe mais de um elemento filho com a mesma **key**. *(esse erro se repete várias vezes)*
~~~javascript
console.error
      Warning: Encountered two children with the same key, `RADIO`. Keys should be 
      unique so that components maintain their identity across updates. Non-unique 
      keys may cause children to be duplicated and/or omitted — the behavior is 
      unsupported and could change in a future version.
~~~

#

* <b>TicketSelectableRow.test.tsx</b>

~~~javascript
console.error
      Warning: Can't perform a React state update on an unmounted component. 
      This is a no-op, but it indicates a memory leak in your application. 
      To fix, cancel all subscriptions and asynchronous tasks in a useEffect 
      cleanup function.
        at ModalBulkResolution 
        (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/src/components/
        molecules/ModalBulkResolution/ModalBulkResolution.tsx:51:64)
~~~

**console.error** </br>
      *Warning:</br> Can't perform a React state update on an unmounted component. This is a no-op, but it indicates a memory leak in your application. To fix, cancel all subscriptions and asynchronous tasks in a useEffect cleanup function.</br>
      **at PreviewTicketComments (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/src/components/pages/TicketList/components/PreviewTicketComments/PreviewTicketComments.tsx:19:80)***

~~~javascript
      44 |      processedResponse.sort((a, b) => a.createdAt.
                  localeCompare(b.createdAt)).reverse();
      45 |     }
    > 46 |     setCommentSize(processedResponse.length);
         |     ^
      47 |     const processedComments = [];
      48 |
      49 |     for (let i = 0; i < 3; i += 1) {
~~~

