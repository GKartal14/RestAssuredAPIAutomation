Web UI Test Automation using Selenium WebDriver and Java

In this project, I created just one test case under main method. I created a Maven project and dowloaded the necessary dependencies which are Selenium WebDriver and WebDriver Manager.

In my test, I used only the Google Chrome browser. Amazon webpage gets opened and in each time, wanted me to pass the CAPTCHA. I added 10 second sleep, within this duration, one should pass the CAPTCHA manually by hand. 

After that, the mainpage of the website gets opened. I entered my keyword to the search bar and the laptops are listed. I was only supposed to choose items from the first page so I added the items who are in-stock and non-discounted. At first, I sought a filter to refine my test but since the tightness of time, I only added the in-stock items not discounted, I determined them manually. One by one, by scrolling down, I added the chosen items to the cart. Finally, I scrolled up, displayed the cart icon and click on the cart. Within the cart, the chosen items get displayed.

The test cases are under src/test/java path, you can find the Maven project which are created for this test.

Tech stack: Eclipse IDE, Java, Selenium WebDriver, Maven, Git.

Gulsah Kartal
Test Engineer



