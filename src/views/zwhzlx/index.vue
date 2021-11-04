<template>
        <div class="lxyk">
            <div class="tab_header">
                <li 
                    v-for="item,index in tabTitle" 
                    :key="index" 
                    @click="cur=index" 
                    :class="{active:cur==index}"
                >
                    {{item}}
                </li>
            </div>
            <div class="tab_content">
                <div class="new_list" v-show="cur==0">
                    <ul>
                        <li>
                            <a href="" title="2022年出国留学申请发生哪些变化？">2022年出国留学申请发生哪些变化？</a>
                            <span>11-02</span>
                        </li>
                        <li>
                            <a href="" title="通过留学预科出国留学，去哪个国家留学比较容易？">通过留学预科出国留学，去哪个国家留学比较容易？</a>
                            <span>10-30</span>
                        </li>
                        <li>
                            <a href="" title="留学预科与3+2留学有什么区别？">留学预科与3+2留学有什么区别？</a>
                            <span>10-28</span>
                        </li>
                        <li>
                            <a href="" title="出国留学要不要读预科？">出国留学要不要读预科？</a>
                            <span>10-19</span>
                        </li>
                        <li>
                            <a href="" title="留学预科与直申留学有什么区别？">留学预科与直申留学有什么区别？</a>
                            <span>09-18</span>
                        </li>
                        <li>
                            <a href="" title="国内大学的留学预科项目好不好？">国内大学的留学预科项目好不好？</a>
                            <span>09-17</span>
                        </li>
                        <li>
                            <a href="" title="出国留学先读预科班有哪些优势？">出国留学先读预科班有哪些优势？</a>
                            <span>09-09</span>
                        </li>
                        <li>
                            <a href="" title="怎么申请国内名校留学预科班？">怎么申请国内名校留学预科班？</a>
                            <span>09-03</span>
                        </li>
                        <li>
                            <a href="" title="出国留学先在国内读留学预科怎么样?">出国留学先在国内读留学预科怎么样?</a>
                            <span>08-26</span>
                        </li>
                        <li>
                            <a href="" title="重点大学的留学预科班靠谱吗？">重点大学的留学预科班靠谱吗？</a>
                            <span>08-23</span>
                        </li>
                        <li>
                            <a href="" title="留学预科班适合哪些孩子读？">留学预科班适合哪些孩子读？</a>
                            <span>08-17</span>
                        </li>
                    </ul>
                    <span class="more">查看更多留学预科动态&gt;&gt;</span>
                </div>

                <div class="new_list" v-show="cur==1">
                    <ul>
                        <li>
                            <a href="" title="出国留学预科班费用高吗？">出国留学预科班费用高吗？</a>
                            <span>11-02</span>
                        </li>
                        <li>
                            <a href="" title="读完留学预科申请出国留学需要满足哪些条件？">读完留学预科申请出国留学需要满足哪些条件？</a>
                            <span>10-28</span>
                        </li>
                        <li>
                            <a href="" title="留学预科一年要花多少钱？">留学预科一年要花多少钱？</a>
                            <span>10-27</span>
                        </li>
                        <li>
                            <a href="" title="国内大学的留学预科班好不好考?">国内大学的留学预科班好不好考?</a>
                            <span>10-26</span>
                        </li>
                        <li>
                            <a href="" title="出国留学预科班有哪些选择？">出国留学预科班有哪些选择？</a>
                            <span>10-25</span>
                        </li>
                        <li>
                            <a href="" title="山东有英国留学预科院校吗？">山东有英国留学预科院校吗？</a>
                            <span>10-24</span>
                        </li>
                        <li>
                            <a href="" title="国内大学的留学预科好考吗？">国内大学的留学预科好考吗？</a>
                            <span>10-15</span>
                        </li>
                        <li>
                            <a href="" title="国内大学的留学预科项目可以申请国外什么大学？">国内大学的留学预科项目可以申请国外什么大学？</a>
                            <span>10-14</span>
                        </li>
                        <li>
                            <a href="" title="出国留学预科学校申请条件有哪些？">出国留学预科学校申请条件有哪些？</a>
                            <span>10-12</span>
                        </li>
                        <li>
                            <a href="" title="哪些高校的留学预科班比较可信？">哪些高校的留学预科班比较可信？</a>
                            <span>10-11</span>
                        </li>
                        <li>
                            <a href="" title="北京哪个大学的留学预科班比较好?">北京哪个大学的留学预科班比较好?</a>
                            <span>10-08</span>
                        </li>
                    </ul>
                    <span class="more">查看更多留学预科择校指南&gt;&gt;</span>
                </div>

                <div class="new_list" v-show="cur==2">
                    <ul>
                        <li>
                            <a href="" title="对外经济贸易大学韩国留学预科录取原则是什么？">对外经济贸易大学韩国留学预科录取原则是什么？</a>
                            <span>11-04</span>
                        </li>
                        <li>
                            <a href="" title="中国传媒大学留学预科音乐专业可以申请哪些国外名校？">中国传媒大学留学预科音乐专业可以申请哪些国外名校？</a>
                            <span>11-04</span>
                        </li>
                        <li>
                            <a href="" title="北外留学预科班和北京外国语大学有关系吗？">北外留学预科班和北京外国语大学有关系吗？</a>
                            <span>11-03</span>
                        </li>
                        <li>
                            <a href="" title="申请中国传媒大学艺术留学预科学历要求是什么？">申请中国传媒大学艺术留学预科学历要求是什么？</a>
                            <span>11-02</span>
                        </li>
                        <li>
                            <a href="" title="北京第二外国语学院日本留学可选预科班有哪些？">北京第二外国语学院日本留学可选预科班有哪些？</a>
                            <span>11-02</span>
                        </li>
                        <li>
                            <a href="" title="对外经济贸易大学韩国留学预科课程学费是多少？">对外经济贸易大学韩国留学预科课程学费是多少？</a>
                            <span>11-01</span>
                        </li>
                        <li>
                            <a href="" title="对外经济贸易大学韩国留学预科需要高考成绩吗？">对外经济贸易大学韩国留学预科需要高考成绩吗？</a>
                            <span>10-29</span>
                        </li>
                        <li>
                            <a href="" title="中国传媒大学留学预科艺术专业一年多少钱？">中国传媒大学留学预科艺术专业一年多少钱？</a>
                            <span>10-29</span>
                        </li>
                        <li>
                            <a href="" title="西北大学马来西亚留学预科班现在还可以报考吗？">西北大学马来西亚留学预科班现在还可以报考吗？</a>
                            <span>10-28</span>
                        </li>
                        <li>
                            <a href="" title="对外经济贸易大学英美澳加留学预科好不好？">对外经济贸易大学英美澳加留学预科好不好？</a>
                            <span>10-28</span>
                        </li>
                        <li>
                            <a href="" title="北京外国语大学留学预科哪个项目比较好？">北京外国语大学留学预科哪个项目比较好？</a>
                            <span>10-28</span>
                        </li>
                        <li>
                            <a href="" title="中央财经大学日本留学预科好不好？">中央财经大学日本留学预科好不好？</a>
                            <span>10-27</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
