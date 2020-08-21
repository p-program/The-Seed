
# Process（处理）

```go
type World struct{
	data *Data
}
func (w *World) Process () *World {
	newWorld:=w.Process()
	return newWorld
}
```