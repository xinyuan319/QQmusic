<template>
	<view>
		<!-- 搜索框 -->
		<view><input type="text" placeholder="搜索"  id="inp1"/></view>
		<!-- 热门推荐 -->
		<view>
		<view class="gd">
			<text class="left">歌曲推荐</text>
			<text class="rigth">更多></text>
		</view>
		<view class="gqtj">
			<view>
				<view class="left gqtjt"><image src="../../static/QQt/gqtj1.webp"></image></view>
				<view class="left gqtjz">
					<view class="left">
						飞鸟和蝉<br/>
						<text class="te1">SQ</text>
						<text class="te2">独家</text>
						<text class="te3">任然·飞鸟和蝉</text>
					</view>
					<view class="te4">></view>
					</view>
			</view>
		</view>
		<view class="gqtj">
			<view>
				<view class="left gqtjt"><image src="../../static/QQt/gqtj2.webp"></image></view>
				<view class="left gqtjz">
					<view class="left">
						和你在一起<br/>
						<text class="te1">SQ</text>
						<text class="te2">独家</text>
						<text class="te3">TFBOYS·和你在一起</text>
					</view>
					<view class="te4">></view>
					</view>
			</view>
		</view>
		<view class="gqtj">
			<view>
				<view class="left gqtjt"><image src="../../static/QQt/gqtj3.webp"></image></view>
				<view class="left gqtjz">
					<view class="left">
						不知所措<br/>
						<text class="te1">SQ</text>
						<text class="te2">独家</text>
						<text class="te3">王靖雯不胖·不知所措</text>
					</view>
					<view class="te4">></view>
					</view>
			</view>
		</view>
		<view class="gqtj">
			<view>
				<view class="left gqtjt"><image src="../../static/QQt/gqtj4.webp"></image></view>
				<view class="left gqtjz">
					<view class="left">
						爸爸妈妈<br/>
						<text class="te1">SQ</text>
						<text class="te2">独家</text>
						<text class="te3">李荣浩·有理想</text>
					</view>
					<view class="te4">></view>
					</view>
			</view>
		</view>
		<view class="gqtj">
			<view>
				<view class="left gqtjt"><image src="../../static/QQt/gqtj5.webp"></image></view>
				<view class="left gqtjz">
					<view class="left">
						下山<br/>
						<text class="te2">HQ</text>
						<text class="te3">要不要买菜·下山</text>
					</view>
					<view class="te4">></view>
					</view>
			</view>
		</view>
		<view class="gqtj">
			<view>
				<view class="left gqtjt"><image src="../../static/QQt/gqtj6.webp"></image></view>
				<view class="left gqtjz">
					<view class="left">
						你是人间四月天（Live）<br/>
						<text class="te1">SQ</text>
						<text class="te2">独家</text>
						<text class="te3">邵帅·跨界歌王第五季 第5期</text>
					</view>
					<view class="te4">></view>
					</view>
			</view>
		</view>
		</view>
		<!-- 热门歌单 -->
		<view>
			<view class="gd">
				<text class="left">热门歌单</text>
				<text class="rigth">更多></text>
			</view>
			<view class="rmgd">
				<view class="rmgd1 left">
					<view class="rmgd2"><image src="../../static/QQt/rmgd1.jpg"></image></view>
					<view class="rmgd3"><image src="../../static/QQt/播放.png">3440万</image></view>
					<view class="rmgd4">运动达人专属：<br/>Adidas门店音乐</view>
				</view>
				<view class="rmgd1 left">
					<view class="rmgd2"><image src="../../static/QQt/rmgd2.jpg"></image></view>
					<view class="rmgd3"><image src="../../static/QQt/播放.png">60.3万</image></view>
					<view class="rmgd4">超燃的BGM听说你<br/>在找这一首</view>
				</view>
				<view class="rmgd1 left">
					<view class="rmgd2"><image src="../../static/QQt/rmgd3.jpg"></image></view>
					<view class="rmgd3"><image src="../../static/QQt/播放.png">416.8万</image></view>
					<view class="rmgd4">TFBOYS合辑</view>
				</view>
				<view class="rmgd1 left">
					<view class="rmgd2"><image src="../../static/QQt/gfgd1.jpg"></image></view>
					<view class="rmgd3"><image src="../../static/QQt/播放.png">2055.3万</image></view>
					<view class="rmgd4">欧美| 流行节奏控</view>
				</view>
				<view class="rmgd1 left">
					<view class="rmgd2"><image src="../../static/QQt/gfgd2.jpg"></image></view>
					<view class="rmgd3"><image src="../../static/QQt/播放.png">10802.2万</image></view>
					<view class="rmgd4">欧美| 流行轻有氧</view>
				</view>
				<view class="rmgd1 left">
					<view class="rmgd2"><image src="../../static/QQt/gfgd3.jpg"></image></view>
					<view class="rmgd3"><image src="../../static/QQt/播放.png">14580.9万</image></view>
					<view class="rmgd4">最·陈奕迅</view>
				</view>
			</view>
		</view>
		<!-- 推荐小程序 -->
		<view>
			<view class="gd">
				<text class="left">推荐小程序</text>
				<text class="rigth"></text>
			</view>
			<view class="xcx">
				<view class="left"><image src="../../static/QQt/xcx1.jpg"></image><br/>听歌识曲</view>
				<view class="left"><image src="../../static/QQt/xcx2.jpg"></image><br/>歌词海报</view>
				<view class="left"><image src="../../static/QQt/xcx3.jpg"></image><br/>睡眠电台</view>
			</view>
		</view>
		<!-- 官方歌单 -->
		<view>
			<view class="gd">
				<text class="left">官方歌单</text>
				<text class="rigth">更多></text>
			</view>
			<view class="rmgd">
				<view class="rmgd1 left">
					<view class="rmgd2"><image src="../../static/QQt/gfgd1.jpg"></image></view>
					<view class="rmgd3"><image src="../../static/QQt/播放.png">2055.3万</image></view>
					<view class="rmgd4">欧美| 流行节奏控</view>
				</view>
				<view class="rmgd1 left">
					<view class="rmgd2"><image src="../../static/QQt/gfgd2.jpg"></image></view>
					<view class="rmgd3"><image src="../../static/QQt/播放.png">10802.2万</image></view>
					<view class="rmgd4">欧美| 流行轻有氧</view>
				</view>
				<view class="rmgd1 left">
					<view class="rmgd2"><image src="../../static/QQt/gfgd3.jpg"></image></view>
					<view class="rmgd3"><image src="../../static/QQt/播放.png">14580.9万</image></view>
					<view class="rmgd4">最·陈奕迅</view>
				</view>
				<view class="rmgd1 left">
					<view class="rmgd2"><image src="../../static/QQt/rmgd1.jpg"></image></view>
					<view class="rmgd3"><image src="../../static/QQt/播放.png">3440万</image></view>
					<view class="rmgd4">运动达人专属：<br/>Adidas门店音乐</view>
				</view>
				<view class="rmgd1 left">
					<view class="rmgd2"><image src="../../static/QQt/rmgd2.jpg"></image></view>
					<view class="rmgd3"><image src="../../static/QQt/播放.png">60.3万</image></view>
					<view class="rmgd4">超燃的BGM听说你<br/>在找这一首</view>
				</view>
				<view class="rmgd1 left">
					<view class="rmgd2"><image src="../../static/QQt/rmgd3.jpg"></image></view>
					<view class="rmgd3"><image src="../../static/QQt/播放.png">416.8万</image></view>
					<view class="rmgd4">TFBOYS合辑</view>
				</view>
			</view>
		</view>
		<!-- 巅峰榜 -->
		<view>
			<view class="gd">
				<text class="left">巅峰榜</text>
				<text class="rigth"></text>
			</view>
			<view class="dfb">
				<view class="dfb1">
					<text class="dfbt1">飙升榜</text><br/>
					<text class="dfbt2">1.姐姐真漂亮</text><text class="dfbt3"> - 时代少年团</text><br/>
					<text class="dfbt2">2.Pinky Murder</text><text class="dfbt3"> - Lil Ghost小鬼</text><br/>
					<text class="dfbt2">3.硬要赢</text><text class="dfbt3"> - 硬糖少女</text>
				</view>
				<view class="dfb2">
					<image src="../../static/QQt/dfb1.webp"></image>
				</view>
				<view class="rmgd3"><image src="../../static/QQt/播放.png">2055.3万</image></view>
			</view>
			<view class="dfb">
				<view class="dfb1">
					<text class="dfbt1">新歌榜</text><br/>
					<text class="dfbt2">1.飞鸟和蝉</text><text class="dfbt3"> - 任然</text><br/>
					<text class="dfbt2">2.和你在一起</text><text class="dfbt3"> - TFBOYS</text><br/>
					<text class="dfbt2">3.不知所措</text><text class="dfbt3"> - 王靖雯不胖</text>
				</view>
				<view class="dfb2">
					<image src="../../static/QQt/dfb2.jpg"></image>
				</view>
				<view class="rmgd3"><image src="../../static/QQt/播放.png">1970万</image></view>
			</view>
			<view class="dfb">
				<view class="dfb1">
					<text class="dfbt1">新歌榜</text><br/>
					<text class="dfbt2">1.粉雾海</text><text class="dfbt3"> - 易烊千玺</text><br/>
					<text class="dfbt2">2.天外来物</text><text class="dfbt3"> - 薛之谦</text><br/>
					<text class="dfbt2">3.和你在一起</text><text class="dfbt3"> - TFBOYS</text>
				</view>
				<view class="dfb2">
					<image src="../../static/QQt/dfb3.jpg"></image>
				</view>
				<view class="rmgd3"><image src="../../static/QQt/播放.png">69.2万</image></view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {

		}
	}
