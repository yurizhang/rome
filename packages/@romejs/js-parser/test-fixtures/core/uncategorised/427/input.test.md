# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 427`

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
      column: 32
      index: 32
      line: 1
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Multiple default clauses'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 22
          index: 22
          line: 1
        }
        start: Object {
          column: 22
          index: 22
          line: 1
        }
      }
    }
  ]
  body: Array [
    SwitchStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 32
          index: 32
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      discriminant: ReferenceIdentifier {
        name: 'c'
        loc: Object {
          filename: 'input.js'
          identifierName: 'c'
          end: Object {
            column: 9
            index: 9
            line: 1
          }
          start: Object {
            column: 8
            index: 8
            line: 1
          }
        }
      }
      cases: Array [
        SwitchCase {
          consequent: Array []
          test: undefined
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
        SwitchCase {
          consequent: Array []
          test: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 30
              index: 30
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
  ]
}
```
