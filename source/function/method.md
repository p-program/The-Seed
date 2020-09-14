
从高维层面，包括浏览网站，使用APP，本质上都是一种“函数”调用。

以手机浏览网络为例：

```go
func BrowseWebsite(cellphone Cellphone) string {
	// 通过手机连接移动互联网
	internet := NewInternet(cellphone)
	// 通过移动互联网获取信息
	information := internet.GetInformation()
	return information
}
```

通过这个“函数”实现你想要的目的（返回值）。
