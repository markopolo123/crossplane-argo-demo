# crossplane-argo-demo

demo for using crossplane with argo events

```bash
curl -L \
  -X POST \
  -H "Accept: application/vnd.github+json" \
  -H "Authorization: Bearer $GITHUB_TOKEN" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  https://api.github.com/repos/markopolo123/example-repository/actions/workflows/demo.yaml/dispatches \
  -d '{"ref":"main"}'
```
