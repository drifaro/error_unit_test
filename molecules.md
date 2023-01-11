# Molecules

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

