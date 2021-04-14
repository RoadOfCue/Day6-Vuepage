<template>
    <div class="main">
        <div class="content">
            <div class="icon">
                <div class="top">ONE</div>
                <div class="tail"></div>
            </div>
            <div class="title">连线学习</div>
            <div class="brief">
                <div class="top">NEW</div>
                <div class="text">可以创建私密学习房，和好友学习不再被人打扰</div>
            </div>
            <img class="bg" src="../assets/one-bg.png" alt="">
            <div class="button">试试新的连线学习</div>
            <div class="foot"></div>
        </div>
        <div class="content two">
            <div class="icon">
                <div class="top">TWO</div>
                <div class="tail"></div>
            </div>
            <div class="title">树洞对讲机</div>
            <div class="brief">
                <p>学习生活中遇到烦心事？快来这里和小伙伴们一起吐槽！</p>
                <div class="text"><div class="top">NEW</div>频道内有主题，方便你找到组织</div>
                <div class="text"><div class="top">NEW</div>对讲人数无上限，一起吐槽一起high！</div>
                <div class="text"><div class="top">NEW</div>频道内直接组学习局，遇到合拍的人别放走！</div>
            </div>
            <div class="button">频道high聊中，快去看看></div>
            <div class="foot"></div>
        </div>
    </div>
</template>

<script>
export default {
    data(){
        return{

        }
    }
}
</script>

<style lang="scss" scoped>
    $bg-color: #ffeec0;

    .main{
        width: 80%;
        margin: 15rem auto 0;
    }

    .content{
        margin: 0 auto;
        width: 90%;
        height: 130rem;
        background-color: $bg-color;
        position: relative;
        border: 1px solid #0e4a8d;
        border-radius: 15rem;
        .title{
            position: absolute;
            top: 0;
            left: 50%;
            transform: translate(-50%,-50%);
            width: 80rem;
            height: 30rem;
            line-height: 30rem;
            background-color: $bg-color;
            text-align: center;
            font-size: 12rem;
            font-weight: bold;
            color: #4d290a;
            letter-spacing: 0.5rem;
        }
        .icon{
            position: relative;
            top: -28%;
            left: 23%;
            z-index: 2;
            transform: rotate(-20deg);
            .top{
                color: #fff;
                width: 15rem;
                height: 8rem;
                line-height: 8rem;
                background-color: #ff2239;
                border-radius: 2rem;
                text-align: center;
            }
            .tail{
                margin-left: 5rem;
                width: 0;
                height: 0;
                border-top: 2rem solid #ff2239;
                border-left: 2rem solid transparent;
                border-right: 2rem solid transparent;
            }
        }
        .brief{
            margin: 0 auto;
            position: relative;
            width: 80%;
            font-size: 6.7rem;
            .top{
                top: -30%;
                left: -10%;
                position: absolute;
                color: #ff2239;
                transform: rotate(-20deg);
                font-size: 6rem;
            }
        }
        .bg{
            display: block;
            margin: 0 auto;
            width: 80%;
        }
        .button{
            width: 80%;
            height: 16rem;
            line-height: 16rem;
            text-align: center;
            font-size: 8rem;
            color: rgb(240, 235, 235);
            margin: 0 auto;
            background-color: #0e4a8d;
            border-radius: 10rem;
            letter-spacing: 0.6rem;
        }
        .foot{
            position: absolute;
            left: 50%;
            transform: translateX(-50%);
            width: 50rem;
            height: 10rem;
            background-color: $bg-color;
        }
    }

    .two{
        margin-top: 25rem;
        .icon{
            top: -29%;
            left: 18%;
        }
        p{
            margin: 4rem 0 8rem;
        }
        .text{
            position: relative;
            margin-bottom: 6rem;
            color: #4d290a;
            font-weight: bold;
            font-size: 7rem;
            .top{
                position: absolute;
                top: -24%;
                left: -10%;
                
            }
        }
    }
</style>