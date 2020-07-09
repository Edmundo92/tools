# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-for-of > for-of-object-pattern`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 0
			index: 19
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSForOfStatement {
			await: false
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 18
					index: 18
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			body: JSEmptyStatement {
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 18
						index: 18
						line: 1
					}
					start: Object {
						column: 17
						index: 17
						line: 1
					}
				}
			}
			right: JSReferenceIdentifier {
				name: "z"
				loc: Object {
					filename: "input.js"
					identifierName: "z"
					end: Object {
						column: 16
						index: 16
						line: 1
					}
					start: Object {
						column: 15
						index: 15
						line: 1
					}
				}
			}
			left: JSAssignmentObjectPattern {
				rest: undefined
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 11
						index: 11
						line: 1
					}
					start: Object {
						column: 5
						index: 5
						line: 1
					}
				}
				properties: Array [
					JSAssignmentObjectPatternProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "x"
								loc: Object {
									filename: "input.js"
									identifierName: "x"
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
							loc: Object {
								filename: "input.js"
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
						value: JSAssignmentIdentifier {
							name: "x"
							loc: Object {
								filename: "input.js"
								identifierName: "x"
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
						loc: Object {
							filename: "input.js"
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
					JSAssignmentObjectPatternProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "y"
								loc: Object {
									filename: "input.js"
									identifierName: "y"
									end: Object {
										column: 10
										index: 10
										line: 1
									}
									start: Object {
										column: 9
										index: 9
										line: 1
									}
								}
							}
							loc: Object {
								filename: "input.js"
								end: Object {
									column: 10
									index: 10
									line: 1
								}
								start: Object {
									column: 9
									index: 9
									line: 1
								}
							}
						}
						value: JSAssignmentIdentifier {
							name: "y"
							loc: Object {
								filename: "input.js"
								identifierName: "y"
								end: Object {
									column: 10
									index: 10
									line: 1
								}
								start: Object {
									column: 9
									index: 9
									line: 1
								}
							}
						}
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 10
								index: 10
								line: 1
							}
							start: Object {
								column: 9
								index: 9
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