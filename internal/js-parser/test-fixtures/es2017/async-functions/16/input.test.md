# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > async-functions > 16`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2017/async-functions/16/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2017/async-functions/16/input.js"
		end: Object {
			column: 50
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "Foo"
				loc: Object {
					filename: "es2017/async-functions/16/input.js"
					identifierName: "Foo"
					end: Object {
						column: 9
						line: 1
					}
					start: Object {
						column: 6
						line: 1
					}
				}
			}
			loc: Object {
				filename: "es2017/async-functions/16/input.js"
				end: Object {
					column: 50
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "es2017/async-functions/16/input.js"
					end: Object {
						column: 50
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				body: Array [
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "bar"
								loc: Object {
									filename: "es2017/async-functions/16/input.js"
									identifierName: "bar"
									end: Object {
										column: 21
										line: 1
									}
									start: Object {
										column: 18
										line: 1
									}
								}
							}
							loc: Object {
								filename: "es2017/async-functions/16/input.js"
								end: Object {
									column: 21
									line: 1
								}
								start: Object {
									column: 18
									line: 1
								}
							}
						}
						loc: Object {
							filename: "es2017/async-functions/16/input.js"
							end: Object {
								column: 48
								line: 1
							}
							start: Object {
								column: 12
								line: 1
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 12
								line: 1
							}
							loc: Object {
								filename: "es2017/async-functions/16/input.js"
								end: Object {
									column: 21
									line: 1
								}
								start: Object {
									column: 12
									line: 1
								}
							}
						}
						head: JSFunctionHead {
							async: true
							generator: false
							hasHoistedVars: false
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "es2017/async-functions/16/input.js"
								end: Object {
									column: 30
									line: 1
								}
								start: Object {
									column: 21
									line: 1
								}
							}
							params: Array [
								JSBindingIdentifier {
									name: "promise"
									loc: Object {
										filename: "es2017/async-functions/16/input.js"
										identifierName: "promise"
										end: Object {
											column: 29
											line: 1
										}
										start: Object {
											column: 22
											line: 1
										}
									}
									meta: JSPatternMeta {
										optional: undefined
										typeAnnotation: undefined
										loc: Object {
											filename: "es2017/async-functions/16/input.js"
											end: Object {
												column: 29
												line: 1
											}
											start: Object {
												column: 22
												line: 1
											}
										}
									}
								}
							]
						}
						body: JSBlockStatement {
							directives: Array []
							loc: Object {
								filename: "es2017/async-functions/16/input.js"
								end: Object {
									column: 48
									line: 1
								}
								start: Object {
									column: 31
									line: 1
								}
							}
							body: Array [
								JSExpressionStatement {
									loc: Object {
										filename: "es2017/async-functions/16/input.js"
										end: Object {
											column: 46
											line: 1
										}
										start: Object {
											column: 33
											line: 1
										}
									}
									expression: JSAwaitExpression {
										loc: Object {
											filename: "es2017/async-functions/16/input.js"
											end: Object {
												column: 46
												line: 1
											}
											start: Object {
												column: 33
												line: 1
											}
										}
										argument: JSReferenceIdentifier {
											name: "promise"
											loc: Object {
												filename: "es2017/async-functions/16/input.js"
												identifierName: "promise"
												end: Object {
													column: 46
													line: 1
												}
												start: Object {
													column: 39
													line: 1
												}
											}
										}
									}
								}
							]
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
