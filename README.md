Thorax & Parse Todo Seed
========================

### *Example of persistent ToDos with Facebook authentication using Thorax and Parse*



Configuration
-------------



-   Create a [Facebook Application]

-   Register & Create a new app at Parse.com

-   Edit your /js/routers/todo-list.js and replace the placeholders with your
    Parse initialize script & Facebook App ID

    Parse.initialize("REPLACE ME", "REPLACE ME");

	window.fbAsyncInit = function() {

		Parse.FacebookUtils.init({

		appId      : 'REPLACE ME',

		cookie   : true,

		xfbml      : true

		});

	};

-   Run npm start

-   ?

-   PROFIT
