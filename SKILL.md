# micronaut.core Skill

Use this skill to work with Norm module `micronaut.core` version 6. Use only declarations listed below.

## `micronaut.core`

Source: `JavaArrays.norm`

### `JavaIntrospected_AccessKindArray`

```norm
class JavaIntrospected_AccessKindArray
```

#### `JavaIntrospected_AccessKindArray`

```norm
JavaIntrospected_AccessKindArray(JavaIntrospected_AccessKindArrayBindingToken token)
```

Parameters:

- `token`: `JavaIntrospected_AccessKindArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
IntrospectedAccessKind? get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `IntrospectedAccessKind?`

#### `set`

```norm
Void set(Integer index, IntrospectedAccessKind? value)
```

Parameters:

- `index`: `Integer`
- `value`: `IntrospectedAccessKind?`

Returns: `Void`

### `javaIntrospected_AccessKindArrayNew`

```norm
JavaIntrospected_AccessKindArray javaIntrospected_AccessKindArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaIntrospected_AccessKindArray`

## `micronaut.core.annotation`

Source: `annotation/Introspected.norm`

### `Introspected`

```norm
annotation Introspected implements PackageTarget, TypeTarget, RuntimeRetention, InheritedAnnotation
```

#### `accessKind`

```norm
List<IntrospectedAccessKind> accessKind
```

Type: `List<IntrospectedAccessKind>`

#### `annotationMetadata`

```norm
Boolean annotationMetadata
```

Type: `Boolean`

#### `Introspected`

```norm
Introspected(List<IntrospectedAccessKind>? accessKind, Boolean? annotationMetadata)
```

Parameters:

- `accessKind`: `List<IntrospectedAccessKind>?`
- `annotationMetadata`: `Boolean?`

## `micronaut.core.annotation`

Source: `annotation/IntrospectedAccessKind.norm`

### `IntrospectedAccessKind`

```norm
enum IntrospectedAccessKind
```

#### `FIELD`

```norm
FIELD
```

#### `METHOD`

```norm
METHOD
```

## `micronaut.core.annotation`

Source: `annotation/Nullable.norm`

### `Nullable`

```norm
annotation Nullable implements TypeTarget, FieldTarget, FunctionTarget, ParameterTarget, RuntimeRetention
```

#### `inherited`

```norm
Boolean inherited
```

Type: `Boolean`

#### `Nullable`

```norm
Nullable(Boolean? inherited)
```

Parameters:

- `inherited`: `Boolean?`

## `micronaut.core.annotation`

Source: `annotation/ReflectiveAccess.norm`

### `ReflectiveAccess`

```norm
annotation ReflectiveAccess implements TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, RuntimeRetention
```

