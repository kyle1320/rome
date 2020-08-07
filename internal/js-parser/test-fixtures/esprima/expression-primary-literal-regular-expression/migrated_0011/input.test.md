# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > expression-primary-literal-regular-expression > migrated_0011`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/expression-primary-literal-regular-expression/migrated_0011/input.js"
	hasHoistedVars: true
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/expression-primary-literal-regular-expression/migrated_0011/input.js"
		end: Object {
			column: 18
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "esprima/expression-primary-literal-regular-expression/migrated_0011/input.js"
				end: Object {
					column: 18
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "var"
				loc: Object {
					filename: "esprima/expression-primary-literal-regular-expression/migrated_0011/input.js"
					end: Object {
						column: 18
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "x"
							loc: Object {
								filename: "esprima/expression-primary-literal-regular-expression/migrated_0011/input.js"
								identifierName: "x"
								end: Object {
									column: 5
									line: 1
								}
								start: Object {
									column: 4
									line: 1
								}
							}
						}
						loc: Object {
							filename: "esprima/expression-primary-literal-regular-expression/migrated_0011/input.js"
							end: Object {
								column: 18
								line: 1
							}
							start: Object {
								column: 4
								line: 1
							}
						}
						init: JSRegExpLiteral {
							global: false
							insensitive: false
							multiline: false
							noDotNewline: false
							sticky: false
							unicode: false
							loc: Object {
								filename: "esprima/expression-primary-literal-regular-expression/migrated_0011/input.js"
								end: Object {
									column: 18
									line: 1
								}
								start: Object {
									column: 8
									line: 1
								}
							}
							expression: JSRegExpSubExpression {
								loc: Object {
									filename: "esprima/expression-primary-literal-regular-expression/migrated_0011/input.js"
									end: Object {
										column: 17
										line: 1
									}
									start: Object {
										column: 9
										line: 1
									}
								}
								body: Array [
									JSRegExpCharacter {
										value: "f"
										loc: Object {
											filename: "esprima/expression-primary-literal-regular-expression/migrated_0011/input.js"
											end: Object {
												column: 10
												line: 1
											}
											start: Object {
												column: 9
												line: 1
											}
										}
									}
									JSRegExpCharacter {
										value: "o"
										loc: Object {
											filename: "esprima/expression-primary-literal-regular-expression/migrated_0011/input.js"
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
									JSRegExpCharacter {
										value: "o"
										loc: Object {
											filename: "esprima/expression-primary-literal-regular-expression/migrated_0011/input.js"
											end: Object {
												column: 12
												line: 1
											}
											start: Object {
												column: 11
												line: 1
											}
										}
									}
									JSRegExpCharacter {
										value: "/"
										loc: Object {
											filename: "esprima/expression-primary-literal-regular-expression/migrated_0011/input.js"
											end: Object {
												column: 14
												line: 1
											}
											start: Object {
												column: 12
												line: 1
											}
										}
									}
									JSRegExpCharacter {
										value: "b"
										loc: Object {
											filename: "esprima/expression-primary-literal-regular-expression/migrated_0011/input.js"
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
									JSRegExpCharacter {
										value: "a"
										loc: Object {
											filename: "esprima/expression-primary-literal-regular-expression/migrated_0011/input.js"
											end: Object {
												column: 16
												line: 1
											}
											start: Object {
												column: 15
												line: 1
											}
										}
									}
									JSRegExpCharacter {
										value: "r"
										loc: Object {
											filename: "esprima/expression-primary-literal-regular-expression/migrated_0011/input.js"
											end: Object {
												column: 17
												line: 1
											}
											start: Object {
												column: 16
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
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```