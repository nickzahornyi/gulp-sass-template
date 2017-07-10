# gulp-sass-template
Simple gulp template (using sass as preprocessor)

## Usage
1. Put your html-templates (like header/footer) into `template folder`. You can include them easily [(more info about html-templates)](https://www.npmjs.com/package/gulp-file-include) :

```html
@@include('components/_header.html')
```
2. Put your sass files into `app/sass` folder <br>
    `base folder` - for common styles (like normalize, variables, mixins)<br>
    `layout folder` - for templates styles and pages basic layouts<br>
    
### Happy coding!