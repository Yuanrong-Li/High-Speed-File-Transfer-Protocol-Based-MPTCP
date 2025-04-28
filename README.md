
# 基于MPTCP的极速文件传输协议

**项目名称**：基于MPTCP的极速文件传输协议

**导师信息**：

* 姓名：马杰

* 邮箱：majie61@huawei.com

**难度**：中

**分类**：新型模块化组件

**题目要求**：

1. 功能需求：基于openEuler 2403LTS sp1操作系统开发基于MPTCP的数据传输协议，满足高性能数据传输需求。
   背景： 当前的广泛使用的可靠传输协议TCP在本质上是一种单路径协议, 难以在网络中的多个路径上实现负载平衡，因为这会导致数据包重新排序，并且TCP在拥塞时会误解此重新排序，从而减慢速度。多路径TCP（MPTCP）是对TCP的扩展，允许设备同时使用多个路径，通过单个 MPTCP 连接发送和接收 TCP 数据包。MPTCP 可以聚合多个路径的带宽，或者优先选择延迟最低的路径，从而提高数据传输的性能。
   目标：基于openEuler 2403LTS sp1操作系统实现基于MPTCP的传输协议，x86/arm架构优先。
2. 性能需求：基于grpc/http2，相比于现有网络通信流程，使用MPTCP协议，性能提升80%。
   如上功能需求为必选，性能需求基于grpc/http2，数据发送场景提升80%以上。通过综合考核功能完成度，编码实现，以及性能提升幅度综合打分评估。

**License**

* MulanPSL-2.0

**参考资料**

* 参考资料1：https://docs.kernel.org/networking/mptcp.html

* 参考资料2：https://www.mptcp.dev/

* 参考资料3：https://www.rfc-editor.org/rfc/rfc8684.html

* 参考资料4：https://colobu.com/2023/07/03/mptcp-a-go-1-21-new-feature/










