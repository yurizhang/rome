# `suppressions.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-compiler/suppressions.test.ts --update-snapshots` to update.

## `duplicates`

```javascript
Object {
  diagnostics: Array [
    Object {
      category: 'suppressions/duplicate'
      filename: 'unknown'
      message: 'Duplicate suppression category <emphasis>foo</emphasis>'
      end: Object {
        column: 0
        index: 0
        line: 1
      }
      start: Object {
        column: 0
        index: 0
        line: 1
      }
    }
  ]
  suppressions: Array [
    Object {
      category: 'foo'
      loc: Object {
        filename: 'unknown'
        end: Object {
          column: 0
          index: 0
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
    }
  ]
}
```

## `multiple categories`

```javascript
Object {
  diagnostics: Array []
  suppressions: Array [
    Object {
      category: 'foo'
      loc: Object {
        filename: 'unknown'
        end: Object {
          column: 0
          index: 0
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
    }
    Object {
      category: 'bar'
      loc: Object {
        filename: 'unknown'
        end: Object {
          column: 0
          index: 0
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
    }
    Object {
      category: 'foo'
      loc: Object {
        filename: 'unknown'
        end: Object {
          column: 0
          index: 0
          line: 2
        }
        start: Object {
          column: 0
          index: 0
          line: 2
        }
      }
    }
    Object {
      category: 'bar'
      loc: Object {
        filename: 'unknown'
        end: Object {
          column: 0
          index: 0
          line: 2
        }
        start: Object {
          column: 0
          index: 0
          line: 2
        }
      }
    }
    Object {
      category: 'foo'
      loc: Object {
        filename: 'unknown'
        end: Object {
          column: 0
          index: 0
          line: 3
        }
        start: Object {
          column: 0
          index: 0
          line: 3
        }
      }
    }
    Object {
      category: 'bar'
      loc: Object {
        filename: 'unknown'
        end: Object {
          column: 0
          index: 0
          line: 3
        }
        start: Object {
          column: 0
          index: 0
          line: 3
        }
      }
    }
    Object {
      category: 'foo'
      loc: Object {
        filename: 'unknown'
        end: Object {
          column: 0
          index: 0
          line: 4
        }
        start: Object {
          column: 0
          index: 0
          line: 4
        }
      }
    }
    Object {
      category: 'bar'
      loc: Object {
        filename: 'unknown'
        end: Object {
          column: 0
          index: 0
          line: 4
        }
        start: Object {
          column: 0
          index: 0
          line: 4
        }
      }
    }
    Object {
      category: 'cat'
      loc: Object {
        filename: 'unknown'
        end: Object {
          column: 0
          index: 0
          line: 4
        }
        start: Object {
          column: 0
          index: 0
          line: 4
        }
      }
    }
    Object {
      category: 'dog'
      loc: Object {
        filename: 'unknown'
        end: Object {
          column: 0
          index: 0
          line: 4
        }
        start: Object {
          column: 0
          index: 0
          line: 4
        }
      }
    }
  ]
}
```

## `single category`

```javascript
Object {
  diagnostics: Array []
  suppressions: Array [
    Object {
      category: 'foo'
      loc: Object {
        filename: 'unknown'
        end: Object {
          column: 0
          index: 0
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
    }
    Object {
      category: 'foo'
      loc: Object {
        filename: 'unknown'
        end: Object {
          column: 0
          index: 0
          line: 2
        }
        start: Object {
          column: 0
          index: 0
          line: 2
        }
      }
    }
    Object {
      category: 'foo'
      loc: Object {
        filename: 'unknown'
        end: Object {
          column: 0
          index: 0
          line: 3
        }
        start: Object {
          column: 0
          index: 0
          line: 3
        }
      }
    }
    Object {
      category: 'foo'
      loc: Object {
        filename: 'unknown'
        end: Object {
          column: 0
          index: 0
          line: 4
        }
        start: Object {
          column: 0
          index: 0
          line: 4
        }
      }
    }
  ]
}
```

## `typos`

```javascript
Object {
  suppressions: Array []
  diagnostics: Array [
    Object {
      category: 'suppressions/incorrectPrefix'
      filename: 'unknown'
      message: 'Invalid suppression prefix <emphasis>rome-ignore</emphasis>'
      end: Object {
        column: 0
        index: 0
        line: 1
      }
      start: Object {
        column: 0
        index: 0
        line: 1
      }
      advice: Array [
        log {
          category: 'info'
          message: 'Did you mean <emphasis>rome-suppress</emphasis>?'
        }
      ]
    }
  ]
}
```