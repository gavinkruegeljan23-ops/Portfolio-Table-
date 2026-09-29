<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Portfolio Table</title>

<style>
    body {
        font-family: Constantia, Georgia, serif;
        margin: 0 auto;
        padding: 20px;
        max-width: 1024px; /* FIXES the gap issue */
        background: #f5f5f5;
    }

    h1 {
        text-align: center;
        font-size: 48pt;
        margin-bottom: 30px;
        text-shadow:
            0 0 6px #E033FF,
            0 0 12px #E033FF,
            0 0 24px #E033FF;
    }

    table {
        width: 100%;
        border-collapse: collapse;
        margin: 0 auto;
        border: 1px solid gray;
        box-shadow: 2px 3px 6px gray;
        background: white;
    }

    thead tr {
        position: sticky;
        top: 0;
        background: white;
    }

    th, td {
        padding: 12px;
        border-bottom: 1px solid #ddd;
        text-align: left;
    }

    th {
        background: #333;
        color: white;
    }

    tr:nth-child(odd) {
        background: whitesmoke;
    }
</style>
</head>

<body>

<h1>Portfolio Table</h1>

<table>
    <thead>
        <tr>
            <th>Title</th>
            <th>File Format</th>
            <th>Resolution</th>
            <th>Year</th>
            <th>Category</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>The Alley Movie Poster</td>
            <td>PNG</td>
            <td>3000 × 4500 px</td>
            <td>2024</td>
            <td>Poster Design</td>
        </tr>
        <tr>
            <td>The Springers World Tour Poster</td>
            <td>PNG</td>
            <td>2400 × 3600 px</td>
            <td>2025</td>
            <td>Poster Design</td>
        </tr>
        <tr>
            <td>Self Drawing on Illustrator</td>
            <td>JPG</td>
            <td>1920 × 1080 px</td>
            <td>2024</td>
            <td>Digital Illustration</td>
        </tr>
        <tr>
            <td>DragonClans Title Screen</td>
            <td>PNG</td>
            <td>2560 × 1440 px</td>
            <td>2026</td>
            <td>Game Art</td>
        </tr>
        <tr>
            <td>The Museum — Andy Warhol Style</td>
            <td>PNG</td>
            <td>3000 × 3000 px</td>
            <td>2023</td>
            <td>Pop Art</td>
        </tr>
        <tr>
            <td>Work Hard Play Hard Nike Photoshoot</td>
            <td>PNG</td>
            <td>1920 × 1080 px</td>
            <td>2025</td>
            <td>Photography</td>
        </tr>
    </tbody>
</table>

</body>
</html>
