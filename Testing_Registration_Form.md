# Testing the registration form
http://itcareer.pythonanywhere.com

# Environment
Windows 11 Chrome v 106.0.5249.62

# Checklist and bug reports 
[RegistrationForm](https://docs.google.com/spreadsheets/d/1X263Fdo5oqqHBoUZ3Vclf1vxHvjuzAfENBIW8qD_SpQ/edit#gid=1816986114)

# Requirements

## Requirements for the field Name/Surname 
> Not case-sensitive 
> Placeholder must disappear during focus setting  
> Can be inserted from buffer  
> When you click on the field, the frame should turn blue, no hints emerge  
> If special characters are not valid, an error message is displayed at the bottom of the field after submit  
> Can start and end only with a number and a letter  
> Any form of name - full, short, double, diminutive  
> Enter does not go to the next field, only through tab  
> Recurring characters are possible except special characters  
> Can only be written from letters and numbers 
> You can enter 'name', 'password' and so on  
> If you have big data (for example 127 characters), you don’t see the beginning

## Requirements for the  field Email 
> Must be the symbol "@" and the dot after it  
> Any mail (mail, gmail, etc)  
> There should be no gaps  
> Allowed Special Symbols '@', '.', '-'  
> Can’t have two "@"  
> No underlining  
> Before @ number of characters from 4 to 64 on  
> After @ to last point from 2 to 32 switch on  
> After the last point from 2 to 16 surprisingly  
> Not case-sensitive
> Cyrillic is not allowed  
> Two special characters in a row is not allowed  
> A domain name may consist of numbers but not a zone  
> There can be more than one dot after the dog (subdomains are possible)  
> The field is unique  
> Points up to dog can be   
> Numbers can be in any part except after the last point  
> A non-existent domain extension is possible  
> Cannot start with "-", but can with a number  
> Can only consist of digits  
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