</script>

<style>
	.left{float:left}
	.rigth{float:right}
	page{
		background-color: #fafafa;
		padding:0px 15px;
		}
	#inp1{
		text-align: center;
		border: 1px solid #dcdcdc;
		border-radius: 25px;
		margin-top: 20px;
	}
	.gd{padding: 20px 0px;}
	.gd text:nth-last-child(1){color: #6E6E6E;font-size: 16px;margin-top: 5px;}
	/* 歌曲推荐 */
	.gqtj{height: 60px;padding: 15px 0px;}
	.gqtjz{position: relative;width: 297px;}
	.gqtjt image{width: 70px;height: 75px;margin-right: 13px;}
	.te1{display: inline-block;border: 1px solid orange;color: orange;font-size: 10px;padding: 0px 4px;border-radius: 8px;margin: 26px 5px 0px 5px;}
	.te2{display: inline-block;border: 1px solid green;color: green;font-size: 10px;padding: 0px 4px;border-radius: 8px;margin-right: 5px;}
	.te3{color: #6E6E6E;font-size: 10px;}
	.te4{position: absolute;top: 18px;right: 0px;}
	/* 热门歌单 */
	.rmgd{height: 150px;margin-top: 20px;display: flex;overflow-x: auto}
	.rmgd1{width: 117px;position: relative;margin: 0px 4px;}
	.rmgd2 image{width: 117px;height: 117px;}
	.rmgd3{border-radius: 10px;color: #fff;font-size: 10px;width: 70px;text-align: center;
		background: rgba(0,0,0,0.3);/*父元素设置背景透明，不影响父类*/
		position: absolute;top: 99px;right: 2px;}
	.rmgd3 image{width: 10px;height: 10px;}
	.rmgd4{font-size: 14px;}
	/* 推荐小程序 */
	.xcx{margin-top: 17px;margin-bottom: 138px;}
	.xcx view image{width: 80px;height: 80px;}
	.xcx view{width: 126px;text-align: center;font-size: 16px;}
	/* 官方歌单 */
	/* 巅峰榜 */
	.dfb{margin-top: 20px;background: #f2f2f2;border-radius: 6px;padding: 10px 0px 10px 10px;position: relative;}
	.dfb2 image{width: 127px;height: 127px;position: absolute;top: 0px;right: 0px;}
	.dfbt1{font-size: 16px;}
	.dfbt2{font-size: 10px;}
	.dfbt3{font-size: 10px;color: #999999;}
</style>
