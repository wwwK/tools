# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > class-private-names-duplicated > static-get-instance-set`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
		end: Object {
			column: 1
			line: 4
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "A"
				loc: Object {
					filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
					identifierName: "A"
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
			loc: Object {
				filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
				end: Object {
					column: 1
					line: 4
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
					filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
					end: Object {
						column: 1
						line: 4
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				body: Array [
					JSClassPrivateMethod {
						kind: "get"
						key: JSPrivateName {
							id: JSIdentifier {
								name: "x"
								loc: Object {
									filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
									identifierName: "x"
									end: Object {
										column: 15
										line: 2
									}
									start: Object {
										column: 14
										line: 2
									}
								}
							}
							loc: Object {
								filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
								end: Object {
									column: 15
									line: 2
								}
								start: Object {
									column: 13
									line: 2
								}
							}
						}
						loc: Object {
							filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
							end: Object {
								column: 20
								line: 2
							}
							start: Object {
								column: 2
								line: 2
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
								end: Object {
									column: 20
									line: 2
								}
								start: Object {
									column: 18
									line: 2
								}
							}
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: Array []
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
								end: Object {
									column: 17
									line: 2
								}
								start: Object {
									column: 15
									line: 2
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 2
								line: 2
							}
							loc: Object {
								filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
								end: Object {
									column: 15
									line: 2
								}
								start: Object {
									column: 2
									line: 2
								}
							}
						}
					}
					JSClassPrivateMethod {
						kind: "set"
						key: JSPrivateName {
							id: JSIdentifier {
								name: "x"
								loc: Object {
									filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
									identifierName: "x"
									end: Object {
										column: 8
										line: 3
									}
									start: Object {
										column: 7
										line: 3
									}
								}
							}
							loc: Object {
								filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
								end: Object {
									column: 8
									line: 3
								}
								start: Object {
									column: 6
									line: 3
								}
							}
						}
						loc: Object {
							filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
							end: Object {
								column: 14
								line: 3
							}
							start: Object {
								column: 2
								line: 3
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
								end: Object {
									column: 14
									line: 3
								}
								start: Object {
									column: 12
									line: 3
								}
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
								column: 2
								line: 3
							}
							loc: Object {
								filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
								end: Object {
									column: 8
									line: 3
								}
								start: Object {
									column: 2
									line: 3
								}
							}
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
								end: Object {
									column: 11
									line: 3
								}
								start: Object {
									column: 8
									line: 3
								}
							}
							params: Array [
								JSBindingIdentifier {
									name: "_"
									loc: Object {
										filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
										identifierName: "_"
										end: Object {
											column: 10
											line: 3
										}
										start: Object {
											column: 9
											line: 3
										}
									}
									meta: JSPatternMeta {
										optional: undefined
										typeAnnotation: undefined
										loc: Object {
											filename: "experimental/class-private-names-duplicated/static-get-instance-set/input.js"
											end: Object {
												column: 10
												line: 3
											}
											start: Object {
												column: 9
												line: 3
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
