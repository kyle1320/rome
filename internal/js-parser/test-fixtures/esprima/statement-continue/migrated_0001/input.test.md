# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > statement-continue > migrated_0001`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/statement-continue/migrated_0001/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/statement-continue/migrated_0001/input.js"
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
		JSWhileStatement {
			loc: Object {
				filename: "esprima/statement-continue/migrated_0001/input.js"
				end: Object {
					column: 25
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			test: JSBooleanLiteral {
				value: true
				loc: Object {
					filename: "esprima/statement-continue/migrated_0001/input.js"
					end: Object {
						column: 11
						line: 1
					}
					start: Object {
						column: 7
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				directives: Array []
				loc: Object {
					filename: "esprima/statement-continue/migrated_0001/input.js"
					end: Object {
						column: 25
						line: 1
					}
					start: Object {
						column: 13
						line: 1
					}
				}
				body: Array [
					JSContinueStatement {
						label: undefined
						loc: Object {
							filename: "esprima/statement-continue/migrated_0001/input.js"
							end: Object {
								column: 23
								line: 1
							}
							start: Object {
								column: 15
								line: 1
							}
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
