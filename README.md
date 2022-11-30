![image](https://user-images.githubusercontent.com/55536824/204709802-875167e2-8d16-4a73-b06e-5c288254ae69.png)


[See the live demo here](https://rifkyzena.github.io/paint-clone/)

# paint-clone
As the name implies, this is an attempt to make a very simple clone of Microsoft Paint on a website. Users will be able to draw using multiple tools from brushes to color pickers, and also load and save their art by the help of localStorage. Users will also able to download their art to their disk as a jpeg file. 

## How to use:
### Every button on the toolbar displayed on the top of the screen will display their name when hovered over.

- **Brush tool:** There is only one type of brush I have made so far. You can click and drag however you like accross the canvas.
- **Brush color:** You can pick a new color from the color selector. The basic color when you open the website will always be black.
- **Brush size slider:** The slider will show your current brush size. Drag it to the left to make your brush thinner, or to the right to make it bigger.
- **Paint bucket tool:** This tool will change the background color immediately. You can pick a new color from the color selector. The paint bucket tool should not cover or overlap what you're currently drawing.

- **Eraser tool:** This tool will only delete the parts what you have drawn with your brush. The brush size slider now also works as the eraser size slider as long as you still use the eraser tool.

- **Clear tool:** This tool clear everything you have drawn with your brush. It will not reset the canvas. Be careful since this is not an undo button.

- **Save to Local Storage:** This tool will 'save' what you have drawn on the canvas to your browser's local storage.

- **Load from Local Storage:** This tool will 'load' what you have previously saved from your local storage. 

- **Clear Local Storage:** This tool will delete everything you have made in this website from your local storage.

- **Save Image File:** Finally, this tool will download whatever you have made on the canvas as a jpeg file. The directory should be on your Downloads folder.

## Resource and references used:
- http://jscolor.com
- https://fontawesome.com/icons?d=gallery&m=free
- https://www.w3schools.com/howto/howto_js_rangeslider.asp
- https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial
- https://www.w3schools.com/jsref/prop_win_innerheight.asp
- https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes
- https://www.w3schools.com/jsref/obj_mouseevent.asp
- https://developer.mozilla.org/en-US/docs/Web/API/Element/getBoundingClientRect
- https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D
- https://developer.mozilla.org/en-US/docs/Web/API/HTMLCanvasElement/toDataURL


