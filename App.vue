<script>
export default {
	onLaunch: function() {
		console.log('App Launch');
	},
	onShow: function() {
		console.log('App Show');
	},
	onHide: function() {
		console.log('App Hide');
	}
};
</script>

<style lang="scss">
/* #ifndef APP-NVUE */
page {
	background-color: #efeff4;
}
/* #endif */

/* #ifdef H5 */

// @media screen and (min-width: 768px) {
// 	body{
// 		overflow-y: scroll;
// 	}
// }

.uni-app--showleftwindow .hideOnPc {
	display: none !important;
}

.uni-app--showleftwindow uni-page-body {
		background-color: #F5F5F5 !important;
		min-height: 100% !important;
	}

/* #endif */
</style>
