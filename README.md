# WeChat Backend Charts

`helm install --name wechat . \
    --set wechat.gitURL=https://github.com/LinuxSuRen/linuxsuren-wechat`


`helm install --name jenkins-wechat . --set wechat.gitURL=https://github.com/jenkins-infra/wechat`

## Remove

`helm del --purge wechat`