// src\components\Event\BottonSvg.vue
<template>
  <div class="taiwan-map-wrapper" :style="{ maxWidth: props.maxWidth + 'px' }">
    <svg 
      class="map-svg"
      viewBox="490 280 420 610"
      xmlns="http://www.w3.org/2000/svg"
      preserveAspectRatio="xMidYMid meet"
    >
      <g fill="none" stroke="#d1ad41" stroke-linecap="round" stroke-linejoin="round" stroke-width="0.5">
        <path id="TWTPE" name="台北" d="M776.8 321.1l-4.2 0-3.5-0.8-2.6-2.3-2.8-3.2-4.1-3.2-2.9-4.9 1.1-5.3-0.8-4.5-4.2-4-2.7-3.1 1.2-2.1 1.3-1.7 1.5-3.3 2.6-2.9 7.8-4.7 2.1-1.8 2.9-1.4 2.8 0.9 1.5 1.6-0.4 2.6 0.3 2.4 1.1 2.4 1.2 2.6 1.8 7.2 2.8 2.5 1.1 3.2-1.1 4.8 0.1 3.6 3.3 1.9 2.7 2.3-1.4 3-5.5 7-3 1.2z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWNWT" name="新北" d="M754.1 381.6l-1.8-4-6.4-6-1-4.1-0.6-3.7 2.3-2.7 1-3.8-6-8.9-3.7-1.4-5.3 0.3-3.7-2.1 1-4.8-0.8-3.7-3.8-3.7-0.8-3.7 0.8-4.1-0.2-4.5 2.7-2.9 9.4-2.8 2.4-2.5 0.7-3-0.3-2.9-3.7-5.4-3.1-1.6-2.9-0.7-2.3-2.1-3.4-2.2-4.6-2.2-3-3.3 8.1-1.5 3.4-1.3 4.5-3.7 1.3-0.7 1.6-0.3 2.2 0 2.6 0.8 1.3 1.9 0.9 2 1.1 1.1 2.5-1-2.6-4.1-4.2-4.2-2.2-1.4 0.7-1.9 1.3-1.1 1.3-0.7 0.6-0.6 1.5-3.8 2.3-4.2 4.7-4.3 7-3.5 7.9-1.8 7.8 0.9 3.2 2.5 7.3 10.1 2.5 5.4 0.9-0.3 1.9-0.6 2.3-0.2 1.5 0.4-0.1 0.7-0.7 0.9-0.7 1.3 0 1.5 0.8 0.9 1.6 1.2-3.1 2.1-5.2 2.3-2.3 1.5 0.4 2.1 2.1 2.7 1.2 2.5 2.1 2.5 2.6 2.5 2.2 1.6 7.6 3.1 3.7 0.5 2.9-1.1 1.8-1.3 0.3-1.8-2.7-2.8-0.1-2.2 0.2-8.6 24.9 6.1 2.4 1.5-1.2 2.6-0.3 2.1 0.5 3.8 1.7 6.2 1.9 3 1.6 0.7 5-0.8 2.6 0.3 3 0.8 2.7 1.3 1.5 1.9-6.3 3.1-0.6-0.8-2.4-1.4-4.3 0.9-6 3.2-2.6 1.8-8.1 1.6-1 2.2 1.8 2.5-1.2 2.8-3.3 2.1-2.5 0.9-2.7 1.4-2.3 2.9-2.3 3.7-3.6 2.6-4.5 1.3-9.7 5.9-9.4 3.8-2.7 1.6-3.4 2.9-1.4 3.6 0.1 3 0.7 2.3 0.3 1.4-2.8 2-4.8 2.3-3.6 2.5-2.7 2.4-3.5 1.3-4.2 1.2z m22.7-60.5l3-1.2 5.5-7 1.4-3-2.7-2.3-3.3-1.9-0.1-3.6 1.1-4.8-1.1-3.2-2.8-2.5-1.8-7.2-1.2-2.6-1.1-2.4-0.3-2.4 0.4-2.6-1.5-1.6-2.8-0.9-2.9 1.4-2.1 1.8-7.8 4.7-2.6 2.9-1.5 3.3-1.3 1.7-1.2 2.1 2.7 3.1 4.2 4 0.8 4.5-1.1 5.3 2.9 4.9 4.1 3.2 2.8 3.2 2.6 2.3 3.5 0.8 4.2 0z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWKEE" name="基隆" d="M806.8 285.1l-0.2 8.6 0.1 2.2 2.7 2.8-0.3 1.8-1.8 1.3-2.9 1.1-3.7-0.5-7.6-3.1-2.2-1.6-2.6-2.5-2.1-2.5-1.2-2.5-2.1-2.7-0.4-2.1 2.3-1.5 5.2-2.3 3.1-2.1 1.1 0.7 0.5 0.8 1.2 1.1 2.8 1.1 8.1 1.9z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWILA" name="宜蘭" d="M740.7 399.4l0.3-1.1 2.9-1.1 2.3 0.5 2.5-1 1.6-2.7-2.3-9 3.9-2.8 2.2-0.6 4.2-1.2 3.5-1.3 2.7-2.4 3.6-2.5 4.8-2.3 2.8-2-0.3-1.4-0.7-2.3-0.1-3 1.4-3.6 3.4-2.9 2.7-1.6 9.4-3.8 9.7-5.9 4.5-1.3 3.6-2.6 2.3-3.7 2.3-2.9 2.7-1.4 2.5-0.9 3.3-2.1 1.2-2.8-1.8-2.5 1-2.2 8.1-1.6 2.6-1.8 6-3.2 4.3-0.9 2.4 1.4 0.6 0.8-8.6 4.3-4 3.4-13.5 16.4-2.1 3.5-1.7 4.8-1.1 5.6-0.4 5.5 0.2 5.3 2.4 11.2-0.2 2.9-1 2.8 0.2 5.8 2.4 4.5 4.7 2.9 5.5 1.1 0 1.2-2.3-0.2-2.2 0.2-1.9 0.6-1.3 1 1.9 3.6 0.9 4.7-0.6 4.1-4.3 2.4-0.3 1.8 0.6 2.1 1.2 2 0.4 2-1.8 1.7-4.5 2.6-5 5.8-0.2 2.3 0.3 5-0.8 2-1 1.6-0.6 2.3-0.3 4.6-0.4 1.2-0.7 0.9-0.4 1 0.7 1.2 0.2 0.2-0.8 0-8-1.3-13.4-7.9-2.7 0.6-1.7 4.3-3.5 3.3-4.7 0-6-2.3-10.8-2.8-4.7-2.2-1.8-1.5-4.2-3.4-3.6 0-3.4 1.7-2.8 0.4-2.7-1.8-3.2-1.9-3.5-0.8-1.1-2.6 0.5-4-2.6-0.8 3.1-7.5 10.1-10.2 2.7-4.2-0.4-3.2 1-3.4 1.7-4.7z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWTAO" name="桃園" d="M657.2 325.1l6.4-10.3 5-5.9 5.2-4.4 13.2-4.4 3.1-1.9 2.7-2.4 3.3-1.8 6.4-2.3 14.5-2.6 3 3.3 4.6 2.2 3.4 2.2 2.3 2.1 2.9 0.7 3.1 1.6 3.7 5.4 0.3 2.9-0.7 3-2.4 2.5-9.4 2.8-2.7 2.9 0.2 4.5-0.8 4.1 0.8 3.7 3.8 3.7 0.8 3.7-1 4.8 3.7 2.1 5.3-0.3 3.7 1.4 6 8.9-1 3.8-2.3 2.7 0.6 3.7 1 4.1 6.4 6 1.8 4-2.2 0.6-3.9 2.8 2.3 9-1.6 2.7-2.5 1-2.3-0.5-2.9 1.1-0.3 1.1-3.5-1.5-5.2-3-2.9-2.1-4-0.7-4.5-2.6-3.7-2.9-0.4-3.1 3.3-4.7 1.4-5.6-1.2-5.2-0.2-3.6-2.5-1.9-3.1-1.6-1.9-3.3-2.4-2.5-2.8 0.2-2.8-0.5-2.2-2.2-3-2.2-4.8-1.5-2.4-2.7 0.8-4.2-2.6-3-4.9-1.6-3-1.4-3.1-0.9-3.6-1.4-2.9-6.3-3.3-2.2-9.8 0.7-2.3-0.8z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWHSQ" name="新竹" d="M657.2 325.1l2.3 0.8 9.8-0.7 3.3 2.2 2.9 6.3 3.6 1.4 3.1 0.9 3 1.4 4.9 1.6 2.6 3-0.8 4.2 2.4 2.7 4.8 1.5 3 2.2 2.2 2.2 2.8 0.5 2.8-0.2 2.4 2.5 1.9 3.3 3.1 1.6 2.5 1.9 0.2 3.6 1.2 5.2-1.4 5.6-3.3 4.7 0.4 3.1 3.7 2.9 4.5 2.6 4 0.7 2.9 2.1 5.2 3 3.5 1.5-1.7 4.7-1 3.4 0.4 3.2-2.7 4.2-10.1 10.2-3.1 7.5-2-0.5-7.7 0.7-0.5 0.4-0.5-3.5-3.3-5.6-2.3-2.4-1-3.1-3.6-2.9-9.1 2.3-3.4-0.4-4.9 0.4-5.5 1.5-3-0.7 0.7-3.7 0.9-3.3-0.7-2.9-0.7-2.1 0.7-2.3 0.5-2.4 0.3-2.8-0.6-3.8-2.7-2.4-8.8-4.2-4.3-3.2-2.8-3.2-3.2-8 1.8-2.2 1.6-4.1 2.5-3.1 4.2-1.7 3.7-0.6 1.7-1 0.7-2.7-1.3-2.6-2.8-2.8-3.9-2-10.9-3.5-6-2.6 0.1-0.1 1.1-1.6 0.4-2.7 0.6-2.1 1.5-2.1 1.9-1.6 1.8-0.6-0.1-0.9 0.5-2.1 1.6-4.4 1.5-2.3z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWHSZ" name="新竹" d="M646.3 345.6l6 2.6 10.9 3.5 3.9 2 2.8 2.8 1.3 2.6-0.7 2.7-1.7 1-3.7 0.6-4.2 1.7-2.5 3.1-1.6 4.1-1.8 2.2-0.2 0.2-3.3 0.8-3.1-1.3-2-2.7-3-1.9-5-1.9 0.8-3 4-8.2 1.6-2.1 0.5-1.2 0-1.2-0.5-1.3-0.8-1.6 1.1-2.2 1.2-1.3z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWMIA" name="苗栗" d="M655 374.5l3.2 8 2.8 3.2 4.3 3.2 8.8 4.2 2.7 2.4 0.6 3.8-0.3 2.8-0.5 2.4-0.7 2.3 0.7 2.1 0.7 2.9-0.9 3.3-0.7 3.7 3 0.7 5.5-1.5 4.9-0.4 3.4 0.4 9.1-2.3 3.6 2.9 1 3.1 2.3 2.4 3.3 5.6 0.5 3.5-2.7 1.9-1.3 4-3.5 1.5-3.9-0.1-3 2.2-3.3 3.1-4.2 2.4-8.4 6.6-4.9 2-6.4 3.5-3.9-1.6-3.6-4-4.4-1.7-7.1-0.6-4 2.4-0.6 5.3-3.7 2-8.8 0.5-8.4-4.8-4.7-0.9-5.3-2.6-10.9-8-4.5-3.9-3.4-3.6-6.6-10.3 5.2-5.8 1.3-2.9 0.7-4.8 1.5-4 4.3-7.5 1.2-4.5 1.1-2 4.8-1.4 1.4-1.5 0.8-1.9 1-1.8 3-3.2 3.4-2.4 4-1.1 5.2 1-0.7-3.9 1.9-2.7 2.7-2.7 1.3-4.2 0.6-1.3 2.6-1.3 0.3-0.9 5 1.9 3 1.9 2 2.7 3.1 1.3 3.3-0.8 0.2-0.2z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWCYI" name="嘉義" d="M496.5 622.6l0.7 0 0.1-0.1 7.6-0.8 6 3.3 4.4 0.1 2.8-2.3 1.3-3.5 1.4-2.2 3.9-0.6 5-4.1 3.2-1.7 2.7-2.7 11.8-6.8 5.2-1.4 9.1-1.7 4.9-0.3 3.8 3.4 3.6 4.2 9.1 3.3 2.7-0.4 6-1.7 3.4 2.4 1.7 2.9 4.6-0.5 8.4-1.7 2.8-0.9 0-2.5 0.3-3.6 0.4 0 4.4 0.5 4.8 1.9 3 0.8 3.7 2.1-0.3 3.8-2.1 3.7 0.9 3.4 1.9 4.7 0.3 4.2 0.8 2.8 5.5 1 18.4 0.1 0.6 0.2-13.3 6.8-6.1 4.8-2.5 4.9-3.1 3.7-5.5 3.1-5.8 4.4-3.2 3.8-8.9 5.3-4.2 0.4-4.9-0.5-2.6 2.6-0.1 3.5 1 3.3 0.7 4.8-6-0.7-2.7-0.8-3.6 0.5-3.8 1.7-2.7 0-3.3-2.5-1.1-3.3 1.2-10.3-0.7-5.4-7.1-7.3-1.3-3.6-1.5-3.1-2.9-1.7-5.1-1.7-6.1 0.3-11 2.1-5.6 2.5-4.4 3.3-3.4 3.4-4.8 3.7-4.1 2.6-1.8 3.6-4.5 2-5.3-1.3-6.3-1-3.8-1.4 2.8-0.2 2.3-1 1 0.3-0.6-2.3-1.6 1.2-1.3-0.4-1.8-0.1 0-2.3 1.8-4.1 2.6-0.2 3.9 0-2.6-7.5-3.1-5.8 1.4-2.6 0-1.4-2.2-1.1 0.3-1.2 1.3-1.5 0.6-1.9 3-3.8-6.2 0.4-0.2-6.3z m62.7 15.5l4.9-2 3.2-0.4 2.2-1.6-1.9-4.9-1.7-2.9-3-1.6-4-1.5-5.7 0.5-6.7 1.2-2.7 2.9 0.6 4.1 4.4 1.7 5.1 3.3 5.3 1.2z m-82.1-1.3l10.1-10.2 7.6-9.7 1.8-0.5-6.5 10.5-3.2 3.2-2.1 2.6-2.7 2.7-2.2 1.5-3.2 2.6-2.2 1.2 2.6-3.9z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWCYQ" name="嘉義" d="M559.2 638.1l-5.3-1.2-5.1-3.3-4.4-1.7-0.6-4.1 2.7-2.9 6.7-1.2 5.7-0.5 4 1.5 3 1.6 1.7 2.9 1.9 4.9-2.2 1.6-3.2 0.4-4.9 2z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWNAN" name="南投" d="M599.5 519.1l3 0.1 13 1.8 3-0.5 3.6-3.4 5.4-10.4 2.7-6.1 4.6-2.2 7.3 1.1 4.3-0.2 4.2-5.5 2.2-1.4 6.4 4.8 2.5-0.7 1.9-3.9 3.4-2.8 4.8 0.1 3.6-1.4 5.7-5.5 3.6-2.1 3.2-0.6 6.4-3.3 4.4-0.2 4.5-0.7 8-3.2 3.4-0.2 3.4 0.8 9.6 0.9 1 4.5 0.2 2.6-3.8 1.7-4.7 1.6-2.7 2.1 0.2 7.2 2 2.2 3.8 2.4 1 3.3-0.1 2.7-5.8 7.6-3.7 7.7-1.7 5.5 1.5 2.4 1.3 3.2-0.5 5.4-1.1 7.2-2.2 6.3-2.8 6.1-1.8 5.1-0.1 2.7-4.1 6.8 1.5 2.9 2.3 2.9 0.8 3.9 0.7 5.2-0.9 6-2.3 9.1-1.1 3.6-3.3 2.3-5.5 2-2.8 3.7-1 6.2-3.8 3.4-5.3 0.2-5.4 1.2-3.7 2.7-1.1 3-1.1 1.9 1.2 4.4-2.2 2.1-4.3 2.5-0.5-1.5-3-4.2-4.2-1.6-3.2-0.7-0.6-0.2-18.4-0.1-5.5-1-0.8-2.8-0.3-4.2-1.9-4.7-0.9-3.4 2.1-3.7 0.3-3.8-3.7-2.1-3-0.8-4.8-1.9-4.4-0.5-1.9-2.5-6 0.6-4.9 1.5-4.2-1.8-2.8-3.4 0.7-4.2 1.3-3.7-0.7-5.5 0.7-5.2 1.5-3.4-1.4-5.2 1.7-1.1 1.8-1.7 2.8-1.1 0.7-2.5-4.1-2.1-2.8-1-2.6-2.4-1.5-4.5 0.7-9.7 0.8-4.7 0.1-4.1 1.2-3.9 1.4-3.3-0.4-2.9 0.9-2.1 3.1-1.1 0-2.6z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWYUN" name="雲林" d="M519.2 556.7l5.5 3.2 15.9-1.9 5.4 0.3 4.8 1.3 8.4 3.2 14.2 1.6 8.7 4.4 4.2-0.1 8.7 1.7 0.7-0.5 1.4 5.2-1.5 3.4-0.7 5.2 0.7 5.5-1.3 3.7-0.7 4.2 2.8 3.4 4.2 1.8 4.9-1.5 6-0.6 1.9 2.5-0.4 0-0.3 3.6 0 2.5-2.8 0.9-8.4 1.7-4.6 0.5-1.7-2.9-3.4-2.4-6 1.7-2.7 0.4-9.1-3.3-3.6-4.2-3.8-3.4-4.9 0.3-9.1 1.7-5.2 1.4-11.8 6.8-2.7 2.7-3.2 1.7-5 4.1-3.9 0.6-1.4 2.2-1.3 3.5-2.8 2.3-4.4-0.1-6-3.3-7.6 0.8-0.1 0.1-0.7 0 3.4-3.7-0.2-11.8 0.5-8.9 2-7 3.2-5.6 0.9-7.2 1.7-6.3 0.9-2.2 4.4-5.8 0.7-2 0.6-1.1 4-3.1 0.6-1.2z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWCHA" name="彰化" d="M563.1 480.3l4.2 1.3 2.9 2.5 1.9 4.6 0.7 5.5 3.3 3.9 8.5 2.5 3.2 2.6 2.3 3.6 1.4 2.9 0 2.8 0.9 2.5 3.1 0.5 3.9 2.6 0.1 1 0 2.6-3.1 1.1-0.9 2.1 0.4 2.9-1.4 3.3-1.2 3.9-0.1 4.1-0.8 4.7-0.7 9.7 1.5 4.5 2.6 2.4 2.8 1 4.1 2.1-0.7 2.5-2.8 1.1-1.8 1.7-1.7 1.1-0.7 0.5-8.7-1.7-4.2 0.1-8.7-4.4-14.2-1.6-8.4-3.2-4.8-1.3-5.4-0.3-15.9 1.9-5.5-3.2 0.6-1 1.1-5.1 0.9-2.1 5.1-4.9 1.5-2.1 1.9-5.6 3-5.6 4.2-11.6 1.9-3.3 2.2-2.2 1.8-1.2 1.5-0.8 1.2-1 0.4-2.2 0.9-2 3.7-2.9 0.8-2.2 0.4-7.2 0.7-2 1.9-1.9 8.2-9.5z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWTXG" name="台中" d="M712.3 433.2l0.5-0.4 7.7-0.7 2 0.5 2.6 0.8-0.5 4 1.1 2.6 3.5 0.8 3.2 1.9 2.7 1.8 2.8-0.4 3.4-1.7 3.6 0 4.2 3.4-3.4 3.5-0.3 3-1.7 4.5-5.4 3.4-2.2 3.6-0.9 3.7-2.2 2.7-2.5 1.3-0.9 1.4-2 1.5-9.6-0.9-3.4-0.8-3.4 0.2-8 3.2-4.5 0.7-4.4 0.2-6.4 3.3-3.2 0.6-3.6 2.1-5.7 5.5-3.6 1.4-4.8-0.1-3.4 2.8-1.9 3.9-2.5 0.7-6.4-4.8-2.2 1.4-4.2 5.5-4.3 0.2-7.3-1.1-4.6 2.2-2.7 6.1-5.4 10.4-3.6 3.4-3 0.5-13-1.8-3-0.1-0.1-1-3.9-2.6-3.1-0.5-0.9-2.5 0-2.8-1.4-2.9-2.3-3.6-3.2-2.6-8.5-2.5-3.3-3.9-0.7-5.5-1.9-4.6-2.9-2.5-4.2-1.3 0.5-0.6 0.5-2.4 2.4-1.9 1.6-4.7 1.9-8.8 6.7-11.7 2.1-7.1 2.4-4 9.6-10.6 6.6 10.3 3.4 3.6 4.5 3.9 10.9 8 5.3 2.6 4.7 0.9 8.4 4.8 8.8-0.5 3.7-2 0.6-5.3 4-2.4 7.1 0.6 4.4 1.7 3.6 4 3.9 1.6 6.4-3.5 4.9-2 8.4-6.6 4.2-2.4 3.3-3.1 3-2.2 3.9 0.1 3.5-1.5 1.3-4 2.7-1.9z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWTNN" name="台南" d="M495.1 664.4l3.8 1.4 6.3 1 5.3 1.3 4.5-2 1.8-3.6 4.1-2.6 4.8-3.7 3.4-3.4 4.4-3.3 5.6-2.5 11-2.1 6.1-0.3 5.1 1.7 2.9 1.7 1.5 3.1 1.3 3.6 7.1 7.3 0.7 5.4-1.2 10.3 1.1 3.3 3.3 2.5 2.7 0 3.8-1.7 3.6-0.5 2.7 0.8 6 0.7-1.6 4.8-7.5 10.9-7.2 12.2-4.7 6-5.4 5.3-4.6 3.9-4.5 4.6-3.8 5.1-2.1 3.7-1.7 4-4.6 3.2-4.6 1.9-2.6 1.8-3 1.1-6.1-0.7-5.9 0.6-11.3-1.6-3.5-1.8-2.8-6.2-0.1-0.3-4.5 2.6-0.7-4.5-1.3-2.6-2.8-2.8 3.5-2.5 1.9-4.3-0.8-3.8-4.6-0.7-0.8 1.4-0.8 2.4-1.3 1.9-2.4-0.1-0.9-1.6 0.3-5-0.5-1.8-3-1.3-1.6 1.5-1.4 2.1-1.9 0.5-2.1-1.8-0.6-2.5 0.5-2.4 0.9-1.7 2.1-1.1 2.7-0.4 2.2-0.7 0.7-2.2-1-1.1-6.7-1.7 0-1.4 5.6 0-0.5-1.9-3.1-2.7-2-2.3 0.5-2.9 1.8-1 1.9-0.7 1-1.8-0.6-2.8-1-2.3 0.7-2.2 1-2.6 1.6-1.9-0.3-1.7 0.3-1.6 2.4-6.5 1.2-1.2 1.8-0.5-2.7-1.8 1.2-2.9z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWKHH" name="高雄" d="M596.8 682.8l-0.7-4.8-1-3.3 0.1-3.5 2.6-2.6 4.9 0.5 4.2-0.4 8.9-5.3 3.2-3.8 5.8-4.4 5.5-3.1 3.1-3.7 2.5-4.9 6.1-4.8 13.3-6.8 3.2 0.7 4.2 1.6 3 4.2 0.5 1.5 1.4 4.2-2.2 3.5-4 1.8-1 2.3 0.7 2.9 4 2.6 4.6 3.7 2 5.5 0.2 1.8-11.2 2.8-4.7 2.9-2.9 2.8-5.6 3.7-0.6 4.1 1.6 4.3-1.9 3.5-5.3 2.9-0.7 5 1.6 7.1-2.2 9.5 0 8.1-3.1 4.2-6.2 5.3-1.7 7 1 5.9 2.2 3.3 4.4 4.6 0.9 3.5-2.8 0.4-3.8-0.7-3.1 0.2-6.1 4.8-4.3-4-5.4-6.4-5.2 1.3-4.8 4.3-9.4-4.8-6.8 3.2-4.6 5.1-5.7 2.1-12.9-0.8-1.3 3.5-0.9 5.2-1.9 5.7 0.4 5-0.1 6.9-4 15.3-0.2 5.1 2 5.4 0.3 5.9-5.8 14.8-1.9-0.8-1.1 0-1.4 0.5-1.5 0.1-9.4-7.4-8.8-12.4 9.2 11.1-1-5.2-1.6-2.9-1.2-2.3-3.8-4.4-6.5-6-2.5-3.1-1.2-3.4 1.6-3.3 0.8-3-1.1-4.1-1.9-4.1-3.6-5.5-3.3-7.4-0.7-3.3 0-2.1 1.1-2.6 0.3-1.7-0.4-0.9-1-0.7-0.9-0.9-0.4-1.7-2.1-3.5-0.5-1.4-1.6-9.9 4.5-2.6 0.1 0.3 2.8 6.2 3.5 1.8 11.3 1.6 5.9-0.6 6.1 0.7 3-1.1 2.6-1.8 4.6-1.9 4.6-3.2 1.7-4 2.1-3.7 3.8-5.1 4.5-4.6 4.6-3.9 5.4-5.3 4.7-6 7.2-12.2 7.5-10.9 1.6-4.8z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWPIF" name="屏東" d="M551.1 836.2l5.8-14.8-0.3-5.9-2-5.4 0.2-5.1 4-15.3 0.1-6.9-0.4-5 1.9-5.7 0.9-5.2 1.3-3.5 12.9 0.8 5.7-2.1 4.6-5.1 6.8-3.2 9.4 4.8 4.8-4.3 5.2-1.3 5.4 6.4 4.3 4 6.1-4.8 3.1-0.2 3.8 0.7 2.5 4.7 0.5 3.5 3.9 1 4 2.6-2 9.9-0.1 3.8-1.5 3.5-7 3-3.5 2-5.5 1.2-3.9 3.2-1.7 4.7-2.6 4.8-2.2 5.4-0.6 10.6 0.9 4.7 1.4 4.4 0.8 5.1 0 3.8 1.9 3.7 3.3 4-1.8 2.7-3.8 2.3-1.5 2.8-0.4 3.3 2 2.8 2.4 1.2 2.3 3.2-0.1 4.1 0.4 4.4 2.3 4.3 3.3 3.5 7.4 3.4 3.2-0.3 0.6 37.2-1.1 5.3-1.8 4.3-2.4 1.8-2.9 2.7 0.1 6 1 6.6-0.2 4.2-3.3-4.9-4.9-3.7-5.7-2.5-5.7-1.4-0.2 4.7-1.7 1.7-2.4-0.6-2.7-2.2-0.1-1.7 0.9-5-4-6.7-0.3-1.8 0-1.4 0.3-2.4 0-7.7 0.4-2.3 1.8-2.5 0.4-2.2-14.4-37.2-1.1-2.1-4-4.9-3.2-7.1-1.4-2.1-5.9-4.6-2.3-1.3-0.8-0.3-0.8-0.6-0.7-2.6-0.5-1-3.1-2.1-7.3-3.4-3.2-2.3-3.5-3-1.6-1-0.2-0.1z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWHUA" name="花蓮" d="M727.6 474.4l2-1.5 0.9-1.4 2.5-1.3 2.2-2.7 0.9-3.7 2.2-3.6 5.4-3.4 1.7-4.5 0.3-3 3.4-3.5 1.8 1.5 4.7 2.2 10.8 2.8 6 2.3 4.7 0 3.5-3.3 1.7-4.3 2.7-0.6 13.4 7.9 8 1.3 0.8 0 0.5 0.5 0.6 1.1 0.5 1.1 0.2 0.7-1 1.7-4.2 4.1-4.6 6.3-3.3 2.7-1 1.4 0.5 1.5-0.6 1.1-4.9 3.6-1.8 1.8-2 4.3-2 8.8-5.4 7.8-1.1 3.2 0.2 3.4 1.3 3.8 1.1 1.6 0.9 0.7 0.6 1 0.1 2.3-0.8 2.7-2.7 4.1-0.5 2.5-0.3 4.6-2.3 11.7-4.6 12.4-5.8 28.8-3.4 7.1-8 46.2-2.5-0.8-7.8 3.8-2.8 3.9 1.3 5 0.4 4.9-2.6 5-2.5 3.7-1.9 4.8-1.8 6.1-2.6 5.5-3.5 9.6-2.2 4.3 0 4.9-0.6 4.4-4.7 2.7-5.9-0.8-8.5-7-6.6-11.5-4.1-1.1-4.5-0.7-3.6-3.4-4.4-2.1-5.6-2-3.7-5.9-0.8-5.3-0.2-1.8-2-5.5-4.6-3.7-4-2.6-0.7-2.9 1-2.3 4-1.8 2.2-3.5-1.4-4.2 4.3-2.5 2.2-2.1-1.2-4.4 1.1-1.9 1.1-3 3.7-2.7 5.4-1.2 5.3-0.2 3.8-3.4 1-6.2 2.8-3.7 5.5-2 3.3-2.3 1.1-3.6 2.3-9.1 0.9-6-0.7-5.2-0.8-3.9-2.3-2.9-1.5-2.9 4.1-6.8 0.1-2.7 1.8-5.1 2.8-6.1 2.2-6.3 1.1-7.2 0.5-5.4-1.3-3.2-1.5-2.4 1.7-5.5 3.7-7.7 5.8-7.6 0.1-2.7-1-3.3-3.8-2.4-2-2.2-0.2-7.2 2.7-2.1 4.7-1.6 3.8-1.7-0.2-2.6-1-4.5z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWTTT" name="台東" d="M634.7 759.1l2.8-0.4-0.9-3.5-4.4-4.6-2.2-3.3-1-5.9 1.7-7 6.2-5.3 3.1-4.2 0-8.1 2.2-9.5-1.6-7.1 0.7-5 5.3-2.9 1.9-3.5-1.6-4.3 0.6-4.1 5.6-3.7 2.9-2.8 4.7-2.9 11.2-2.8 0.8 5.3 3.7 5.9 5.6 2 4.4 2.1 3.6 3.4 4.5 0.7 4.1 1.1 6.6 11.5 8.5 7 5.9 0.8 4.7-2.7 0.6-4.4 0-4.9 2.2-4.3 3.5-9.6 2.6-5.5 1.8-6.1 1.9-4.8 2.5-3.7 2.6-5-0.4-4.9-1.3-5 2.8-3.9 7.8-3.8 2.5 0.8-3.3 19-1.6 3.5-5.1 6.8-1.9 3.5-1.5 4.4-1 8.3 0.1 7.3-0.8 6.9-3.5 7.2-1.5 1.6-3.4 2.5-1.5 1.6-0.8 1.6-1.2 4.2-3.5 6.1-2.1 9.4-1.5 4.2-7.4 10.7-0.9 2-10 8.4-2.4 2.8-0.4 1.9 0.5 4.5-0.1 2-0.9 2.3-1.6 2.6-3.4 4.3-3.4 3.2-11.6 7.8-7.8 8.5-1.9 1-1.5 2-3.8 9.7-1.8 3.6-5.8 7.3-2.4 4.3-1.3 8.8-3.5 12.1-6.9 12.1-1 4.1-1.2 11.6 0.2 10.5-3.2 0.3-7.4-3.4-3.3-3.5-2.3-4.3-0.4-4.4 0.1-4.1-2.3-3.2-2.4-1.2-2-2.8 0.4-3.3 1.5-2.8 3.8-2.3 1.8-2.7-3.3-4-1.9-3.7 0-3.8-0.8-5.1-1.4-4.4-0.9-4.7 0.6-10.6 2.2-5.4 2.6-4.8 1.7-4.7 3.9-3.2 5.5-1.2 3.5-2 7-3 1.5-3.5 0.1-3.8 2-9.9-4-2.6-3.9-1-0.5-3.5-2.5-4.7z m134.6 166.8l3.3 2.6 1.5 1.7-0.2 2-3.9 1.3-5.3-2.2-4.9-3.4-2.8-2.7 0.8-1.9 0-1.9-0.7-1.6-1.3-1.5 14.1 0 0 1.2-0.4 0.8-0.6 1.7-0.2 2.1 0.6 1.8z m-19.5-125.9l-1-3 0.4-0.4 7.3-0.6 0.8 0.5 0.5 1.4-0.6 2.8-0.6 1.2-0.3 1.2 0.3 1.1-0.1 0.8-0.5-0.1-1.3 0-0.6-0.2-0.3-0.4-1.9-0.7-2.1-3.6z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
        <path id="TWKIN" name="金門" d="M776.8 321.1l-4.2 0-3.5-0.8-2.6-2.3-2.8-3.2-4.1-3.2-2.9-4.9 1.1-5.3-0.8-4.5-4.2-4-2.7-3.1 1.2-2.1 1.3-1.7 1.5-3.3 2.6-2.9 7.8-4.7 2.1-1.8 2.9-1.4 2.8 0.9 1.5 1.6-0.4 2.6 0.3 2.4 1.1 2.4 1.2 2.6 1.8 7.2 2.8 2.5 1.1 3.2-1.1 4.8 0.1 3.6 3.3 1.9 2.7 2.3-1.4 3-5.5 7-3 1.2z" @mouseenter="hoveredName = $event.target.getAttribute('name')" @mouseleave="hoveredName = ''" @click="handleClick($event)" />
      </g>
    </svg>
    <div v-if="hoveredName" class="map-label">
      {{ hoveredName }}
    </div>
  </div>
