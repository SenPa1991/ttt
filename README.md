<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Table</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
            font-size: 18px;
            text-align: left;
        }
        th, td {
            border: 1px solid #dddddd;
            padding: 12px;
        }
        th {
            background-color: #f4f4f4;
            color: #333;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        tr:hover {
            background-color: #f1f1f1;
        }
        caption {
            caption-side: top;
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 10px;
        }
        .color-box {
            width: 100px;
            height: 30px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
            border-radius: 5px;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
        }
    </style>
</head>
<body>
    <table>
        <caption>20 Colors with Numbers</caption>
        <thead>
            <tr>
                <th>Color</th>
                <th>Number</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><span class="color-box" style="background-color: #FF5733;">1</span></td>
                <td>1</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #33FF57;">2</span></td>
                <td>2</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #3357FF;">3</span></td>
                <td>3</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #F1C40F;">4</span></td>
                <td>4</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #8E44AD;">5</span></td>
                <td>5</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #1ABC9C;">6</span></td>
                <td>6</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #E74C3C;">7</span></td>
                <td>7</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #3498DB;">8</span></td>
                <td>8</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #2ECC71;">9</span></td>
                <td>9</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #9B59B6;">10</span></td>
                <td>10</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #34495E;">11</span></td>
                <td>11</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #16A085;">12</span></td>
                <td>12</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #27AE60;">13</span></td>
                <td>13</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #2980B9;">14</span></td>
                <td>14</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #D35400;">15</span></td>
                <td>15</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #C0392B;">16</span></td>
                <td>16</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #BDC3C7;">17</span></td>
                <td>17</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #7F8C8D;">18</span></td>
                <td>18</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #F39C12;">19</span></td>
                <td>19</td>
            </tr>
            <tr>
                <td><span class="color-box" style="background-color: #E67E22;">20</span></td>
                <td>20</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
