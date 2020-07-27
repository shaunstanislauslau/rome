# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 357`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: true
	directives: Array []
	filename: "es2015/uncategorised/357/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "es2015/uncategorised/357/input.js"
		end: Object {
			column: 0
			index: 15
			line: 2
		}
		start: Object {
			column: 0
			index: 0
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
						RAW_MARKUP {value: "Unknown start to an "}
						"await argument"
					]
				}
			}
			location: Object {
				filename: "es2015/uncategorised/357/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 5
					index: 5
					line: 1
				}
				start: Object {
					column: 6
					index: 6
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2015/uncategorised/357/input.js"
				end: Object {
					column: 7
					index: 7
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSAwaitExpression {
				loc: Object {
					filename: "es2015/uncategorised/357/input.js"
					end: Object {
						column: 7
						index: 7
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				argument: JSReferenceIdentifier {
					name: "INVALID_PLACEHOLDER"
					loc: Object {
						filename: "es2015/uncategorised/357/input.js"
						end: Object {
							column: 7
							index: 7
							line: 1
						}
						start: Object {
							column: 6
							index: 6
							line: 1
						}
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "es2015/uncategorised/357/input.js"
				end: Object {
					column: 14
					index: 14
					line: 1
				}
				start: Object {
					column: 8
					index: 8
					line: 1
				}
			}
			expression: JSCallExpression {
				arguments: Array []
				loc: Object {
					filename: "es2015/uncategorised/357/input.js"
					end: Object {
						column: 13
						index: 13
						line: 1
					}
					start: Object {
						column: 8
						index: 8
						line: 1
					}
				}
				callee: JSReferenceIdentifier {
					name: "foo"
					loc: Object {
						filename: "es2015/uncategorised/357/input.js"
						identifierName: "foo"
						end: Object {
							column: 11
							index: 11
							line: 1
						}
						start: Object {
							column: 8
							index: 8
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

 es2015/uncategorised/357/input.js:1:6 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unknown start to an await argument

    await = foo();
          ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```