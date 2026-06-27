# MI-Corazon
Her, her and only herr



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>brio_vault_sync</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #EAD8C7; /* Matte 4:44 Peach-Tan */
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            overflow: hidden;
            font-family: "Segoe Print", "Comic Sans MS", cursive;
        }
        .nickname {
            color: #8A2BE2; /* Stark Neon-Violet */
            font-size: 3.5rem;
            font-weight: bold;
            opacity: 0;
            transform: translateY(20px);
            animation: revealText 1.5s ease-out 1s forwards;
        }
        .subtext {
            font-family: monospace;
            color: #555;
            font-size: 0.75rem;
            margin-top: 15px;
            letter-spacing: 2px;
            opacity: 0;
            animation: fadeInSub 1s ease-in 2.5s forwards;
        }
        @keyframes revealText {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        @keyframes fadeInSub {
            to {
                opacity: 0.6;
            }
        }
    </style>
</head>
<body>
    <div class="nickname">Dione</div>
    <div class= " shortform">Dio</div>    
    <div class="subtext">[server_sync_complete // asset_vault_encrypted]</div>
</body>
</html>
