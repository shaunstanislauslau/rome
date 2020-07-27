# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > scope > export-namespace`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "input.ts"
		end: Object {
			column: 0
			index: 30
			line: 4
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		TSModuleDeclaration {
			id: JSBindingIdentifier {
				name: "N"
				loc: Object {
					filename: "input.ts"
					identifierName: "N"
					end: Object {
						column: 11
						index: 11
						line: 1
					}
					start: Object {
						column: 10
						index: 10
						line: 1
					}
				}
			}
			loc: Object {
				filename: "input.ts"
				end: Object {
					column: 14
					index: 14
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			body: TSModuleBlock {
				body: Array []
				loc: Object {
					filename: "input.ts"
					end: Object {
						column: 14
						index: 14
						line: 1
					}
					start: Object {
						column: 12
						index: 12
						line: 1
					}
				}
			}
		}
		JSExportLocalDeclaration {
			declaration: undefined
			exportKind: "value"
			loc: Object {
				filename: "input.ts"
				end: Object {
					column: 13
					index: 29
					line: 3
				}
				start: Object {
					column: 0
					index: 16
					line: 3
				}
			}
			specifiers: Array [
				JSExportLocalSpecifier {
					loc: Object {
						filename: "input.ts"
						end: Object {
							column: 10
							index: 26
							line: 3
						}
						start: Object {
							column: 9
							index: 25
							line: 3
						}
					}
					exported: JSIdentifier {
						name: "N"
						loc: Object {
							filename: "input.ts"
							identifierName: "N"
							end: Object {
								column: 10
								index: 26
								line: 3
							}
							start: Object {
								column: 9
								index: 25
								line: 3
							}
						}
					}
					local: JSReferenceIdentifier {
						name: "N"
						loc: Object {
							filename: "input.ts"
							identifierName: "N"
							end: Object {
								column: 10
								index: 26
								line: 3
							}
							start: Object {
								column: 9
								index: 25
								line: 3
							}
						}
					}
				}
			]
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```