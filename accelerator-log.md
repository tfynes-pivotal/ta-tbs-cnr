# Accelerator Log

## Options
```json
{
  "branch" : "master",
  "name" : "ta-tbs-cnr",
  "projectDescription" : "Sample application deployed to CNR (kNative Serving)",
  "projectName" : "Tanzu Cloud Native Runtime Hello World",
  "tags" : [ ],
  "url" : "https://github.com/tfynes-pivotal/ta-tbs-cnr"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Combo, UniquePath)
┃ ┏ engine.transformations[0] (Combo)
┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ engine.transformations[0].merge (Chain)
┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┏ engine.transformations[0].merge.transformations[0] (Merge)
┃ ┃ ┃  Info Running Merge(YTT, Combo)
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[0] (YTT)
┃ ┃ ┃ ┗ Debug Wrote values file with json content:   {"artifactVersion":"0.0.1-beta","name":"ta-tbs-cnr","projectDescription":"Sample application deployed to CNR (kNative Serving)","icon":"https://raw.githubusercontent.com/simple-starters/icons/master/icon-tanzu-light.png","artifactId":"Tanzu_Cloud_Native_Runtime_Hello_World","projectName":"Tanzu Cloud Native Runtime Hello World","branch":"master","url":"https://github.com/tfynes-pivotal/ta-tbs-cnr","tags":[]}
┃ ┃ ┃ ┏ engine.transformations[0].merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ engine.transformations[0].merge.transformations[0].sources[1].include (Include)
┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ Debug k8s-resource.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ Debug new-accelerator.yaml didn't match [README.md] -> excluded
┃ ┃ ┗ ┗ Debug README.md matched [README.md] -> included
┃ ┗ ╺ engine.transformations[0].merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
