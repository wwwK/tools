# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0056`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: true
	directives: Array []
	filename: "esprima/invalid-syntax/migrated_0056/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/invalid-syntax/migrated_0056/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse"}]
			description: Object {
				advice: Array []
				category: "parse"
				categoryValue: "js"
				message: Array [
					RAW_MARKUP {value: "Invalid left-hand side in "}
					"for-in statement"
				]
			}
			location: Object {
				filename: "esprima/invalid-syntax/migrated_0056/input.js"
				integrity: undefined
				language: "js"
				sourceText: undefined
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
	]
	body: Array [
		JSForInStatement {
			loc: Object {
				filename: "esprima/invalid-syntax/migrated_0056/input.js"
				end: Object {
					column: 32
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			left: JSAssignmentIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: Object {
					filename: "esprima/invalid-syntax/migrated_0056/input.js"
					end: Object {
						column: 11
						line: 1
					}
					start: Object {
						column: 12
						line: 1
					}
				}
			}
			right: JSReferenceIdentifier {
				name: "list"
				loc: Object {
					filename: "esprima/invalid-syntax/migrated_0056/input.js"
					identifierName: "list"
					end: Object {
						column: 19
						line: 1
					}
					start: Object {
						column: 15
						line: 1
					}
				}
			}
			body: JSExpressionStatement {
				loc: Object {
					filename: "esprima/invalid-syntax/migrated_0056/input.js"
					end: Object {
						column: 32
						line: 1
					}
					start: Object {
						column: 21
						line: 1
					}
				}
				expression: JSCallExpression {
					loc: Object {
						filename: "esprima/invalid-syntax/migrated_0056/input.js"
						end: Object {
							column: 31
							line: 1
						}
						start: Object {
							column: 21
							line: 1
						}
					}
					callee: JSReferenceIdentifier {
						name: "process"
						loc: Object {
							filename: "esprima/invalid-syntax/migrated_0056/input.js"
							identifierName: "process"
							end: Object {
								column: 28
								line: 1
							}
							start: Object {
								column: 21
								line: 1
							}
						}
					}
					arguments: Array [
						JSReferenceIdentifier {
							name: "x"
							loc: Object {
								filename: "esprima/invalid-syntax/migrated_0056/input.js"
								identifierName: "x"
								end: Object {
									column: 30
									line: 1
								}
								start: Object {
									column: 29
									line: 1
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

 esprima/invalid-syntax/migrated_0056/input.js:1:5 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Invalid left-hand side in for-in statement

    for((1 + 1) in list) process(x);
         ^^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
