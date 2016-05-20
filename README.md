# elipsesForBiggerText
This library can be used as addon to get elipses for a big text after 5 lines.


/**
 * Shortens a string by the limit character or line
 *
 * @example
 * Example usage {{shorten-string-line project.name charLimit="45" lineLimit="5"}}
 *
 * Sample Input:
 * This is first line which contians lots of unwanted first word to make it long as well as marked as first line.
   This is comparatively small second line .
   As usual Third line should be extremely large because these comments are for testing purpose so third line is the largest line and this comment is not containing five new line end
 *
 * Expected output:
 * This is first line which contians lots of
   unwanted first word to make it long as well
   as marked as first line.
   This is comparatively small second line .
   As usual Third line should be extremely...
 *
 *
 * If Input is a big single line
 * Sample Input:Lightning is a fictional character from Square Enix's Final Fantasy series. She first appeared as a playable character and protagonist in the role-playing video game Final Fantasy XIII, and reappeared as a supporting character in Final Fantasy XIII-2 and as the sole playable character in Lightning Returns: Final Fantasy XIII.
 *
 * Expected Output:
 * Lightning is a fictional character from
   Square Enix's Final Fantasy series. She
   appeared as a playable character and
   protagonist in the role-playing video game
   Final Fantasy XIII....

 *If Input is a big line without space
 *
 * Sample Input:http://localhost:8080/platformservices/studio/#/projects/7/inputshttp://localhost:8080/platformservices/studio/#/projects/7/inputshttp://localhost:8080/platformservices/studio/#/projects/7/inputshttp://localhost:8080/platformservices/studio/#/projects/7/inputs
 *
 * Expected Output:
 *http://localhost:8080/platformservices/studi
  o/#/projects/7/inputshttp://localhost:8080/p
  latformservices/studio/#/projects/7/inputsht
  tp://localhost:8080/platformservices/studio/
  #/projects/7/inputshttp://localhost:8080/pla...
 * @param string
 * @param options {'hash':{ charLimit:value,lineLimit:value}}
 * @returns {*}
 */
