# keras-notebook
```bash
docker run --rm -it  \
    -p 8888:8888 \
    -v $PWD:$PWD \
    -w $PWD \
    --user  33333  --group-add users \
    -e DOCKER_STACKS_JUPYTER_CMD="notebook" \
    -e NOTEBOOK_ARGS="--NotebookApp.token='' " \
    registry.cn-hangzhou.aliyuncs.com/wybioinfo/keras-notebook:3.5.0
```
<http://localhost:8888>
