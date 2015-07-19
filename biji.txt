1、background-size 必须设置在background之后才能生效
2、定位的span可以设置宽高
3、initial可以作为所有属性的值，表示默认的样式
4、降级（功能衰减）意味着往回看；而渐进增强则意味着朝前看，同时保证其根基处于安全地带。
5、可以用到渐进增强的css3属性为：圆角、阴影、动画
6、如果要媒体插叙起效果，媒体查询必须放在后面。若媒体查询放前面，则字体大小还是17px。
    .about-top p{
	  font-size:17px;
	}
	@media (max-width: 640px){
		.about-top p.about-p {
	  		font-size:14px;
		}
	}