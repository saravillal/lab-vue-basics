<template>
<div class="FooterMenu">
<h1> Footer </h1>
<ul>
    <li>
        <a href="#">Home</a>
    </li>
    <li>
        <a href="#">About</a>
    </li>
    <li>
      <a href="#">Contact Us</a>
    </li>
</ul>
</div>
</template>

<script>
export default {
  name: 'FooterMenu',
  props: {
    msg: String,
  },
};
</script>
