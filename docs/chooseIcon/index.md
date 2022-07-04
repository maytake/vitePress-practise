## 图标选择器
用户点击按钮，可以弹出所有图标，点击图标可以复制图标代码

### 基本用法
<br>
<div style="padding:1em;margin:1em;border:1px solid #ccc">
    
  <el-row class="mb-4">
    <el-button round>Round</el-button>
    <el-button type="primary" round>Primary</el-button>
    <el-button type="success" round>Success</el-button>
    <el-button type="info" round>Info</el-button>
    <el-button type="warning" round>Warning</el-button>
    <el-button type="danger" round>Danger</el-button>
  </el-row>

</div>

### 代码示例
<script  setup>
import {
  Check,
  Delete,
  Edit,
  Message,
  Search,
  Star,
} from '@element-plus/icons-vue'
</script>

``` js
<m-choose-icon title="选择图标" v-model:visible="visible">选择图标</m-choose-icon>
<script lang="ts" setup>
import { ref } from "vue";
let visible = ref<boolean>(false)
</script>
```