目前`{{version}}`版本机器人的默认有一种自动清理消息的工作行为，它会延迟清理例如验证通过、自动放行、解除限制等消息。记录模式会关闭这种行为，不对任何类型的消息进行删除操作。

如果想保留所有中间消息的话可以启用记录模式，但它的缺点是会让机器人显得特别刷存在感。