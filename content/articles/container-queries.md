---
title: Container Query State of Mind
date: 2021-06-21
hero: https://www.cargocreative.co.uk/wp-content/uploads/2022/06/img-blog-container-banner.jpg
heroCaption: © Cargo Creative via "The Freedom of Container Queries"
heroCaptionLink: https://www.cargocreative.co.uk/updates/website-development-agency/the-freedom-of-container-queries/
excerpt: User Interface layout the way it should be
authors:
  - Eric Thayer
---

Front-end development has come a long way in recent years. With responsive design and mobile-first approaches, developers have been able to design and develop websites that work well on all devices. However, as the number of device sizes and resolutions continues to grow, responsive design alone may not be enough. This is where container queries come in.

So, what exactly are container queries? Container queries allow developers to apply CSS styles based on the size of a container, rather than the size of the viewport. This makes it possible to create designs that respond to the content within them, rather than just the size of the screen. With container queries, developers can create styles that are specific to a certain element, which can make it easier to maintain and update code.

{{< codepen dyjPNvB>}}

Traditionally, responsive design relied on media queries that applied to the entire page. This meant that developers had to create styles that worked well across all screen sizes, which could lead to bloated CSS files. With container queries, developers can create styles that only apply to certain elements, which can result in more modular and reusable code. This can lead to faster load times and a better user experience.

Container queries work by allowing developers to define a set of CSS styles that will be applied when a container reaches a certain size. This is done using a new type of CSS rule called the `@container` rule. We can define a container using the `contain` property, and then apply styles using the `@container` rule. For example, we could define a container with a max-width of 600px and apply styles that only take effect when the container is less than 400px wide.

One of the key benefits of using container queries is that they make it possible to create more specific and targeted styles. Instead of having to rely on media queries that apply to the entire page, we can create styles that are specific to a certain element. This can make it easier to maintain and update code, as well as create more complex designs that respond well to different screen sizes.

In conclusion, container queries are a powerful new feature in front-end development that allow us to create more flexible and modular designs. By applying styles based on the size of a container, rather than the viewport, we can create more specific and targeted styles that make our code easier to maintain and update. As container queries continue to gain popularity, we can expect to see more and more developers using them in their projects.

## The Advantages of Container Queries over Media Queries

Container queries are a relatively new concept in web development, but they have already been proven to offer several advantages over traditional media queries. Here are a few of the ways that container queries can be superior:

### More Specific Targeting

Media queries are applied to the entire viewport, meaning that even if you only want to target a specific element, you have to apply the same styles to the entire page. With container queries, you can target specific elements by applying styles based on their container size. This means you can create more targeted and specific designs that are easier to maintain.

### Better Reusability

Because media queries apply to the entire viewport, they are often duplicated across multiple stylesheets, making it difficult to reuse them. Container queries, on the other hand, are specific to a certain element, meaning that they can be easily reused across different stylesheets.

### Improved Performance

Media queries can lead to bloated CSS files, as developers often have to create styles that work across all screen sizes. With container queries, you can create styles that only apply to specific elements, leading to more modular and reusable code. This can result in faster load times and a better user experience for your users.

## How to Use Container Queries in Your Projects

Now that you understand the benefits of container queries, you may be wondering how to use them in your own projects. Here are a few steps you can follow to get started:

### 1. Define Your Containers

To use container queries, you need to define your containers using the `contain` property. This property defines the container for your element, and the size of the container will determine which styles are applied. For example, you could define a container with a max-width of 600px and apply styles that only take effect when the container is less than 400px wide.

### 2. Use the `@container` Rule

Once you have defined your containers, you can start applying styles using the `@container` rule. This rule allows you to apply styles based on the size of your container, rather than the viewport. For example, you could use the `@container` rule to apply a different font size or background color to an element when it is inside a specific container.

### 3. Test Your Code

As with any new technology, it is important to test your code thoroughly to ensure that it works as expected. Use different devices and screen sizes to test your container queries and make sure that they are working correctly.

## Conclusion

Container queries are a powerful new feature in front-end development that allow us to create more flexible and modular designs. By applying styles based on the size of a container, rather than the viewport, we can create more specific and targeted styles that make our code easier to maintain and update. As container queries continue to gain popularity, we can expect to see more and more developers using them in their projects. With the benefits of more specific targeting, better reusability, and improved performance, container queries are a valuable addition to any front-end developer's toolkit.
