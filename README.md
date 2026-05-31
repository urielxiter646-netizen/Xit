# Xit
Xit
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FFH4X Panel</title>
    <style>
        :root {
            --bg-color: #121214;
            --panel-bg: #1a1a1e;
            --primary: #ff0043;
            --primary-hover: #ff2b61;
            --text: #ffffff;
            --text-secondary: #a0a0a8;
            --border: #2a2a30;
        }

        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            user-select: none;
        }

        /* Tela de Login */
        .login-screen {
            background-color: var(--panel-bg);
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.5);
            border: 1px solid var(--border);
            text-align: center;
            width: 320px;
        }

        .login-screen h2 {
            color: var(--primary);
            margin-bottom: 20px;
            letter-spacing: 2px;
        }

        .login-screen input {
            width: 100%;
            padding: 12px;
            margin-bottom: 20px;
            background: #0f0f12;
            border: 1px solid var(--border);
            border-radius: 6px;
            color: white;
            text-align: center;
            font-size: 16px;
            box-sizing: border-box;
        }

        .login-screen input:focus {
            border-color: var(--primary);
            outline: none;
        }

        /* Painel Principal (Oculto inicialmente) */
        .panel {
            display: none;
            width: 360px;
            background-color: var(--panel-bg);
            border-radius: 14px;
            border: 1px solid var(--border);
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.7);
            overflow: hidden;
        }

        /* Cabeçalho */
        .panel-header {
            background: linear-gradient(90deg, #151518, #1
