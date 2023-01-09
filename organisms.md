# Organisms

* <b>SearchBar.test.tsx</b>

**console.error**</br>
    *Warning: An update to ForwardRef inside a test was not wrapped in act(...).*    
    *When testing, code that causes React state updates should be wrapped into act(...):*
    
    act(() => {
      /* fire events that update state */
    });
    /* assert on the output */

~~~javascript
      20 |
      21 |   const handleErrorSearch = () => {
        > 22 |     openToastRef?.current?.publish();
         |                            ^
      23 |     setOpenToast(true);
      24 |   };
      25 |
~~~
~~~javascript
      21 |   const handleErrorSearch = () => {
      22 |     openToastRef?.current?.publish();
    > 23 |     setOpenToast(true);
         |     ^
      24 |   };
      25 |
      26 |   const handleChangeInput = 
              async (e: React.FormEvent<HTMLInputElement>) => {
~~~

**console.error**</br>
    *Warning: Can't perform a React state update on an unmounted component. This is a no-op, but it indicates a memory leak in your application. To fix, cancel all subscriptions and asynchronous tasks in a useEffect cleanup function.*

~~~javascript
      67 |       if (data?.account?.taxId) {
      68 |         navigate(`/beescare/l2-tickets/ticket-history?searchKey=$
                    {data?.account?.taxId}`);
    > 69 |         setTicketId('');
         |         ^
      70 |       } else {
      71 |         handleErrorSearch();
      72 |       }
~~~ 