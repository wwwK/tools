# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-yield > yield-arrow-parameter-default`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-yield/yield-arrow-parameter-default/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-yield/yield-arrow-parameter-default/input.js"
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
				filename: "esprima/es2015-yield/yield-arrow-parameter-default/input.js"
				end: Object {
					column: 17
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSArrowFunctionExpression {
				loc: Object {
					filename: "esprima/es2015-yield/yield-arrow-parameter-default/input.js"
					end: Object {
						column: 17
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				body: JSBlockStatement {
					body: Array []
					directives: Array []
					loc: Object {
						filename: "esprima/es2015-yield/yield-arrow-parameter-default/input.js"
						end: Object {
							column: 17
							line: 1
						}
						start: Object {
							column: 15
							line: 1
						}
					}
				}
				head: JSFunctionHead {
					async: false
					hasHoistedVars: false
					rest: undefined
					returnType: undefined
					thisType: undefined
					loc: Object {
						filename: "esprima/es2015-yield/yield-arrow-parameter-default/input.js"
						end: Object {
							column: 14
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
					params: Array [
						JSBindingAssignmentPattern {
							operator: "="
							loc: Object {
								filename: "esprima/es2015-yield/yield-arrow-parameter-default/input.js"
								end: Object {
									column: 10
									line: 1
								}
								start: Object {
									column: 1
									line: 1
								}
							}
							left: JSBindingIdentifier {
								name: "x"
								loc: Object {
									filename: "esprima/es2015-yield/yield-arrow-parameter-default/input.js"
									identifierName: "x"
									end: Object {
										column: 2
										line: 1
									}
									start: Object {
										column: 1
										line: 1
									}
								}
							}
							right: JSReferenceIdentifier {
								name: "yield"
								loc: Object {
									filename: "esprima/es2015-yield/yield-arrow-parameter-default/input.js"
									identifierName: "yield"
									end: Object {
										column: 10
										line: 1
									}
									start: Object {
										column: 5
										line: 1
									}
								}
							}
						}
					]
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
