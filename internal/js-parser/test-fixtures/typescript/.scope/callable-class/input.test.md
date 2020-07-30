# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > scope > callable-class`

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
			index: 37
			line: 3
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "C"
				loc: Object {
					filename: "input.ts"
					identifierName: "C"
					end: Object {
						column: 15
						index: 15
						line: 1
					}
					start: Object {
						column: 14
						index: 14
						line: 1
					}
				}
			}
			declare: true
			loc: Object {
				filename: "input.ts"
				end: Object {
					column: 19
					index: 19
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			meta: JSClassHead {
				body: Array []
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "input.ts"
					end: Object {
						column: 19
						index: 19
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
			}
		}
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "C"
				loc: Object {
					filename: "input.ts"
					identifierName: "C"
					end: Object {
						column: 10
						index: 30
						line: 2
					}
					start: Object {
						column: 9
						index: 29
						line: 2
					}
				}
			}
			loc: Object {
				filename: "input.ts"
				end: Object {
					column: 16
					index: 36
					line: 2
				}
				start: Object {
					column: 0
					index: 20
					line: 2
				}
			}
			body: JSBlockStatement {
				body: Array []
				directives: Array []
				loc: Object {
					filename: "input.ts"
					end: Object {
						column: 16
						index: 36
						line: 2
					}
					start: Object {
						column: 13
						index: 33
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
					filename: "input.ts"
					end: Object {
						column: 12
						index: 32
						line: 2
					}
					start: Object {
						column: 10
						index: 30
						line: 2
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