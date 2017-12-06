# **DataSave.js**
A simple JavaScript application to save many properties into objects, which is useful especially for saving information for clicker games made in JavaScript 

# **Functions:**


## **Data.save()**

**Function Syntax:**

   Data.save(Object name,poperty      name, value);

**Example:**
   Data.save(“Cookies”,”amount”,10);

This would now save in a Object (which is always Data.(name of object) The information is stored as an aaray. So, if we create a new object, and save this information, **amount** will now br stored in Data.Cookies[0] and the value of the value of that property, **10** will be stored at Data.Cookies[1]. The next property added to **Cookies** will then be located in the aray index of 2 and 3, and so on after that.

## **Data.get()**

**Function Syntax:**

   Data.get(Object Name, Property Name);

**Example:**
   Data.get(“Cookies”,”amount”);
Using the previous example, doing this function would now returm the value of the property, **amount**
This means that you can use it later by calling this function to get the value of a given property.