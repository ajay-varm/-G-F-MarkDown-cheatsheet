# **git flavoured markdown** :

## **Commenting** :

* #### **code** : 
   * `<hello every one>`
* #### **output** : 
  *  itshows nothing
## **Normal Text** :
* **code** :
  * ` `This is normal text.` `
* **Output** :

     * This is normal text.

## **Horizontal Rules** :

* To draw a hortizontal rule, use 3 hyphens in new line (---).

## **Headings** :
```bash
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
* Output :

  * # Heading 1

  * ## Heading 2

  * ### Heading 3

  * #### Heading 4

  *  ##### Heading 5
  * ###### Heading 6


## **Text Formatting** :

1. Italics :

   *  _Italic Text should be wrapped with single underscores_


2. Bold Text :

   * Bold Text should be wrapped with double asterisks(**)

3. Strike-Through Text :

     * Strike-Through Text should be wrapped with double tildes(~~)

4. Block-Quotes :

     * A Block-Quote should start with a greater than sign (>)

## **Lists** :

1. **Unordered Lists** :

    * Unordered lists can be formed using asterisks(*).
         ```bash
          * Item 1
          * Item 2
          * Item 3
            * Nested Item 1
            * Nested Item 2
        ```


2. **Ordered Lists** :

    * Ordered lists can be formed using numbers.

        1. Item 1
        2. Item 2
        3. Item 3
            1. Nested Item 1
            2. Nested Item 2

## **Code** :

1. **Inline Code** :

   * For inline code, we wrap the code in back-ticks (``)

2. **Code-Blocks** :

    * We wrap the code-blocks with three back-ticks(```).
 
    * By default, these are NOT syntax highlighted.To get syntax-highlighting, we have to specify the name of the language after the first 3 back-ticks.
* **code** :
```
   '''java
    class MainClass {
    public static void main(String args[]) 
     {
        System.out.println("Hello, World!");
     }
    }
   '''
```    
* **output** :
```java
class MainClass {
    public static void main(String args[]) {
        System.out.println("Hello, World!");
    }
}
```

3. **Diff** :
   * you can have some fancy stuff.
   * **code** :
     * ```
       '''diff
       + add it
       - delete it 
       '''
   * **output** :
     * ```diff
       + add it
       - delete it    

## **Images** :

 * **Syntax for image** :
   * `![display_name](path "alternate_text")`
## **Links** :
 * **Syntax for links** :
    * `[display_name](path "alternate_text")`


    ---

>  **These are basic stuff for most of the usage  and I will update the sheet when i find some complicated stuff with more features...**

`Happy cheating` :)
 
