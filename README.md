# Punya-al🤍
UNTUK PACAR AKU MEILANI
<!DOCTYPE html>
<html>
<head>
    <title>Happy Valentine</title>
    <style>
        body {
            background: linear-gradient(to right, #ff9a9e, #fad0c4);
            text-align: center;
            font-family: Arial;
            margin-top: 150px;
        }

        h1 {
            font-size: 35px;
            color: white;
        }
    </style>
</head>
<body>

    <h1 id="text"></h1>

    <script>
        let pesan = "Happy Valentine's Day sayanggkuu meilani🤍🤍 makasihh ya udah hadir dalam hidup aku,aku bahagia banget sayangg sama kamuu,sinii sinii pelukk ciuman sayanngg,selalu bahagia ya sayangg sama akuu I love you moree🤍🤍 ";
        let i = 0;

        function ketik() {
            if (i < pesan.length) {
                document.getElementById("text").innerHTML += pesan.charAt(i);
                i++;
                setTimeout(ketik, 80);
            }
        }

        ketik();
    </script>

</body>
</html>
