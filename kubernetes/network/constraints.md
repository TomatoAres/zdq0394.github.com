# Kubernetes网络
## 三点约束
* 所有容器与容器之间无需SNAT，即可通过IP相互直接通信。
* 所有主机与容器之间无需SNAP，即可通过IP相互直接通信。
* 容器看到的自身IP与其它容器看到的容器IP相同。