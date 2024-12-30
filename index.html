<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nepali Datepicker Converter</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 70vh;
            background-color: #f0f0f0;
            margin: 0;
            font-family: Arial, sans-serif;
        }

        h1 {
            margin-bottom: 50px;
            font-size: 24px;
            text-align: center;
        }

        .input-container {
            display: flex;
            align-items: center;
            gap: 20px;
        }

        .vertical-bar {
            width: 2px;
            height: 40px;
            background-color: #ccc;
        }

        .input-field {
            width: 200px;
            height: 40px;
            border: none;
            outline: none;
            padding: 10px;
            font-size: 16px;
            box-shadow: 3px 3px 5px rgba(0, 0, 0, 0.2), -3px -3px 5px rgba(255, 255, 255, 0.7);
            background-color: #e0e0e0;
            border-radius: 8px;
            transition: box-shadow 0.3s ease;
        }

        .input-field:focus {
            box-shadow: 5px 5px 7px rgba(0, 0, 0, 0.3), -5px -5px 7px rgba(255, 255, 255, 0.8);
        }

        .label-container {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        label {
            margin-bottom: 5px;
            font-size: 14px;
        }

        footer {
            position: absolute;
            bottom: 10px;
            font-size: 14px;
            color: #555;
        }

        #selected-date {
            margin-top: 20px;
            font-size: 16px;
            color: #333;
        }

        .button {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 16px;
            color: #fff;
            background-color: #007bff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-align: center;
        }

        .button a {
            color: #fff;
            text-decoration: none;
        }

        .button:hover {
            background-color: #0056b3;
        }
    </style>
    <!-- Nepali Datepicker -->
    <link href="http://nepalidatepicker.sajanmaharjan.com.np/nepali.datepicker/css/nepali.datepicker.v3.7.min.css" rel="stylesheet" type="text/css"/>
</head>
<body>

    <h1>Nepali Datepicker Converter</h1>

    <div class="input-container">
        <div class="label-container">
            <label for="nepali-datepicker">BS</label>
            <input type="text" id="nepali-datepicker" class="input-field nepali-datepicker" placeholder="BS Date">
        </div>
        <div class="vertical-bar"></div>
        <div class="label-container">
            <label for="english-datepicker">AD</label>
            <input type="date" id="english-datepicker" class="input-field" placeholder="AD Date">
        </div>
    </div>

    <p id="selected-date">Selected Date: AD - , BS - </p>

    <div class="button">
        <a href="https://nirajang.info.np/posts/date-converter">Go Back</a>
    </div>

    

    <script src="http://nepalidatepicker.sajanmaharjan.com.np/nepali.datepicker/js/nepali.datepicker.v3.7.min.js" type="text/javascript"></script>
    <script type="text/javascript">
        // Function to format today's date in YYYY-MM-DD
        function formatDate(date) {
            var day = ("0" + date.getDate()).slice(-2);
            var month = ("0" + (date.getMonth() + 1)).slice(-2);
            var year = date.getFullYear();
            return year + "-" + month + "-" + day;
        }

        // Set today's date as the default date in the datepicker
        var today = new Date();
        document.getElementById('english-datepicker').value = formatDate(today);

        var nepaliDatePicker = document.getElementById("nepali-datepicker");
        var englishDatePicker = document.getElementById("english-datepicker");

        // Initialize Nepali datepicker with the current date
        var currentDate = NepaliFunctions.ConvertDateFormat(NepaliFunctions.GetCurrentBsDate(), "YYYY-MM-DD");
        nepaliDatePicker.value = currentDate;

        nepaliDatePicker.nepaliDatePicker({
            language: "english",
            readOnlyInput: true,
            onChange: function() {
                var innepali = nepaliDatePicker.value;
                var dateObj = NepaliFunctions.ConvertToDateObject(innepali, "YYYY-MM-DD");
                var convertDate = NepaliFunctions.ConvertDateFormat(NepaliFunctions.BS2AD(dateObj), "YYYY-MM-DD");
                englishDatePicker.value = convertDate;

                // Update the selected date paragraph
                document.getElementById('selected-date').innerText = "Selected Date: AD - " + convertDate + ", BS - " + innepali;
            }
        });

        // Event listener for date change on the English datepicker
        englishDatePicker.addEventListener('change', function() {
            var selectedDate = englishDatePicker.value;
            var bsDate = NepaliFunctions.ConvertDateFormat(NepaliFunctions.AD2BS(NepaliFunctions.ConvertToDateObject(selectedDate, "YYYY-MM-DD")), "YYYY-MM-DD");
            nepaliDatePicker.value = bsDate;

            // Update the selected date paragraph
            document.getElementById('selected-date').innerText = "Selected Date: AD - " + selectedDate + ", BS - " + bsDate;
        });
    </script>

</body>
</html>
