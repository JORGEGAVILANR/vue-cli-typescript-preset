# vue-cli-typescript-preset

{
	"All with typescript, Sass, Prettier, Jest and Nightwatch": {
	  "useConfigFiles": true,
	  "plugins": {
		"@vue/cli-plugin-babel": {},
		"@vue/cli-plugin-typescript": {
		  "classComponent": true,
		  "useTsWithBabel": true
		},
		"@vue/cli-plugin-pwa": {},
		"@vue/cli-plugin-eslint": {
		  "config": "prettier",
		  "lintOn": [
			"save"
		  ]
		},
		"@vue/cli-plugin-unit-jest": {},
		"@vue/cli-plugin-e2e-nightwatch": {}
	  },
	  "router": true,
	  "routerHistoryMode": true,
	  "vuex": true,
	  "cssPreprocessor": "dart-sass"
	}
}
