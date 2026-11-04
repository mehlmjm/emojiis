# emojiis

## Installation
To get started with the module, use go get command to pulldown the packages:

```
go get github.com/mmehlmjm/emojiis@latest
```

## Usage
Here is a simple example of how to use the API:

```go
emojies := search.ByDescription(search.Params{
  Include: []string("face"),
  Exclude: []string{"smile", "laugh", "grin", "upside-down"}
})
```

Returns:

```
[]string("🍈", "🍉", "🍋")
```
