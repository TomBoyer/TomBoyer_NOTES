<!-- Notes en vrac pour moi même -->

<!-- Snippets utiles -->

https://www.youtube.com/watch?v=WIKznBi-QqI&ab_channel=LeDesignerduWeb

{
	"Query Selector" : {
		"prefix": "queryElmnt",
		"body": ["const $1 = document.querySelector('$2');"],
		"description": "quick query select"
	},

	"Query Selector All" : {
		"prefix": "queryElmntS",
		"body": ["const $1 = document.querySelectorAll('$2');"],
		"description": "quick query select all"
	},

	"Quick function" : {
		"prefix": "functionQuick",
		"body": ["($1, $2) => { $3 }"],
		"description": "quick function =>"
	},
}


{
	"absolute-centered" : {
		"prefix" : "abs-center",
		"body" : [
			"position:absolute;",
			"top:50%;",
			"left:50%;",
			"transform:translate(-50%, -50%);"
		],
		"description": "centrage element absolute"
	},

	"flex-center": {
		"prefix" : "flex-center",
		"body" : [
			"display:flex;",
			"justify-content:center;",
			"align-items:center;"
		],
		"description": "display flex center"
	},

	"circle-basic": {
		"prefix" : "circle-basic",
		"body" : [
			"width:100px;",
			"height:100px;",
			"border-radius:50%;"
		],
		"description": "cercle simple"
	},

	"border-test": {
		"prefix" : "border-test",
		"body" : [
			"border:solid 1px black;",
		],
		"description": "border simple pour visualiser élément phase de test"
	},

	"background": {
		"prefix" : "background",
		"body" : [
			"background:#${1};",
		],
		"description": "border simple pour visualiser élément phase de test"
	},

	"media-query-tel": {
		"prefix" : "mediaTel",
		"body" : [
			"@media all and (max-width:767px){$1}",
		],
		"description": "media query pour tel"
	},

	"media-query-tablet": {
		"prefix" : "mediaTablet",
		"body" : [
			"@media all and (max-width:992px){$1}",
		],
		"description": "media query pour tablet"
	},

	"media-query-desktop": {
		"prefix" : "mediaDesktop",
		"body" : [
			"@media all and (max-width:1440px){$1}",
		],
		"description": "media query pour desktop"
	},
}

<!-- End Snippets utiles -->#   T o m B o y e r _ N O T E S  
 