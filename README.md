# zeudocode
A Sublime Text pseudocode syntax definition

A very rough start on a very loose syntax definition for Sublime Text.

At the moment, only the barebones of syntax highlighting rules are defined, but I expect to slowly enhance this as I use it.

Briefly:
* comments
 * //␣ anywhere to end-of-line
 * #␣ at start of line
 * ; at start of line
 * /* to */
 * <-- to -->

* keywords
 * a bunch, including if|then|elif|else|fi|end|endif|for|next|while|wend|loop|until etc
 * 'operators' like let|set|not|and|or|xor|is|to
 * operators like =|==|<=|>=|<>|!=|:=|-->|\+|\+\+|--|\+=|-=|\*|\/ and \s(&&|&|\||\|\||!|!!)\s
* constants
 * true|false|TRUE|FALSE|yes|no|YES|NO|etc
 * hex numerics starting 0x or #
 * decimal numeric 
 * named start with uppercase alpha, followed by uppercase alphanumerics 
* strings
 * double or single quoted
* Elements
 * 'support.class' start with an Uppercase alpha, followed by a lowercase letter, followed by alphanumerics
 * 'entity.name.function' start with lowercase alpha, followed by alphanumerics, terminated by ( or ()
 * 'variable.parameter' starts with $ or %, then a lowercase alpha
