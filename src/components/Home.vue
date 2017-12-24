<<template>
  <el-container style="height: 500px; border: 1px solid #eee">
  <el-aside width="200px" style="background-color: rgb(238, 241, 246)">
    <el-menu :default-openeds="['1', '3']">
      <el-submenu index="1">
        <template slot="title"><i class="el-icon-message"></i>Navigator One</template>
        <el-menu-item-group>
          <template slot="title">Group 1</template>
          <el-menu-item index="1-1">Option 1</el-menu-item>
          <el-menu-item index="1-2">Option 2</el-menu-item>
        </el-menu-item-group>
        <el-menu-item-group title="Group 2">
          <el-menu-item index="1-3">Option 3</el-menu-item>
        </el-menu-item-group>
        <el-submenu index="1-4">
          <template slot="title">Option4</template>
          <el-menu-item index="1-4-1">Option 4-1</el-menu-item>
        </el-submenu>
      </el-submenu>
      <el-submenu index="2">
        <template slot="title"><i class="el-icon-menu"></i>Navigator Two</template>
        <el-menu-item-group>
          <template slot="title">Group 1</template>
          <el-menu-item index="2-1">Option 1</el-menu-item>
          <el-menu-item index="2-2">Option 2</el-menu-item>
        </el-menu-item-group>
        <el-menu-item-group title="Group 2">
          <el-menu-item index="2-3">Option 3</el-menu-item>
        </el-menu-item-group>
        <el-submenu index="2-4">
          <template slot="title">Option 4</template>
          <el-menu-item index="2-4-1">Option 4-1</el-menu-item>
        </el-submenu>
      </el-submenu>
      <el-submenu index="3">
        <template slot="title"><i class="el-icon-setting"></i>Navigator Three</template>
        <el-menu-item-group>
          <template slot="title">Group 1</template>
          <el-menu-item index="3-1">Option 1</el-menu-item>
          <el-menu-item index="3-2">Option 2</el-menu-item>
        </el-menu-item-group>
        <el-menu-item-group title="Group 2">
          <el-menu-item index="3-3">Option 3</el-menu-item>
        </el-menu-item-group>
        <el-submenu index="3-4">
          <template slot="title">Option 4</template>
          <el-menu-item index="3-4-1">Option 4-1</el-menu-item>
        </el-submenu>
      </el-submenu>
    </el-menu>
  </el-aside>
  
  <el-container>
    <el-main>
   <div class="main">
       	<svg id="bqlogo" xmlns="http://www.w3.org/2000/svg" version="1.1" xmlns:xlink="http://www.w3.org/1999/xlink" preserveAspectRatio="none"
	 x="0px" y="0px" width="200px" height="200px" viewBox="0 0 200 200">
		<path id="q1" stroke="#ffffff" stroke-width="6" stroke-linejoin="round" stroke-linecap="square" fill="none" d="
M 158.15 105.15
Q 157.85 105.5 157.45 105.9 146.6 116.7 131.4 116.7 116 116.7 105.2 105.9 94.4 95.1 94.3 79.85 94.3 64.45 105.1 53.65 116 42.75 131.4 42.75 146.7 42.75 157.55 53.65 168.45 64.45 168.45 79.85 168.45 80.25 168.45 80.65
L 168.45 157.3" />
		<path id="b1" stroke="#ffffff" stroke-width="6" stroke-linejoin="round" stroke-linecap="square" fill="none" d="
M 41.95 94.85
Q 42.25 94.55 42.65 94.15 53.5 83.3 68.7 83.3 84.05 83.3 94.9 94.15 105.7 104.95 105.8 120.2 105.8 135.55 95 146.35 84.05 157.25 68.7 157.25 53.4 157.25 42.55 146.35 31.65 135.55 31.65 120.2 31.65 119.8 31.65 119.35
L 31.65 42.7" />
	</svg>
   </div>
    </el-main>
  </el-container>
</el-container>
</template>

<style>
  .el-header {
    background-color: #B3C0D1;
    color: #333;
    line-height: 60px;
  }
  
  .el-aside {
    color: #333;
  }
  .el-main {
    background: #333;
    color: #eee;
    font-family: monospace;
  }
		#bqlogo {
			display: block;
			width: 200px;
			height: 200px;
			margin: 50px auto;
		}
</style>


<script>
  export default {
    data () {
      const item = {
        date: '2016-05-02',
        name: 'Tom',
        address: 'No. 189, Grove St, Los Angeles'
      }
      return {
        tableData: Array(20).fill(item)
      }
    }
  }
</script>