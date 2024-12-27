<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>feedback form</h1>
    <FORM ACTION="/FEEBACK" METHOD="POST">
        <TABLE BORDER="1">
            <TR>
                <TD><LABEL FOR="USERNAME">NAME:</LABEL>
                <INPUT TYPE="TEXT" ID="USERNAME" NAME="USERNAME" PLACEHOLDER="ENTER NAME"></TD>
            </TR> 
            <TR>
                <TD><LABEL FOR="EMAIL">EMAIL:</LABEL>
                <INPUT TYPE="EMAIL" ID="EMAIL" NAME="EMAIL" PLACEHOLDER="ENTER EMAIL"></TD>
            </TR>
            <TR>
                <TD>
                <LABEL FOR="RATING">RATING:</LABEL>
                <INPUT TYPE="RADIO" ID="RATING" NAME="RATING" VALUE="1">*
                <INPUT TYPE="RADIO" ID="RATING" NAME="RATING" VALUE="2">**
                <INPUT TYPE="RADIO" ID="RATING" NAME="RATING" VALUE="3">***
                 <INPUT TYPE="RADIO" ID="RATING" NAME="RATING" VALUE="4">****
                 <INPUT TYPE="RADIO" ID="RATING" NAME="RATING" VALUE="5">*****</TD>   
            </TR>
            <TR>
                <TD><LABEL FOR="MESSAGE">FEEDBACK</LABEL>
                    <TEXTAREA ID="MESSAGE" NAME="MESSAGE" ROWS="4" COLS="50"></TEXTAREA></TD>
            </TR>
            <TR>
                <TD><BUTTON TYPE="SUBMIT">SUBMIT</BUTTON>
                <BUTTON TYPE="RESET">REFRESH</BUTTON></TD>
            </TR>
        </TABLE>
    </FORM>
</body>
</html>
