# Testing the registration form
http://itcareer.pythonanywhere.com

# Environment
Windows 11 Chrome v 106.0.5249.62

# Checklist and bug reports 
https://docs.google.com/spreadsheets/d/1X263Fdo5oqqHBoUZ3Vclf1vxHvjuzAfENBIW8qD_SpQ/edit#gid=0

# Requirements

## Requirements for the field Name/Surname 
> Number of characters from 2 to 128 inclusive
> Special characters can only be "-", "." , "_" and space
> Not case-sensitive
> Latin characters and numbers only
> The placeholder should disappear when the focus is set
> Paste from the buffer is allowed
> When you click on the box, the frame should turn blue, no tooltips pop up
> If invalid wildcards are used, an error message will appear at the bottom of submit to indicate an error in the specific field
> A script with allowed special characters will be sent
> Can start and end with a number and a letter only
> Any form of name is acceptable - full, short, double, diminutive
> Move to the next field only via Tab
> Extended characters are not allowed
> Emoji cannot be used
> Repetitive characters are possible except for special characters
> Can only be written from letters and numbers
> You can enter 'name', 'password' etc.
> With large data (e.g. 127 characters) we do not see the beginning

## Requirements for the  field Email 
> There must be an "@" and a dot after it
> Any mail (mail, gmail, etc.)
> There should be no gaps
> Allowed wildcards '@', '.', '-'
> Can't have two "@'s."
> Underscore is not allowed
> Before @ number of characters from 4 to 64 inclusive
> After @ to the last point 2 to 32 inclusive
> After the last point from 2 to 16 inclusively
> No check for a one-time email
> Not case-sensitive
> Cyrillic is not allowed
> Two special characters in a row is not allowed
> There can be more than one dot after @ (subdomains are possible)
> The field is unique
> Non-existent email is allowed 
> A domain zone that does not exist can be
> Can't start with a "-", but it can start with a number
> Can only consist of numbers
> The repeated email should cause an error
> Email can be pasted from the buffer

## Requirements for the Password field
> It must be one of the three special symbols - "@", "!" , "." and only these are allowed    
> At least one digit, at least one large letter and at least one small letter      
> 8 to 16 characters inclusive, the field is not blocked during the process of overfilling    
> Can be multiple and consecutive special characters, you can start with a symbol    
> Name and Password may coincide    
> Can be inserted from the buffer  
> No password confirmation - in improvements  
> Latin only  
> Possible clear the field with Ctrl+X and paste, but not copy  
> The field should be cleared on restart  
> Same characters are possible  
> The fields are not dragging with the mouse 
> Common passwords are possible

## Requirements for the form
> View must be unified (in one style)!  
> Required fields name, email, password  
> When you click on the field, the frame should turn blue, no hints emerge  
> Data should not be saved when restarting  
> Unique only email  
> Enter does not go to the next field, only through tab  
> If invalid characters are used, after submit, an error message is displayed in a specific field (and the field should be red), t  
> validation script works when you click submit  
> After pressing the submit button, the shape is cleared  
> Placeholder must disappear during focus setting  
> With all valid data - window (Halloween...)  
> After the page is updated, the error message should disappear  
> Error messages are general, without specification, only about the field  
> Data in fields can be the same 
> If several fields are not filled in at the same time, the error shows all fields at once  
> Title clear (Registration form)  
> Required fields marked    
> Submit is active even with empty fields  
> Fields accept scripts with allowed characters  
> The submit button is obscured when hovering on it  
> Header in H2  
> Fields do not stretch  
> Data cannot be cut