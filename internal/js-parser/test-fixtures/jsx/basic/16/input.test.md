# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `jsx > basic > 16`

### `ast`

```javascript
JSRoot {
	body: [
		JSExpressionStatement {
			expression: JSBinaryExpression {
				operator: "<"
				left: JSXElement {
					attributes: []
					children: []
					selfClosing: true
					name: JSXIdentifier {
						name: "div"
						loc: SourceLocation jsx/basic/16/input.jsx 1:2-1:5
					}
					loc: SourceLocation jsx/basic/16/input.jsx 1:1-1:8
				}
				right: JSReferenceIdentifier {
					name: "x"
					loc: SourceLocation jsx/basic/16/input.jsx 1:12-1:13 (x)
				}
				loc: SourceLocation jsx/basic/16/input.jsx 1:0-1:13
			}
			loc: SourceLocation jsx/basic/16/input.jsx 1:0-1:14
		}
	]
	comments: []
	corrupt: false
	diagnostics: []
	directives: []
	hasHoistedVars: false
	sourceType: "script"
	syntax: ["jsx"]
	path: UIDPath<jsx/basic/16/input.jsx>
	loc: SourceLocation jsx/basic/16/input.jsx 1:0-1:14
}
```

### `diagnostics`

```

```
