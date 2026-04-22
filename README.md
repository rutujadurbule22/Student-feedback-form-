# Student-feedback-form-
<!DOCTYPE html>
<html>
<head>
    <title>Student Feedback Form</title>
</head>
<body>

<center>

    <h2>Student Feedback Form</h2>

    <table border="1" cellpadding="8" cellspacing="0">
        <form>

            <tr>
                <td><b>Student Name</b></td>
                <td><input type="text" size="30"></td>
            </tr>

            <tr>
                <td><b>USN</b></td>
                <td><input type="text" size="30"></td>
            </tr>

            <tr>
                <td><b>Email</b></td>
                <td><input type="email" size="30"></td>
            </tr>

            <tr>
                <td><b>Section</b></td>
                <td>
                    <select>
                        <option>A</option>
                        <option>B</option>
                        <option>C</option>
                    </select>
                </td>
            </tr>

            <tr>
                <td><b>Course</b></td>
                <td><input type="text" size="30"></td>
            </tr>

            <tr>
                <td><b>Difficulty Level</b></td>
                <td>
                    <select>
                        <option>Easy</option>
                        <option>Medium</option>
                        <option>Hard</option>
                    </select>
                </td>
            </tr>

            <tr>
                <td><b>Rating</b></td>
                <td>
                    <input type="radio" name="r">1
                    <input type="radio" name="r">2
                    <input type="radio" name="r">3
                    <input type="radio" name="r">4
                    <input type="radio" name="r">5
                </td>
            </tr>

            <tr>
                <td><b>Comments</b></td>
                <td>
                    <textarea rows="4" cols="30"></textarea>
                </td>
            </tr>

            <tr>
                <td colspan="2" align="center">
                    <input type="submit" value="Submit">
                    <input type="reset" value="Reset">
                </td>
            </tr>

        </form>
    </table>

</center>

</body>
</html>
