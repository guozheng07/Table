# Table
表格开发中常见的技巧
## 一个 form-item 中有多个字段校验
问题描述：https://blog.csdn.net/palmer_kai/article/details/106586817
## el-table设置了fixed固定列导致的滚动条无法拖动问题
问题描述：https://blog.csdn.net/qq_43201542/article/details/121275771

解决方式一：不care错位问题，右固定列设置为可滚动
```
// 设置右固定列可滚动
::v-deep .el-table__fixed-right {
    overflow-y: auto !important;
}
```
