# Python_DevOps_JSON

JSON (JavaScript Object Notation) manipulation in Python involves working with JSON data, which is a lightweight data-interchange format. It is easy for humans to read and write and easy for machines to parse and generate.

In Python, you can manipulate JSON data using the `json` module, which provides methods for encoding and decoding JSON data. Here are some common JSON manipulation tasks in Python:

1. **Loading JSON Data:**
   - The `json.loads()` function is used to parse a JSON string and convert it into a Python data structure (usually a dictionary or a list).

   ```python
   import json

   json_string = '{"name": "John Doe", "age": 30, "city": "New York"}'
   data = json.loads(json_string)
   print(data)
   ```
   
2. **Reading JSON from a File:**
   - The `json.load()` function is used to read JSON data from a file and convert it into a Python data structure.

   ```python
   import json

   with open('data.json', 'r') as file:
       data = json.load(file)
   print(data)
   ```


3. **Dumping JSON Data:**
   - The `json.dumps()` function is used to convert a Python object (usually a dictionary or a list) into a JSON formatted string.

   ```python
   import json

   data = {'name': 'John Doe', 'age': 30, 'city': 'New York'}
   json_string = json.dumps(data)
   print(json_string)
   ```
   
4. **Writing JSON to a File:**
   - The `json.dump()` function is used to write JSON data to a file.

   ```python
   import json

   data = {'name': 'John Doe', 'age': 30, 'city': 'New York'}
   with open('output.json', 'w') as file:
       json.dump(data, file)
   ```4. **Writing JSON to a File:**
   - The `json.dump()` function is used to write JSON data to a file.

   ```python
   import json

   data = {'name': 'John Doe', 'age': 30, 'city': 'New York'}
   with open('output.json', 'w') as file:
       json.dump(data, file)
   ```

