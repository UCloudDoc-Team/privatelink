### 使用限制

#### 配额限制

<table>
  <tr>
    <th><b>实例</b></th>
    <th><b>资源</b></th>
    <th><b>默认限制</b></th>
  </tr>
  <tr>
    <td rowspan="5">终端节点服务</td>
    <td>单个账号可创建的终端节点服务的数量</td>
    <td>100个</td>
  </tr>
  <tr>
    <td>单个终端节点服务可添加的服务资源的数量</td>
    <td>1个</td>
  </tr>
   <tr>
    <td>终端节点服务后端服务资源支持的资源类型</td>
    <td>应用型负载均衡，网络型负载均衡</td>
  </tr>
   <tr>
    <td>终端节点服务支持的流量</td>
    <td>IPv4,<b>双栈</b></td>
  </tr>
   <tr>
    <td>终端节点服务支持的协议</td>
    <td>TCP、UDP（仅支持这两种或基于这两种之上的协议）</td>
  </tr>
  <tr>
    <td rowspan="5">终端节点</td>
    <td>终端节点数量</td>
    <td>50</td>
  </tr>
  <tr>
    <td>单个VPC到单个终端节点服务的终端节点数量</td>
    <td>1个</td>
  </tr>
   <tr>
    <td>终端节点支持的流量</td>
    <td>IPv4,<b>双栈</b></td>
  </tr>
   <tr>
    <td>单个终端节点网卡可支持的带宽</td>
    <td>100-10240Mbps</td>
  </tr>
   <tr>
    <td>终端节点支持的协议</td>
    <td>TCP、UDP</td>
  </tr>
</table>

#### 其他限制

不支持跨地域的私有连接
