# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > arrow-function > destructuring`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: true
	directives: Array []
	filename: "typescript/arrow-function/destructuring/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/arrow-function/destructuring/input.ts"
		end: Object {
			column: 0
			line: 2
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
						RAW_MARKUP {value: "Unexpected token, expected "}
						","
					]
				}
			}
			location: Object {
				filename: "typescript/arrow-function/destructuring/input.ts"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 6
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
		JSExpressionStatement {
			loc: Object {
				filename: "typescript/arrow-function/destructuring/input.ts"
				end: Object {
					column: 8
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
					filename: "typescript/arrow-function/destructuring/input.ts"
					end: Object {
						column: 8
						line: 1
					}
					start: Object {
						column: 1
						line: 1
					}
				}
				right: JSNumericLiteral {
					value: 0
					format: undefined
					loc: Object {
						filename: "typescript/arrow-function/destructuring/input.ts"
						end: Object {
							column: 8
							line: 1
						}
						start: Object {
							column: 7
							line: 1
						}
					}
				}
				left: JSAssignmentObjectPattern {
					rest: undefined
					loc: Object {
						filename: "typescript/arrow-function/destructuring/input.ts"
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
										filename: "typescript/arrow-function/destructuring/input.ts"
										identifierName: "a"
										end: Object {
											column: 4
											line: 1
										}
										start: Object {
											column: 3
											line: 1
										}
									}
								}
								loc: Object {
									filename: "typescript/arrow-function/destructuring/input.ts"
									end: Object {
										column: 4
										line: 1
									}
									start: Object {
										column: 3
										line: 1
									}
								}
							}
							value: JSAssignmentIdentifier {
								name: "a"
								loc: Object {
									filename: "typescript/arrow-function/destructuring/input.ts"
									identifierName: "a"
									end: Object {
										column: 4
										line: 1
									}
									start: Object {
										column: 3
										line: 1
									}
								}
							}
							loc: Object {
								filename: "typescript/arrow-function/destructuring/input.ts"
								end: Object {
									column: 4
									line: 1
								}
								start: Object {
									column: 3
									line: 1
								}
							}
						}
					]
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "typescript/arrow-function/destructuring/input.ts"
				end: Object {
					column: 10
					line: 1
				}
				start: Object {
					column: 9
					line: 1
				}
			}
			expression: JSReferenceIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: Object {
					filename: "typescript/arrow-function/destructuring/input.ts"
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
		}
		JSExpressionStatement {
			loc: Object {
				filename: "typescript/arrow-function/destructuring/input.ts"
				end: Object {
					column: 11
					line: 1
				}
				start: Object {
					column: 10
					line: 1
				}
			}
			expression: JSReferenceIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: Object {
					filename: "typescript/arrow-function/destructuring/input.ts"
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
		}
		JSExpressionStatement {
			loc: Object {
				filename: "typescript/arrow-function/destructuring/input.ts"
				end: Object {
					column: 14
					line: 1
				}
				start: Object {
					column: 12
					line: 1
				}
			}
			expression: JSReferenceIdentifier {
				name: "INVALID_PLACEHOLDER"
				loc: Object {
					filename: "typescript/arrow-function/destructuring/input.ts"
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
		}
		JSExpressionStatement {
			loc: Object {
				filename: "typescript/arrow-function/destructuring/input.ts"
				end: Object {
					column: 17
					line: 1
				}
				start: Object {
					column: 15
					line: 1
				}
			}
			expression: JSNumericLiteral {
				value: 0
				format: undefined
				loc: Object {
					filename: "typescript/arrow-function/destructuring/input.ts"
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
		}
	]
}
```

### `diagnostics`

```

 typescript/arrow-function/destructuring/input.ts:1:5 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unexpected token, expected ,

    ({ a = 0 }) => 0;
         ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
