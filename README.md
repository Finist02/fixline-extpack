# Kaskad-extpack Fixlne


## Поправить расширение doxygen
`package.json`
```
"activationEvents": [
		"onLanguage:cuda",
		"onLanguage:cuda-cpp",
		"onLanguage:cpp",
		"onLanguage:ctrlpp",
		"onLanguage:c"
	],
```

`extension.js`

![extension](./images/extDoxy.png)

`CodeParserController.js`
![extension](./images/codeParserDoxy.png)