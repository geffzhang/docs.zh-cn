### <a name="objectdisposedexception-thrown-by-wpf-spellchecker"></a>WPF 拼写检查器引发的 ObjectDisposedException

|   |   |
|---|---|
|详细信息|应用程序关闭，拼写检查器引发 <xref:System.ObjectDisposedException?displayProperty=name>，在这期间，WPF 应用程序有时会出现故障。 .NET Framework 4.7 WPF 中已通过妥善处理异常解决了此问题，因此确保了应用程序不再受到不良影响。 应注意，在调试器控制下运行的应用程序中会继续观察到偶尔引发的最可能异常。|
|建议|升级到 .NET Framework 4.7|
|范围|边缘|
|版本|4.6.1|
|类型|运行时|

