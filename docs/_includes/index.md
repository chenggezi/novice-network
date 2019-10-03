<div class=mnheader>
    <h1>《新大陆见闻录》<img src="/images/title.png" alt="新大陆见闻录" /></h1>
    <div class="desc">
        <p>由于《最终幻想14》游戏内容繁多，新人上手也不够友好，新人经常面临迷茫。
            鉴于此，本站，即 **《新大陆见闻录》** 希望能给刚进入《最终幻想14》国服的玩家提供入门级别的攻略指引，帮助新玩家更好地游玩这个游戏。</p>
        <p>新大陆见闻录提供完整的手机布局，确保各位玩家能通过手机、平板访问本站的所有内容。用电脑访问时，工具栏右上角会显示二维码按钮 <i class="ui icon qrcode"></i> ，鼠标悬浮即可显示当前页面二维码，扫码即可在手机上打开当前页面。</p> 
        <p>你可以通过 ==左侧侧边栏== （电脑）或 ==左下角绿色按钮（手机）== 查看本站的目录。</p>
    </div>
</div>
<div class="mntab mn-before">
    <h2>入坑准备</h2>
    <ul>
        <li><a href="before/pay.html">收费及入坑福利</a></li>
        <li><a href="before/world.html">世界观与游戏版本</a></li>
        <li><a href="before/char.html">选服捏人</a></li>
        <li><a href="before/job.html">职业选择</a></li>
    </ul>
</div>
<div class="mntab mn-guide">
    <h2>新人指南</h2>
    <ul>  
        <li><a href="basic/core.html">新人必知</a></li>
        <li><a href="basic/battle.html">战斗基础</a></li>
        <li><a href="basic/#">练级指南</a></li>
        <li><a href="basic/config.html">常用设置</a></li>
    </ul>
</div>
<div class="mntab mn-sys">
    <h2>游戏系统</h2>
    <ul>
        <li><a href="basic/quest.html">推荐任务</a></li>
        <li><a href="basic/equip.html">装备品级提升与幻化</a></li>
        <li><a href="basic/map.html">地图移动与飞行</a></li>
        <li><a href="#">货币系统</a></li>
    </ul>
</div>
<div class="mntab mn-battle">
    <h2>战斗玩法</h2>
    <ul>
        <li><a href="#">休闲战斗</a></li>
        <li><a href="#">副本挑战</a></li>
        <li><a href="#">PVP排位与战场</a></li>
        <li><a href="#">发光武器</a></li>
        <li><a href="#">青魔法师</a></li>
    </ul>
</div>
<div class="mntab mn-play">
    <h2>日常休闲</h2>
    <ul>
        <li><a href="#">每日/每周任务</a></li>
        <li><a href="#">剧情任务</a></li>
        <li><a href="#">金碟游乐场</a></li>
        <li><a href="#">自娱自乐</a></li>
        <li><a href="#">社交活动</a></li>
    </ul>
</div>
<div class="mntab mn-play">
    <h2>生产采集</h2>
    <ul>
        <li><a href="#">能工巧匠</a></li>
        <li><a href="#">大地使者</a></li>
        <li><a href="#">挥杆降龙</a></li>
    </ul>
</div>

<style>
    .content.default{
        display:flex;
        flex-wrap: wrap;
    }
    .mnheader{
        width: 100%;
        display: flex;
        position: relative;
    }
    .mnheader h1{
        flex: auto;
        font-size: 0;
    }
    .mnheader .desc{
        font-size: .8em;
        color: #666;
    }
    .mntab{
        flex: 1 1 0;
        margin: 0 2px;
        padding: 5px 0;
        background: #f0f4c3;
        border-radius: 4px;
        border: 1px solid #aeea00;
    }
    .mntab h2{
        margin: 5px 20px;
    }
    .mntab ul{
        list-style: none;
        padding: 0;
        margin: 0;
    }
    .mntab li a{
        display: block;
        color: #33691e;
        font-size: 1.2em;
        padding: 5px 20px;
    }
    .mntab li a:hover{
        background: #aeea00;
        transition: all .3s;
    }
    .included-page~*{
        display: none;
    }
    @media screen and (max-width: 960px){
        /*小屏幕*/
        .mnheader{
            flex-wrap: wrap;
        }
        .mnheader h1{
            width: 100%;
            text-align: center;
        }
        .content.default{
            flex-direction: column;
        }
        .mntab{
            margin: 2px 0;
        }
    }
</style>