# k8s
practice for k8s

# kubectlの基本的な使い方
simple-pod.yamlにて定義されたPodをデプロイする例をとって説明する。  
## Podをデプロイする

```zsh
$ kubectl apply -f simple-pod.yaml
pod/simple-echo created
```

## Podを操作する
Podの状態を取得する
```zsh
$ kubectl get pod
NAME          READY   STATUS             RESTARTS   AGE
simple-echo   1/2     CrashLoopBackOff   5          4m11s
```

コンテナの中に入る
```
$
```