Write a PHP script which decodes the following JSON string.

```json
{
    "Title": "The Cuckoos Calling",
    "Author": "Robert Galbraith",
    "Detail": {
        "Publisher": "Little Brown"
    }
}
```

Expected Output:

```
Title: The Cuckoos Calling
Author: Robert Galbraith
Publisher: Little Brown
```

Your code should not depend on amount of nested levels. 
For example, `Publisher` can be on 4th nested level.
