# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 351`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 44
      index: 44
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 44
          index: 44
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: ObjectExpression {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 43
            index: 43
            line: 1
          }
          start: Object {
            column: 1
            index: 1
            line: 1
          }
        }
        properties: Array [
          ObjectMethod {
            kind: 'method'
            key: StaticPropertyKey {
              value: Identifier {
                name: '__proto__'
                loc: Object {
                  filename: 'input.js'
                  identifierName: '__proto__'
                  end: Object {
                    column: 12
                    index: 12
                    line: 1
                  }
                  start: Object {
                    column: 3
                    index: 3
                    line: 1
                  }
                }
              }
              variance: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 12
                  index: 12
                  line: 1
                }
                start: Object {
                  column: 3
                  index: 3
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 27
                index: 27
                line: 1
              }
              start: Object {
                column: 3
                index: 3
                line: 1
              }
            }
            head: FunctionHead {
              async: false
              generator: false
              hasHoistedVars: false
              params: Array []
              predicate: undefined
              rest: undefined
              returnType: undefined
              thisType: undefined
              typeParameters: undefined
              loc: Object {
                filename: 'input.js'
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
            body: BlockStatement {
              directives: Array []
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 27
                  index: 27
                  line: 1
                }
                start: Object {
                  column: 15
                  index: 15
                  line: 1
                }
              }
              body: Array [
                ReturnStatement {
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 25
                      index: 25
                      line: 1
                    }
                    start: Object {
                      column: 17
                      index: 17
                      line: 1
                    }
                  }
                  argument: NumericLiteral {
                    value: 1
                    format: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 25
                        index: 25
                        line: 1
                      }
                      start: Object {
                        column: 24
                        index: 24
                        line: 1
                      }
                    }
                  }
                }
              ]
            }
          }
          ObjectProperty {
            key: StaticPropertyKey {
              value: Identifier {
                name: '__proto__'
                loc: Object {
                  filename: 'input.js'
                  identifierName: '__proto__'
                  end: Object {
                    column: 38
                    index: 38
                    line: 1
                  }
                  start: Object {
                    column: 29
                    index: 29
                    line: 1
                  }
                }
              }
              variance: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 38
                  index: 38
                  line: 1
                }
                start: Object {
                  column: 29
                  index: 29
                  line: 1
                }
              }
            }
            value: NumericLiteral {
              value: 2
              format: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 41
                  index: 41
                  line: 1
                }
                start: Object {
                  column: 40
                  index: 40
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 41
                index: 41
                line: 1
              }
              start: Object {
                column: 29
                index: 29
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
