# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0051`

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
      index: 9
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Expecting Unicode escape sequence \\uXXXX'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 1
          index: 1
          line: 1
        }
        start: Object {
          column: 1
          index: 1
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
          column: 3
          index: 3
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: ReferenceIdentifier {
        name: '\0u'
        loc: Object {
          filename: 'input.js'
          identifierName: '\0u'
          end: Object {
            column: 3
            index: 3
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
    BlockStatement {
      directives: Array []
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 8
          index: 8
          line: 1
        }
        start: Object {
          column: 3
          index: 3
          line: 1
        }
      }
      body: Array [
        ExpressionStatement {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 7
              index: 7
              line: 1
            }
            start: Object {
              column: 4
              index: 4
              line: 1
            }
          }
          expression: ReferenceIdentifier {
            name: 'FFZ'
            loc: Object {
              filename: 'input.js'
              identifierName: 'FFZ'
              end: Object {
                column: 7
                index: 7
                line: 1
              }
              start: Object {
                column: 4
                index: 4
                line: 1
              }
            }
          }
        }
      ]
    }
  ]
}
```
