# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-yield > yield-expression-precedence`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-yield/yield-expression-precedence/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-yield/yield-expression-precedence/input.js"
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
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "g"
				loc: Object {
					filename: "esprima/es2015-yield/yield-expression-precedence/input.js"
					identifierName: "g"
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
			loc: Object {
				filename: "esprima/es2015-yield/yield-expression-precedence/input.js"
				end: Object {
					column: 42
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			head: JSFunctionHead {
				async: false
				generator: true
				hasHoistedVars: false
				params: Array []
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "esprima/es2015-yield/yield-expression-precedence/input.js"
					end: Object {
						column: 13
						line: 1
					}
					start: Object {
						column: 11
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				directives: Array []
				loc: Object {
					filename: "esprima/es2015-yield/yield-expression-precedence/input.js"
					end: Object {
						column: 42
						line: 1
					}
					start: Object {
						column: 14
						line: 1
					}
				}
				body: Array [
					JSExpressionStatement {
						loc: Object {
							filename: "esprima/es2015-yield/yield-expression-precedence/input.js"
							end: Object {
								column: 40
								line: 1
							}
							start: Object {
								column: 16
								line: 1
							}
						}
						expression: JSSequenceExpression {
							loc: Object {
								filename: "esprima/es2015-yield/yield-expression-precedence/input.js"
								end: Object {
									column: 40
									line: 1
								}
								start: Object {
									column: 16
									line: 1
								}
							}
							expressions: Array [
								JSYieldExpression {
									delegate: false
									loc: Object {
										filename: "esprima/es2015-yield/yield-expression-precedence/input.js"
										end: Object {
											column: 25
											line: 1
										}
										start: Object {
											column: 16
											line: 1
										}
									}
									argument: JSAssignmentExpression {
										operator: "="
										loc: Object {
											filename: "esprima/es2015-yield/yield-expression-precedence/input.js"
											end: Object {
												column: 25
												line: 1
											}
											start: Object {
												column: 22
												line: 1
											}
										}
										left: JSAssignmentIdentifier {
											name: "a"
											loc: Object {
												filename: "esprima/es2015-yield/yield-expression-precedence/input.js"
												identifierName: "a"
												end: Object {
													column: 23
													line: 1
												}
												start: Object {
													column: 22
													line: 1
												}
											}
										}
										right: JSReferenceIdentifier {
											name: "b"
											loc: Object {
												filename: "esprima/es2015-yield/yield-expression-precedence/input.js"
												identifierName: "b"
												end: Object {
													column: 25
													line: 1
												}
												start: Object {
													column: 24
													line: 1
												}
											}
										}
									}
								}
								JSYieldExpression {
									delegate: true
									loc: Object {
										filename: "esprima/es2015-yield/yield-expression-precedence/input.js"
										end: Object {
											column: 37
											line: 1
										}
										start: Object {
											column: 27
											line: 1
										}
									}
									argument: JSAssignmentExpression {
										operator: "="
										loc: Object {
											filename: "esprima/es2015-yield/yield-expression-precedence/input.js"
											end: Object {
												column: 37
												line: 1
											}
											start: Object {
												column: 34
												line: 1
											}
										}
										left: JSAssignmentIdentifier {
											name: "c"
											loc: Object {
												filename: "esprima/es2015-yield/yield-expression-precedence/input.js"
												identifierName: "c"
												end: Object {
													column: 35
													line: 1
												}
												start: Object {
													column: 34
													line: 1
												}
											}
										}
										right: JSReferenceIdentifier {
											name: "d"
											loc: Object {
												filename: "esprima/es2015-yield/yield-expression-precedence/input.js"
												identifierName: "d"
												end: Object {
													column: 37
													line: 1
												}
												start: Object {
													column: 36
													line: 1
												}
											}
										}
									}
								}
								JSReferenceIdentifier {
									name: "e"
									loc: Object {
										filename: "esprima/es2015-yield/yield-expression-precedence/input.js"
										identifierName: "e"
										end: Object {
											column: 40
											line: 1
										}
										start: Object {
											column: 39
											line: 1
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