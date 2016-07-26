# alipayDemo
这是alipay的即时到账的utf-8编码的demo,其他编码demo[点我下载](https://doc.open.alipay.com/doc2/detail?treeId=60&articleId=103564&docType=1)，[API文档](https://doc.open.alipay.com/doc2/detail.htm?spm=a219a.7629140.0.0.INbvBn&treeId=60&articleId=104790&docType=1)   
### 使用
具体只需要修改AlipayConfig.java.   
	
	public static String partner = "您的商户号";
	public static String seller_id = partner;
    public static String key = "您的MD5密钥";
	public static String notify_url = "同步通知地址";
	public static String return_url = "异步通知地址";
其他配置，可以参照 [readingme.txt](readingme.txt)