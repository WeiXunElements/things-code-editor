# things-code-editor

## 이는 code를 편집 및 저장할 수 있는 컴포넌트이다.

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
# things-template-editor

## 이는 template을 편집 및 저장할 수 있는 컴포넌트이다.
  Example:
  ```html
    <things-template-editor
        id="template-editor"
        theme="ace/theme/monokai"
        mode="ace/mode/html"
        fontsize="10"
        tabsize="2"
        source="<h1>Hello, this is Template Editor</h1>">
    </things-template-editor>
  ```
# things-editor-script

## 이는 ace-editor를 이용한 테마 설정이 가능한 WEB Editor이다.

  Example:
  ```html
    <things-editor-script
      id="editor"
      value="{{text}}"
      theme="ace/theme/monokai"
      mode="ace/mode/javascript">
    </things-editor-script>
  ```
    
    
## Dependencies

element의 종속성은 [Bower](http://bower.io/)를 통해 관리되며, 아래의 방법을 통해 설치할 수 있다.

    npm install -g bower

다음, element의 종속성을 다운로드한다.

    bower install


## Playing With Your Element

element를 독립적으로 처리하려면 [Polyserve](https://github.com/PolymerLabs/polyserve)를 사용하여 element의 bower 의존성을 유지하도록 하며, 이는 아래의 방법을 통해 설치할 수 있다.

    npm install -g polymer-cli

그리고, 아래의 방법을 통해 실행할 수 있다.

    polymer serve

element를 실행한 경우, `things-code-editor`가 디렉토리 이름으로 포함되어 있는 `http://localhost:8080/components/things-code-editor/`를 통해 이를 미리 확인할 수 있다. 
