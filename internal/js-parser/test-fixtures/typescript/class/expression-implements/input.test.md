# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > class > expression-implements`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/class/expression-implements/input.ts"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/class/expression-implements/input.ts"
		end: Object {
			column: 0
			line: 3
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "typescript/class/expression-implements/input.ts"
				end: Object {
					column: 29
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSClassExpression {
				id: undefined
				loc: Object {
					filename: "typescript/class/expression-implements/input.ts"
					end: Object {
						column: 27
						line: 1
					}
					start: Object {
						column: 1
						line: 1
					}
				}
				meta: JSClassHead {
					body: Array []
					superClass: undefined
					superTypeParameters: undefined
					typeParameters: undefined
					loc: Object {
						filename: "typescript/class/expression-implements/input.ts"
						end: Object {
							column: 27
							line: 1
						}
						start: Object {
							column: 1
							line: 1
						}
					}
					implements: Array [
						TSExpressionWithTypeArguments {
							loc: Object {
								filename: "typescript/class/expression-implements/input.ts"
								end: Object {
									column: 24
									line: 1
								}
								start: Object {
									column: 18
									line: 1
								}
							}
							expression: TSQualifiedName {
								loc: Object {
									filename: "typescript/class/expression-implements/input.ts"
									end: Object {
										column: 21
										line: 1
									}
									start: Object {
										column: 18
										line: 1
									}
								}
								left: JSReferenceIdentifier {
									name: "X"
									loc: Object {
										filename: "typescript/class/expression-implements/input.ts"
										identifierName: "X"
										end: Object {
											column: 19
											line: 1
										}
										start: Object {
											column: 18
											line: 1
										}
									}
								}
								right: JSIdentifier {
									name: "Y"
									loc: Object {
										filename: "typescript/class/expression-implements/input.ts"
										identifierName: "Y"
										end: Object {
											column: 21
											line: 1
										}
										start: Object {
											column: 20
											line: 1
										}
									}
								}
							}
							typeParameters: TSTypeParameterInstantiation {
								loc: Object {
									filename: "typescript/class/expression-implements/input.ts"
									end: Object {
										column: 24
										line: 1
									}
									start: Object {
										column: 21
										line: 1
									}
								}
								params: Array [
									TSTypeReference {
										typeParameters: undefined
										loc: Object {
											filename: "typescript/class/expression-implements/input.ts"
											end: Object {
												column: 23
												line: 1
											}
											start: Object {
												column: 22
												line: 1
											}
										}
										typeName: JSReferenceIdentifier {
											name: "T"
											loc: Object {
												filename: "typescript/class/expression-implements/input.ts"
												identifierName: "T"
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
									}
								]
							}
						}
					]
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "typescript/class/expression-implements/input.ts"
				end: Object {
					column: 31
					line: 2
				}
				start: Object {
					column: 0
					line: 2
				}
			}
			expression: JSClassExpression {
				id: JSBindingIdentifier {
					name: "C"
					loc: Object {
						filename: "typescript/class/expression-implements/input.ts"
						identifierName: "C"
						end: Object {
							column: 8
							line: 2
						}
						start: Object {
							column: 7
							line: 2
						}
					}
				}
				loc: Object {
					filename: "typescript/class/expression-implements/input.ts"
					end: Object {
						column: 29
						line: 2
					}
					start: Object {
						column: 1
						line: 2
					}
				}
				meta: JSClassHead {
					body: Array []
					superClass: undefined
					superTypeParameters: undefined
					typeParameters: undefined
					loc: Object {
						filename: "typescript/class/expression-implements/input.ts"
						end: Object {
							column: 29
							line: 2
						}
						start: Object {
							column: 1
							line: 2
						}
					}
					implements: Array [
						TSExpressionWithTypeArguments {
							loc: Object {
								filename: "typescript/class/expression-implements/input.ts"
								end: Object {
									column: 26
									line: 2
								}
								start: Object {
									column: 20
									line: 2
								}
							}
							expression: TSQualifiedName {
								loc: Object {
									filename: "typescript/class/expression-implements/input.ts"
									end: Object {
										column: 23
										line: 2
									}
									start: Object {
										column: 20
										line: 2
									}
								}
								left: JSReferenceIdentifier {
									name: "X"
									loc: Object {
										filename: "typescript/class/expression-implements/input.ts"
										identifierName: "X"
										end: Object {
											column: 21
											line: 2
										}
										start: Object {
											column: 20
											line: 2
										}
									}
								}
								right: JSIdentifier {
									name: "Y"
									loc: Object {
										filename: "typescript/class/expression-implements/input.ts"
										identifierName: "Y"
										end: Object {
											column: 23
											line: 2
										}
										start: Object {
											column: 22
											line: 2
										}
									}
								}
							}
							typeParameters: TSTypeParameterInstantiation {
								loc: Object {
									filename: "typescript/class/expression-implements/input.ts"
									end: Object {
										column: 26
										line: 2
									}
									start: Object {
										column: 23
										line: 2
									}
								}
								params: Array [
									TSTypeReference {
										typeParameters: undefined
										loc: Object {
											filename: "typescript/class/expression-implements/input.ts"
											end: Object {
												column: 25
												line: 2
											}
											start: Object {
												column: 24
												line: 2
											}
										}
										typeName: JSReferenceIdentifier {
											name: "T"
											loc: Object {
												filename: "typescript/class/expression-implements/input.ts"
												identifierName: "T"
												end: Object {
													column: 25
													line: 2
												}
												start: Object {
													column: 24
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
