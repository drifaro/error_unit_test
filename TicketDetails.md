# Ticket Details

* <b>TicketDetails.test.tsx</b>

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

**console.error**<br>
  *Warning: Can't perform a React state update on an unmounted component. This is a no-op, but it indicates a memory leak in your application. To fix, cancel all subscriptions and asynchronous tasks in a useEffect cleanup function.*
    
~~~javascript
      41 |   const [groupNameRender, setGroupNameRender] = React.useState(value);
      42 |
    > 43 |   setTimeout(() => setGroupNameRender(groupName), 2000);
         |                    ^
      44 |
      45 |   const handleSearchGroup = debounce((inputValue: string) => {
        46 |     setOldGroup(value.name);
~~~
#
* <b>MacroSelectPopover.test.tsx</b>

 O React espera que o atributo esteja em lowercase ou kebab case.
  ~~~javascript
  console.error
  Warning: React does not recognize the `disableUnderline` prop on a DOM element. 
  If you intentionally want it to appear in the DOM as a custom attribute, spell it as lowercase `disableunderline` instead.* 
~~~    
#
* <b>TicketInformation.test.tsx</b>

Existe uma ***div*** entre uma tag ***p***.
  ~~~html
  console.error <br>
  Warning: validateDOMNesting(...): <div> cannot appear as a descendant of <p>.
  ~~~
#

* <b>ComboBoxGroup.test.tsx</b>
~~~javascript
console.error
      MUI: The `getOptionLabel` method of Autocomplete returned object ([object Object]) 
      instead of a string for {}.
~~~