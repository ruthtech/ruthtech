```diff
- text in red
+ text in green
! text in orange
# text in grey
@@ text in purple (and bold)@@
```

```json
   {
      "example-json-field": "This is a test",
      "example-json-field2": "This is also a test",
      "example-json-field3" : [
           "Do",
           "not",
           "pass",
           "Go.",
           "Do",
           "not",
           "collect",
           "$200."
      ]
   }
```

```html
   <h1>This is a top level heading</h1>
   <h2>This is a subheading.</h2>
   <p>This is a paragraph.</p>
```

```javascript
"use strict"

function guessThePassword( guess ) {
    if((typeof guess != "string") ||
        (guess.length < 8)){
        return "The password must be at least 8 characters long.";
    }

    var howPopular = mostCommonPasswords.indexOf(guess);
    var message = "";
    if(howPopular < 0) {
        message = `\'${guess}\' is not one of the 50,000 most common passwords. `;
    } else {
        howPopular++; // Human index starts at 1, not 0.
        message = `\'${guess}\' is #${howPopular} on the list.`;
    }
    return message;
}   
```

```css
.skills-card {
    width: 100%;
    margin-bottom: .5rem;
    border-radius: 15px!important;
}

.skills-title {
    font-weight: bold;
    font-size: large;
    margin-bottom: 0!important;
}

.skills-body {
    border-radius: 0 0 15px 15px!important;
}
```

```java
    @RequiredArgsConstructor
    public class JavaExample {
        private final String value;
    }
```
