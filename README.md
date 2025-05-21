## Check your understanding

1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why. <br>

    Answer: **Within a Github action that runs whenever code is pushed** because it runs test automatically every time you update the code, helping you catch problems early and keep the project.
   
2. Would you use an end to end test to check if a function is returning the correct output? 
   <br>

   Answer: **No** because end to end tests check the whole app working together, not individual functions. Use unit tests instead to check a functions output.

3. What is the difference between navigation and snapshot mode?
   <br>

   Answer: Navigation mode analyzes a webpage immediaely after it fully loads which provides an overall performance score but it does not capture user interactions or dynamic changes. However, snapshot mode captures the current state of the page at a specific moment.
   
4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
   <br>

   Answer:

   * Using WebP files for images instead. Image formats like WebP and AVIF often provide better compression than PNG or JPEG, which means faster downloads and less data consumption. 
   * Add a <meta name="viewport">` tag with width or initial-scale to ensure that the site scales properly on different screen sizes
   * If the LCP element is dynamically added to the page, you should preload the image in order to improve LCP.






