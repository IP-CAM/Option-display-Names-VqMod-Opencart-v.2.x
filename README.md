# opencart-option-display-names
## by Lucas Krupinski

This VQMOD gives every option a display name in addition to a name.

The use case for this is where you have have different option sets for different manufacturers with the same name.

This way in your back end you can give that option set it's own name ("ABC Co - Colors" and "XZY Inc - Colors") while displaying them both as "Color" to the customer.

## IMPORTANT 

This requires adding a new column to the "option_description" table called 'display' as VARCHAR(128);

I don't know how to do this properly as a VQMOD. Assistance on this matter would be greatly appreciated. :)
