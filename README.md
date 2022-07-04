JSON
JSON is a lightweight data-interchange format. Mostly it is used to transfer data between computers.

Things to Remember
JSON means Javascript Object Notation.
It is self-describing and easy to understand.
JSON is Language Independent.
Note: The file type of json is .json
Use of JSON
It is used to transfer data between the web server and web application.
Web Services and APIs use JSON format to provide data.
JSON Data Types
Data Type	Description
String	A string is a sequence of characters.
Number	A number is a sequence of digits.
Boolean	A Boolean is either true or false.
Null	A Null is an empty value.
Array	An array is an ordered list of values. Represented By: []
Object	An object is a collection of key-value pairs. Represented By: {}
JSON Syntax
Data is represented in name/value pairs.
Each name is associated with a value.
Curly bracket {} holds objects.
Square bracket [] holds arrays.
Name and value pairs are separated by a comma.
Example of JSON
            {
                "name": "Bishworaj Poudel",
                "address": "Pokhara, Nepal",
                "age": 24,
                "image": "g",
                "description": "Hello World, I am Bishworaj Poudel."
            }
        
JSON Vs XML
JSON and XML are human-readable formats and are language-independent. JSON is easier than XML.

JSON is shorter and simple.
JSON is quick to read and write.
JSON doesn't use an end tag
JSON with Javascript
              text = ` {
                    "name": "Bishworaj Poudel",
                    "address": "Pokhara, Nepal",
                    "age": 24,
                    "image": "https://raw.githubusercontent.com/bishworajpoudelofficial/JsonGuide/main/brp.png",
                    "description": "Hello World, I am Bishworaj Poudel."
                }`

                obj = JSON.parse(text)
                console.log(obj.name)
                console.log(obj.address)
                console.log(obj.age)
                console.log(obj.image)
                console.log(obj.description)
            
JSON with Python
                import json
                text = """ {
                                    "name": "Bishworaj Poudel",
                                    "address": "Pokhara, Nepal",
                                    "age": 24,
                                    "image": "https://raw.githubusercontent.com/bishworajpoudelofficial/JsonGuide/main/brp.png",
                                    "description": "Hello World, I am Bishworaj Poudel."
                                } """
                
                obj = json.loads(text)
                print(obj["name"])
                print(obj["address"])
            
Convert Python Dictionary to JSON
                import json

                # This is python object
                data = {
                    "name":"Bishworaj Poudel",
                    "age":24,
                    "address": "Pokhara, Nepal"
                } 
                
                text = json.dumps(data)
                print(type(text))
                print(text)
            
Some Examples of JSON
Demo Example 1 [Personal Info]
Demo Example 2 [Personal Info Complex]
Demo Example 3 [Motivational Quotes]
