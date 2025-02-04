# aii
rundown
<!DOCTYPE html>
<html>
<head>
    <title>Rundown Acara Konferensi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffefd5; /* Warna latar belakang cerah */
            margin: 0;
            padding: 20px;
        }
        h1 {
            color: #2c3e50;
            text-align: center;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            background-color: #ffffff;
            margin: 10px 0;
            padding: 10px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s, background-color 0.2s;
            cursor: pointer;
        }
        li:hover {
            transform: scale(1.05);
            background-color: #ffe4b5; /* Warna elemen saat cursor didekatkan */
        }
        li strong {
            color: #d2691e; /* Warna elemen judul */
        }
        li em {
            color: #8b4513; /* Warna elemen penanggung jawab */
        }
        .details {
            display: none;
            margin-top: 10px;
            opacity: 0;
            transition: opacity 0.5s ease-in-out;
        }
        li.active .details {
            display: block;
            opacity: 1;
        }
        .editable {
            outline: none;
        }
    </style>
    <script>
        function toggleDetails(event) {
            const listItem = event.currentTarget;
            listItem.classList.toggle('active');
        }
    </script>
</head>
<body>
    <h1 contenteditable="true" class="editable">Rundown Acara Konferensi</h1>
    <ul>
        <li onclick="toggleDetails(event)">
            <strong contenteditable="true" class="editable">08:00 - 09:00</strong> - <span contenteditable="true" class="editable">Registrasi dan Penerimaan Peserta</span>
            <br>
            <em contenteditable="true" class="editable">Penanggung Jawab: Budi Santoso</em>
            <div class="details">
                <p contenteditable="true" class="editable">Detail acara: Peserta diminta untuk melakukan registrasi dan mendapatkan tanda pengenal.</p>
            </div>
        </li>
        <li onclick="toggleDetails(event)">
            <strong contenteditable="true" class="editable">09:00 - 09:30</strong> - <span contenteditable="true" class="editable">Pembukaan Acara dan Sambutan</span>
            <br>
            <em contenteditable="true" class="editable">Penanggung Jawab: Ani Wijaya</em>
            <div class="details">
                <p contenteditable="true" class="editable">Detail acara: Sambutan dari penyelenggara dan perkenalan tema acara.</p>
            </div>
        </li>
        <li onclick="toggleDetails(event)">
            <strong contenteditable="true" class="editable">09:30 - 10:30</strong> - <span contenteditable="true" class="editable">Sesi Pertama: Topik Utama</span>
            <br>
            <em contenteditable="true" class="editable">Penanggung Jawab: Citra Rahayu</em>
            <div class="details">
                <p contenteditable="true" class="editable">Detail acara: Pembicaraan tentang topik utama oleh ahli terkait.</p>
            </div>
        </li>
        <li onclick="toggleDetails(event)">
            <strong contenteditable="true" class="editable">10:30 - 10:45</strong> - <span contenteditable="true" class="editable">Jeda dan Minum Kopi</span>
            <br>
            <em contenteditable="true" class="editable">Penanggung Jawab: Dewi Saraswati</em>
            <div class="details">
                <p contenteditable="true" class="editable">Detail acara: Waktu istirahat dan menikmati kopi.</p>
            </div>
        </li>
        <li onclick="toggleDetails(event)">
            <strong contenteditable="true" class="editable">10:45 - 12:00</strong> - <span contenteditable="true" class="editable">Sesi Kedua: Panel Diskusi</span>
            <br>
            <em contenteditable="true" class="editable">Penanggung Jawab: Eko Prasetyo</em>
            <div class="details">
                <p contenteditable="true" class="editable">Detail acara: Diskusi panel dengan beberapa pembicara mengenai topik terkait.</p>
            </div>
        </li>
        <li onclick="toggleDetails(event)">
            <strong contenteditable="true" class="editable">12:00 - 13:00</strong> - <span contenteditable="true" class="editable">Makan Siang dan Jejaring</span>
            <br>
            <em contenteditable="true" class="editable">Penanggung Jawab: Fitri Handayani</em>
            <div class="details">
                <p contenteditable="true" class="editable">Detail acara: Waktu makan siang dan kesempatan untuk berjejaring.</p>
            </div>
        </li>
        <li onclick="toggleDetails(event)">
            <strong contenteditable="true" class="editable">13:00 - 14:00</strong> - <span contenteditable="true" class="editable">Sesi Ketiga: Workshop</span>
            <br>
            <em contenteditable="true" class="editable">Penanggung Jawab: Guntur Saputra</em>
            <div class="details">
                <p contenteditable="true" class="editable">Detail acara: Workshop yang dipandu oleh instruktur berpengalaman.</p>
            </div>
        </li>
        <li onclick="toggleDetails(event)">
            <strong contenteditable="true" class="editable">14:00 - 14:15</strong> - <span contenteditable="true" class="editable">Jeda dan Minum Teh</span>
            <br>
            <em contenteditable="true" class="editable">Penanggung Jawab: Hana Kartika</em>
            <div class="details">
                <p contenteditable="true" class="editable">Detail acara: Waktu istirahat dan menikmati teh.</p>
            </div>
        </li>
        <li onclick="toggleDetails(event)">
            <strong contenteditable="true" class="editable">14:15 - 15:30</strong> - <span contenteditable="true" class="editable">Sesi Keempat: Presentasi Studi Kasus</span>
            <br>
            <em contenteditable="true" class="editable">Penanggung Jawab: Indra Kurniawan</em>
            <div class="details">
                <p contenteditable="true" class="editable">Detail acara: Presentasi mengenai studi kasus oleh pembicara terpilih.</p>
            </div>
        </li>
        <li onclick="toggleDetails(event)">
            <strong contenteditable="true" class="editable">15:30 - 16:00</strong> - <span contenteditable="true" class="editable">Penutupan dan Penghargaan</span>
            <br>
            <em contenteditable="true" class="editable">Penanggung Jawab: Joko Susilo</em>
            <div class="details">
                <p contenteditable="true" class="editable">Detail acara: Penutupan acara dan pemberian penghargaan.</p>
            </div>
        </li>
    </ul>
</body>
</html>
