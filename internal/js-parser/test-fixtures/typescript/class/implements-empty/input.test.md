# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > class > implements-empty`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "typescript/class/implements-empty/input.ts"
	hasHoistedVars: false
	integrity: undefined
	interpreter: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/class/implements-empty/input.ts"
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
					"implements"
					RAW_MARKUP {value: " list cannot be empty"}
				]
			}
			location: Object {
				filename: "typescript/class/implements-empty/input.ts"
				integrity: undefined
				language: "js"
				sourceText: undefined
				end: Object {
					column: 21
					line: 1
				}
				start: Object {
					column: 21
					line: 1
				}
			}
		}
	]
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "Foo"
				loc: Object {
					filename: "typescript/class/implements-empty/input.ts"
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
				filename: "typescript/class/implements-empty/input.ts"
				end: Object {
					column: 1
					line: 2
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			meta: JSClassHead {
				body: Array []
				implements: Array []
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "typescript/class/implements-empty/input.ts"
					end: Object {
						column: 1
						line: 2
					}
					start: Object {
						column: 0
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

 typescript/class/implements-empty/input.ts:1:21 parse(js) ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ implements list cannot be empty

  > 1 │ class Foo implements {
      │                      ^
    2 │ }

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
