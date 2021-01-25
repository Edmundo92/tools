# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/css-parser/index.test.ts --update-snapshots` to update.

## `values`

```javascript
CSSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	filename: "values/input.css"
	integrity: undefined
	loc: Object {
		filename: "values/input.css"
		end: Object {
			column: 1
			line: 10
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		CSSRule {
			loc: Object {
				filename: "values/input.css"
				end: Object {
					column: 1
					line: 3
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			prelude: Array [
				CSSSelector {
					loc: Object {
						filename: "values/input.css"
						end: Object {
							column: 10
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
					patterns: Array [
						CSSTypeSelector {
							value: "p"
							loc: Object {
								filename: "values/input.css"
								end: Object {
									column: 1
									line: 1
								}
								start: Object {
									column: 0
									line: 1
								}
							}
						}
						CSSPseudoElementSelector {
							value: "before"
							loc: Object {
								filename: "values/input.css"
								end: Object {
									column: 9
									line: 1
								}
								start: Object {
									column: 1
									line: 1
								}
							}
						}
					]
				}
			]
			block: CSSBlock {
				value: Array [
					CSSDeclaration {
						name: "content"
						value: Array [
							CSSString {
								value: " content "
								loc: Object {
									filename: "values/input.css"
									end: Object {
										column: 21
										line: 2
									}
									start: Object {
										column: 10
										line: 2
									}
								}
							}
						]
						important: false
						loc: Object {
							filename: "values/input.css"
							end: Object {
								column: 21
								line: 2
							}
							start: Object {
								column: 1
								line: 2
							}
						}
					}
				]
				startingTokenValue: "{"
				loc: Object {
					filename: "values/input.css"
					end: Object {
						column: 1
						line: 3
					}
					start: Object {
						column: 10
						line: 1
					}
				}
			}
		}
		CSSRule {
			loc: Object {
				filename: "values/input.css"
				end: Object {
					column: 1
					line: 10
				}
				start: Object {
					column: 0
					line: 5
				}
			}
			prelude: Array [
				CSSSelector {
					loc: Object {
						filename: "values/input.css"
						end: Object {
							column: 8
							line: 5
						}
						start: Object {
							column: 0
							line: 5
						}
					}
					patterns: Array [
						CSSClassSelector {
							value: "number"
							loc: Object {
								filename: "values/input.css"
								end: Object {
									column: 7
									line: 5
								}
								start: Object {
									column: 0
									line: 5
								}
							}
						}
					]
				}
			]
			block: CSSBlock {
				value: Array [
					CSSDeclaration {
						name: "opacity"
						value: Array [
							CSSNumber {
								value: 0.001
								raw: "1e-3"
								loc: Object {
									filename: "values/input.css"
									end: Object {
										column: 14
										line: 6
									}
									start: Object {
										column: 10
										line: 6
									}
								}
							}
						]
						important: false
						loc: Object {
							filename: "values/input.css"
							end: Object {
								column: 14
								line: 6
							}
							start: Object {
								column: 1
								line: 6
							}
						}
					}
					CSSDeclaration {
						name: "line-height"
						value: Array [
							CSSNumber {
								value: 0.2
								raw: "0.2"
								loc: Object {
									filename: "values/input.css"
									end: Object {
										column: 17
										line: 7
									}
									start: Object {
										column: 14
										line: 7
									}
								}
							}
						]
						important: false
						loc: Object {
							filename: "values/input.css"
							end: Object {
								column: 17
								line: 7
							}
							start: Object {
								column: 1
								line: 7
							}
						}
					}
					CSSDeclaration {
						name: "width"
						value: Array [
							CSSPercentage {
								value: 20
								loc: Object {
									filename: "values/input.css"
									end: Object {
										column: 11
										line: 8
									}
									start: Object {
										column: 8
										line: 8
									}
								}
							}
						]
						important: false
						loc: Object {
							filename: "values/input.css"
							end: Object {
								column: 11
								line: 8
							}
							start: Object {
								column: 1
								line: 8
							}
						}
					}
					CSSDeclaration {
						name: "margin-top"
						value: Array [
							CSSPercentage {
								value: -5
								loc: Object {
									filename: "values/input.css"
									end: Object {
										column: 16
										line: 9
									}
									start: Object {
										column: 13
										line: 9
									}
								}
							}
						]
						important: false
						loc: Object {
							filename: "values/input.css"
							end: Object {
								column: 16
								line: 9
							}
							start: Object {
								column: 1
								line: 9
							}
						}
					}
				]
				startingTokenValue: "{"
				loc: Object {
					filename: "values/input.css"
					end: Object {
						column: 1
						line: 10
					}
					start: Object {
						column: 8
						line: 5
					}
				}
			}
		}
	]
}
```