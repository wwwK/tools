# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2020 > nullish-coalescing-operator > no-paren-and-nullish`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2020/nullish-coalescing-operator/no-paren-and-nullish/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2020/nullish-coalescing-operator/no-paren-and-nullish/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2020/nullish-coalescing-operator/no-paren-and-nullish/input.js"
				end: Object {
					column: 12
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSLogicalExpression {
				operator: "??"
				loc: Object {
					filename: "es2020/nullish-coalescing-operator/no-paren-and-nullish/input.js"
					end: Object {
						column: 11
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				right: JSReferenceIdentifier {
					name: "e"
					loc: Object {
						filename: "es2020/nullish-coalescing-operator/no-paren-and-nullish/input.js"
						identifierName: "e"
						end: Object {
							column: 11
							line: 1
						}
						start: Object {
							column: 10
							line: 1
						}
					}
				}
				left: JSLogicalExpression {
					operator: "&&"
					loc: Object {
						filename: "es2020/nullish-coalescing-operator/no-paren-and-nullish/input.js"
						end: Object {
							column: 6
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
					left: JSReferenceIdentifier {
						name: "c"
						loc: Object {
							filename: "es2020/nullish-coalescing-operator/no-paren-and-nullish/input.js"
							identifierName: "c"
							end: Object {
								column: 1
								line: 1
							}
							start: Object {
								column: 0
								line: 1
							}
						}
					}
					right: JSReferenceIdentifier {
						name: "d"
						loc: Object {
							filename: "es2020/nullish-coalescing-operator/no-paren-and-nullish/input.js"
							identifierName: "d"
							end: Object {
								column: 6
								line: 1
							}
							start: Object {
								column: 5
								line: 1
							}
						}
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
