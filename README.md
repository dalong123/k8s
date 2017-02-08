 
>需要记住Master创建时候所生成的Token，后面Node在Join的时候需要用到    
>cd easypack/k8s   
sh easypack_kubernetes.sh MASTER
 
>在node所在节点执行，需要知道Master创建时候所生成的Token和Master的IP地址   
>git clone https://github.com/liumiaocn/easypack   
>cd easypack/k8s   
>sh easypack_kubernetes.sh NODE token MASTERIP


#问题详细查询
>（LOG文件）：/tmp/k8s_install.$$.log