</template>

<script setup>
import { ref } from 'vue'
import { defineProps } from 'vue'

const props = defineProps({
  maxWidth: { type: Number, default: 400 } // 你可以自定義大小
})

// 暫存 hover 名稱
const hoveredName = ref('')

// 點擊時 emit
const emit = defineEmits(['select'])

const handleClick = (e) => {
  const name = e.target.getAttribute('name')
  emit('select', name)
}

const mapContainer = ref(null)
</script>

<style scoped>
.taiwan-map-wrapper {
  width: 100%;
  aspect-ratio: 225 / 415;
  margin: 0 auto;
  background-color: #12150e;
  position: relative;
  padding: 1rem;
}

.map-svg {
  width: 100%;
  height: 100%;
  display: block;
}

.map-label {
  position: absolute;
  top: 5%;
  left: 5%;
  padding: 0.5em 1em;
  background-color: rgba(255, 215, 0, 0.9);
  color: #12150e;
  border-radius: 0.5em;
  font-size: 1.2vw;
  font-weight: bold;
  font-family: 'Inter', sans-serif;
  box-shadow: 0 0 8px rgba(255, 215, 0, 0.5);
  pointer-events: none;
}

path {
  stroke: #d1ad41;
  stroke-width: 1;
  fill: transparent;
  cursor: pointer;
  transform-origin: center;
  transform-box: fill-box;
  transition: transform 0.3s ease, fill 0.3s ease;
}

path:hover {
  transform: scale(1.1);
  fill: #d1ad41;
  opacity: 0.5;
}
</style>