# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 49`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2015/uncategorised/49/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/uncategorised/49/input.js"
		end: Object {
			column: 13
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2015/uncategorised/49/input.js"
				end: Object {
					column: 13
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSCallExpression {
				loc: Object {
					filename: "es2015/uncategorised/49/input.js"
					end: Object {
						column: 13
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				callee: JSReferenceIdentifier {
					name: "foo"
					loc: Object {
						filename: "es2015/uncategorised/49/input.js"
						identifierName: "foo"
						end: Object {
							column: 3
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
				}
				arguments: Array [
					JSArrowFunctionExpression {
						loc: Object {
							filename: "es2015/uncategorised/49/input.js"
							end: Object {
								column: 12
								line: 1
							}
							start: Object {
								column: 4
								line: 1
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "es2015/uncategorised/49/input.js"
								end: Object {
									column: 12
									line: 1
								}
								start: Object {
									column: 10
									line: 1
								}
							}
						}
						head: JSFunctionHead {
							async: false
							hasHoistedVars: false
							params: Array []
							rest: undefined
							returnType: undefined
							thisType: undefined
							loc: Object {
								filename: "es2015/uncategorised/49/input.js"
								end: Object {
									column: 9
									line: 1
								}
								start: Object {
									column: 4
									line: 1
								}
							}
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
