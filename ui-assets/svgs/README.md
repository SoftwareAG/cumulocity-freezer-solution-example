# Instructions

## Using the SVGs

Both SVGs are customized to be used inside the SCADA widget of Cumulocity IoT and can simply a selected inside the widget for upload.

![Fan](https://user-images.githubusercontent.com/1639884/84354731-b0b65a80-abc1-11ea-8439-e2b3f407cd6c.png)

![Fridge](https://user-images.githubusercontent.com/1639884/84354845-dcd1db80-abc1-11ea-84bb-af20dd41f9e3.png)

## What is the input for the SVGs?

The SVGs are not fixed for this solution and don't need a specifc measurements. You can map any measurement into the SVGs as long as the value ranges play together with them.

## Expected values ranges for mapped measurements

### Fan SVG

|Value|Result|
|---|---|
|0|Not moving|
|0-59|Slow|
|60-79|Medium|
|80-99|Fast|
|>=100|Very fast|

### Fridge Door SVG

|Value|Result|
|---|---|
|0|Closed|
|1|Open|