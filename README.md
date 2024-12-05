<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Donate Mỹ Nhàn</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        table {
            margin: 20px auto;
            border-collapse: collapse;
            width: 60%;
            background-color: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            overflow: hidden;
        }
        table img {
            width: 100%;
            height: auto;
        }
        td {
            padding: 15px;
            text-align: left;
        }
        h2 {
            text-align: center;
            color: #333;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            padding: 5px 0;
            font-size: 16px;
            color: #555;
        }
        p {
            font-size: 16px;
            line-height: 1.6;
            color: #333;
        }
        .donate-table {
            width: 100%;
            max-width: 600px;
            margin: 20px auto;
            border-collapse: collapse;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .donate-table th {
            background-color: #f2f2f2;
            padding: 15px;
            font-size: 20px;
            text-align: center;
            color: #333;
        }
        .donate-table td {
            padding: 10px;
            text-align: left;
        }
        .donate-table input {
            width: 100%;
            padding: 8px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .donate-table button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .donate-table button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <table>
        <tr>
            <td colspan="2">
                <img src="17fc8f901ec1a49ffdd0.jpg" alt="Image of Mỹ Nhàn">
            </td>
        </tr>
        <tr>
            <td colspan="2">
                <h2>Tóm tắt tiểu sử Mỹ Nhàn</h2>
                <ul>
                    <li>Họ tên: Ngô Mỹ Nhàn</li>
                    <li>Ngày sinh: 11/06/2007</li>
                    <li>Quê quán: Tp.Bến Tre, Bến Tre</li>
                    <li>Cung hoàng đạo: Song Tử</li>
                    <li>Học tại: Trường THPT Chuyên Bến Tre</li>
                    <li>Sở thích: Tiêu tiền</li>
                    <li>Ước mơ: Mua nhà trên Đà Lạt</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td colspan="2">
                <h2>Giới thiệu bản thân</h2>
                <p align="justify">Chào các bạn của bảnh nha. Bảnh là Nhàn nè. Bảnh ở Bến Tre đang học lớp 12 Lý tại CBT. Bảnh thích đi ngủ lắm với bảnh thích ăn bún đậu mắm tôm thích đi du lịch nữa. Dạo gần đây điện thoại bảnh bị hư mà không có tiền mua mới ai có lòng có thể donate qua 0918167809 BIDV nha. Cảm ơn mọi người!</p>
            </td>
        </tr>
    </table>

<table class="donate-table">
        <thead>
            <tr>
                <th colspan="2">Donate cho Mỹ Nhàn</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Họ và Tên:</td>
                <td><input type="text" name="name" placeholder="Nhập tên của bạn" required></td>
            </tr>
            <tr>
                <td>Email:</td>
                <td><input type="email" name="email" placeholder="Nhập email của bạn" required></td>
            </tr>
            <tr>
                <td>Số tiền (VNĐ):</td>
                <td><input type="number" name="amount" placeholder="Nhập số tiền" min="1000" required></td>
            </tr>
            <tr>
                <td colspan="2" style="text-align: center;">
                    <button type="submit">Donate ngay</button>
                </td>
            </tr>
        </tbody>
    </table>
</body>
</html>
