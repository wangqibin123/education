<template>
  <div class="country">
    <div class="country-top">
        <h2>
            <svg class="icon" aria-hidden="true">
                <use :xlink:href="data.icon"></use>
            </svg>
            {{data.name}}留学
        </h2>
        <div>
            <ul>
                <li>{{data.name}}留学频道</li>
                <li>{{data.name}}留学院校库</li>
            </ul>
        </div> 
    </div>
    <div class="country-center">
        <div class="center-lift" :style="{background:data.background,height:'487px'}">
            <div class="left-top">
                <div class="top-title">
                    <span>01</span>
                    直接申请
                </div>
                <ul>
                    <li>
                        <span>学制</span>
                        本科4年；硕士2年
                    </li>
                    <li>
                        <span>学制</span>
                        本科4年；硕士2年
                    </li>
                    <li>
                        <span>学制</span>
                        本科4年；硕士2年
                    </li>
                    <li>
                        <span>学制</span>
                        本科4年；硕士2年
                    </li>
                    <li>
                        <span>学制</span>
                        本科4年；硕士2年
                    </li>
                </ul>
            </div>
            <div class="left-center">
                <div class="top-title">
                    <span>02</span>
                    中外合作
                </div>
                <ul>
                    <li>
                        <span>学制</span>
                        本科4年；硕士2年
                    </li>
                    <li>
                        <span>学制</span>
                        本科4年；硕士2年
                    </li>
                    <li>
                        <span>学制</span>
                        本科4年；硕士2年
                    </li>
                    <li>
                        <span>学制</span>
                        本科4年；硕士2年
                    </li>
                    <li>
                        <span>学制</span>
                        本科4年；硕士2年
                    </li>
                </ul>
            </div>
            <a class="left-botton">
                <span>进入美国留学频道</span>
            </a>
        </div>
        <div class="center-moddle" style="height:487px;">
            <div class="center-top">
                <ul>
                    <li>{{data.recommend}}</li>
                    <li v-if="data.recommends.length!=0">{{data.recommends}}</li>
                </ul>
            </div>
            <div class="center-moddles">
                <div class="one">
                    <a href=""><img src="../assets/16279652616108c74de934c.jpg"></a>
                    <span>北京航空航天大学出国留学</span>
                </div>
                <div class="one">
                    <a href=""><img src="../assets/16279652616108c74de934c.jpg"></a>
                    <span>北京航空航天大学出国留学</span>
                </div>
                <div class="one">
                    <a href=""><img src="../assets/16279652616108c74de934c.jpg"></a>
                    <span>北京航空航天大学出国留学</span>
                </div>
                <div class="one">
                    <a href=""><img src="../assets/16279652616108c74de934c.jpg"></a>
                    <span>北京航空航天大学出国留学</span>
                </div>
                <div class="one">
                    <a href=""><img src="../assets/16279652616108c74de934c.jpg"></a>
                    <span>北京航空航天大学出国留学</span>
                </div>
                <div class="one">
                    <a href=""><img src="../assets/16279652616108c74de934c.jpg"></a>
                    <span>北京航空航天大学出国留学</span>
                </div>
            </div>
            <div class="center-bottom">
                <div>加拿大留学招生简章</div>
                <ul>
                    <li>
                        <a href="">【中央财经大学】</a>
                        <a href="" title="3+2留学招生简章">3+2留学招生简章</a>
                    </li>
                    <li>
                        <a href="">【中央财经大学】</a>
                        <a href="" title="3+2留学招生简章">3+2留学招生简章</a>
                    </li>
                    <li>
                        <a href="">【中央财经大学】</a>
                        <a href="" title="3+2留学招生简章">3+2留学招生简章</a>
                    </li>
                    <li>
                        <a href="">【中央财经大学】</a>
                        <a href="" title="3+2留学招生简章">3+2留学招生简章</a>
                    </li>
                    <li>
                        <a href="">【中央财经大学】</a>
                        <a href="" title="3+2留学招生简章">3+2留学招生简章</a>
                    </li>
                    <li>
                        <a href="">【中央财经大学】</a>
                        <a href="" title="3+2留学招生简章">3+2留学招生简章</a>
                    </li>
                </ul>
            </div>
        </div>
        <div class="center-right" style="height:360px;">
            <zwh></zwh>
        </div>
    </div>
  </div>
</template>

<script>
import zwh from "@/views/zwhzlx/index.vue";

export default {
     props:['data'],
     mounted(){
         console.log(this.data);
     },
     components:{
         zwh
     }
}
</script>

