# JS-Code-Snippets


<h2>Remove duplication in an array of objects</h2>

```javascript

  const removeDuplicate = (arr) =>
	[...new Set(arr.map((object) => JSON.stringify(object)))].map((object) =>
		JSON.parse(object)
	);


```
