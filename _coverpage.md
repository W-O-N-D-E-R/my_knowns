<!-- 封面 -->

<style>
    section.cover{
        background: unset!important;
    }
    #video{
		position: fixed;
        right: 0;
		bottom: 0;
		width: auto;
        height: auto;
        min-width: 100%;
        min-height: 100%;
        z-index: -1;
	}
    .cover-main{
        user-select: none;
    }
    .cover-main img{
        -webkit-user-drag: none;
    }
    .cover-main p{
        color: #fff;
        cursor: default;
    }
    .cover-main p a, .cover-main p a:hover{
        text-decoration: underline;
    }
</style>
<!-- 封面 -->

![logo](./static/images/head.jpg ':size=100')

<video id="video" autoplay loop muted onloadstart="document.querySelector('#catLoading').style.display = 'flex'" onplay="document.querySelector('#catLoading').style.display = 'none'" onerror="document.querySelector('#catLoading').style.display = 'none'">
    <source id="mp4" src="./static/video/forest.mp4" type="video/mp4">
</video>

**wonder**

的个人知识库

各平台资料汇总整理

不定期更新、不定期删除

且看且珍惜

[Blog](https://w-o-n-d-e-r.github.io)

[GitHub](https://github.com/W-O-N-D-E-R)

[随便看看](./README)
