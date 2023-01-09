# Ticket Prioritization

* <b>TicketPriorization.test.tsx</b>

Existe uma ***div*** entre uma tag ***p***.
  ~~~html
  console.error
      Warning: validateDOMNesting(...): <div> cannot appear as a descendant of <p>.
        at div
          at AlertBall (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
          src/components/atoms/AlertBall/AlertBall.tsx:6:29)
        at p
  ~~~

Adicionar um ***keyprop*** a cada filho.
~~~html
    console.error
      Warning: Each child in a list should have a unique "key" prop.
      Check the render method of `ExpiringDays`.
~~~
~~~javascript
      63 |       </Heading>
      64 |
    > 65 |       <ul
         |       ^
      66 |         className={expiringAllGroups.count > 0 ? hoverFixUl : 'none'}
      67 |         style={{ paddingLeft: '8px', width: '477px' }}
      68 |       >
~~~

Existe um ***h5*** entre uma tag ***p***
  ~~~html
  console.error
      Warning: validateDOMNesting(...): <h5> cannot appear as a descendant of <p>.
        at h5
          at Styled.span
          at /home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/node_modules/
          @hexa-ui/components/dist/hexa-ui-components.cjs.dev.js:1498:24
          at div
          at BadgeContainer(/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
          src/components/pages/TicketDetails/components/BadgeContainer/BadgeContainer.tsx:16:3)
          at div
        at p        
  ~~~

  React está reclamando sobre propriedades de estilo não suportadas.
  ~~~javascript
  console.error
      Warning: Unsupported style property &:first-child. Did you mean &:firstChild?
          at div
          at CardRender (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
          src/components/pages/TicketPriorization/components/ByGroups/components/
          CardExpiringIn7Days/CardExpiringIn7Days.tsx:50:46)
  ~~~
  ~~~javascript
  console.error
      Warning: Unsupported style property &:last-child. Did you mean &:lastChild?
          at div
          at CardRender (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
          src/components/pages/TicketPriorization/components/ByGroups/components/
          CardExpiringIn7Days/CardExpiringIn7Days.tsx:50:46)
  ~~~

lastChildObserver não é uma função
~~~html
console.error
  Error: Uncaught [TypeError: lastChildObserver.unobserve is not a function]
~~~
#
* <b>AllGroups.test.tsx</b>

Existe uma ***div*** entre uma tag ***p***.
  ~~~html
  console.error
      Warning: validateDOMNesting(...): <div> cannot appear as a descendant of <p>.
        at div
          at AlertBall (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
          src/components/atoms/AlertBall/AlertBall.tsx:6:29)
        at p
  ~~~
#

* <b>CardGroup.test.tsx</b>

Existe um ***h5*** entre uma tag ***p***
  ~~~html
  console.error
      Warning: validateDOMNesting(...): <h5> cannot appear as a descendant of <p>.
        at h5
          at Styled.span
          at /home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/node_modules/
          @hexa-ui/components/dist/hexa-ui-components.cjs.dev.js:1498:24
          at div
          at BadgeContainer(/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
          src/components/pages/TicketDetails/components/BadgeContainer/BadgeContainer.tsx:16:3)
          at div
        at p        
  ~~~

Existe uma ***div*** entre uma tag ***p***.
  ~~~html
  console.error
      Warning: validateDOMNesting(...): <div> cannot appear as a descendant of <p>.
        at div
          at BadgeContainer (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
          src/components/pages/TicketDetails/components/BadgeContainer/BadgeContainer.tsx:16:3)
          at div
        at p

  ~~~

React está reclamando sobre propriedades de estilo não suportadas.
  ~~~javascript
 console.error
      Warning: Unsupported style property &:first-child. Did you mean &:firstChild?
  ~~~
  ~~~javascript
 console.error
      Warning: Unsupported style property &:last-child. Did you mean &:lastChild?
  ~~~
#

* <b>TicketInformation.test.tsx</b>

Existe uma ***div*** entre uma tag ***p***.
  ~~~html
  console.error
      Warning: validateDOMNesting(...): <div> cannot appear as a descendant of <p>.
        at div
          at AlertBall (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
          src/components/atoms/AlertBall/AlertBall.tsx:6:29)
        at p
  ~~~
#
* <b>ByForms.test.tsx</b>

Existe um ***h5*** entre uma tag ***p***
  ~~~html
  console.error
      Warning: validateDOMNesting(...): <h5> cannot appear as a descendant of <p>.
        at h5
          at Styled.span
          at /home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/node_modules/
          @hexa-ui/components/dist/hexa-ui-components.cjs.dev.js:1498:24
          at div
          at BadgeContainer(/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
          src/components/pages/TicketDetails/components/BadgeContainer/BadgeContainer.tsx:16:3)
          at div
        at p        
  ~~~
Existe uma ***div*** entre uma tag ***p***
  ~~~html
  console.error
      Warning: validateDOMNesting(...): <div> cannot appear as a descendant of <p>.
          at div
          at BadgeContainer (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
          src/components/pages/TicketDetails/components/BadgeContainer/BadgeContainer.tsx:16:3)
          at div
          at p
  ~~~

React está reclamando sobre propriedades de estilo não suportadas.
  ~~~javascript
 console.error
      Warning: Unsupported style property &:first-child. Did you mean &:firstChild?
  ~~~
  ~~~javascript
 console.error
      Warning: Unsupported style property &:last-child. Did you mean &:lastChild?
  ~~~
#
* <b>ByGroups.test.tsx</b>

Existe um ***h5*** entre uma tag ***p***
  ~~~html
  console.error
      Warning: validateDOMNesting(...): <h5> cannot appear as a descendant of <p>.
        at h5
          at Styled.span
          at /home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/node_modules/
          @hexa-ui/components/dist/hexa-ui-components.cjs.dev.js:1498:24
          at div
          at BadgeContainer(/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
          src/components/pages/TicketDetails/components/BadgeContainer/BadgeContainer.tsx:16:3)
          at div
        at p        
  ~~~
Existe uma ***div*** entre uma tag ***p***
  ~~~html
  console.error
      Warning: validateDOMNesting(...): <div> cannot appear as a descendant of <p>.
          at div
          at BadgeContainer (/home/drislainefaro/Work/admin-portal-beescare-l2-tickets-mfe/
          src/components/pages/TicketDetails/components/BadgeContainer/BadgeContainer.tsx:16:3)
          at div
          at p
  ~~~

React está reclamando sobre propriedades de estilo não suportadas.
  ~~~javascript
 console.error
      Warning: Unsupported style property &:first-child. Did you mean &:firstChild?
  ~~~
  ~~~javascript
 console.error
      Warning: Unsupported style property &:last-child. Did you mean &:lastChild?
  ~~~
