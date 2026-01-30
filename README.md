<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Biodata Keluarga</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #74ebd5, #9face6);
            padding: 20px;
        }
        h1 {
            text-align: center;
            color: #fff;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            background: #ffffff;
            border-radius: 10px;
            overflow: hidden;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 12px;
            text-align: center;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
        img {
            width: 120px;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
        }
        audio {
            width: 150px;
        }
    </style>
</head>
<body>

<h1>👨‍👩‍👧‍👦 Biodata Keluarga</h1>

<table>
    <tr>
        <th>No</th>
        <th>Foto</th>
        <th>Nama</th>
        <th>Hubungan</th>
        <th>Tempat, Tgl Lahir</th>
        <th>Hobi</th>
        <th>Musik Favorit</th>
    </tr>

    <tr>
        <td>1</td>
        <td><img src="amba.jpg"></td>
        <td>Amba</td>
        <td>Anak</td>
        <td>Jakarta, 10-05-1980</td>
        <td>Membangun</td>
        <td>
            <audio controls>
                <source src="Amba.mp3" type="audio/mpeg">
            </audio>
        </td>
    </tr>

    <tr>
        <td>2</td>
        <td><img src="Fuad.jpg"></td>
        <td>Fuad</td>
        <td>Paman</td>
        <td>Bandung, 12-08-1982</td>
        <td>Tidur</td>
        <td>
            <audio controls>
                <source src="Fuad.mp3" type="audio/mpeg">
            </audio>
        </td>
    </tr>

    <tr>
        <td>3</td>
        <td><img src="Rusdi.jpg"></td>
        <td>Rusdi</td>
        <td>Paman</td>
        <td>Surabaya, 20-03-2008</td>
        <td>Game</td>
        <td>
            <audio controls>
                <source src="Rusdi.mp3" type="audio/mpeg">
            </audio>
        </td>
    </tr>

</table>

</body>
</html>
