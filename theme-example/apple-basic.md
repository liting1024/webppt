---
theme: apple-basic
layout: intro
---

# 主标题
副标题
<div class="absolute bottom-10">
  <span class="font-700">
    Author and Date
  </span>
</div>

---
layout: intro-image
image: 'https://source.unsplash.com/collection/94734566/1920x1080'

---

<div class="absolute top-10">
  <span class="font-700">
    Author and Date
  </span>
</div>

<div class="absolute bottom-10">
  <h1>Presentation title</h1>
  <p>Presentation subtitle</p>
</div>

---
layout: image-right
image: 'https://source.unsplash.com/collection/94734566/1920x1080'
---

# Slide Title
## Slide Subtitle

* Slide bullet text

---
# 一级
## 二级
### 三级
#### 四级

---
layout: 
---

# 动画


<!-- 组件用法：在你按下 “下一步” 之前，这是不可见的 -->
<div v-click>点击下一步后可见</div>
<!-- 组件用法：在你按下 “下一步” 之前，这是可见的 -->
<div v-click-hide>点击下一步后消失</div>

<div
  v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">
  Slidev
</div>

---
layout: center
background: '../bg2.JPG'
---


# 代码


这是一个monaco编辑器

```python{monaco}
print('hello')
```

