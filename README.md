## document.createElement()

`Chỉ đơn giản là giúp mình tạo ra 1 element`

```bash
const h1 = document.createElement("h1");

console.log(h1);
```

`Cách hoạt động của react dưới dạng SPA`

```bash
<div id='root'></div>

<script>
const root = document.getElementById('root');

const h1 = document.createElement('h1');

h1.innerText = 'Hello guys'

root.appendChild(h1);
</script>
```
