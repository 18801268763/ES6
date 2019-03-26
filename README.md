# ES6
ES6学习
ES6数组去重
<script>
    var arr = [1,1,'1','1',null,null,true,true,undefined,undefined,NaN,NaN];
    var unique = Array.from(new Set(arr));
    console.log(unique);
</script>
