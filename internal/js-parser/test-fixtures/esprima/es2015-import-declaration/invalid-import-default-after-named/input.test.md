# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-import-declaration > invalid-import-default-after-named`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: true
	directives: Array []
	filename: "esprima/es2015-import-declaration/invalid-import-default-after-named/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-import-declaration/invalid-import-default-after-named/input.js"
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
					RAW_MARKUP {value: "Expected keyword "}
					"from"
				]
			}
			location: Object {
				filename: "esprima/es2015-import-declaration/invalid-import-default-after-named/input.js"
				integrity: undefined
				language: "js"
				sourceText: undefined
				end: Object {
					column: 12
					line: 1
				}
				start: Object {
					column: 12
					line: 1
				}
			}
		}
	]
	body: Array [
		JSImportDeclaration {
			defaultSpecifier: undefined
			importKind: undefined
			namespaceSpecifier: undefined
			loc: Object {
				filename: "esprima/es2015-import-declaration/invalid-import-default-after-named/input.js"
				end: Object {
					column: 12
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			source: JSStringLiteral {
				value: ""
				loc: Object {
					filename: "esprima/es2015-import-declaration/invalid-import-default-after-named/input.js"
					end: Object {
						column: 12
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
			}
			namedSpecifiers: Array [
				JSImportSpecifier {
					loc: Object {
						filename: "esprima/es2015-import-declaration/invalid-import-default-after-named/input.js"
						end: Object {
							column: 11
							line: 1
						}
						start: Object {
							column: 8
							line: 1
						}
					}
					imported: JSIdentifier {
						name: "bar"
						loc: Object {
							filename: "esprima/es2015-import-declaration/invalid-import-default-after-named/input.js"
							identifierName: "bar"
							end: Object {
								column: 11
								line: 1
							}
							start: Object {
								column: 8
								line: 1
							}
						}
					}
					local: JSImportSpecifierLocal {
						name: JSBindingIdentifier {
							name: "bar"
							loc: Object {
								filename: "esprima/es2015-import-declaration/invalid-import-default-after-named/input.js"
								identifierName: "bar"
								end: Object {
									column: 11
									line: 1
								}
								start: Object {
									column: 8
									line: 1
								}
							}
						}
						importKind: undefined
						loc: Object {
							filename: "esprima/es2015-import-declaration/invalid-import-default-after-named/input.js"
							end: Object {
								column: 11
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
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/es2015-import-declaration/invalid-import-default-after-named/input.js"
				end: Object {
					column: 13
					line: 1
				}
				start: Object {
					column: 12
					line: 1
				}
			}
			expression: JSReferenceIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: Object {
					filename: "esprima/es2015-import-declaration/invalid-import-default-after-named/input.js"
					end: Object {
						column: 13
						line: 1
					}
					start: Object {
						column: 12
						line: 1
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/es2015-import-declaration/invalid-import-default-after-named/input.js"
				end: Object {
					column: 17
					line: 1
				}
				start: Object {
					column: 14
					line: 1
				}
			}
			expression: JSReferenceIdentifier {
				name: "foo"
				loc: Object {
					filename: "esprima/es2015-import-declaration/invalid-import-default-after-named/input.js"
					identifierName: "foo"
					end: Object {
						column: 17
						line: 1
					}
					start: Object {
						column: 14
						line: 1
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/es2015-import-declaration/invalid-import-default-after-named/input.js"
				end: Object {
					column: 22
					line: 1
				}
				start: Object {
					column: 18
					line: 1
				}
			}
			expression: JSReferenceIdentifier {
				name: "from"
				loc: Object {
					filename: "esprima/es2015-import-declaration/invalid-import-default-after-named/input.js"
					identifierName: "from"
					end: Object {
						column: 22
						line: 1
					}
					start: Object {
						column: 18
						line: 1
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/es2015-import-declaration/invalid-import-default-after-named/input.js"
				end: Object {
					column: 28
					line: 1
				}
				start: Object {
					column: 23
					line: 1
				}
			}
			expression: JSStringLiteral {
				value: "foo"
				loc: Object {
					filename: "esprima/es2015-import-declaration/invalid-import-default-after-named/input.js"
					end: Object {
						column: 28
						line: 1
					}
					start: Object {
						column: 23
						line: 1
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```

 esprima/es2015-import-declaration/invalid-import-default-after-named/input.js:1:12 parse(js) ━━━━━━

  ✖ Expected keyword from

    import {bar}, foo from "foo"
                ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
