# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 527`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "core/uncategorised/527/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "core/uncategorised/527/input.js"
		end: Object {
			column: 10
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "core/uncategorised/527/input.js"
				end: Object {
					column: 10
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "let"
				loc: Object {
					filename: "core/uncategorised/527/input.js"
					end: Object {
						column: 10
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "x"
							loc: Object {
								filename: "core/uncategorised/527/input.js"
								identifierName: "x"
								end: Object {
									column: 5
									line: 1
								}
								start: Object {
									column: 4
									line: 1
								}
							}
						}
						loc: Object {
							filename: "core/uncategorised/527/input.js"
							end: Object {
								column: 10
								line: 1
							}
							start: Object {
								column: 4
								line: 1
							}
						}
						init: JSNumericLiteral {
							value: 42
							format: undefined
							raw: "42"
							loc: Object {
								filename: "core/uncategorised/527/input.js"
								end: Object {
									column: 10
									line: 1
								}
								start: Object {
									column: 8
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
