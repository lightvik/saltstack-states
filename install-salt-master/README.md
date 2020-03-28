# Этот стейт поднимет salt-master на вашей машине с Centos 8 - воспользуйтесь salt-ssh для этого
`salt-ssh -i --config-dir=`pwd` --roster-file=`pwd`/roster 'new.salt.server' state.apply initial-salt-master test=false`
