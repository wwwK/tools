# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > logical-assignment-operator > mallet`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: true
	directives: Array []
	filename: "experimental/logical-assignment-operator/mallet/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "experimental/logical-assignment-operator/mallet/input.js"
		end: Object {
			column: 0
			line: 3
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
					RAW_MARKUP {value: "Unknown start to an "}
					"statement expression"
				]
			}
			location: Object {
				filename: "experimental/logical-assignment-operator/mallet/input.js"
				integrity: undefined
				language: "js"
				sourceText: undefined
				end: Object {
					column: 4
					line: 1
				}
				start: Object {
					column: 4
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "experimental/logical-assignment-operator/mallet/input.js"
				end: Object {
					column: 5
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSLogicalExpression {
				operator: "||"
				loc: Object {
					filename: "experimental/logical-assignment-operator/mallet/input.js"
					end: Object {
						column: 5
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				right: JSReferenceIdentifier {
					name: "INVALID_PLACEHOLDER"
					loc: Object {
						filename: "experimental/logical-assignment-operator/mallet/input.js"
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
				left: JSReferenceIdentifier {
					name: "a"
					loc: Object {
						filename: "experimental/logical-assignment-operator/mallet/input.js"
						identifierName: "a"
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
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "experimental/logical-assignment-operator/mallet/input.js"
				end: Object {
					column: 8
					line: 1
				}
				start: Object {
					column: 6
					line: 1
				}
			}
			expression: JSReferenceIdentifier {
				name: "b"
				loc: Object {
					filename: "experimental/logical-assignment-operator/mallet/input.js"
					identifierName: "b"
					end: Object {
						column: 7
						line: 1
					}
					start: Object {
						column: 6
						line: 1
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "experimental/logical-assignment-operator/mallet/input.js"
				end: Object {
					column: 9
					line: 2
				}
				start: Object {
					column: 0
					line: 2
				}
			}
			expression: JSLogicalExpression {
				operator: "||"
				loc: Object {
					filename: "experimental/logical-assignment-operator/mallet/input.js"
					end: Object {
						column: 9
						line: 2
					}
					start: Object {
						column: 0
						line: 2
					}
				}
				right: JSReferenceIdentifier {
					name: "INVALID_PLACEHOLDER"
					loc: Object {
						filename: "experimental/logical-assignment-operator/mallet/input.js"
						end: Object {
							column: 9
							line: 2
						}
						start: Object {
							column: 8
							line: 2
						}
					}
				}
				left: JSMemberExpression {
					loc: Object {
						filename: "experimental/logical-assignment-operator/mallet/input.js"
						end: Object {
							column: 5
							line: 2
						}
						start: Object {
							column: 0
							line: 2
						}
					}
					object: JSReferenceIdentifier {
						name: "obj"
						loc: Object {
							filename: "experimental/logical-assignment-operator/mallet/input.js"
							identifierName: "obj"
							end: Object {
								column: 3
								line: 2
							}
							start: Object {
								column: 0
								line: 2
							}
						}
					}
					property: JSStaticMemberProperty {
						value: JSIdentifier {
							name: "a"
							loc: Object {
								filename: "experimental/logical-assignment-operator/mallet/input.js"
								identifierName: "a"
								end: Object {
									column: 5
									line: 2
								}
								start: Object {
									column: 4
									line: 2
								}
							}
						}
						loc: Object {
							filename: "experimental/logical-assignment-operator/mallet/input.js"
							identifierName: "a"
							end: Object {
								column: 5
								line: 2
							}
							start: Object {
								column: 4
								line: 2
							}
						}
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "experimental/logical-assignment-operator/mallet/input.js"
				end: Object {
					column: 12
					line: 2
				}
				start: Object {
					column: 10
					line: 2
				}
			}
			expression: JSReferenceIdentifier {
				name: "b"
				loc: Object {
					filename: "experimental/logical-assignment-operator/mallet/input.js"
					identifierName: "b"
					end: Object {
						column: 11
						line: 2
					}
					start: Object {
						column: 10
						line: 2
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```

 experimental/logical-assignment-operator/mallet/input.js:1:4 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unknown start to an statement expression

  > 1 │ a ||= b;
      │     ^
    2 │ obj.a ||= b;

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
