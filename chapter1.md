# First Chapter

###ARIA

W3C has also created a development language supplement called Web Accessibility Initiative (WAI) Accessible Rich Internet Applications (ARIA) Suite. It helps to identify and describe elements and how they relate to each other. This is a framework for adding attributes to complex applications that would otherwise be inaccessible because the native development language doesn't have certain capabilities. This enables technologies that have been inaccessible in the past to communicate more effectively with screen readers and other assistive technology devices. However, you don't need to double up. For example, if you are using an ```<h1>``` tag, there is **no** need to use ARIA to define the object's role as "heading". ARIA is only a supplement to help if a development language can't support identifying or describing elements in the application.



###OZONE-specific Guidelines for 508 Compliance

1. OZONE makes use of rendering technology designed to allow users to mashup web applications together in a common view. As a result, we can only supply 508 compliance to the iframe boundary, and not beyond.

2. The webtop renderer should consist of ARIA/metatags designed to allow screen readers to read which applications are open.

3. Keyboard navigation should exist for every function within the system, regardless of what it is. Being able to navigate between windows or applications, configuration, and stateful actions should have a defining keystroke matching with common standards (see GSA guidelines for software).

4. All images being presented to the browser, via direct HTML ```<img>``` tags or CSS, must present descriptive text.

5. All buttons and form elements must be presented with common descriptive text and labels.
