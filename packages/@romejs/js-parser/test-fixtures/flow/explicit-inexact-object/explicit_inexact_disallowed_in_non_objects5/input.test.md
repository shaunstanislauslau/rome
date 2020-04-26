# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > explicit-inexact-object > explicit_inexact_disallowed_in_non_objects5`

```javascript
Program {
  corrupt: false
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
      index: 46
      line: 6
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  comments: Array [
    CommentLine {
      id: '0'
      value: '@flow'
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 7
          index: 7
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
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Spread operator cannot appear in class or interface definitions'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 14
          index: 36
          line: 3
        }
        start: Object {
          column: 2
          index: 39
          line: 4
        }
      }
    }
  ]
  body: Array [
    FlowInterfaceDeclaration {
      id: BindingIdentifier {
        name: 'F'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 11
            index: 19
            line: 2
          }
          start: Object {
            column: 10
            index: 18
            line: 2
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
          column: 1
          index: 45
          line: 5
        }
        start: Object {
          column: 0
          index: 8
          line: 2
        }
      }
      body: FlowObjectTypeAnnotation {
        exact: false
        inexact: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 1
            index: 45
            line: 5
          }
          start: Object {
            column: 12
            index: 20
            line: 2
          }
        }
        properties: Array [
          FlowObjectTypeProperty {
            kind: 'init'
            key: Identifier {
              name: 'foo'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 5
                  index: 27
                  line: 3
                }
                start: Object {
                  column: 2
                  index: 24
                  line: 3
                }
              }
            }
            value: NumberKeywordTypeAnnotation {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 13
                  index: 35
                  line: 3
                }
                start: Object {
                  column: 7
                  index: 29
                  line: 3
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
                column: 13
                index: 35
                line: 3
              }
              start: Object {
                column: 2
                index: 24
                line: 3
              }
            }
          }
          FlowObjectTypeSpreadProperty {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 6
                index: 43
                line: 4
              }
              start: Object {
                column: 2
                index: 39
                line: 4
              }
            }
            argument: MixedKeywordTypeAnnotation {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 6
                  index: 43
                  line: 4
                }
                start: Object {
                  column: 0
                  index: 44
                  line: 5
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