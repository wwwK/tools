# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 395`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "core/uncategorised/395/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "core/uncategorised/395/input.js"
		end: Object {
			column: 19
			line: 1
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
				message: RAW_MARKUP {value: "Expected an identifier"}
			}
			location: Object {
				filename: "core/uncategorised/395/input.js"
				integrity: undefined
				language: "js"
				sourceText: undefined
				end: Object {
					column: 14
					line: 1
				}
				start: Object {
					column: 14
					line: 1
				}
			}
		}
	]
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "t"
				loc: Object {
					filename: "core/uncategorised/395/input.js"
					identifierName: "t"
					end: Object {
						column: 10
						line: 1
					}
					start: Object {
						column: 9
						line: 1
					}
				}
			}
			loc: Object {
				filename: "core/uncategorised/395/input.js"
				end: Object {
					column: 19
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
					filename: "core/uncategorised/395/input.js"
					end: Object {
						column: 19
						line: 1
					}
					start: Object {
						column: 16
						line: 1
					}
				}
			}
			head: JSFunctionHead {
				async: false
				generator: false
				hasHoistedVars: false
				params: Array []
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "core/uncategorised/395/input.js"
					end: Object {
						column: 15
						line: 1
					}
					start: Object {
						column: 10
						line: 1
					}
				}
				rest: JSBindingIdentifier {
					name: ""
					loc: Object {
						filename: "core/uncategorised/395/input.js"
						identifierName: ""
						end: Object {
							column: 15
							line: 1
						}
						start: Object {
							column: 14
							line: 1
						}
					}
					meta: JSPatternMeta {
						optional: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "core/uncategorised/395/input.js"
							end: Object {
								column: 15
								line: 1
							}
							start: Object {
								column: 14
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

 core/uncategorised/395/input.js:1:14 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Expected an identifier

    function t(...) { }
                  ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
