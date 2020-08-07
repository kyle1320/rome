# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > destructuring > parenthesized-lhs-object`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "es2015/destructuring/parenthesized-lhs-object/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/destructuring/parenthesized-lhs-object/input.js"
		end: Object {
			column: 10
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
				message: MARKUP {parts: Array [RAW_MARKUP {value: "Invalid parenthesized binding"}]}
			}
			location: Object {
				filename: "es2015/destructuring/parenthesized-lhs-object/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 4
					line: 1
				}
				start: Object {
					column: 1
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2015/destructuring/parenthesized-lhs-object/input.js"
				end: Object {
					column: 10
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSAssignmentExpression {
				operator: "="
				loc: Object {
					filename: "es2015/destructuring/parenthesized-lhs-object/input.js"
					end: Object {
						column: 9
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				right: JSNumericLiteral {
					value: 2
					format: undefined
					loc: Object {
						filename: "es2015/destructuring/parenthesized-lhs-object/input.js"
						end: Object {
							column: 9
							line: 1
						}
						start: Object {
							column: 8
							line: 1
						}
					}
				}
				left: JSAssignmentObjectPattern {
					rest: undefined
					loc: Object {
						filename: "es2015/destructuring/parenthesized-lhs-object/input.js"
						end: Object {
							column: 4
							line: 1
						}
						start: Object {
							column: 1
							line: 1
						}
					}
					properties: Array [
						JSAssignmentObjectPatternProperty {
							key: JSStaticPropertyKey {
								value: JSIdentifier {
									name: "a"
									loc: Object {
										filename: "es2015/destructuring/parenthesized-lhs-object/input.js"
										identifierName: "a"
										end: Object {
											column: 3
											line: 1
										}
										start: Object {
											column: 2
											line: 1
										}
									}
								}
								loc: Object {
									filename: "es2015/destructuring/parenthesized-lhs-object/input.js"
									end: Object {
										column: 3
										line: 1
									}
									start: Object {
										column: 2
										line: 1
									}
								}
							}
							value: JSAssignmentIdentifier {
								name: "a"
								loc: Object {
									filename: "es2015/destructuring/parenthesized-lhs-object/input.js"
									identifierName: "a"
									end: Object {
										column: 3
										line: 1
									}
									start: Object {
										column: 2
										line: 1
									}
								}
							}
							loc: Object {
								filename: "es2015/destructuring/parenthesized-lhs-object/input.js"
								end: Object {
									column: 3
									line: 1
								}
								start: Object {
									column: 2
									line: 1
								}
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

 es2015/destructuring/parenthesized-lhs-object/input.js:1:1 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Invalid parenthesized binding

    ({a}) = 2;
     ^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```