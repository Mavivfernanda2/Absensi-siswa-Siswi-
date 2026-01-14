<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aplikasi Absensi Siswa Siswi</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Absensi Siswa Siswi</h1>
        <form id="attendanceForm">
            <div class="form-group">
                <label for="name">Nama Siswa:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="class">Kelas:</label>
                <input type="text" id="class" name="class" required>
            </div>
            <div class="form-group">
                <label for="status">Status Kehadiran:</label>
                <select id="status" name="status" required>
                    <option value="Hadir">Hadir</option>
                    <option value="Tidak Hadir">Tidak Hadir</option>
                </select>
            </div>
            <button type="submit">Submit</button>
        </form>

        <h2>Daftar Kehadiran</h2>
        <table id="attendanceList">
            <thead>
                <tr>
                    <th>Nama Siswa</th>
                    <th>Kelas</th>
                    <th>Status Kehadiran</th>
                </tr>
            </thead>
            <tbody>
                <!-- Data akan ditambahkan di sini -->
            </tbody>
        </table>
    </div>

    <script src="script.js"></script>
</body>
</html>

