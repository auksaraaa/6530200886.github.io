<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parity Bits</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #f4f4f4;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        tr:hover {
            background-color: #f1f1f1;
        }
    </style>
</head>
<body>
    <h1>📚 Parity Bits</h1>

    <h2>📖 CISSP Glossary - Student Guide</h2>
    <table>
        <thead>
            <tr>
                <th>Source</th>
                <th>Definition</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>CISSP Glossary</td>
                <td>RAID Technique; Logical mechanism used to mark striped data; allows recovery of missing drive(s) by pulling data from adjacent drives.</td>
            </tr>
            <tr>
                <td>ChatGPT</td>
                <td>กลไกทางตรรกะที่ใช้ในการทำเครื่องหมายข้อมูลแบบแบ่งแถบ (striped data); ช่วยให้สามารถกู้คืนไดรฟ์ที่สูญหายได้ โดยดึงข้อมูลจากไดรฟ์ที่อยู่ติดกัน.</td>
            </tr>
            <tr>
                <td>Gemini</td>
                <td>เทคนิค RAID; กลไกเชิงตรรกะที่ใช้ทำเครื่องหมายข้อมูลในรูปแบบแถบ; อนุญาตให้กู้คืนไดรฟ์ที่หายไป โดยดึงข้อมูลจากไดรฟ์ที่อยู่ติดกัน.</td>
            </tr>
        </tbody>
    </table>

    <h2>📖 NIST</h2>
    <table>
        <thead>
            <tr>
                <th>Source</th>
                <th>Definition</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>NIST</td>
                <td>A checksum that is computed on a block of bits by computing the binary sum of the individual bits in the block and then discarding all but the low-order bit of the sum. See checksum.</td>
            </tr>
            <tr>
                <td>ChatGPT</td>
                <td>Checksum ที่ถูกคำนวณบนบล็อกของบิต โดยการคำนวณผลรวมแบบไบนารีของบิตแต่ละตัวในบล็อก แล้วทิ้งบิตทั้งหมดที่อยู่นอกเหนือจากบิตลำดับต่ำสุดของผลรวมออกไป.</td>
            </tr>
            <tr>
                <td>Gemini</td>
                <td>Checksum คือ ค่าตรวจสอบความถูกต้องของข้อมูล (data integrity) โดยคำนวณจากบล็อกของบิต (bits) ด้วยวิธีการบวกเลขฐานสอง (binary sum) ของแต่ละบิตในบล็อกนั้น จากนั้นนำผลรวมที่ได้มาตัดทอนเหลือเพียงบิตต่ำสุด (low-order bit) เท่านั้น.</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
