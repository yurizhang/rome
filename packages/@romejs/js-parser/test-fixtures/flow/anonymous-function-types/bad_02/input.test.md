# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > anonymous-function-types > bad_02`

```javascript
Program {
  comments: Array []
  corrupt: true
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: true
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 46
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
        sourceType: 'module'
        end: Object {
          column: 37
          index: 37
          line: 1
        }
        start: Object {
          column: 38
          index: 38
          line: 1
        }
      }
    }
  ]
  body: Array [
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 37
          index: 37
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: VariableDeclaration {
        kind: 'var'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 37
            index: 37
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingIdentifier {
              name: 'f'
              loc: Object {
                filename: 'input.js'
                identifierName: 'f'
                end: Object {
                  column: 5
                  index: 5
                  line: 1
                }
                start: Object {
                  column: 4
                  index: 4
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 37
                index: 37
                line: 1
              }
              start: Object {
                column: 4
                index: 4
                line: 1
              }
            }
            init: ArrowFunctionExpression {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 37
                  index: 37
                  line: 1
                }
                start: Object {
                  column: 8
                  index: 8
                  line: 1
                }
              }
              body: NumericLiteral {
                value: 123
                format: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 37
                    index: 37
                    line: 1
                  }
                  start: Object {
                    column: 34
                    index: 34
                    line: 1
                  }
                }
              }
              head: FunctionHead {
                async: false
                hasHoistedVars: false
                predicate: undefined
                rest: undefined
                thisType: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 33
                    index: 33
                    line: 1
                  }
                  start: Object {
                    column: 8
                    index: 8
                    line: 1
                  }
                }
                params: Array [
                  BindingIdentifier {
                    name: 'x'
                    loc: Object {
                      filename: 'input.js'
                      identifierName: 'x'
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
                returnType: UnionTypeAnnotation {
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 30
                      index: 30
                      line: 1
                    }
                    start: Object {
                      column: 13
                      index: 13
                      line: 1
                    }
                  }
                  types: Array [
                    StringKeywordTypeAnnotation {
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 19
                          index: 19
                          line: 1
                        }
                        start: Object {
                          column: 13
                          index: 13
                          line: 1
                        }
                      }
                    }
                    NumberKeywordTypeAnnotation {
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 29
                          index: 29
                          line: 1
                        }
                        start: Object {
                          column: 23
                          index: 23
                          line: 1
                        }
                      }
                    }
                  ]
                }
              }
            }
          }
        ]
      }
    }
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 40
          index: 40
          line: 1
        }
        start: Object {
          column: 38
          index: 38
          line: 1
        }
      }
      expression: ReferenceIdentifier {
        name: 'INVALID_PLACEHOLDER'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 40
            index: 40
            line: 1
          }
          start: Object {
            column: 38
            index: 38
            line: 1
          }
        }
      }
    }
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 45
          index: 45
          line: 1
        }
        start: Object {
          column: 41
          index: 41
          line: 1
        }
      }
      expression: NumericLiteral {
        value: 123
        format: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 44
            index: 44
            line: 1
          }
          start: Object {
            column: 41
            index: 41
            line: 1
          }
        }
      }
    }
  ]
}
```
