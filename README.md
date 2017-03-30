# things-code-editor

### things-code-editor. Code성 텍스트를 편집 및 저장 할 수 있는 컴퍼넌트

  Example:

```html
    <things-code-editor
      id="code-editor"
      theme="ace/theme/monokai"
      mode="ace/mode/javascript"
      fontsize="12px"
      tabsize="2"
      source="var source = function() { console.log('this is Code Editor') };">
    </things-code-editor>
```


## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polymer-cli

And you can run it via:

    polymer serve

Once running, you can preview your element at
`http://localhost:8080/components/things-code-editor/`, where `things-code-editor` is the name of the directory containing it.


## Example 1. Things code editor
`<things-code-editor>` Code성 텍스트를 편집 및 저장 할 수 있는 컴퍼넌트

## Example 2. Things template editor
`<things-template-editor>`. template성 텍스트를 편집 및 저장 할 수 있는 컴퍼넌트
