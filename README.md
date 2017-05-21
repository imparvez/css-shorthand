# CSS ShortHand

Basic useful feature list:

 * Background
 	```css
    /*
      BackGround CSS shorthand:
      background: background-color | background-image |   
      background-repeat | background-attachment | background-position;
    */
    .background-css {
      width: 100%;
      height: 200px;
      background: #fff url(http://lorempixel.com/400/200) no-repeat fixed center center;
      background-size: contain;
    }
    ```
* Font
	```css
    /*
      font: font-style | font-variant | font-weight |  
      font-size | line-height | font-family
    */

    p {
    	font: 700 20px/26px 'sans-serif';
    }
    ```
* Margin & Padding
	```css
   .margin-padding-shorthand {
        padding: 1em 4em;
        margin: 15px 25px;
    }
    ```
* Border
	```css
    /*
    border: border-width | border-style | color
    */

    .border {
    	border: 1px solid #ccc;
    }
    ```
* List Style
	```css
    /*
    list-style: list-style-type | list-style-position | list-style-image
    */

    ul li {
      list-style-image: url('http://lorempixel.com/10/10/');
      list-style-type: circle;
      list-style-position: outside;
    }
    ```