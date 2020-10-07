As I mentioned in "README.md", during the time working as a PLM System Engineer of ASECL, I designed several customized functions 
by using JAVA programming language.

I was not allowed to take away any code that I wrote within the company, so I will share some of the screenshots that I took in my 
personal handbook.

## Navigation Icon

This customized function shows how to add a "Navigation Icon" to the "Browse Panel".

* Step 1: Create a new navigator in "action.xml".

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Navigation%20Icon/Step1.png)

* Step 2: Create a new navigator in "actionModels.xml".

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Navigation%20Icon/Step2.png)

* Step 3: Find an image for the new icon.

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Navigation%20Icon/Step3.png)

* Step 4: Modify several ".properties" files under the Windchill installation folder.

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Navigation%20Icon/Step4.png)

* Step 5: Restart Windchill System.

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Navigation%20Icon/Step5.png)

* Step 6: Result.

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Navigation%20Icon/Step6.png)


## MVC Table

This customized function shows how to add an "MVC Table" to the webpage.

* Step 1: Add an MVC builder path.

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/MVC%20Table/Step1.png)

* Step 2:  Create a custom XML file.

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/MVC%20Table/Step2.png)

* Step 3:  Create an MVC class.

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/MVC%20Table/Step3.png)

* Step 4:  Modify "actionModels.xml".

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/MVC%20Table/Step4.png)

* Step 5:  Modify "action.xml".

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/MVC%20Table/Step5.png)

* Step 6:  Modify ".properties".

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/MVC%20Table/Step6.png)

* Step 7: Result.

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/MVC%20Table/Step7.png)


## Custom Action on Customized Menu

In this customized function, I added a "Custom Action" to the "Customized Menu" of a "Part".

* Step 1: Find the "PartInfoBuilder".

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Custom%20Action%20on%20Customized%20Menu/Step1.png)

* Step 2: Find the "PartClient-actionModels.xml" which controls the third-level navigation menu.

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Custom%20Action%20on%20Customized%20Menu/Step2.png)

* Step 3: Add the resource bundle and modify my "actionModels.xml".

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Custom%20Action%20on%20Customized%20Menu/Step3.png)

* Step 4: Modify my "action.xml".

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Custom%20Action%20on%20Customized%20Menu/Step4.png)

* Step 5: Modify ".properties".

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Custom%20Action%20on%20Customized%20Menu/Step5.png)

* Step 6: Result demo.

  * Choose a "Part".

  ![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Custom%20Action%20on%20Customized%20Menu/Step6.png)

  * Add a new tab.

  ![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Custom%20Action%20on%20Customized%20Menu/Step7.png)

  * Select the custom action.

  ![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Custom%20Action%20on%20Customized%20Menu/Step8.png)

  * Return with the customized table.

  ![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Custom%20Action%20on%20Customized%20Menu/Step9.png)


## Redirect to another Information System through PLM

In this customized function, I linked one of the internal information systems directly from Windchill PLM System by writing a JSP.
 
* Step 1: Add a custom action in "actionModels.xml".

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Redirect%20to%20another%20Information%20System%20through%20PLM/Step1.png)

* Step 2: Define the action in "action.xml".

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Redirect%20to%20another%20Information%20System%20through%20PLM/Step2.png)

* Step 3: Create and define a JSP.

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Redirect%20to%20another%20Information%20System%20through%20PLM/Step3.png)

* Step 4: Modify ".properties".

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Redirect%20to%20another%20Information%20System%20through%20PLM/Step4.png)

* Step 5: Result demo.

* Choose a "Part".

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Redirect%20to%20another%20Information%20System%20through%20PLM/Step5.png)

* Add a new tab.

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Redirect%20to%20another%20Information%20System%20through%20PLM/Step6.png)

* Select the new custom action, which will redirect to another internal information system.

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Redirect%20to%20another%20Information%20System%20through%20PLM/Step7.png)

* Return result.

![](https://github.com/Johnny9527/ASECL_2017-2019/blob/main/Pictures/Redirect%20to%20another%20Information%20System%20through%20PLM/Step8.png)

