# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > async-functions > invalid-escape-sequence-function`

```javascript
Program {
  comments: Array []
  corrupt: false
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
      column: 0
      index: 34
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
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Expected a semicolon or a line terminator'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 10
          index: 10
          line: 1
        }
        start: Object {
          column: 11
          index: 11
          line: 1
        }
      }
    }
  ]
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 10
          index: 10
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: ReferenceIdentifier {
        name: 'async'
        loc: Object {
          filename: 'input.js'
          identifierName: 'async'
          end: Object {
            column: 10
            index: 10
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
    FunctionDeclaration {
      id: BindingIdentifier {
        name: ''
        loc: Object {
          filename: 'input.js'
          identifierName: ''
          end: Object {
            column: 20
            index: 20
            line: 1
          }
          start: Object {
            column: 19
            index: 19
            line: 1
          }
        }
      }
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 33
          index: 33
          line: 1
        }
        start: Object {
          column: 11
          index: 11
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
            column: 21
            index: 21
            line: 1
          }
          start: Object {
            column: 20
            index: 20
            line: 1
          }
        }
      }
      body: BlockStatement {
        directives: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 33
            index: 33
            line: 1
          }
          start: Object {
            column: 22
            index: 22
            line: 1
          }
        }
        body: Array [
          ExpressionStatement {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 29
                index: 29
                line: 1
              }
              start: Object {
                column: 24
                index: 24
                line: 1
              }
            }
            expression: ReferenceIdentifier {
              name: 'await'
              loc: Object {
                filename: 'input.js'
                identifierName: 'await'
                end: Object {
                  column: 29
                  index: 29
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
          ExpressionStatement {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 31
                index: 31
                line: 1
              }
              start: Object {
                column: 30
                index: 30
                line: 1
              }
            }
            expression: ReferenceIdentifier {
              name: 'x'
              loc: Object {
                filename: 'input.js'
                identifierName: 'x'
                end: Object {
                  column: 31
                  index: 31
                  line: 1
                }
                start: Object {
                  column: 30
                  index: 30
                  line: 1
                }
              }
            }
          }
        ]
      }
    }
  ]
}
```
