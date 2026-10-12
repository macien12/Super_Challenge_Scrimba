# Houses for Sale

A Scrimba JavaScript challenge that renders property cards with an image, location, price in GBP, description, and total floor area.

## Example usage

In `index.js`, pass the property array to `getPropertyHtml` to display all listings:

```js
document.getElementById('container').innerHTML = getPropertyHtml(propertyForSaleArr)
```

For example, the Kensington listing uses this data:

```js
{
    propertyLocation: 'Kensington, London',
    priceGBP: 890000,
    roomsM2: [14, 18, 14, 10, 6],
    comment: 'Highly desirable location in stunning scenery!',
    image: 'cottage.jpg'
}
```

Its card displays Kensington, London, a price of `890000`, and a total area of **62 m²**, calculated by adding the room sizes.

Call the function without an argument to display the placeholder property:

```js
document.getElementById('container').innerHTML = getPropertyHtml()
```

The challenge practices import/export, `.map()`, `.join()`, object destructuring, `.reduce()`, and default parameters.

