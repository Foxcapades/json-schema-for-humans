# Person

- [1. ![Optional](https://img.shields.io/badge/Optional-yellow) Property `Person > not_a_pattern`](#not_a_pattern)
  - [1.1. ![Optional](https://img.shields.io/badge/Optional-yellow) Pattern Property `Person > not_a_pattern > Title 4`](#not_a_pattern_pattern1)
- [2. ![Optional](https://img.shields.io/badge/Optional-yellow) Pattern Property `Person > Title 1`](#pattern1)
- [3. ![Optional](https://img.shields.io/badge/Optional-yellow) Pattern Property `Person > Title 2`](#pattern2)
- [4. ![Optional](https://img.shields.io/badge/Optional-yellow) Pattern Property `Person > Title 3`](#pattern3)

**Title:** Person

|                           |                                                                             |
| ------------------------- | --------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                    |
| **Additional properties** | ![Any type: allowed](https://img.shields.io/badge/Any%20type-allowed-green) |

| Property                           | Pattern | Type   | Deprecated | Definition | Title/Description |
| ---------------------------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| - [not_a_pattern](#not_a_pattern ) | No      | object | No         | -          | -                 |
| - [.*](#pattern1 )                 | Yes     | object | No         | -          | Title 1           |
| - [..](#pattern2 )                 | Yes     | object | No         | -          | Title 2           |
| - [^.](#pattern3 )                 | Yes     | object | No         | -          | Title 3           |

## <a name="not_a_pattern"></a>1. ![Optional](https://img.shields.io/badge/Optional-yellow) Property `Person > not_a_pattern`

|                           |                                                                             |
| ------------------------- | --------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                    |
| **Additional properties** | ![Any type: allowed](https://img.shields.io/badge/Any%20type-allowed-green) |

| Property                         | Pattern | Type   | Deprecated | Definition | Title/Description |
| -------------------------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| - [.$](#not_a_pattern_pattern1 ) | Yes     | object | No         | -          | Title 4           |

### <a name="not_a_pattern_pattern1"></a>1.1. ![Optional](https://img.shields.io/badge/Optional-yellow) Pattern Property `Person > not_a_pattern > Title 4`
> All properties whose name matches the regular expression
```.$``` ([Test](https://regex101.com/?regex=.%24))
must respect the following conditions

**Title:** Title 4

|                           |                                                                             |
| ------------------------- | --------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                    |
| **Additional properties** | ![Any type: allowed](https://img.shields.io/badge/Any%20type-allowed-green) |

**Description:** Description 4

## <a name="pattern1"></a>2. ![Optional](https://img.shields.io/badge/Optional-yellow) Pattern Property `Person > Title 1`
> All properties whose name matches the regular expression
```.*``` ([Test](https://regex101.com/?regex=.%2A))
must respect the following conditions

**Title:** Title 1

|                           |                                                                             |
| ------------------------- | --------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                    |
| **Additional properties** | ![Any type: allowed](https://img.shields.io/badge/Any%20type-allowed-green) |

**Description:** Description 1

## <a name="pattern2"></a>3. ![Optional](https://img.shields.io/badge/Optional-yellow) Pattern Property `Person > Title 2`
> All properties whose name matches the regular expression
```..``` ([Test](https://regex101.com/?regex=..))
must respect the following conditions

**Title:** Title 2

|                           |                                                                             |
| ------------------------- | --------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                    |
| **Additional properties** | ![Any type: allowed](https://img.shields.io/badge/Any%20type-allowed-green) |

**Description:** Description 2

## <a name="pattern3"></a>4. ![Optional](https://img.shields.io/badge/Optional-yellow) Pattern Property `Person > Title 3`
> All properties whose name matches the regular expression
```^.``` ([Test](https://regex101.com/?regex=%5E.))
must respect the following conditions

**Title:** Title 3

|                           |                                                                             |
| ------------------------- | --------------------------------------------------------------------------- |
| **Type**                  | `object`                                                                    |
| **Additional properties** | ![Any type: allowed](https://img.shields.io/badge/Any%20type-allowed-green) |

**Description:** Description 3

----------------------------------------------------------------------------------------------------------------------------
Generated using [json-schema-for-humans](https://github.com/coveooss/json-schema-for-humans)
