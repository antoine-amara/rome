# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > declare-module > 5`

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
      column: 55
      index: 55
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    FlowDeclareModule {
      id: BindingIdentifier {
        name: 'A'
        loc: Object {
          filename: 'input.js'
          identifierName: 'A'
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
      kind: 'commonjs'
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 55
          index: 55
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: BlockStatement {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 55
            index: 55
            line: 1
          }
          start: Object {
            column: 17
            index: 17
            line: 1
          }
        }
        body: Array [
          FlowDeclareClass {
            id: BindingIdentifier {
              name: 'B'
              loc: Object {
                filename: 'input.js'
                identifierName: 'B'
                end: Object {
                  column: 34
                  index: 34
                  line: 1
                }
                start: Object {
                  column: 33
                  index: 33
                  line: 1
                }
              }
            }
            extends: Array []
            implements: Array []
            mixins: Array []
            typeParameters: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 53
                index: 53
                line: 1
              }
              start: Object {
                column: 19
                index: 19
                line: 1
              }
            }
            body: FlowObjectTypeAnnotation {
              exact: false
              inexact: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 53
                  index: 53
                  line: 1
                }
                start: Object {
                  column: 35
                  index: 35
                  line: 1
                }
              }
              properties: Array [
                FlowObjectTypeProperty {
                  kind: 'init'
                  key: Identifier {
                    name: 'foo'
                    loc: Object {
                      filename: 'input.js'
                      identifierName: 'foo'
                      end: Object {
                        column: 40
                        index: 40
                        line: 1
                      }
                      start: Object {
                        column: 37
                        index: 37
                        line: 1
                      }
                    }
                  }
                  value: FlowFunctionTypeAnnotation {
                    params: Array []
                    rest: undefined
                    typeParameters: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 50
                        index: 50
                        line: 1
                      }
                      start: Object {
                        column: 37
                        index: 37
                        line: 1
                      }
                    }
                    returnType: NumberKeywordTypeAnnotation {
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 50
                          index: 50
                          line: 1
                        }
                        start: Object {
                          column: 44
                          index: 44
                          line: 1
                        }
                      }
                    }
                  }
                  optional: false
                  proto: false
                  static: false
                  variance: undefined
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 50
                      index: 50
                      line: 1
                    }
                    start: Object {
                      column: 37
                      index: 37
                      line: 1
                    }
                  }
                }
              ]
            }
          }
        ]
      }
    }
  ]
}
```
