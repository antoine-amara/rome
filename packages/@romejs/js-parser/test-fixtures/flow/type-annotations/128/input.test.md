# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > type-annotations > 128`

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
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 41
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    TypeAliasTypeAnnotation {
      id: BindingIdentifier {
        name: 'A'
        loc: Object {
          filename: 'input.js'
          identifierName: 'A'
          end: Object {
            column: 6
            index: 6
            line: 1
          }
          start: Object {
            column: 5
            index: 5
            line: 1
          }
        }
      }
      typeParameters: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 40
          index: 40
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      right: FlowObjectTypeAnnotation {
        exact: false
        inexact: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 39
            index: 39
            line: 1
          }
          start: Object {
            column: 9
            index: 9
            line: 1
          }
        }
        properties: Array [
          FlowObjectTypeIndexer {
            id: undefined
            key: UnionTypeAnnotation {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 28
                  index: 28
                  line: 1
                }
                start: Object {
                  column: 12
                  index: 12
                  line: 1
                }
              }
              types: Array [
                StringKeywordTypeAnnotation {
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 18
                      index: 18
                      line: 1
                    }
                    start: Object {
                      column: 12
                      index: 12
                      line: 1
                    }
                  }
                }
                BooleanKeywordTypeAnnotation {
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 28
                      index: 28
                      line: 1
                    }
                    start: Object {
                      column: 21
                      index: 21
                      line: 1
                    }
                  }
                }
              ]
            }
            value: NumberKeywordTypeAnnotation {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 37
                  index: 37
                  line: 1
                }
                start: Object {
                  column: 31
                  index: 31
                  line: 1
                }
              }
            }
            static: false
            variance: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 37
                index: 37
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
      }
    }
  ]
}
```
