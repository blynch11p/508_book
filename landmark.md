# ARIA Landmark

`ARIA` or ``Accessible Rich Internet Applications`` provides a framework of roles, properties, and guidelines to help develop accessible user interactions.

One small part of ``WAI-ARIA`` called ``landmark regions``. Landmark regions help screen reader users do what others do when they glance at a page, i.e., see its different parts from a bird's-eye view. They also make it easy to move the screen reader's reading cursor to different locations on the page.

There are several types of landmark roles. Some of them are:

```<main> = <div role=”main”>``` - Equivalent to “directing the gaze” of the screen reader user. Should contain only the primary content of the page.

```<nav> = <div role=”navigation”>``` - contains a set of links or elements for navigating the site

```<aside> = <div role=”complementary”>``` - content that supplements the main content

```<div role=”search”>``` - search widget

```<header> = <div role=”banner”>``` - the banner of the page

```<footer> = <div role=”contentinfo”>``` - information about the page such as copyright, help, and information links that appear in the footer