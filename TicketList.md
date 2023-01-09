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
      69 |
      70 |   setTimeout(() => {
    > 71 |     setIsBackgroundJobRunning(true);
         |     ^
      72 |   }, TICKET_UPDATES_REFRESH_IN_MILLISECONDS)
      73 |
      74 |   const { currentUser, locale } = useAuthContext();
~~~
**console.error** </br>
      *Warning: Can't perform a React state update on an unmounted component. This is a no-op, but it indicates a memory leak in your application. To fix, cancel all subscriptions and asynchronous tasks in a useEffect cleanup function.*
~~~javascript
      69 |
      70 |   setTimeout(() => {
    > 71 |     setIsBackgroundJobRunning(true);
         |     ^
      72 |   }, TICKET_UPDATES_REFRESH_IN_MILLISECONDS)
      73 |
      74 |   const { currentUser, locale } = useAuthContext();
~~~

#
* <b>PicklistRadio.test.tsx</b>

Existe mais de um elemento filho com a mesma **key**. *(esse erro se repete várias vezes)*
~~~javascript
console.error
      Warning: Encountered two children with the same key, `PICKLIST_RADIO`. 
      Keys should be unique so that components maintain their identity across 
      updates. Non-unique keys may cause children to be duplicated and/or 
      omitted — the behavior is unsupported and could change in a future version.
~~~

#
* <b>TIcketTableSolved.test.tsx</b>

Existe um ***p*** entre uma tag ***p***.
~~~html
console.error
      Warning: validateDOMNesting(...): <p> cannot appear as a descendant of <p>.
          at p
            at Styled.span
            at /home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/node_modules
            /@hexa-ui/components/dist/hexa-ui-components.cjs.dev.js:1625:24
            at div
            at /home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/node_modules/
            @emotion/react/dist/emotion-element-ae8cc4ba.cjs.dev.js:63:23
            at Box (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
            node_modules/@mui/system/createBox.js:41:41)
          at p
~~~
Existe um ***div*** entre uma tag ***p***.
~~~html
 console.error
      Warning: validateDOMNesting(...): <div> cannot appear as a descendant of <p>.
          at div
            at /home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/node_modules/
            @emotion/react/dist/emotion-element-ae8cc4ba.cjs.dev.js:63:23
            at Box (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/n
            ode_modules/@mui/system/createBox.js:41:41)
          at p
~~~
#
* <b>TicketTableUnsolved.test.tsx</b>

Existe um ***p*** entre uma tag ***p***.
~~~html
console.error
      Warning: validateDOMNesting(...): <p> cannot appear as a descendant of <p>.
          at p
            at Styled.span
            at /home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/node_modules/
            @hexa-ui/components/dist/hexa-ui-components.cjs.dev.js:1625:24
            at div
            at /home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/node_modules/
            @emotion/react/dist/emotion-element-ae8cc4ba.cjs.dev.js:63:23
            at Box (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
            node_modules/@mui/system/createBox.js:41:41)
          at p
~~~

Existe um ***div*** entre uma tag ***p***.
~~~html
 console.error
      Warning: validateDOMNesting(...): <div> cannot appear as a descendant of <p>.
          at div
            at /home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/node_modules/
            @emotion/react/dist/emotion-element-ae8cc4ba.cjs.dev.js:63:23
            at Box (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
            node_modules/@mui/system/createBox.js:41:41)
          at p
~~~
#
* <b>TIcketTableList.test.tsx</b>

Existe um ***p*** entre uma tag ***p***.
~~~html
console.error
      Warning: validateDOMNesting(...): <p> cannot appear as a descendant of <p>.
          at p
            at Styled.span
            at /home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/node_modules/
            @hexa-ui/components/dist/hexa-ui-components.cjs.dev.js:1625:24
            at div
            at /home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/node_modules/
            @emotion/react/dist/emotion-element-ae8cc4ba.cjs.dev.js:63:23
            at Box (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
            node_modules/@mui/system/createBox.js:41:41)
          at p
~~~

Existe um ***div*** entre uma tag ***p***.
~~~html
 console.error
      Warning: validateDOMNesting(...): <div> cannot appear as a descendant of <p>.
          at div
            at /home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/node_modules/
            @emotion/react/dist/emotion-element-ae8cc4ba.cjs.dev.js:63:23
            at Box (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
            node_modules/@mui/system/createBox.js:41:41)
          at p
~~~
#

* <b>FilterPopover.test.tsx</b>

React espera que o data-testid esteja em lowecase.

~~~javascript
console.error
      Warning: React does not recognize the `data-testId` prop on a DOM element. 
      If you intentionally want it to appear in the DOM as a custom attribute, spell 
      it as lowercase `data-testid` instead. If you accidentally passed it from a 
      parent component, remove it from the DOM element.
~~~

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

Existe um ***p*** entre uma tag ***p***.
~~~html
console.error
      Warning: validateDOMNesting(...): <p> cannot appear as a descendant of <p>.
          at p
            at Styled.span
            at /home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/node_modules/
            @hexa-ui/components/dist/hexa-ui-components.cjs.dev.js:1625:24
            at div
            at /home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/node_modules/
            @emotion/react/dist/emotion-element-ae8cc4ba.cjs.dev.js:63:23
            at Box (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
            node_modules/@mui/system/createBox.js:41:41)
          at p
~~~

Existe um ***div*** entre uma tag ***p***.
~~~html
 console.error
      Warning: validateDOMNesting(...): <div> cannot appear as a descendant of <p>.
          at div
            at /home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/node_modules/
            @emotion/react/dist/emotion-element-ae8cc4ba.cjs.dev.js:63:23
            at Box (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
            node_modules/@mui/system/createBox.js:41:41)
          at p
~~~

**console.error** </br>
      *Warning: Can't perform a React state update on an unmounted component. This is a no-op, but it indicates a memory leak in your application. To fix, cancel all subscriptions and asynchronous tasks in a useEffect cleanup function.*
~~~javascript
      44 |      processedResponse.sort((a, b) => a.createdAt.localeCompare(b.createdAt)).reverse();
      45 |     }
    > 46 |     setCommentSize(processedResponse.length);
         |     ^
      47 |     const processedComments = [];
      48 |
      49 |     for (let i = 0; i < 3; i += 1) {
~~~

