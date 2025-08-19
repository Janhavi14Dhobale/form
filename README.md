<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
        <form action="/action.php">
            <fieldset>
                <legend>Personal details</legend>
            <br>
            <input type="text" placeholder="username">
            <br>
            <br>
            <input type="text" placeholder="password">
            <br>
            <br>
            </fieldset>
            <fieldset>
                <legend>year of study</legend>
            <label for="id1">
                <input type="radio" value="First yr" name="year" id="id1">first yr
                <br>
                <label for="id2">
                    <input type="radio" value="second yr" name="year" id="id2">second yr
                </label>
                <br>
                
                <label for="id3">
                    <input type="radio" value="third yr" name="year" id="id1">third yr
                </label>
                <br>
                
               <label for="id4">
                <input type="radio" value="fourth Yr" name="year" id="id2">fourth yr
               </label>
            </label>
            </fieldset>
            <br>
            <br>
            <textarea name="feedback" id="feedback" placeholder="Add your suggestions"></textarea>
            <br>
            <br>
            <select name="branch" id="branch" size="3">
                <option value="Ctech">Ctech</option>
                <option value="CSE">CSE</option>
                <option value="AIML">AIML</option>
                <option value="AIDS">AIDS</option>
                <option value="ETC">ETC</option>
                <option value="VLSI">VLSI</option>
            </select>
            <br>
            <br>
            <br>
            <button type ="button">submit</button>
        </form>
    
</body>
</html>
