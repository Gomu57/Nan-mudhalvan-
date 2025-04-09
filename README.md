xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE bookstore [
  <!ELEMENT bookstore (book+)>
  <!ELEMENT book (title, author, year)>
  <!ELEMENT title (#PCDATA)>
  <!ELEMENT author (#PCDATA)>
  <!ELEMENT year (#PCDATA)>
  <!ATTLIST book id ID #REQUIRED>
]>
<bookstore>
  <book id="001">
    <title>Programming in ANSI C</title>
    <author>E.Balagurusamy</author>
    <year>2020</year>
  </book>
  
