# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 417`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: true
	directives: Array []
	filename: "core/uncategorised/417/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "core/uncategorised/417/input.js"
		end: Object {
			column: 18
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {
					parts: Array [
						RAW_MARKUP {value: "Invalid left-hand side in "}
						"for-in statement"
					]
				}
			}
			location: Object {
				filename: "core/uncategorised/417/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 10
					line: 1
				}
				start: Object {
					column: 5
					line: 1
				}
			}
		}
	]
	body: Array [
		JSForInStatement {
			loc: Object {
				filename: "core/uncategorised/417/input.js"
				end: Object {
					column: 18
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			body: JSEmptyStatement {
				loc: Object {
					filename: "core/uncategorised/417/input.js"
					end: Object {
						column: 18
						line: 1
					}
					start: Object {
						column: 17
						line: 1
					}
				}
			}
			left: JSAssignmentIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: Object {
					filename: "core/uncategorised/417/input.js"
					end: Object {
						column: 10
						line: 1
					}
					start: Object {
						column: 11
						line: 1
					}
				}
			}
			right: JSObjectExpression {
				properties: Array []
				loc: Object {
					filename: "core/uncategorised/417/input.js"
					end: Object {
						column: 16
						line: 1
					}
					start: Object {
						column: 14
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

 core/uncategorised/417/input.js:1:5 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Invalid left-hand side in for-in statement

    for (i + 1 in {});
         ^^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