</template>
<script>
    export default{
        data(){
            return{
                tabTitle: ['留学预科动态', '择校指南', '招生院校'],
                // tabMain: ['测试数据一', '测试数据二', '测试数据三'],
                cur: 0 
            }
             
        }
    }
</script>
<style>
    body {
        margin: 0;
        padding: 0;
    }

    /* :root {
        overflow-y: auto;
        overflow-x: hidden;
    }

    :root body {
        position: absolute;
    } */
    .lxyk{
        width: 100%;
        height: auto;
        box-sizing: border-box;
        margin-top: 0.5rem;
        margin-bottom: .5rem;
    }
    .tab_header{
        width: 100%;
        height: .5rem;
        display: flex;
        background: #F2F2F2;
        box-sizing: border-box;
    }
    .tab_header>li{
        flex:1;
        text-align: center;
        line-height: .5rem;
    }
    .active{
        background: #36477A;
        font-weight: 700;
        color: white;
    }
    .tab_content{
        width: 100%;
        height: 3rem;
        background: white;
    }
    .new_list{
        width: 98%;
        border: 0.01rem solid #F0F0F0;
        height: auto;
        margin: 0 auto;
        /* background: pink; */
    }
    .new_list>ul{
        width: 92%;
        margin: 0 auto;
    }
    .new_list>ul>li{
        margin-top: 0.05rem;
        margin-bottom: 0.05rem;
        font-size: 0.12rem;
        display: flex;

    }
    .new_list>ul>li>a{
        flex: 1;
    }
    .more{
        margin-top: .2rem;
        margin-bottom: .2rem;
        display: flex;
        justify-content: center;
        color: #36477A;
        font-size: .12rem;
    }
</style>