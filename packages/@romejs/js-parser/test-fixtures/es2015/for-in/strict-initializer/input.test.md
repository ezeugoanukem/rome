# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > for-in > strict-initializer`

```javascript
Program {
  comments: Array []
  corrupt: false
  filename: 'input.js'
  hasHoistedVars: true
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 22
      index: 36
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  directives: Array [
    Directive {
      value: 'use strict'
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 13
          index: 13
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
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Loop variable declaration may not have an initializer'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 14
          index: 28
          line: 2
        }
        start: Object {
          column: 5
          index: 19
          line: 2
        }
      }
    }
  ]
  body: Array [
    ForInStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 22
          index: 36
          line: 2
        }
        start: Object {
          column: 0
          index: 14
          line: 2
        }
      }
      body: EmptyStatement {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 22
            index: 36
            line: 2
          }
          start: Object {
            column: 21
            index: 35
            line: 2
          }
        }
      }
      right: ObjectExpression {
        properties: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 20
            index: 34
            line: 2
          }
          start: Object {
            column: 18
            index: 32
            line: 2
          }
        }
      }
      left: VariableDeclaration {
        kind: 'var'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 14
            index: 28
            line: 2
          }
          start: Object {
            column: 5
            index: 19
            line: 2
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingIdentifier {
              name: 'a'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 10
                  index: 24
                  line: 2
                }
                start: Object {
                  column: 9
                  index: 23
                  line: 2
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 14
                index: 28
                line: 2
              }
              start: Object {
                column: 9
                index: 23
                line: 2
              }
            }
            init: NumericLiteral {
              value: 0
              format: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 14
                  index: 28
                  line: 2
                }
                start: Object {
                  column: 13
                  index: 27
                  line: 2
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