# Bug List

> Make a list of the things that don't work as expected. Keep a list of things that you have fixed and try to document how you solved them.

1. Problem: Images not showing need to change them from a local file. Problem ongoing.
2. Problem: "plan-your-trip" page did not work. Solved by adding .html
3. Problem: When I click a link the hyperlinks do not show when they have been visited. Problem could not be solved so visited was removed
4. Problem: Fix the layout box as there is too much space. Problem ongoing
5. Problem: Line length on the index page to make it easier to read. Problem solved
6. Validation for index page:  The frameborder attribute on the iframe element is obsolete. Use CSS instead.

From line 186, column 17; to line 192, column 61

          <iframe ↩                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d19801.78607739016!2d-…2C%20Bethnal%20Green%2C%20London%20E2%209LY%2C%20UK!5e0!3m2!1sen!2suk!4v1716137023062!5m2!1sen!2suk"↩                    width="100"↩                    height="300"↩                    frameborder="0"↩                    style="border:0;"↩                    title="Approach Road, Bethnal Green Map">↩    
Probem solved by Adding <meta charset="UTF-8"> to <head>
Changed width="100" to width="100%"
Confirmed proper closing of the <iframe> element
Adjusted the map container to ensure it appears square and centered
All pages now validated 
