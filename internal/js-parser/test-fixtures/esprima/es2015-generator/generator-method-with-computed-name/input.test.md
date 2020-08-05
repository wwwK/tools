# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-generator > generator-method-with-computed-name`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-generator/generator-method-with-computed-name/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-generator/generator-method-with-computed-name/input.js"
		end: Object {
			column: 0
			line: 4
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/es2015-generator/generator-method-with-computed-name/input.js"
				end: Object {
					column: 2
					line: 3
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSFunctionExpression {
				id: undefined
				loc: Object {
					filename: "esprima/es2015-generator/generator-method-with-computed-name/input.js"
					end: Object {
						column: 1
						line: 3
					}
					start: Object {
						column: 1
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
						filename: "esprima/es2015-generator/generator-method-with-computed-name/input.js"
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
				body: JSBlockStatement {
					directives: Array []
					loc: Object {
						filename: "esprima/es2015-generator/generator-method-with-computed-name/input.js"
						end: Object {
							column: 1
							line: 3
						}
						start: Object {
							column: 13
							line: 1
						}
					}
					body: Array [
						JSReturnStatement {
							loc: Object {
								filename: "esprima/es2015-generator/generator-method-with-computed-name/input.js"
								end: Object {
									column: 33
									line: 2
								}
								start: Object {
									column: 4
									line: 2
								}
							}
							argument: JSObjectExpression {
								loc: Object {
									filename: "esprima/es2015-generator/generator-method-with-computed-name/input.js"
									end: Object {
										column: 33
										line: 2
									}
									start: Object {
										column: 11
										line: 2
									}
								}
								properties: Array [
									JSObjectMethod {
										kind: "method"
										key: JSComputedPropertyKey {
											value: JSYieldExpression {
												delegate: false
												loc: Object {
													filename: "esprima/es2015-generator/generator-method-with-computed-name/input.js"
													end: Object {
														column: 25
														line: 2
													}
													start: Object {
														column: 15
														line: 2
													}
												}
												argument: JSReferenceIdentifier {
													name: "iter"
													loc: Object {
														filename: "esprima/es2015-generator/generator-method-with-computed-name/input.js"
														identifierName: "iter"
														end: Object {
															column: 25
															line: 2
														}
														start: Object {
															column: 21
															line: 2
														}
													}
												}
											}
											loc: Object {
												filename: "esprima/es2015-generator/generator-method-with-computed-name/input.js"
												end: Object {
													column: 26
													line: 2
												}
												start: Object {
													column: 14
													line: 2
												}
											}
										}
										loc: Object {
											filename: "esprima/es2015-generator/generator-method-with-computed-name/input.js"
											end: Object {
												column: 31
												line: 2
											}
											start: Object {
												column: 13
												line: 2
											}
										}
										body: JSBlockStatement {
											body: Array []
											directives: Array []
											loc: Object {
												filename: "esprima/es2015-generator/generator-method-with-computed-name/input.js"
												end: Object {
													column: 31
													line: 2
												}
												start: Object {
													column: 29
													line: 2
												}
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
												filename: "esprima/es2015-generator/generator-method-with-computed-name/input.js"
												end: Object {
													column: 28
													line: 2
												}
												start: Object {
													column: 26
													line: 2
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
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```