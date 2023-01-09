# Molecules

* <b>CommentPreview.test.tsx</b>

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
            at Box (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
            node_modules/@mui/system/createBox.js:41:41)
          at p
            at Styled.span
            at /home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/node_modules/
            @hexa-ui/components/dist/hexa-ui-components.cjs.dev.js:1625:24
          at div
~~~
#

* <b>ModalBulkResolution.test.tsx</b>

***console.error***</br>
      *Warning: Can't perform a React state update on an unmounted component. This is a no-op, but it indicates a memory leak in your application. To fix, cancel all subscriptions and asynchronous tasks in a useEffect cleanup function.*

~~~javascript
      68 |     {
      69 |       onSuccess: async (successData) => {
    > 70 |         setDynamicFormsInfo(cloneDeep(successData?.ticket));
         |         ^
      71 |         handleShowDynamicForms(successData?.ticket);
      72 |       },
      73 |       refetchOnWindowFocus: false,
~~~

