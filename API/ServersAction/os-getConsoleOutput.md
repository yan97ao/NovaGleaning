# 展示虚拟机的控制台输出

API文档：https://docs.openstack.org/api-ref/compute/?expanded=show-console-output-os-getconsoleoutput-action-detail#show-console-output-os-getconsoleoutput-action

在[OpenStack Virtual Machine Image Guide](https://docs.openstack.org/image-guide/)中，有说明[要求](https://docs.openstack.org/image-guide/openstack-images.html#ensure-image-writes-boot-log-to-console)将`console=tty0 console=ttyS0,115200n8`加入到虚拟机内核的启动参数中


