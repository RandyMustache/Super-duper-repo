# FE Assessment

## HTML Knowledge

The box model is effectively the base blocks of HTML. It's the main element (eg a div) and its padding, margin and borders. The box size comprises of padding and border by default. Using box-sizing: border-box gives us the 100px element is actually 100px we all know and love, so padding and border sizes don't affect the final size of your element. 

## JS Excersies

1. 
    ```javascript
    const getPrice = sales.map((x) => x.price); //create a new a array with the prices
    const sumPrice = () => getPrice.reduce((a, b) => a + b, 0); //add em all up
    const usePrice = sumPrice(); //use it
    ```
2. ```javascript
      const getDates = sales.filter(date => date.dateSold.includes('2017')) //get only sold in 2017
    ```
3. ```javascript
    const getUnique = sales.filter(saleID => saleID.id.includes('j_999')) //get object with only the matched ID
    const setUniqueString = getUnique.map(a => a.itemSold).toString() //convert to string
    ```
4. ```javascript
    const getUnique = sales.filter(saleID => saleID.id.includes('j_999')) //get object with only the matched ID
    ```
    
## Layout Excersise 

I chose to build the layout using flexbox as it provides a really simple way to do this sort of layout with minimal CSS and minimal media queries. This layout only needed a querie at 768px to reflow 2 elements of it. This also means less literal pixel heights and widths need to be set, therefore the layout is accessible ready. 

Since IE does not count as a modern browser, flex is safe. I also don't think the layout needs documentation, as it uses descriptive HTML tags and descriptive CSS.

### Code 
For Layout:
 https://codesandbox.io/s/strange-thunder-xvc2h

For box model and JS questions:
https://codesandbox.io/s/bold-moon-pb9ls
