<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV - Armando Jordan</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body, html {
            height: 100%;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: #1e293b;
            color: #f8fafc;
            display: flex;
            flex-direction: column;
        }
        header {
            background-color: #0f172a;
            padding: 12px 24px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #334155;
        }
        header h1 {
            font-size: 1.1rem;
            font-weight: 600;
        }
        .actions {
            display: flex;
            gap: 10px;
        }
        .btn {
            background-color: #2563eb;
            color: white;
            text-decoration: none;
            padding: 8px 16px;
            border-radius: 6px;
            font-size: 0.9rem;
            font-weight: 500;
            transition: background-color 0.2s;
        }
        .btn:hover {
            background-color: #1d4ed8;
        }
        .btn-secondary {
            background-color: #334155;
        }
        .btn-secondary:hover {
            background-color: #475569;
        }
        .pdf-container {
            flex: 1;
            width: 100%;
            height: 100%;
        }
        iframe {
            width: 100%;
            height: 100%;
            border: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Armando Jordan — Currículum Vitae</h1>
        <div class="actions">
            <a href="https://github.com/Armandjk10" target="_blank" class="btn btn-secondary">GitHub</a>
            <a href="https://www.linkedin.com/in/armando-emanuel-jordan-kana-b2a25127a/" target="_blank" class="btn btn-secondary">LinkedIn</a>
            <a href="CV_Armando_Jordan.pdf" download class="btn">Descargar PDF</a>
        </div>
    </header>
    <div class="pdf-container">
        <iframe src="CV_Armando_Jordan.pdf" title="CV Armando Jordan"></iframe>
    </div>
</body>
</html>
