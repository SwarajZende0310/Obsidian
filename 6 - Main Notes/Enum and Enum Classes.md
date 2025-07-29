2025-07-23 15:12

Status: [[Adult]]

Tags: [[C++]]

## Enum and Enum Classes

Enum classes are stringly typed and scoped which is better than normal enums.
Use normal enums only in case for C APIs.

| Feature                    | `enum`                      | `enum class`            |
| -------------------------- | --------------------------- | ----------------------- |
| Scope                      | Unscoped                    | Scoped                  |
| Enum value access          | `LEFT`, `RIGHT`             | `Direction::LEFT`, etc. |
| Implicit conversion to int | Yes                         | No                      |
| Type safety                | Low                         | High                    |
| Risk of name collision     | High                        | None (scoped)           |
| Usage in modern C++        | Discouraged (unless needed) | Recommended             |

## References
1. https://en.cppreference.com/w/cpp/language/enum.html



---

