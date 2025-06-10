---
theme: seriph
title: Folk
info: folk-karusell
class: text-center
transition: slide-left
layout: center
---

<script setup>
if ($slidev.nav.currentPage===$page.value){
  setTimeout(()=> {$slidev.nav.nextSlide()},2000)
}
</script>

# Velkommen!
 

---
class: text-center
transition: slide-left
layout: center
---

<script setup>

if ($slidev.nav.currentPage===$page.value){
  setTimeout(()=> {$slidev.nav.nextSlide()},2000)
}
</script>

# 20. Juni: Konsert med Asbjørn Ribe

<div>
<img src=./images/ribe.jpg />
</div>

---
transition: fade-out
layout: center
---

<script setup>
if ($slidev.nav.currentPage===$page.value){
  
  setTimeout(()=> {$slidev.nav.nextSlide()},2000)
}
</script>

# Tid for Dugnad!
## mandag 17:30-21:00
## onsdag 11:00-14:00
## torsdag 17:30:21:00


---
transition: slide-up
layout: center
---

<script setup>

if ($slidev.nav.currentPage===$page.value){
  setTimeout(()=> {window.location.href=1} ,2000)
}
</script>

## Søndag 15 Juni. Brettspillkveld

---
transition: slide-down
layout: center
zoom: 0.5
---

<script setup>
 if ($slidev.nav.currentPage===$page.value){
  setTimeout(()=> {
    window.location.href=6
     },3000
    )
}
</script>

<div>
<img src=./images/4.png />
</div>

---
transition: fade-out
layout: center
zoom: 0.5
---

<script setup>
import {onMounted} from 'vue';
onMounted(() => {
if ($slidev.nav.currentPage===$page.value){
  setTimeout(()=> {window.location.href=7},3000)
}})
</script>
<div>
<img src=./images/5.png />
</div>


---
transition: zoom
layout: center
zoom: 0.3
---

<script setup>
import {onMounted} from 'vue';
onMounted(() => {
if ($slidev.nav.currentPage===$page.value){
  setTimeout(()=> {window.location.href=8},3000)
}})
</script>

<div>
<img src=./images/6.jpg />
</div>

---
transition: fade-out
layout: center
zoom: 0.3
---

<script setup>
import {onMounted} from 'vue';
onMounted(() => {
if ($slidev.nav.currentPage===$page.value){
  setTimeout(()=> {window.location.href=9},3000)
}})
</script>

<div>
<img src=./images/7.jpg />
</div>

---
transition: fade-out
layout: center
zoom: 0.3
---

<script setup>
import {onMounted} from 'vue';
onMounted(() => {
if ($slidev.nav.currentPage===$page.value){
  setTimeout(()=> {window.location.href=1},3000)
}})
</script>

<div>
<img src=./images/8.jpg />
</div>


