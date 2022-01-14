# Welcome!




<!-- Make sure you don't change the form action-->
<form action="https://api.staticforms.xyz/submit" method="post">
    <!-- Replace with accesKey sent to your email -->
    <input type="hidden" name="accessKey" value="7002f1fd-2259-4bca-ae5e-9fda452cd394"> <!-- Required -->
    <input type="text" name="name"> <!-- Optional -->
    <input type="text" name="subject"> <!-- Optional -->
    <input type="text" name="email"> <!-- Optional -->
    <input type="text" name="phone"> <!-- Optional -->
    <textarea name="message"></textarea> <!-- Optional -->
    <!-- If you want replyTo to be set to specific email -->
    <!-- <input type="text" name="replyTo" value="myreplytoemail@example.com"> Optional -->
    <!-- Specify @ as reply to value if you want it to be customers email -->
    <input type="hidden" name="replyTo" value="@"> <!-- Optional -->
    <!-- If you want form to redirect to a specific url after submission -->
    <!-- <input type="hidden" name="redirectTo" value="https://example.com/contact/success"> Optional -->
    <!-- If we receive data in this field submission will be ignored -->
    <input type="text" name="honeypot" style="display: none;"> <!-- Optional -->
    <input type="text" name="$myCustomField1">
    <input type="text" name="$myCustomField2">
    <input type="submit" value="Submit" />
</form>