# **git flavoured markdown** :

## **Commenting** :

* #### **code** : 
   * `<hello every one>`
* #### **output** : 
  *  itshows nothing
## **Normal Text** :
* **code** :
  * `This is normal text.`
* **Output** :

     * >This is normal text.

## **Horizontal Rules** :

* >To draw a hortizontal rule, use 3 hyphens in new line (---).

D. Headings :

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
Output :

Heading 1

Heading 2

Heading 3

Heading 4

Heading 5
Heading 6
After the 1st type heading, (at times the 2nd type too) a horizontal rule will be drawn.

E. Text Formatting :

1. Italics :

_Italic Text should be wrapped with single underscores_
*Italic Text can also be wrapped with single asterisks*
Output :

Italic Text should be wrapped with single underscores

Italic Text can also be wrapped with single asterisks

2. Bold Text :

**Bold Text should be wrapped with double asterisks**
__Bold Text can also be wrapped with double underscores__
Output :

Bold Text should be wrapped with double asterisks

Bold Text can also be wrapped with double underscores

Use asterisks for strong text and underscores for italics, for better and clean code.

3. Strike-Through Text :

~~Strike-Through Text should be wrapped with double tildes~~
Output :

Strike-Through Text should be wrapped with double tildes

4. Block-Quotes :

> A Block-Quote should start with a greater than sign (>)
Output :

A Block-Quote should start with a greater than sign (>)

F. Lists :

1. Unordered Lists :

Unordered lists can be formed using asterisks(*).

* Item 1
* Item 2
* Item 3
    * Nested Item 1
    * Nested Item 2
Output :

Item 1
Item 2
Item 3
Nested Item 1
Nested Item 2
2. Ordered Lists :

Ordered lists can be formed using numbers.

1. Item 1
2. Item 2
3. Item 3
    1. Nested Item 1
    2. Nested Item 2
Output :

Item 1
Item 2
Item 3
Nested Item 1
Nested Item 2
G. Code :

1. Inline Code :

For inline code, we wrap the code in back-ticks, like this : git commit -m "Initial Commit" or echo "Hello, World!"

2. Code-Blocks :

We wrap the code-blocks with three back-ticks.

By default, these are NOT syntax highlighted.

class MainClass {
    public static void main(String args[]) {
        System.out.println("Hello, World!");
    }
}
To get syntax-highlighting, we can specify the name of the language after the first 3 back-ticks.
javascript
Copy
const add = (num1, num2) => num1 + num2;

if (add(1, 2))
  console.log('The sum is a number');
else
  console.log('The sum is zero');
Some Other Examples :
python
Copy
#!/usr/bin/python

def add(num1,  num2):
    return num1 + num2
