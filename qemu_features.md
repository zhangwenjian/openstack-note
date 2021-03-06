特性      	|子特性		|支持	|
:---------------|:--------------|:------|
[内存超分配]	|透明页面共享	|是	|
          	|内存气泡	|是	|
          	|页面交换	|是	|
          	|页面压缩	|否	|
[CPU QoS]		|上限		|是	|
		|预留		|否	|
		|份额		|是	|
[内存 QoS]	|上限		|是	|
		|预留		|是	|
		|份额		|否	|
[虚拟机快照]	|内存快照	|是	|	
		|无中断内存快照	|	|	
[Host]		|Logical Processors|	|	
		|Physical Memory|	|	
		|Virtual CPUs per Host|	|	
VM		|Virtual CPUs per VM|	|	
		|Memory per VM	|	|	
		|Active VMs per Host|   | 	
热拔插		|CPU		|是*	|
		|内存		|	|	
		|虚拟硬盘	|是	|
		|虚拟光驱	|是	|
		|虚拟软驱	|	|
		|虚拟USB设备	|是	|
		|虚拟网卡	|是	|
虚拟机操作	|创建		|是	|
		|启动		|是	|
		|安全关闭	|是	|
		|强制停止	|是	|
		|删除		|是	|
		|重启		|是	|
		|休眠		|是	|
		|唤醒		|是	|
		|暂停		|是	|
		|恢复		|是	|
		|导入		|是	|
		|导出		|是	|
		|复制		|是	|
计算资源调度	|动态资源调度（负载均衡）| |	
		|动态电源管理（节能减排）| |	
		|虚拟机互斥	|	|	
		|亲和性		|	|	
		|虚拟机组与主机组的关联| |	
安全		|SELinux访问控制的隔离| |	
音频		|回放		|是	|
		|录音		|是	|
虚拟外设	|USB redir	|是	|
		|PS/2		|是	|
		|串口		|是	|
		|并口		|	|	
		|光驱		|是	|
		|Watchdog	|	|
		|USB1.0 UHCI	|	|	
		|USB1.0 OHCI	|	|	
		|USB2.0 EHCI	|	|
		|USB3.0 XHCI	|	|	
		|TPM		|	|	
主机设备直通	|USB		|是	|
		|网卡		|是	|
		|光驱		|	|	
		|显卡		|	|	
		|HBA卡		|	|	
		|TPM		|是	|
		|VMDQ		|	|
		|SR-IOV		|是	|
		|VFIO		|	|	
内核级设备模拟	|vhost-scsi	|	|	
		|vhost-net	|	|	
		|APIC		|	|
		|PIT		|	|
虚拟机迁移	|共享存储热迁移	|是	|
		|不同版本之间迁移|	|	
		|异构CPU的热迁移 |	|
		|无共享存储热迁移|是	|
		|热迁移压缩	|是	|
		|基于RDMA	|是	|
		|热迁移加密	|是	|
		|热迁移限速	|是	|
		|迁移时去重	|是	|
		|热迁移自动负载降低|是	|		
FT（Fault Tolerance）|	单vcpu  |NA 	|
		|多vcpu		|NA	|
		|HA		|是	|
虚拟机时钟同步	|		|	|		
虚拟机故障检测	|	是	|	|
Guest [NUMA]|	|是	|
Host [NUMA]	|		|是	|
Virtual SMP	|即支持多个VCPU |是	|
[Transparent Huge Page]|		|是	|
x2apic		|		|是	|
msi-x		|		|	|
posted interrupt|		|NA	|
APIC-v		|		|NA	|
PVEOI		|		|是	|
半虚拟化	|		|否	|
Inter-VM Share Memory(IVSMEM)|	|	|		
ELI		|		|	|

[内存超分配]: QF_mem_overcommit.md 
[CPU QoS]: QF_CPUQos.md 
[内存 QoS]: QF_MEMQos.md 
[虚拟机快照]:QF_vm_snapshot.md
[NUMA]:QF_numa.md
[Transparent Huge Page]:QF_hugepage.md
[Host]:QF_host.md
