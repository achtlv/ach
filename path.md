### ACH跳转器

**作者：[achtlv](https://achtlv.kdns.fr/c/)**

<style>
.ach-form{
  display:flex; flex-wrap:nowrap; align-items:center; gap:8px;
  width:100%; max-width:450px;   /* 桌面端总宽，调这个改整体长度 */
  box-sizing:border-box;
}
.ach-form input[name="p"]{
  flex:5 1 0; width:0; min-width:0; box-sizing:border-box;  /* 占 5 份 */
  padding:10px 14px; font-size:15px; border:1px solid #d5d8dd;
  border-radius:8px; outline:none;
}
.ach-form input[type="submit"]{
  flex:1 1 0; min-width:fit-content; box-sizing:border-box; /* 占 1 份 */
  white-space:nowrap; padding:10px 12px; font-size:15px;
  border:none; border-radius:8px; background:#2f6fed;
  color:#fff; cursor:pointer;
}

/* 小屏（手表、手机）：占满一行，比例仍 5:1 */
@media (max-width: 600px){
  .ach-form{ max-width:100%; }
}
</style>

<form class="ach-form" action="https://l.achtlv.kdns.fr/shortlinks" method="get">
  <input name="p" placeholder="路径&amp;参数">
  <input type="submit" value="确认">
</form><form action="https://l.achtlv.kdns.fr/shortlinks" method="get"
      style="display:flex; flex-wrap:nowrap; align-items:center; gap:8px;
             width:100%; max-width:100%; box-sizing:border-box;">
  <input name="p" placeholder="路径&amp;参数"
         style="flex:1 1 0; width:0; min-width:0; box-sizing:border-box;
                padding:10px 14px; font-size:15px; border:1px solid #d5d8dd;
                border-radius:8px; outline:none;">
  <input type="submit" value="确认"
         style="flex:0 0 auto; white-space:nowrap;
                padding:10px 20px; font-size:15px; border:none;
                border-radius:8px; background:#2f6fed; color:#fff; cursor:pointer;">
</form>
