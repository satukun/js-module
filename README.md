# component
## 共通モジュール
**必ず**下記２行は先に読ませてください:bowtie:
```
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
	<script src="../../js/main.js"></script>
```
###posttime.js
*****
投稿日から今日まで投稿時間差
```
	<script src="js/postTime.js"></script>
	<script>
	$(function(){
		CA.postTime();
	});
	</script>
```

###circleFall.js
*****
背景で丸が移動

```
	<script src="js/circleFall.js"></script>
	<script>
	$(function(){
		CA.circleFall({
			size      : 10,
			speed     : 1.5,
			timing    : 100,
			len       : 30,
			direction : "top" // "top" or "left"
		});
	});
	</script>
```

###boxMove.js
*****
箱が領域外が出現

```
	<script src="js/boxMove.js"></script>
	<script>
	$(function(){
		CA.boxMove({
			size      : 100,
			speed     : 20,
			timing    : 10,
			len       : 0,
			direction : "top"
		});
	});
	</script>
```

###targetPost.js
*****
射的ゲームっぽい

```
	<script src="js/boxMove.js"></script>
	<script>
    $(function(){
		CA.targetPost({
			/*レーン数 1~10*/
			lane:1,
			/*的スピードレベル 1~5*/
			speed:3000,
			/*的数 1~10*/
			target:50
		});
    });
	</script>
```