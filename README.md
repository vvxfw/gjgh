<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site Bonitão</title>
    <style>
        /* Importando uma fonte moderna do Google */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700&display=swap');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', sans-serif;
        }

        body {
            background-color: #f4f7f6;
            color: #333;
            line-height: 1.6;
        }

        /* Cabeçalho com Degradê */
        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            height: 400px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            padding: 20px;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            letter-spacing: -1px;
        }

        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        /* Seção de Conteúdo */
        .container {
            max-width: 900px;
            margin: -50px auto 50px;
            background: white;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }

        .cards {
            display: grid
