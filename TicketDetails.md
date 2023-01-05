# Ticket Details
	
* O React espera que o atributo esteja em lowercase ou kebab case.
  
  **console.error**<br>
  *Warning: React does not recognize the `disableUnderline` prop on a DOM element. 
  If you intentionally want it to appear in the DOM as a custom attribute, spell it as lowercase `disableunderline` instead.* 
    
#

* Existe uma <'div> entre uma tag <'p>.
  ~~~html
  console.error <br>
  Warning: validateDOMNesting(...): <div> cannot appear as a descendant of <p>.
  ~~~

#
 **console.error**<br>
 *Warning: Can't perform a React state update on an unmounted component. This is a no-op, but it indicates a memory leak in your application. To fix, cancel all subscriptions and asynchronous tasks in a useEffect cleanup function.*
    
~~~javascript
  processedComments.sort((a, b) => a.createdAt.localeCompare(b.createdAt));
    > 394 |     setComments(processedComments);
          |     ^
      395 |     scrollCommentsToBottom();
      396 |   };
~~~
#

console.error<br>
  Warning: Can't perform a React state update on an unmounted component. This is a no-op, but it indicates a memory leak in your application. To fix, cancel all subscriptions and asynchronous tasks in a useEffect cleanup function.
    
~~~javascript
      41 |   const [groupNameRender, setGroupNameRender] = React.useState(value);
      42 |
    > 43 |   setTimeout(() => setGroupNameRender(groupName), 2000);
         |                    ^
      44 |
      45 |   const handleSearchGroup = debounce((inputValue: string) => {
      46 |     setOldGroup(value.name);
~~~