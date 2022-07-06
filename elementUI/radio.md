# 针对单个radio可来回切换
具体实现在clickFunction
```
    <el-radio
        :value="value"
        :label="true"
        @click.native.prevent="clickFunction"
    />
```