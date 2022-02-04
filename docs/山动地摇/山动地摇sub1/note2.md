# note2.md
```
<style lang="stylus">
.box
  width: 100%
  height: 100px
  line-height: 100px
  text-align: center
  color: #fff
  background-color: #fb3
</style>
#### 使用原生的JS和CSS
<div id="container"></div>

<script>
window.onload = function() {
  var dom = document.getElementById('container');
  dom.innerHTML = 'box content'
  dom.className = 'box'
}
</script>
```