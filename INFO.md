Mobile-first responsive design -:-
It is an approach to web design and development that prioritizes the design and functionality of a website for mobile devices first and then scales up to larger screens, such as tablets, laptops, and desktop computers.

Advantages and Disadvantages -:-
Advantages:
1. Delevopment Hierarchy:
In this you start with the mobile view which is the simplest and critical for user journeys
2. Tried and Tested:
It and tried and tested methodology that has been tried and tested which has work for many year, it help solve desing problems.
3. Prioritise Mobile View:
considering that mobile users contribute largely website visitors thus considering the mobile view is advantageouse.
4. Prevents desktop Centric development
By starting with mobile it prevents the common mistake of initially focusing on the desktop view which can lead to difficulties later on.

Disadvanteges:
1. More comlexity
as you add break points you end up with unnecessary code from lower break points leading to increased complexity.
2. Higher CSS specificity
overriding Styles at higher break points increases CSS specificity making selectors more complex
3. Requires more testing
any changes made at lower View's necessitate regression testing for all higher break points
4. CSS download prioritization
mobile fist CSS doesn't leverage the browser's ability to prioritize CSS downloads at wider breakpoints


CSS rule or rules that help us create mobile first websites.
1. Viewport Meta Tag: 
While not a CSS rule, it's important to include the viewport meta tag in your HTML to ensure proper scaling and rendering on mobile devices.
<meta name="viewport" content="width=device-width, initial-scale=1">

2. Media Queries: Media queries are a key CSS feature for creating responsive designs. They allow you to apply different styles based on the screen size or other characteristics of the user's device.

@media screen and (max-width: 768px) {
/* This allow you to apply styles only when the screen size is a max-width of 768px*/
}

@media screen and (min-width: 769px) {
/* This allow you to apply styles only when the screen size is a max-width of 768px*/
}
3. Flexible Grids: Use CSS grid or flexbox layouts to create fluid, responsive layouts that adapt to different screen sizes. For example, you can create a two-column layout that collapses into a single column on smaller screens
4. Fluid Typography: Use relative units like percentages or "em" for font sizes to allow text to scale with the screen size. This ensures that text remains readable on both small and large screens.

References:
YouTube: Webwise| The Death of Mobile First CSS: What You Must Know! | https://www.youtube.com/watch?v=opSo9vlh5mA

