<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
    <meta charset="utf-8">
    <title>Sign Up Form</title>
</head>

<body>
    <form action="http://fptaptech.herokuapp.com" method="get">
        <fieldset>
            <legend>Your details:</legend>
            <label>Name: <input type="text" name = "name" size="30" maxlegth="100"></label><br />
            <label>Email: <input type="email" name="email" size="30" maxlegth="100"></label><br />
        </fieldset><br />
        <fieldset>
            <legend>Your review:</legend>
            <p>
                <label for="hear-about">How did you hear about us?</label>
                <select name="referrer" id="hear-about">
                    <option value="Google">Google</option>
                    <option value="Friend">Friend</option>
                    <option value="Ads">Ads</option>
                    <option value="Other">Other</option>
                </select>
            </p>
            <p>
                Would you visit again?<br />
                <label><input type="radio" name rating value="yes" /> Yes </label>
                <label><input type="radio" name rating value="no" /> No </label>
                <label><input type="radio" name rating value="maybe" /> Maybe </label>
            </p>
            <p>
                <label for="comments">Comments:</label><br />
                <textarea rows="4" cols="40" id="comments"></textarea>
            </p>
                <label><input type="checkbox" name="subscribe" checked="checked" />Sign me up for email updates</label><br />
                <input type="submit" values="submit review" />
        </fieldset>
    </form>
</body>
