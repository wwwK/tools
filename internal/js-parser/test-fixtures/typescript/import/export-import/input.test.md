# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > import > export-import`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/import/export-import/input.ts"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/import/export-import/input.ts"
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
		TSImportEqualsDeclaration {
			id: JSBindingIdentifier {
				name: "A"
				loc: Object {
					filename: "typescript/import/export-import/input.ts"
					identifierName: "A"
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
			isExport: true
			loc: Object {
				filename: "typescript/import/export-import/input.ts"
				end: Object {
					column: 22
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			moduleReference: TSQualifiedName {
				loc: Object {
					filename: "typescript/import/export-import/input.ts"
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
					name: "B"
					loc: Object {
						filename: "typescript/import/export-import/input.ts"
						identifierName: "B"
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
					name: "C"
					loc: Object {
						filename: "typescript/import/export-import/input.ts"
						identifierName: "C"
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
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
