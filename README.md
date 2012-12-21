## Installation

Paste the repo folder into the `<SublimeText2Folder>/Packages`

## Snippets

*	``for`` - foreach ``#foreach( $var in $!{colection} ) ... #end``
*	``param`` - get url param ``$!{request.getParameter( 'someparameter' )}``
*	``host`` - get host name ``$!{link.getHost()}``
*	``if`` - if structure, without else ``#if(condition) ... #end``
*	``ifel`` - if else structure ``#if(condition) ... #else ... #end``
*	``ifparam`` - if some url param ``#if($!{request.getParameter( 'someparameter' )}) ... #end``
*	``else`` - only an else ``#else``
*	``set`` - set ``#set( $var = _value_ )``
*	``read`` - gets the content of file ``$_reader.read("path/to/file.ext")``
*	``$`` - use variable ``$!{var}``
*	``!`` - html comment ``<!-- ... -->``
*	``vm`` - velocity head ``#!vm;utf-8``
*	``+`` - addition ``$math.add($number, $number)``
*	``-`` - subtraction ``$math.sub($number, $number)``
*	``*`` - multiplication ``$math.mul($number, $number)``
*	``debug`` - html output debug with parameter
*	``par`` - parse ``#parse("url")``