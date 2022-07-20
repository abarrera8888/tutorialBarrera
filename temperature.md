# How to Display Temperature Data
## First, drag a "show number" block into the forever loop.
```blocks
basic.forever(function () {
    basic.showNumber(0)
})
```
## Next, drag a "temperature" sensor bubble into the number hole within the forever loop.
```blocks
basic.forever(function () {
    basic.showNumber(input.temperature())
})
```
