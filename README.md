<div align="center">

### Tomorrow will be better, yearn for the bright future.
# 明天会更好，向往美好

<small id="show_time"></small>

</div>

<script>
const week = ['周日','周一','周二','周三','周四','周五','周六']
function updateTime() {
  const d = new Date()
  const text = `${d.getFullYear()}年${d.getMonth()+1}月${d.getDate()}日 ${week[d.getDay()]} ${String(d.getHours()).padStart(2,'0')}:${String(d.getMinutes()).padStart(2,'0')}:${String(d.getSeconds()).padStart(2,'0')}`
  document.getElementById('show_time').innerText = text
}
updateTime()
setInterval(updateTime, 1000)
</script>