<style lang='scss' scoped>
.country{
    width: 1200px;
    margin: 0 auto;
    margin-bottom: 40px;
    background: #fff;
    @media only screen and (max-width: 1200px) {
        width:95%;
    }
    @media only screen and (max-width: 768px) {
        margin-bottom:5%;
    }
}
.icon {
    width: 1em; height: 1em;
    vertical-align: -0.15em;
    fill: currentColor;
    overflow: hidden;
}
.country-top{
    height: 54px;
    position: relative;
    overflow: hidden;
    background: #fff;
    box-shadow: 0 3px 3px rgb(0 0 0 / 10%);
}
.country-top h2{
    background: #435d89;
    font-size: 26px;
    color: #fff;
    padding: 10px;
    font-weight: 700;
    float: left;
    height: 54px;
    position: relative;
    @media only screen and (max-width: 768px) {
        font-size: 22px;
    }
}
.country-top h2::before{
    content: '';
    position: absolute;
    display: inline-block;
    background-image: url(../assets/mg-md-tit-bg.jpg);
    width:52px;
    height: 54px;
    top: 0;
    right: -49px;
}
.country-top div{
    float: right;
    width: 669px;
    height: 54px;
    font-size: 16px;
    line-height: 54px;
    color: #333;
    @media only screen and (max-width: 460px) {
        display: none;
    }
    ul{
        width: 100%;
        li{
            float: right;
            min-width: 167px;
        }
    }
}
.country-center{
    padding: 20px 16px;
    overflow: hidden;
    .center-lift{
        padding: 15px 15px;
        width: 358px;
        float: left;
        box-sizing: border-box;
        @media only screen and (max-width: 800px) {
            width: 100%;
        }
        .left-top{
            margin-bottom: 20px;
        }
        .top-title{
            position: relative;
            padding-left: 18px;
            margin-bottom: 13px;
            font-size: 16px;
            font-weight: bold;
            line-height: 1;
            span{
                position: absolute;
                display: block;
                width: 26px;
                left: -15px;
                font-size: 12px;
                line-height: 16px;
                text-align: center;
                font-weight: normal;
                color: #fff;
                border-radius: 0 20px 20px 0;
                background: #435d89;
            }
        }
        ul{
            background: #fff;
            padding: 10px 0 0;
            border-radius: 4px;
            border: 1px solid #d9d9e9;
            font-size: 14px;
            li{
                position: relative;
                list-style-type: none;
                padding-left: 83px;
                padding-bottom: 10px;
                span{
                    color: #435d89 !important;
                    background: #f3f3f7 !important;
                    position: absolute;
                    width: 76px;
                    left: 0;
                    top: 0;
                    line-height: 18px;
                    border: 1px solid #36477a;
                    border-radius: 2px;
                    color: #36477a;
                    text-align: center;
                    border-color: #e0eced !important;
                    border-left: none !important;
                }
                span::before{
                    content: '';
                    display: block;
                    content: '';
                    position: absolute;
                    width: 11px;
                    height: 20px;
                    background: url(../assets/mg-md-sj.jpg) no-repeat center center;
                    top: -1px;
                    right: -1px;
                }
            }
        }
        .left-botton{
            display: block;
            width: 100%;
            font-size: 16px;
            line-height: 18px;
            padding: 8px 0;
            text-align: center;
            color: #36477a;
            border-radius: 4px;
            border: 1px solid #36477a;
            margin-top: 17px;
            border-color: #625990;
            color: #435d89;
            @media only screen and (max-width: 800px) {
                position: static;
                max-width: 270px;
                margin: 3% auto 0;
                font-size: 15px;
            }
        }
    }
    .center-moddle{
        padding: 15px 15px 10px;
        margin: 0 16px;
        width: 388px;
        float: left;
        box-sizing: border-box;
        border-radius: 4px;
        overflow: hidden;
        border: 1px solid #e7e7e7;
        @media only screen and (max-width: 800px) {
            width: 100%;
            margin: 0;
        }
        .center-top{
            margin-bottom: 14px;
            overflow: hidden;
            ul{
                margin-top: -10px;
                padding-left: 0;
                margin-bottom: 0;
                list-style: none;
                li{
                    width: 50%;
                    float: left;
                    margin-bottom: 0;
                    text-align: center;
                    position: relative;
                    padding: 6px 0 12px;
                    margin: 0;
                    font-size: 16px;
                    border: none !important;
                    background: #fff !important;
                    cursor: pointer !important;
                }
                li:hover{
                    color: #625990 !important;
                }
            }
        }
        .center-moddles{
            overflow: hidden;
            .one{
                width: 42.5%;
                float: left;
                font-size: 14px;
                padding: 3%;
                border: 1px solid #e7e7e7;
                margin-bottom: 10px;
                a{
                    display: inline-block;
                    width: 36px;
                    height: 36px;
                    float: left;
                    img{
                        width: 100%;
                        height: 100%;
                    }
                }
                span{
                    height: 36px;
                    overflow: hidden;
                }
            }
            .one:nth-of-type(2n){
                margin-left: 1%;
            }
        }
        .center-bottom{
            div{
                position: relative;
                height: 20px;
                line-height: 20px;
                margin-bottom: 8px;
                padding-left: 13px;
                margin-left: -15px;
                font-size: 16px;
            }
            li{
                height: 30px;
                font-size: 14px;
            }
        }
    }
    .center-right{
        width: 390px;
        float: left;
        @media only screen and (max-width: 800px) {
            width: 100%;
        }
    }
}
</style>
