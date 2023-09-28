<!DOCTYPE html>
<html>
<head>
    <title>Facebook Login Example</title>
    <!-- Include the Facebook JavaScript SDK -->
    <script>
      window.fbAsyncInit = function() {
        FB.init({
          appId: '1007648737225863',
          cookie: true,
          xfbml: true,
          version: 'v12.0'
        });
      };

      (function(d, s, id) {
        var js, fjs = d.getElementsByTagName(s)[0];
        if (d.getElementById(id)) return;
        js = d.createElement(s); js.id = id;
        js.src = 'https://connect.facebook.net/en_US/sdk.js';
        fjs.parentNode.insertBefore(js, fjs);
      }(document, 'script', 'facebook-jssdk'));
    </script>
</head>
<body>
    <h1>Facebook Login Example</h1>

    <!-- Create a login button -->
    <div class="fb-login-button" 
         data-size="large" 
         data-button-type="continue_with" 
         data-layout="default" 
         data-auto-logout-link="false" 
         data-use-continue-as="true" 
         data-width=""></div>

    <!-- Display user information once logged in -->
    <div id="user-info"></div>

    <script>
        // Function to update user information on the page
        function updateUserInfo(response) {
            var userInfo = document.getElementById('user-info');
            userInfo.innerHTML = '<p>Welcome, ' + response.name + '!</p>';
        }

        // Check the user's login status
        FB.getLoginStatus(function(response) {
            if (response.status === 'connected') {
                // User is logged in, display user information
                updateUserInfo(response.authResponse);
            }
        });
        
        // Subscribe to the login event
        FB.Event.subscribe('auth.login', function(response) {
            // User just logged in, display user information
            updateUserInfo(response.authResponse);
        });
    </script>
</body>
</html>
