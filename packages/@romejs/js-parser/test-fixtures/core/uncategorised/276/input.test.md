# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 276`

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
      column: 21
      index: 21
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    TryStatement {
      finalizer: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 21
          index: 21
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      block: BlockStatement {
        body: Array []
        directives: Array []
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
      }
      handler: CatchClause {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 21
            index: 21
            line: 1
          }
          start: Object {
            column: 8
            index: 8
            line: 1
          }
        }
        body: BlockStatement {
          body: Array []
          directives: Array []
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 21
              index: 21
              line: 1
            }
            start: Object {
              column: 18
              index: 18
              line: 1
            }
          }
        }
        param: BindingIdentifier {
          name: 'e'
          loc: Object {
            filename: 'input.js'
            identifierName: 'e'
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
      }
    }
  ]
}
```
