# monaco-proto
Supporting Protobuf language for monaco-editor

## Install
`npm i -S monaco-proto`

## Usage
```javascript
import registerProtobufLanguage from 'monaco-proto';


registerProtobufLanguage(monaco);
monaco.editor.create(document.getElementById("container"), {
	language: "protobuf",
	theme: "protobuf"
});
```
