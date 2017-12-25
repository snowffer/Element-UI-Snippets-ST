### 安装
将整个文件夹拷贝到如下路径：

#### Mac
/Users/*< your-user-name >*/Library/Application Support/Sublime Text 3/Packages/User/

### 特殊说明：

1. 对于类似于`el-table`这样的组件，内部的`el-table-column`采用`v-for`循环渲染的方式

### 对应一览表
1. 以下忽略了结束符，以及更详细的信息，比如：`elr`对应着`<el-radio>`，其实代表着`<el-radio v-model="${1}" label="${2}">$3</el-radio>`
2. 结构基本按照官方文档对组件的介绍顺序进行排列，额外提供了General和Options部分
3. 一共89个，其中有8个尚未实现



#### Basic Part
No. |  Trigger Key | Element Tag
|:-----------|------------:|:------------:|
1. | `elrow` | `<el-row>` |
2. | `elcol` | `<el-col>` |
3. | `elcon` | `<el-container>` |
4. | `elas` | `<el-aside>` |
5. | `elhe` | `<el-header>` |
6. | `elma` | `<el-main>` |
7. | `elfo` | `<el-footer>` |
8. | `elcb` | `#409EFF` |
9. | `elcs` | `#67C23A` |
10. | `elcw` | `#E6A23C` |
11. | `elcd` | `#F56C6C` |
12. | `elci` | `#909399` |
13. | TBD | `#303133` |
14. | TBD | `#606266` |
15. | TBD | `#909399` |
16. | TBD | `#C0C4CC` |
17. | TBD | `#DCDFE6` |
18. | TBD | `#E4E7ED` |
19. | TBD | `#EBEEF5` |
20. | TBD | `#F2F6FC` |
21. | `eltypo` | `font-family: "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif;` |
22. | `elb` | `el-button` |

#### Form Part

No. |  Trigger Key | Element Tag
|---|--------|--------|
1. | `elr` | `<el-radio>` |
2. | `elrg` | `<el-radio-group>` |
3. | `elc` | `<el-checkbox>` |
4. | `elcg` | `<el-checkbox-group>` |
5. | `eli` | `<el-input>` |
6. | `elit` | `<el-input type="textarea">` |
7. | `elin` | `<el-input-number>` |
8. | `else` | `<el-select>` |
9. | `elca` | `<el-cascader>` |
10. | `elsw` | `<el-swtich>` |
11. | `elsl` | `<el-slider>` |
12. | `eltp` | `<el-time-picker>` |
13. | `elts` | `<el-time-select>` |
14. | `eldp` | `<el-date-picker>` |
15. | `eldtp` | `<el-date-picker type="datetime">` |
16. | `elu` | `<el-upload>` |
17. | `elra` | `<el-rate>` |
18. | `elcp` | `<el-color-picker>` |
19. | `eltr` | `<el-transfer>` |
20. | `elf` | `<el-form>` |
21. | `elfi` | `<el-form-item>` |

#### Data Part

No. |  Trigger Key | Element Tag
|---|--------|--------|
1. | `elta` | `<el-table>` |
2. | `eltac` | `<el-table-column>` |
3. | `eltag` | `<el-tag>` |
4. | `eltags` | `<el-tag type="success">` |
5. | `eltagi` | `<el-tag type="info">` |
6. | `eltagw` | `<el-tag type="warning">` |
7. | `eltagd` | `<el-tag type="danger">` |
8. | `elpr` | `<el-progress>` |
9. | `elprc` | `<el-progress type="circle">` |
10. | `eltree` | `<el-tree>` |
11. | `elpa` | `<el-pagination>` |
12. | `elba` | `<el-badge>` |


#### Notice Part

No. |  Trigger Key | Element Tag
|---|--------|--------|
1. | `elal` | `<el-alert>` |
2. | `elals` | `<el-alert type="success">` |
3. | `elali` | `<el-alert type="info">` |
4. | `elalw` | `<el-alert type="warning">` |
5. | `elale` | `<el-alert type="error">` |
6. | `elloads` | 	`element-loading-*` |
7. | `elme` | 	`this.$message({})` |
8. | `elmes` | 	`this.$message({type: 'success'})` |
9. | `elmew` | 	`this.$message({type: 'warning'})` |
10. | `elmee` | 	`this.$message({type: 'error'})` |
11. | `elmei` | 	`this.$message({type: 'info'})` |
12. TODO: VNode for Message


#### Navigation Part
No. |  Trigger Key | Element Tag
|---|--------|--------|
1. | `elmen` | `<el-menu>` |
2. | `elsubmen` | `<el-submenu>` |
3. | `elmeni` | `<el-menu-item>` |
4. | `eltabs` | `<el-tabs>` |
5. | `eltabp` | `<el-tab-pane>` |
6. | `elbr` | `<el-breadcrumb>` |
7. | `elbri` | `<el-breadcrumb-item>` |
8. | `eldr` | `<el-dropdown>` |
9. | `eldri` | `<el-dropdown-item>` |
10. | `elsts` | `<el-steps>` |
11. | `elst` | `<el-step>` |

#### Others Part
No. |  Trigger Key | Element Tag
|---|--------|--------|
1. | `eldi` | `<el-dialog>` |
2. | `elto` | `<el-tooltip>` |
3. | `elpop` | `<el-popover>` |
4. | `elcard` | `<el-card>` |
5. | `elcaro` | `<el-carousel>` |
6. | `elcaroi` | `<el-carousel-item>` |
7. | `elcolla` | `<el-collapse>` |
8. | `elcollai` | `<el-collapse-item>` |

#### General Part
No. |  Trigger Key | Element Tag
|---|--------|--------|
1. | `el` | `<el-*>` |
2. | `elic` | `<el-icon-*>` |

#### Options Part
No. |  Trigger Key | Element Tag
|---|--------|--------|
1. | `elpos` | positions |
2. | `elanims` | animation types |

#### #TODO
1. `tree`的data值
2. `import`样式的快捷方式
3. 不同类型的`button`
4. 各种引用路径：内置动画，样式

