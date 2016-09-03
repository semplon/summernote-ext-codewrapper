# Summernote Codewrapper Extension
Code Wrapper for Summernote Editor, this will wrap your code into one part. Not like the default code styler by summernote.

## WHY ?
I made this plugin because the default Summernote had is not wrap the code into one part when using summernote's code styler. It will break into paragraph. And when the code is long, we had to edit it manually. 

When copying and paste the code, summernote can wrap html code but not the others. 

see videos for the demo

https://www.youtube.com/watch?v=TTUgPvp6DQs

## Installation
call your plugin script after summernote 

```html
<script src="http://path.to/your/summernote-ext-codewrapper.min.js"></script>
```

load the summernote 
```js
$(document).ready(function() {
     $('.editor').summernote({
         height: 300,
         toolbar: [
                 ['insert', ['gxcode']]
             ]
     });
 }
```

## License
**MIT License**
