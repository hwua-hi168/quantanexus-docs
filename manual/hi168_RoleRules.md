## <font color='blue'>角色规则</font>
#### 概述
Hi168的系统角色规则的作用是通过定义不同角色在系统中的权限、职责和操作边界，确保系统的安全性、效率性和可控性。它通常用于权限管理、资源分配和行为规范，具体作用主要包括：访问控制与权限管理、职责分离、提升系统安全性与合规性、简化管理与维护、行为规范与审计追踪和适应复杂业务场景。总体上，系统角色规则的核心是"以角色为中心"的权限控制机制，它通过角色划分、权限绑定和动态管理，实现以下目标：
<li>安全：防止越权访问和操作。</li>
<li>高效：简化权限分配流程。</li>
<li>合规：满足监管要求。</li>
<li>透明：明确责任边界，便于审计。</li>

Hi168的系统角色分类如下：
<style>
  td {
    text-align: center;     /* 水平居中 */
    vertical-align: middle; /* 垂直居中 */
  }
</style>
<table border='0'>
    <tr><th>序号</th><th>角色代号</th><th>角色名称</th><th>角色说明</th></tr>
    <tr><td>1</td><td>vvvip_user</td><td>VVVIP用户</td><td>VVVIP用户</td></tr>
    <tr><td>2</td><td>vvip_user</td><td>VVIP用户</td><td>VVIP用户</td></tr>
    <tr><td>3</td><td>vip_user</td><td>VIP用户</td><td>VIP用户</td></tr>
    <tr><td>4</td><td>verified_face_user</td><td>已认证人脸用户</td><td>已通过人脸认证的用户</td></tr>
    <tr><td>5</td><td>verified_meta3phone_user</td><td>已认证用户名、手机、身份证三要素用户</td><td>已通过用户名、手机、身份证三要素认证的用户</td></tr>
    <tr><td>6</td><td>verified_meta1phone_user</td><td>已认证手机用户</td><td>已通过手机短信认证的用户</td></tr>
    <tr><td>7</td><td>registered_user</td><td>注册用户</td><td>用户注册后成为registered_user，给registered_user赠送算力后，就变成未认证用户了</td></tr>
    <tr><td>8</td><td>public_user</td><td>未注册用户</td><td>未注册的用户，通常用不到</td></tr>
</table>